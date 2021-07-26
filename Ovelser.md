# Øvelser

## Grundlæggende programmering {#grundlæggende-programmering .unnumbered}

I denne øvelse skal vi installere den nyeste og korrekte version af
`Eclipse`.

1.  Klik på linket
    [https://www.eclipse.org/downloads](https://www.eclipse.org/downloads/).

2.  På den side der kommer frem, skal du klikke på Download-knappen.

3.  Der kommer nu en side frem, der giver dig mulighed for at vælge
    hvorfra, at du vil downloade installationsværktøjet til `Eclipse`
    fra. Bare klik på Download-knappen.

4.  Når du har downloadet `Eclipse`-installationsværktøjsfilen, skal den
    udpakkes. Når det er gjort, klikkes på filen med `Eclipse`-ikonet.
    Installationsværktøjet skulle gerne starte op nu.

5.  Under installationen bliver du spurgt om, hvilken type `Eclipse`, du
    vil installere. Vælg `Eclipse for Java Developers` og fortsæt
    installationen.

6.  Du kan undervejs i installationen også blive spurgt, om du vil
    acceptere diverse vilkår for brug af `Eclipse`. Sæt roligt hak ved
    alle betingelser.

Den version af `Eclipse` som vi netop har installeret, er som
udgangspunkt sat op til at skulle bruges til Java-udvikling. For at
kunne anvende `Eclipse` til Python-udvikling er vi derfor nødt til at
installere et plugin.

1.  Åbn `Eclipse`.

2.  Åbn fanen Help.

3.  Klik på menu-punktet Eclipse Marketplace\...

4.  Der popper nu et vindue frem, hvor du kan søge øverst efter et
    plugin. Søg på PyDev.

5.  Installér PyDev og lad `Eclipse` genstarte for at færdiggøre
    installationen.

[\[ov:eclipse\]]{#ov:eclipse label="ov:eclipse"} I denne øvelse skal vi
lære, hvordan man opretter et nyt java-projekt i `Eclipse`, samt hvordan
man afvikler/kører ens java-kode.

1.  Åbn `Eclipse`.

2.  Klik på `New` øverst i venstre hjørne og vælg `Java Project`.

3.  Giv dit projekt et navn og klik på `Finish`.

4.  Klik på `New` igen og vælg `Class`.

5.  Giv din nye java-klasse et navn. Sæt hak ved
    `public static void main(String[] args)`.

6.  Tilføj følgende til din `main`-funktion, så den ser således ud:

    ``` java
    public static void main(String[] args) {
      // TODO Auto-generated method stub
      System.out.println("Hej verden")
    }
    ```

7.  Prøv at køre din kode ved at trykke `Ctrl+F11`. I bunden af skærmen
    under `Console`-fanen skulle der gerne stå: `Hej verden!`.

I denne øvelse skal vi lære, hvordan man opretter et nyt python-projekt
i `Eclipse`, samt hvordan man afvikler/kører ens python-kode.

1.  Åbn `Eclipse`.

2.  Klik på `New` øverst i venstre hjørne og vælg `Other`.

3.  Søg efter `PyDev Project` og vælg denne.

4.  Giv dit `PyDev Project` et navn.

5.  Benyt `Quick Auto-Config` til at konfigurere python-fortolkeren.

6.  Klik på `Finish` og sig ja til åbne `PyDev perspectives`.

7.  Klik på `New` øverst i venstre hjørne og vælg `PyDev Module`.

8.  Giv dit python-modul et navn (du behøver ikke give pakken et navn).

9.  Indsæt følgende i din nye py-fil:

    ``` python
    print("Hej verden!")
    ```

10. Prøv at køre din kode ved at trykke `Ctrl+F11`. I bunden af skærmen
    under `Console`-fanen skulle der gerne stå: `Hej verden!`.

```{=html}
<!-- -->
```
1.  Skriv et program, der fjerner alle kommaer, punktummer, udråbstegn,
    anførselstegn, semikolon, kolon, m.fl. fra en tekst. Vink: Benyt
    replace-metoden.

2.  Udvid programmet så det tæller sammen, hvor mange ord, der er i
    teksten. Vink: Benyt split-metoden.

3.  Udvid programmet, så det viser, hvor mange forskellige ord, der er i
    teksten. Vink: Konvertér din liste til et set.

4.  Udvid programmet så brugeren kan spørge og få svar på, om et givent
    ord forekommer i teksten.

5.  Udvid programmet, så brugeren kan spørge og få svar på, om en given
    sætning forekommer i teksten.

Lixtallet er et udtryk for en teksts læsbarhed. Formlen til at beregne
LIX-tallet er givet ved
$$\text{LIX} = \frac{O}{P}+\frac{L\cdot 100}{O}$$ hvor $O$ er antal ord
i teksten, $P$ er antal punktummer i teksten og $L$ antal lange ord
(over 6 bogstaver lange).

Formlen kan altså forstås som antal ord per mellem hvert punktum lagt
sammen med procentdelen af de lange ord i teksten. Man har så følgende
skala til at vurdere LIX-tallet med:

-   $\text{LIX}\geq 55$: Meget svær, faglitteratur på akademisk niveau,
    lovtekster.

-   $45\leq\text{LIX}< 55$: Svær, f.eks. saglige bøger,
    populærvidenskabelige værker, akademiske udgivelser.

-   $35\leq\text{LIX}< 45$: Middel, f.eks. dagblade og tidsskrifter.

-   $25\leq\text{LIX}< 35$: Let for øvede læsere, f.eks.
    ugebladslitteratur og skønlitteratur for voksne.

-   $\text{LIX}<25$: Let tekst for alle læsere, f.eks. børnelitteratur.

1.  Lav et program, der bestemmer Lix-tallet af en tekststreng.
    Programmet skal fortælle hvilket niveau teksten ligger på. Antag at
    du får teksten i en string-variable.

2.  Benyt din LIX-beregner på en tekst du skrev i folkeskolen og en
    tekst, du har skrevet i gymnasiet (det kunne f.eks. være en dansk
    stil).

Skriv et program, der genererer de første n Fibonnaci-tal. Første tal er
0 og andet tal er 1. Dernæst angives det n'te Fibonacci tal som summen
af de to foregående.

Skriv et program der konstruerer 3 tekst variabler, som rummer teksterne
\"Der var engang\", \" en mand som\" og \"boede i en spand. Spanden var
af ler\".

-   Sammenkæd de tre tekststrenge via variablerne

-   Bestem længden af hver af dem.

-   Undersøg det andet bogstav i hver af dem

-   Undersøg om to af variablerne er det samme

-   Skriv hele teksten som versaler

-   Lav en ny variable der er en delstreng af en af variablerne.

-   Sammenflet de tre variabler så det første bog stav er fra den første
    variable, den anden fra den anden osv.

-   Undersøg hvor mange forekomster af e der er i teksten.

1.  Skriv et program, der generer multiplikationstabellen for 2 fra 2
    til og med 20 og gem tabellen i en liste: \[2, 4, 6, 8, 10, 12,
    \..., 20\].

2.  Udvid programmet, så 20 kan specificeres af brugeren.

3.  Udvid programmet, så brugeren kan få multiplikationstabellen for et
    vilkårligt naturligt tal x.

4.  Udvid programmet, så det udskriver multiplikationstabellerne fra 2
    til og med x.

Skriv et program, der finder det mindste hele tal n så n\*n er større
end 12000. Skriv dernæst et program, der finder det største hele tal n,
så n\*n\*n er mindre 12000.

1.  Lav en Basal Metabolic Rate (BMR) beregner, der fortæller hvor meget
    energi du forbrænder i hviletilstand i løbet af en dag (kalorier).
    Input er hvorvidt du er mand eller kvinder samt vægt, alder og
    aktivitetsniveau. Formlen (kendt som Harris--Benedicts ligninger) og
    er givet ved: $$\begin{aligned}
      \text{BMR} &= 10\cdot (\text{vægt i kg}) + 6,25\cdot(\text{højde i cm})-5\cdot(\text{alder i år}) +5 & & \text{(mænd)}\\
        \text{BMR} &= 10\cdot (\text{vægt i kg}) + 6,25\cdot(\text{højde i cm})-5\cdot(\text{alder i år}) -161 & & \text{(kvinder)}\\\end{aligned}$$

```{=html}
<!-- -->
```
1.  Undersøg om en given tekststreng (string variable) udgør et validt
    CPR-NR.

2.  Skriv et program, der oplister alle CPR-numre.

Skriv et program, der finder alle de store bogstaver og små bogstaver i
en streng.

Skriv et program, der finder alle mellemrum

Skriv et program, der undersøger hvor mange forskellige bogstaver to
strenge har.

Skriv et program, der erstatter alle bogstaver \"i\" med \"k\" i en
streng.

Skriv et program, der undersøger om en given delstreng er indeholdt i en
anden streng

Givet to tekststrenge. Overvej forskellige måder til at undersøge om den
ene er et plagiat af den anden.

Skriv et program der generer et Haiku digt ud fra nogle fastsatte
sætninger. Der er 17 stavelser i et Haiku digt fordelt på 5-7-5 i de tre
linjer.

Lav et tekstbaseret \"sten-saks-papir\"-spil.

Lav et tekstbaseret \"Hang-man\" spil

1.  Lav et program, der undersøger om et givent password er et sikkert
    password. Ved sikkert forstås, at det skal være minimum 8 bogstaver
    langt samt indeholde både et stort og lille bogstav samt et tal. Du
    må gerne udvide kriterierne.

```{=html}
<!-- -->
```
1.  Lav et program der omregner fra grader til radianer eller omvendt.
    Hint: $2\cdot\pi$ radianer svarer til 360 grader.

```{=html}
<!-- -->
```
1.  Givet en retvinkel trekant. Lav en trekantsberegner, der bestemmer
    alle sider og vinkler i trekanten. Brug gerne matematikpakken i
    Python:

    ``` python
    import math as m
        print(m.cos(m.pi)) # udskriver -1.0. Hvorfor mon?
    ```

Tilnærmelse af tallet kan gøres ved følgende formel
$$\pi = 3 + \frac{4}{2\cdot 3\cdot 4}-\frac{4}{4\cdot 5\cdot 6}+\frac{4}{6\cdot 7\cdot 8}-\ldots$$

1.  Lav et program, der beregner en tilnærmelse af $\pi$, hvor input er
    antallet af brøkled i formlen.

```{=html}
<!-- -->
```
1.  Lav et program, der finder alle a'er i en tekststreng.

Skriv et program, der fylder en liste med heltal i en tilfældig række.
Bestem selv hvilke.

-   Sorter listen.

-   Byt om på rækkefølgen af tal når den er sorteret

-   Indsæt et element midt i listen

-   Udvid programmet så du kan tilføje et element til listen ved brug af
    input fra brugeren

Skriv et program, der tager en tekststreng indlæst i en variable.
Teksten skal bestå af mindst 100 ord og split ordene op i en liste ved
brug af split-funktionen.

-   Tæl antallet af kommaer og punktummer

-   Find det ord der forekommer flest gange

-   Lav en liste der viser hvor mange gange hvert ord forekommmer

Skriv et program der kan bruges til Lotto, hvor der genereres 7
tilfældige tal. De skal være forskellige (mellem 1 og 40) og returneres
i stigende rækkefølge.

Skriv en funktion, der undersøger om en given delliste af tal er
indeholdt i en liste af tal. Dellisten skal optræde fra start til slut i
listen. Dvs. \[2,3\] er en delliste af \[1,2,3,4\] men \[1,4\] er ikke.

1.  Definér følgende dictionary i din kode:

    ``` python
    løn = {'Niels': 85000, 'Peter': 40000, 'Jakob': 90000, 'Poul': 100000, 'Dorte': 40000}
    ```

2.  Gennemløb løn og udskriv navn og løn for hver person på en linje for
    sig.

3.  Undersøg om \"Bente\" findes i løn.

4.  Hent og udskriv kun nøgler af løn.

5.  Hent og udskriv kun værdierne af løn.

6.  Bestem gennemsnitslønnen.

7.  Bestem den hyppigst forekomne lønindkomst.

8.  Bestem mindste- og størstelønnen i løn.

9.  Undersøg programmatisk om der findes flere personer med samme løn.

```{=html}
<!-- -->
```
1.  Skriv et program, der på baggrund af en tekst, konstruerer en
    dictionary kaldt bogstav, så f.eks. bogstav\['a'\] er lig med
    antallet af a'er i teksten, bogstav\['b'\] er lig med antallet af
    b'er osv.

Skriv et program der bruger en dictionary til at rumme en filmdatabase.
Dictionary skal rumme filmens titel, produktionsår, og instruktør samt
en genre.

Du afgør selv strukturen.

-   Lav en funktion der afgør om en given film eksisterer i biblioteket
    fra forrige opgave.

-   Lav en funktion der sletter en given film fra databasen

-   Lav en funktion der tilføjer en ny film til databasen.

-   Lav en funktion der opdaterer en egenskab ved en film. Dvs.
    instruktør, titel, genre eller produktionsår.

Betragt nedenstående 4 funktioner:

``` python
# Funktion med 3 keyword-argumenter
def udskriv_gennemsnit(a=10, b=20, c=30):
    print((a + b + c) / 3)

# Funktion med vilkårligt mange positionelle argumenter
def udskriv_argumenter(*args):
    for value in args:
        print(value)

# Funktion med vilkårligt mange keyword-argumenter
def udskriv_argumenter2(**kwargs):
    for key, value in kwargs.items():
        print(key, value)

# Funktion med et tvungent positionelt argument, efterfulgt af
# vilkårligt mange positionelle argumenter og til sidst 
# vilkårligt mange keyword-argumenter. Bemærk:Rækkefølgen 
# på argumenterne har betydning. 
def udskriv_argumenter3(pos, *args, **kwargs):
    print(pos)
    udskriv_argumenter(*args)
    udskriv_argumenter2(**kwargs)


# Test af ovenstående funktioner
udskriv_gennemsnit()  # Udskriver 20
udskriv_gennemsnit(a=1, b=2, c=3)  # Udskriver 2
udskriv_argumenter("Hej", "verden")  # Udskriver Hej og verden
udskriv_argumenter2(a=100, b=200)  # Udskriver a 100 og b 200
udskriv_argumenter3(1, 2, 3, a=4, b=5)  # Udskriver alle argumenter
```

1.  Forklar hvad forskellen er på positionelle og nøgleordsargumenter.

2.  Forklar hvorfor der benyttes \* og \*\* i nogle af
    funktionsdefinitionerne.

3.  Hvad foregår der i koden ovenfor? Forklar hvad de fire funktioner
    hver især gør.

```{=html}
<!-- -->
```
1.  Skriv et program, der implementerer Cæsars krypteringsalgoritme.

2.  Skriv et program, der dekrypterer en Cæsar-indkodet tekst.

```{=html}
<!-- -->
```
1.  Skriv et program, der sorterer en liste af tal vha.
    bubblesort-algoritmen.

2.  Skriv et program, der sorterer en liste af tal vha.
    mergesort-algoritmen.

3.  Afprøv dine sorteringsalgoritmer på lister med mange tusinde tal.
    Hvilken en af algoritmerne er mon hurtigst?

```{=html}
<!-- -->
```
1.  Undersøg om en tekststreng er et palindrom. Dvs. om tekststrengen
    læses og skrives på samme måde forfra og bagfra.

```{=html}
<!-- -->
```
1.  Konstruér et program der løser ligninger på formen $ax+b=c$. Input
    er tallene $a,b$ og $c$.

2.  Konstruér et program der løser ligninger på formen $ax+b=cx+d$.
    Input er tallene $a,b,c$ og $d$.

```{=html}
<!-- -->
```
1.  Konstruér et program der beregner toppunkt og evt. rødder for et
    andengradspolynomium $f(x)=ax^2+bx+c$, hvor $a\neq 0$.

2.  Udvid programmet så det også kan finde tilnærmede løsninger til 3.
    og 4.gradsligninger.

```{=html}
<!-- -->
```
1.  Skriv et program der afgør om et givent tal er et primtal.

2.  Undersøg hvad der er det største primtal, som går op i
    tallet 600851475143.

```{=html}
<!-- -->
```
1.  Givet to tekststrenge gemt i to strengvariabler. Lav en eller flere
    metoder til at undersøge i hvor høj grad de to tekststrenge er
    similære.

```{=html}
<!-- -->
```
1.  Lav et simpelt tekstbaseret kryds og bolle spil.

```{=html}
<!-- -->
```
1.  Skriv et program, der konverterer en tekst til morsekode.

```{=html}
<!-- -->
```
1.  Lav en tekstbaseret version af "Fire-på-stribe".

En amortisationsplan (tilbagebetalingsplan) benyttes i forbindelse med
et annuitetslån og giver en oversigt over lånets afvikling.

Vi låner f.eks. 1000 kr som afbetales med 100 kr per termin. Renten er
$5\%$ per termin. Et uddrag af amortisationsplanen er vist nedenfor.

::: center
   Primo restgæld   Ydelse   Renter (5%)   Afdrag ($=\text{Ydelse}-\text{Renter}$)   Ultimo restgæld
  ---------------- -------- ------------- ----------------------------------------- -----------------
        1000         100         50                          50                            950
        950          100        47,50                       52,50                        897,50
       897,50        100        44,88                       55,22                        842,28
        \...         \...       \...                        \...                          \...
:::

1.  Konstruér et program der genererer en tekstbaseret version af
    amortisationsplanen. Input er gældens størrelse, annuitetsydelsen
    samt rente per termin.

Inden for deskriptiv statistik konstruerer man ofte den såkaldte
hyppigheds- og frekvenstabel. Antag f.eks. at vi i en undersøgelse har
spurgt 10 gymnasie-elever hvor mange stykker frugt, de hver især har
spist i den sidste uge. De 10 svar er vist herunder:
$$5\quad 6\quad 7\quad 7\quad 6\quad 8\quad 7\quad 8\quad 6\quad 6.$$
Hyppighedstabellen kommer da til at således ud:

::: center
   Stykker frugt $(x_i)$   Hyppighed $(h_i)$    Frekvens $(f_i)$    Summerede frekvens $(F_i)$
  ----------------------- ------------------- -------------------- ----------------------------
             5                     1           $\frac{1}{10}=0,1$       $\frac{1}{10}=0,1$
             6                     4           $\frac{4}{10}=0,4$       $\frac{5}{10}=0,5$
             7                     3           $\frac{3}{10}=0,3$       $\frac{8}{10}=0,8$
             8                     2           $\frac{2}{10}=0,2$       $\frac{10}{10}=1$
:::

1.  Lav et program, der konstruerer hyppighedstabellen. Antag at
    observationerne er givet som en liste. Vink: Der er hjælp at hente
    nedenfor, hvor vi benytter `dictionaries` i Python til hurtigt at
    konstruere hyppighederne med:

    ``` python
    data = [5, 6, 7, 7, 6, 8, 7, 8, 6, 6]
    hyp = {}

    # udskriver observationerne en ad gangen.
    for i in range(0, len(data)):
        print(data[i]) 

    # konstruerer en dictionary hvor observationerne
    # er nøglerne og værdierne er hyppighederne
    for i in range(0, len(data)):
        if data[i] in hyp:
            hyp[data[i]] = hyp[data[i]] + 1
        else:
            hyp[data[i]] = 1

    print(hyp) # udskriver {5: 1, 6: 4, 7: 3, 8: 2}
    ```

Følgende opgave kræver en forståelse af hvorledes filer indlæses. I skal
hente datasættet fra

::: url
https://www.kaggle.com/gregorut/videogamesales
:::

, som er et datasæt der rummer statistikker over hvor meget 16500
forskellige spil har solgt på forskellige platforme. I skal indlæse
filen og lave følgende statistikker:

-   En statistik over de ti mest solgte spil på alle tilgængelige
    platforme

-   De mest solgte spil i Europa i 2014

-   Hvor meget Grand Theft Auto-serien har solgt på platformene PC,
    Playstation og XBOx. Bemærk der er flere spil

## Objektorienteret programmering {#objektorienteret-programmering .unnumbered}

Beskriv relationen mellem et objekt og dens definerende klasse

Hvordan defineres en klasse?

Hvordan laves et objekts reference variable

Hvordan konstrueres et objekt

Hvad er forskellen mellem konstruktøren og metoder?

Hvordan kaldes en metode fra en klasse?

Opret en klasse for en cirkel. Den skal have et centrum (x,y) og en
radius som data. Klassen skal have en metode der printer klassens
attributter ud.

Opret en klasse for en linje i planen. Den skal have en hældning og en
skæring med y-aksen. Klassen skal have en metode der printer klassens
attributter ud.

Udvid klasserne i de foregående øvelser med konstruktører så de kan
oprette med argumenter. For cirkel skal det være radius og centrum. For
linjen skal det være hældningstal og skæring med y-aksen.

Udvid linjens klasse så den rummer en konstruktør der tager fire
talværdier svarende til (x1,y1) og (x2,y2).

Udvid cirklen med to metoder. En der beregner areal af cirklen og en
anden der beregner omkredsen

Beskriv f.eks. vha. ER-diagrammer de forskellige objekter i en
todo-liste-applikation.

Beskriv f.eks. vha. ER-diagrammer de forskellige objekter i et
lectio-lignende system. Overvej, hvordan vi programmatisk sikrer, at
hver elev-objekt er unikt. Afslut med at skrive kode, der tester dine
klasser.

Beskriv f.eks. vha. ER-diagrammer de forskellige objekter i et
løn-medarbejder-system. Afslut med at skrive kode, der tester dine
klasser.

Beskriv f.eks. vha. ER-diagrammer de forskellige objekter i et
betalings-system som f.eks. benyttes på enhver webshop. Implementér de
nødvendige klasser i Python. Afslut med at skrive kode, der tester dine
klasser.

I denne øvelse skal vi udvikle en todo-liste-applikation. **Advarsel!**
Dette er en enorm svær og tidskrævende øvelse, som kræver mange måneders
(måske endda års) forberedelse og oplæring i diverse udviklingsværtøjer
før, at man er i stand til at gennemføre øvelsen. Det er derfor absolut
**ikke** et krav, at man færdiggør hele øvelsen. Tanken er blot, at man
får en fornemmelse af, hvor omfattende et arbejde det er, at udvikle en
'state-of-art' SPA (Single Page Application), som vi kender det fra alle
de web applikationer, vi benytter i vores dagligdag (såsom facebook,
twitter, gmail og mange flere).

> "*Begin at the beginning,* the King said, gravely, *and go on till you
> come to the end; then stop*" - Lewis Carroll, Alice in Wonderland

> "*And so it begins\...*" - King Theoden, Lord of the Rings \"The Two
> Towers\".

1.  Installér git (versions-kontrol-system) fra her:
    <https://git-scm.com/downloads>

2.  Installér Google App Engine Standard Environment til Python på din
    maskine. Følg vejledningen her:
    <https://cloud.google.com/appengine/docs/standard/python/download>.
    **Bemærk:** Det koster ikke noget at bruge Google App Engine på ens
    egen maskine. Hvis man ønsker at hoste et projekt på Googles servere
    og deres infrastruktur, da skal man oprette et projekt via deres
    site og når den gratis prøveperiode er udløbet, da koster det penge.
    Så vi skal kun installere Google App Engine til offline brug.

3.  Benyt git til at klone gæstebog-repository:

        git clone https://github.com/GoogleCloudPlatform/appengine-guestbook-python.git

4.  Start den lokale udviklingsserver fra en terminal i roden af
    gæstebog-mappen ved at indtaste kommandoen:

        dev_appserver.py

5.  Du kan nu se gæstebogen i din browser: <http://localhost:8080/>

6.  Gennemgå tutorial til Google App Engine:
    <https://cloud.google.com/appengine/docs/standard/python/getting-started/creating-guestbook>.
    **Bemærk:** Du skal ikke oprette et nyt GCP Console Projekt, da det
    koster penge!

7.  Når du har gennemgået gæstebog-tutorial, er du klar til at skriv de
    nødvendige RequestHandlers til at implementere din todo-liste. Benyt
    din kode fra tidligere øvelse.

Når vi er færdige med vores backend, skal vi i gang med at implementere
vores frontend, som er den del af vores applikation, brugeren ser. Hvis
du ikke har arbejdet med javascript, typescript, html og css er det en
rigtig god ide at starte med at gennemføre en tutorial i disse
teknologier først. Det kunne f.eks. være følgende:

-   HTML: <https://www.tutorialspoint.com/html/>

-   CSS: <https://www.tutorialspoint.com/css/>

-   Javascript: <https://www.tutorialspoint.com/javascript/>

-   Typescript: <https://www.tutorialspoint.com/typescript/>

Vi er nu klar til at fortsætte øvelsen:

1.  Installér nodejs: <https://nodejs.org/en/download/>

2.  Installér angular: <https://angular.io/guide/quickstart>

3.  Gennemgå angular tutorial: <https://angular.io/tutorial>

4.  Opret nyt angular-projekt og påbegynd udvikling af din frontend.

5.  Inkludér Material design, så du hurtigt og nemt kan få din frontend
    til at se flot ud:
    <https://material.angular.io/guide/getting-started>.
