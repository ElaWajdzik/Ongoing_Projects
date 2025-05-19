# Miliarderzy w liczbach. Kim są najbogatsi ludzie świata?


Spis treście:
* [Wprowadzenie - krótkie tło analizowanego tematu](#wprowadzanie)
* [Pytania, na które szukałam odpowiedzi](#kluczowe-pytania-na-które-szukałam-odpowiedzi)
* [Czy wiesz, że... Najciekawsze wnioski wyciągnięte z analizy](#czy-wiesz-że)
* [Przegląd przygotowanych wizualizacji](#przygotowane-wizualizację)
* [Szczegółowa analiza z wizualizacjami](#szczegółowe-omówienie-zagadnienia)
* [Dalsze kierunki](#dalsze-kroki)

<br>

📌
*Uwaga:* Dane do analizy zostały samodzielnie pobrane za pomocą publicznego API Forbes. [Szczegółowy opis procesu pobierania i przygotowania danych.](https://github.com/ElaWajdzik/Ongoing_Projects/blob/main/Jupyter%20Notebook/Miliarderzy%20Forbes.ipynb)

<br>

### Wprowadzanie

Na świecie żyje ponad 8 miliardów ludzi. Jak wynika z raportu [Global Wealth Report 2024](https://www.ubs.com/us/en/wealth-management/insights/global-wealth-report.html), łącznie dysponujemy majątkiem bliskim **488 bilionów dolarów** (czyli około **1,95 biliarda złotych**).
Gdyby rozdzielić ten globalny majątek równo pomiędzy wszystkich dorosłych, każdy z nas miałby na koncie blisko **85 tysięcy dolarów** (~340 tysięcy złotych).

Jednak rzeczywistość jest inna.

Na świecie żyją zarówno osoby w wielkim bogactwie, jak i te pogrążone w skrajnym ubóstwie, a nasze szanse często zależą od miejsca urodzenia, rodziny czy dostępu do edukacji i zasobów.

Dziś **połowa ludzi na Ziemi posiada majątek mniejszy niż 8,6 tysiąca dolarów** (~34,6 tysiąca złotych).

A gdzie Ty jesteś w tym układzie?

Policz wszystko, co posiadasz (samochód, mieszkanie, środki na koncie itp.), a następnie odejmij od tego wszystkie swoje zobowiązania (kredyty, hipoteki, pożyczki).


Jeśli Twój majątek wynosi:
* **więcej niż 34,6 tysiąca złotych** - jesteś bogatszy od połowy ludzi na świecie;
* **więcej niż 114,4 tysiąca złotych** - jesteś bogatszy od połowy mieszkańców Europy[^1];
* **więcej niż 90,4 tysiąca złotych** - jesteś bogatszy niż połowa Polaków.

[^1]: Europa w tym zestawieniu rozumiana jest szerzej jako obszar EMEA (Europa, Bliski Wschód i Afryka).

A może Twój majątek jest jeszcze większy?
A może dopiero zaczynasz swoją drogę i zastanawiasz się, jak wysoko zawieszona jest poprzeczka?

W poniższym opracowaniu przyjrzymy się osobom z listy miliarderów magazynu Forbes.
Jeśli jesteś ciekaw, kim są, skąd się wzięli i co ich łączy to zapraszam do dalszego czytania!


<br>

### Kluczowe pytania, na które szukałam odpowiedzi:

* Skąd pochodzą miliarderzy? Czy urodzenie w konkretnym kraju lub regionie zwiększa szanse na bycie miliarderem?
* Kim są osoby na liście? Jakie mają cechy wspólne - wiek, płeć, źródło majątku?
* W jakim wieku najczęściej są miliarderzy? Czy wiek ma związek z wysokością zgromadzonego majątku?
* Skąd pochodzi majątek miliarderów? Czy zawdzięczają go pracy własnej, czy dziedziczeniu?
* W jakich branżach działa najwięcej miliarderów? Które sektory generują największy majątek?

<br>

## Czy wiesz, że...

Choć na świecie żyje niemal 3 tysiące miliarderów, to aż **co piąty z nich mieszka w zaledwie 9 miastach**. Najwięcej - w Nowym Jorku.

**Stany Zjednoczone to ojczyzna największej liczby miliarderów**, ale w przeliczeniu na populację zajmują dopiero ósme miejsce. Liderami są Hongkong i Singapur, dwa azjatyckie miasta-państwa.

Dziś prawdziwą **„krainą miliarderów” jest Monako**, niewielkie państwo o powierzchni 2 km², w którym na 39 tysięcy mieszkańców przypada aż 18 miliarderów.

**Miliarderem jest średnio jedna osoba na 3 miliony ludzi**, ale w Ameryce Północnej ta „szansa” jest aż **pięciokrotnie wyższa** niż globalna średnia.

<p align="center">
    <a>
        <img src="assets/12 - Miliarderzy - kontynent pochodzenia.png" width="500">
    </a>
</p>


**Ponad połowa osób na liście to pokolenie baby boomers** - dziś w wieku 60-79 lat. Najczęściej powtarzający się wiek to 69 lat.

**Najmłodszy miliarder ma 19 lat, a najstarszy - 103**. Pierwszy to niemiecki spadkobierca rodzinnej firmy farmaceutycznej. Drugi to amerykański przedsiębiorca, który sam w 1961 roku założył firmę ubezpieczeniową.

**2 na 3 miliarderów zbudowało majątek samodzielnie**, ale w Europie dominują fortuny dziedziczone. W Niemczech tylko 1 na 4 miliarderów dorobił się samodzielnie.

**Kobiety stanowią zaledwie 13% listy**, ale gdy już się na niej znajdą to są równie zamożne jak mężczyźni. 

Tylko wśród kobiet obserwujemy związek między wiekiem a wartością majątku - starsze miliarderki mają statystycznie wyższy majątek niż młodsze.

**Technologia to najmłodsza branża**, z przeciętnym wiekiem wynoszącym 56 lat (czyli o 10 lat mniej niż ogólna mediana). Aż 92% osób z tej branży zbudowało majątek samodzielnie.

<br> 


## Przygotowane wizualizację:

* **kartogram z podziałem na kontynenty** - przedstawia współczynnik liczby miliarderów przypadających na każde 3 miliony mieszkańców, z podziałem na kontynenty;
* **wykres słupkowy - liczba miliarderów według kraju pochodzenia** - ranking krajów z największą liczbą osób na liście, bez uwzględniania populacji;
* **wykres słupkowy - współczynnik liczby miliarderów na 1 mln mieszkańców** - porównanie krajów z uwzględnieniem ich populacji, pozwalające ocenić względne „szanse” na zostanie miliarderem;
* **wykres nachyleń - wpływ migracji na współczynnik** - wizualizacja pokazuje, jak zmienia się wskaźnik liczby miliarderów na 1 mln mieszkańców w zależności od kraju pochodzenia i aktualnej rezydencji;
* **wykres słupkowy - liczba miliarderów według miasta zamieszkania** - zestawienie największych skupisk miliarderów na poziomie miejskim;
* **mapa świata z lokalizacjami rezydencji miliarderów** - wizualizacja 789 miejsc zamieszkania osób z listy Forbes ze zróżnicowanych wielkością punktu;
* **histogram wieku w przedziałach 10-letnich** - prezentacja rozkładu wieku miliarderów z podziałem na grupy wiekowe;
* **histogram rozkładu wieku** - szczegółowy rozkład wieku, pozwalający dostrzec konkretne „szczyty” liczebności;
* **skumulowany wykres słupkowy - źródła majątku** - procentowy podział miliarderów według typu pochodzenia majątku (self-made, odziedziczony i rozwijany, w pełni odziedziczony)  w państwach z największą liczbą miliarderów;
* **wykres słupkowy - branże i majątek** - porównanie udziału poszczególnych branż w liczbie miliarderów oraz w wartości całkowitego majątku;
* **wykres słupkowy - mediana wieku według branży** - pokazuje różnice w przeciętnym wieku miliarderów w zależności od sektora działalności;
* **wykres rozrzutu (beeswarm)** - rozkład wieku i płci miliarderów w pięciu najważniejszych branżach (dostępna także [wersja interaktywna](https://public.flourish.studio/visualisation/23240788/) z filtrem majątku i podglądem szczegółów).


Wizualizacje zostały przygotowane przy użyciu narzędzi **Datawrapper** i **Flourish**. Wybrane grafiki zostały dodatkowo opracowane wizualnie w programie **Canva**.


<br>


## Szczegółowe omówienie zagadnienia

Kiedy myślimy o miliarderach, najczęściej kojarzymy takie nazwiska jak **Elon Musk** (Tesla, SpaceX), **Jeff Bezos** (Amazon), **Mark Zuckerberg** (Meta/Facebook) czy **Warren Buffett** (Berkshire Hathaway, inwestycje). Elon Musk to także jedyna osoba w historii, której majątek przekroczył wartość **400 miliardów dolarów**. Jednak świat miliarderów to znacznie więcej niż kilku medialnych gigantów. Dzięki rankingowi tworzonym przez magazyn [**Forbes**](https://www.forbes.com/real-time-billionaires/) mamy możliwość przyjrzenia się im **z perspektywy danych** i zobaczyć, skąd pochodzą, w jakich branżach działają, ile mają lat i gdzie mieszkają.

<p align="center">
    <a>
        <img src="assets/Miliarderzy - top 4.png" width="600">
    </a>
</p>



Na podstawie danych z listy Forbes, aktualnych na dzień 10.04.2025, na świecie żyje **2 886 miliarderów**, których **łączny majątek wynosi 15,3 biliona dolarów** co stanowi 3,1% całkowitego globalnego majątku.

Jeśli zestawimy tę liczbę z populacją świata, okazuje się, że **średnio 1 miliarder przypada na każde 3 miliony ludzi**. Ale ta proporcja to tylko uśrednienie, w rzeczywistości szanse na zgromadzenie miliarda dolarów są silnie zależne od miejsca urodzenia.

Choć **Azja** jest kontynentem, z którego pochodzi najwięcej miliarderów w ujęciu bezwzględnym, to **ze względu na swoją ogromną populację**, jej **współczynnik miliarderów na mieszkańca jest relatywnie niski**. W rankingu szans na zostanie miliarderem wyprzedzają ją aż trzy inne kontynenty.

**Najwięcej „szczęścia do bogactwa” mają osoby urodzone w Ameryce Północnej** to tam przypada aż **4,7 miliardera na każde 3 miliony mieszkańców**, czyli niemal pięć razy więcej niż globalna średnia. Po drugiej stronie skali znajduje się **Afryka**, gdzie ten sam wskaźnik wynosi zaledwie **0,04** - co oznacza, że szanse na zostanie miliarderem są tam **117 razy niższe niż** w Ameryce Północnej.

Poniższy kartogram pokazuje te dysproporcje w ujęciu kontynentalnym. Już na pierwszy rzut oka widać, że globalne bogactwo **nie jest rozłożone równo ani sprawiedliwie**.

<p align="center">
    <a>
        <img src="assets/12 - Miliarderzy - kontynent pochodzenia.png" width="800">
    </a>
</p>

Zagłębiając się w dane, możemy również przyjrzeć się **poszczególnym krajom**. Czy miejsce urodzenia wpływa na to, **jak duże mamy szanse, by znaleźć się w gronie najbogatszych ludzi na świecie**?

Jak wynika z danych, niemal **co trzeci miliarder przyszedł na świat w Stanach Zjednoczonych**. W 17 krajach urodziło się **co najmniej 40 miliarderów**, a wśród nich znajduje się **7 państw europejskich**.

**Polska zajmuje 35 miejsce** w rankingu liczby miliarderów na 78 krajów znajdujących się w zestawieniu. Na liście Forbes znalazło się **9 osób pochodzących z Polski**.


<p align="center">
    <a>
        <img src="assets/13 - Miliarderzy - kraj pochodzenie.png" width="450">
    </a>
</p>

Samo porównywanie liczby miliarderów między krajami **może być jednak mylące**, przede wszystkim z uwagi na **znaczne różnice w liczebności populacji**. Aby rzetelnie ocenić, czy pochodzenie z danego państwa rzeczywiście daje „większe szanse” na zbudowanie fortuny, warto spojrzeć na **współczynnik liczby miliarderów przypadających na milion mieszkańców**. Dopiero taki wskaźnik umożliwia uczciwe i porównywalne zestawienie.

Patrząc z perspektywy krajów o populacji przekraczającej **1 milion mieszkańców**, najwyższe pozycje w rankingu współczynnika liczby miliarderów przypadających na milion mieszkańców zajmują **dwa azjatyckie miasta-państwa** - **Hongkong** i **Singapur**. Co ciekawe, w klasycznym ujęciu liczby miliarderów nie znalazły się one w pierwszej piątce krajów.

**Stany Zjednoczone**, mimo zdecydowanej przewagi nominalnej, uplasowały się dopiero na **8 miejscu** pod względem badanego współczynnika. Wyprzedziły je m.in. **Szwajcaria**, **Szwecja** i **Norwegia**, czyli trzy kraje europejskie, które nie tylko cechują się wysokim poziomem rozwoju, ale także stosunkowo niewielką populacją - co wyraźnie podnosi wartość tego wskaźnika.

W wizualizacji celowo **pominięłam kraje o populacji mniejszej niż 1 milion osób**, ponieważ analizowany współczynnik jest bardzo wrażliwy na wartość mianownika - w przypadku mikropaństw nawet jeden miliarder może znacząco zawyżać wynik. Omówienie tych przypadków wymagałoby osobnego zestawienia. 

Pierwsza trójka w rankingu mikropaństw:
* **Monako** → współczynnik = 51 (populacja 39 tys. i 2 miliarderów)
* **Saint Kitts i Nevis** → 43 (populacja 47 tys. i 2 miliarderów)
* **Liechtenstein** → 25 (populacja 40 tys. i 1 miliarderów)


<p align="center">
    <a>
        <img src="assets/14 - Miliarderzy - kraj pochodzenie współczynnik.png" width="450">
    </a>
</p>

Urodzenie to coś, na co nie mamy wpływu, ale miejsce, w którym zdecydujemy się żyć później, bywa już w pewnym stopniu kwestią wyboru. Czy miliarderzy często opuszczają swoje ojczyzny w poszukiwaniu korzystniejszych warunków?

Dane, którymi dysponuję, zawierają informacje o **aktualnej rezydencji** miliarderów, jednak co istotne **nie wiemy, czy przeprowadzili się oni do tych krajów przed czy po osiągnięciu miliardowego majątku**. Analizowana migracja nie obrazuje więc motywacji, a jedynie **efekt końcowy** - gdzie miliarderzy mieszkają dziś.

Zdecydowana większość, bo aż **89% miliarderów**, mieszka w kraju, w którym się urodziła. Może to sugerować, że **zmiana kraju zamieszkania nie jest uniwersalnym przepisem na sukces**. Mimo to, dla wybranych państw migracja miała istotny wpływ na wskaźnik liczby miliarderów przypadających na 1 milion mieszkańców.

Największy wzrost współczynnika zanotowała **Szwajcaria** zmiana z 4,6 do 9,0, co jest efektem napływu netto aż **39 miliarderów**. To największy nominalny wzrost w całym zestawieniu. Na kolejnych miejscach znalazły się **Singapur** (+10) oraz **Hongkong** (+7).

Największy spadków współczynnika dotknął **Cypr** zmiana z 7,4 do 5,2, w wyniku odpływu 3 miliarderów. Największy **nominalny spadek** dotyczył jednak **Kanady**, gdzie liczba miliarderów zmniejszyła się tam z 73 do 45, czyli **o 28 osób**.

Podobnie jak wcześniej, w analizie celowo pominięto państwa o populacji mniejszej niż 1 milion mieszkańców, ze względu na dużą wrażliwość współczynnika na niewielkie zmiany liczebności.

Nie sposób jednak pominąć przypadku **Monako** to mikropaństwa o powierzchni zaledwie 2 km² i populacji niespełna 40 tysięcy osób. Według danych o rezydencji, mieszka tam dziś aż 18 miliarderów, co oznacza, że współczynnik wzrósł z 51 do aż 462. To jeden z najbardziej ekstremalnych przykładów koncentracji bogactwa, wynikający właśnie z migracji.

<p align="center">
    <a>
        <img src="assets/15 - Miliarderzy - emigracja.png" width="450">
    </a>
</p>

Wiemy już, w jakich krajach mieszkają miliarderzy i jak wygląda rozkład ich liczby w odniesieniu do populacji. Ale czy da się wskazać **konkretne miasta**, które stanowią **prawdziwe skupiska najbogatszych ludzi świata**?

Z danych wynika, że **Nowy Jork** to niekwestionowana **„stolica miliarderów”**. Aż **119 osób z listy Forbes** ma tam swoją rezydencję, co oznacza, że **ponad 4% wszystkich miliarderów** mieszka właśnie w tym jednym mieście.

Co więcej, **zaledwie 9 miast na świecie** może pochwalić się liczbą **co najmniej 50 miliarderów**. Łącznie mieszka w nich 6**38 osób z całej listy**, co stanowi aż **22,5% wszystkich miliarderów**. Mówiąc inaczej - **co piąty miliarder na świecie mieszka w jednym z tych 9 miast**.

Taka koncentracja nie jest przypadkowa, może świadczyć o **szczególnych warunkach**, jakie oferują te miejsca, np. dostęp do rynków kapitałowych, korzystne prawo podatkowe, rozwinięta infrastruktura biznesowa czy prestiżowe środowisko inwestycyjne.


<p align="center">
    <a>
        <img src="assets/16 - Miliarderzy - miasta.png" width="450">
    </a>
</p>

Poprzedni wykres obejmował jedynie **9 miast**, w których mieszka największa liczba miliarderów. Tymczasem dane wskazują, że osoby z listy Forbes mają swoją rezydencję w **aż 789 różnych lokalizacjach na całym świecie**, czyli miejsca gdzie mieszka choćby jeden miliarder.

Aby lepiej zobrazować **geograficzne skupiska bogactwa**, przygotowałam mapę, na której każda lokalizacja została oznaczona punktem, a jego **wielkość odpowiada liczbie miliarderów** mieszkających w danym miejscu. Dzięki temu widzimy wyraźnie, że miliarderzy koncentrują się przede wszystkim w **trzech głównych obszarach**:

* **Wschodnie wybrzeże USA**, czyli przede wszystkim stan **Nowy Jork** i **Floryda**,
* **Środkowa Europa**, obejmująca **Niemcy**, **Szwajcarię** oraz **północne Włochy**,
* **Wschodnia Azja**, zdominowana przez **Chiny** (głównie prowincje Guangdong, Pekin i Zhejiang), a także **Hongkong** i **Tajwan**.

Warto również zwrócić uwagę na **Kalifornię**, gdzie widoczne jest wyraźne zagęszczenie lokalizacji, szczególnie w rejonie Doliny Krzemowej.

Na mapie wyraźnie widać również **brak intensywnych skupisk** w **Ameryce Południowej**, **Afryce** i **Australii**. W tych regionach punkty rezydencji miliarderów są nieliczne i rozproszone, co dodatkowo podkreśla nierówną geograficzną dystrybucję prywatnego bogactwa na świecie.


<p align="center">
    <a>
        <img src="assets/17 - Miliarderzy - mapa miasta.png" width="800">
    </a>
</p>

Wiemy już, skąd pochodzą miliarderzy i gdzie mieszkają dziś. Kolejnym krokiem w analizie jest odpowiedź na pytanie **Kim są?** W jakim są wieku, jakiej są płci i skąd pochodzi ich majątek?

Lista miliarderów magazynu Forbes jest **zdecydowanie zdominowana przez mężczyzn** na każde 15 osób na liście aż 13 to mężczyźni. Najwyżej notowaną kobietą jest **Alice Walton**, spadkobierczyni sieci Walmart, która z majątkiem wycenianym na **99 miliardów dolarów** zajmuje ona **16 miejsce** w globalnym rankingu.

<p align="center">
    <a>
        <img src="assets/Miliarderzy - top kobieta.png" width="600">
    </a>
</p>


Choć kobiet na liście jest znacznie mniej, to z punktu widzenia zgromadzonego majątku **różnice między płciami są zaskakująco niewielkie**. Średni majątek mężczyzn wynosi 2,46 miliarda dolarów, a kobiet 2,43 miliarda. To pokazuje, że kobiety, które trafiają na listę, są **przeciętnie równie zamożne** jak mężczyźni.

Jedną z podstawowych cech opisujących miliarderów jest wiek. Ponad połowa osób z listy znajduje się w przedziale **60-79 lat** jest to pokolenie urodzone tuż po zakończeniu II wojny światowej, często określane jako **baby boomers**. Co ciekawe, ta grupa odpowiada też za niemal połowę całkowitego majątku wszystkich miliarderów.

Choć intuicyjnie mogłoby się wydawać, że im ktoś starszy, tym więcej zgromadził majątku, jednak dane tego nie potwierdzają. **Wiek miliardera praktycznie nie ma wpływu na wysokość jego fortuny** - zależność między tymi dwoma czynnikami jest znikoma.

Nieco inaczej wygląda to w przypadku **kobiet**. U nich widać, że **starsze miliarderki mają przeciętnie nieco większy majątek niż młodsze**. Wśród mężczyzn taki związek nie występuje — ich wiek nie ma zauważalnego znaczenia dla poziomu zgromadzonego majątku.

<p align="center">
    <a>
        <img src="assets/18 - Miliarderzy - wiek 10lat.png" width="600">
    </a>
</p>

Wiek miliarderów z listy Forbes rozciąga się **od 19 do aż 103 lat**, a każdy rocznik jest reprezentowany co najmniej raz. Najmłodszym miliarderem jest **Johannes von Baumbach**, 19-letni niemiec, który wraz z rodzeństwem odziedziczył rodzinną firmę farmaceutyczną **Boehringer Ingelheim**. Z kolei najstarszym przedstawicielem rankingu jest **George Joseph**, 103-letni amerykanin, właściciel firmy ubezpieczeniowej **Mercury General Corporation**, który na początku dorosłego życia służył w armii podczas II wojny światowej.

<p align="center">
    <a>
        <img src="assets/Miliarderzy - wiek.png" width="600">
    </a>
</p>

Analiza wieku pokazuje, że najliczniej reprezentowane są dwie grupy wiekowe **59-63 lata** oraz **67-71 lat**. Każda z nich skupia po około **14,5% wszystkich miliarderów** i odpowiada za **14,3% całkowitego majątku** zgromadzonego przez osoby z listy. Co ciekawe, pomiędzy tymi dwoma „szczytami” znajduje się **trzyletni spadek liczebności (64-66 lat)**. Liczba miliarderów w tym wieku jest wyraźnie niższa od oczekiwanej, niestety trudno jednoznacznie stwierdzić, z czego to wynika. Jeśli masz pomysł na możliwe wyjaśnienie, chętnie go poznam.

Obecnie **przeciętny miliarder ma 66 lat**, a **najczęściej występujący wiek to 69 lat**.

<p align="center">
    <a>
        <img src="assets/19 - Miliarderzy - wiek.png" width="600">
    </a>
</p>

**Skąd pochodzi majątek miliarderów?** Czy to efekt własnej pracy, czy raczej spuścizna po poprzednich pokoleniach?

Z danych wynika, że **na każde 15 osób z listy aż 10 doszło do swojej fortuny samodzielnie**. Pozostała piątka odziedziczyła majątek przy czym **3 na 5 spadkobierców aktywnie rozwija odziedziczony kapitał**.

Warto też zwrócić uwagę na wyraźne różnice między płciami. **Kobiety na liście Forbes to w większości spadkobierczynie - aż 74% z nich odziedziczyło majątek**, a tylko nieliczne kontynuują jego rozwój. Dla porównania, **wśród mężczyzn aż 73% zbudowało majątek samodzielnie**, a wśród dziedziców przeważają ci, którzy nadal rozwijają swój kapitał.

Podobne różnice można zaobserwować na poziomie geograficznym. **W Azji i Ameryce Północnej ponad 70% miliarderów to osoby self-made**. Natomiast **w Europie tylko 45% miliarderów samodzielnie doszło do swojego majątku**, co wskazuje na silniejsze dziedziczenie fortun w tej części świata.

**Jeszcze większe różnice w strukturze majątku widać na poziomie poszczególnych krajów**. W takich państwach jak **Chiny**, **Rosja** czy **Wielka Brytania**, zdecydowana większość miliarderów (ponad 90%) zbudowała swój majątek samodzielnie. Z kolei w **Niemczech**, **Francji** i **Włoszech** przeważają fortuny dziedziczone, które często nie są dalej rozwijane.

<p align="center">
    <a>
        <img src="assets/20 - Miliarderzy - self-made.png" width="600">
    </a>
</p>

**Czym właściwie zajmują się najbogatsi?** W jakich branżach działa najwięcej miliarderów, a które odpowiadają za największy majątek?

W danych z listy Forbes wyróżniono **18 głównych branż**, w których funkcjonują miliarderzy - od technologii i finansów, przez modę, nieruchomości, media, energetykę, aż po branżę spożywczą.

**Najwięcej miliarderów działa w finansach i inwestycjach** łącznie 455 osób, czyli 15,8% całej listy. Jednak to **technologia odpowiada za największy łączny majątek**, aż 19,4% całkowitej wartości majątków miliarderów.

**Cztery najliczniejsze branże** - finanse i inwestycje, technologia, produkcja oraz moda i handel detaliczny, skupiają blisko **połowę wszystkich miliarderów** (49,1%) i odpowiadają za **ponad połowę globalnego majątku** (54,7%).

Najbogatsi przeciętnie działają w branży **motoryzacyjnej**, choć to jedna z najmniej licznych grup (zaledwie 73 osoby). Po drugiej stronie znajduje się **produkcja**, w której przeciętny majątek jest najniższy spośród wszystkich branż.

**Technologia** to również branża z **największym udziałem kapitałów wypracowanych samodzielnie**, aż 92% osób to miliarderzy self-made. Z kolei największy udział majątków dziedziczonych występuje w kategorii o **zdywersyfikowanej działalności**, gdzie jedynie 42% osób zbudowało swoją fortunę od podstaw.


<p align="center">
    <a>
        <img src="assets/21 - Miliarderzy - branza.png" width="600">
    </a>
</p>

Branże miliarderów różnią się nie tylko skalą majątku czy liczebnością przedstawicieli, ale także strukturą demograficzną i geograficzną. Jednym z ciekawszych wymiarów tych różnic jest udział kobiet w poszczególnych sektorach.

**Choć kobiety stanowią zaledwie ok. 13% wszystkich miliarderów**, w niektórych branżach ich obecność jest wyraźnie bardziej zauważalna. **Największy odsetek kobiet występuje w sektorze żywności i napojów**, gdzie aż **22%** osób na liście to miliarderki. Na przeciwnym biegunie znajdują się finanse i inwestycje - zaledwie 8,6% kobiet - oraz telekomunikacja, w której nie ma ani jednej kobiety. W ujęciu liczbowym najwięcej kobiet (52 osoby) działa w branży produkcyjnej.

Kolejną czynnikiem różnicującym jest **wiek**. Mediana wieku wszystkich miliarderów to 66 lat, jednak między branżami widać silne rozbieżności. **Technologia to zdecydowanie najmłodsza branża**, gdzie mediana wieku wynosi 56 lat. Z kolei w **motoryzacji działają osoby starsze**, przeciętny miliarder w tym sektorze ma 72 lata. Co ciekawe, to właśnie w tej branży występuje najwyższy przeciętny majątek, co może sugerować długotrwałe budowanie fortuny lub koncentrację kapitału wśród wąskiej grupy.

<p align="center">
    <a>
        <img src="assets/22 - Miliarderzy - mediana wieku.png" width="500">
    </a>
</p>

Zamiast uśrednionych wskaźników, **poniższa wizualizacja przedstawia każdą osobę z listy Forbes jako pojedynczy punkt**, z podziałem na branżę, wiek i płeć. Dzięki temu można dostrzec realny rozkład, zagęszczenia, wyjątki oraz proporcje kobiet i mężczyzn w pięciu największych sektorach.

* **Finanse i inwestycje** - branża z największą liczbą miliarderów, w której kobiety stanowią jedynie 8,6% wszystkich przedstawicieli.
* **Technologia** - najmłodszy sektor, z przeciętnym wiekiem wynoszącym 56 lat. Aż 92% osób z tej branży zbudowało swój majątek samodzielnie.
* **Produkcja** - branża z największą liczbą miliarderek (52 kobiety, 16,5% udziału). Dominuje tu pochodzenie azjatyckie, a przeciętny majątek jest najniższy spośród wszystkich sektorów.
* **Moda i handel detaliczny** - branża silnie europejska, z przewagą majątków dziedziczonych (42%).
* **Żywność i napoje** - sektor z najwyższym udziałem kobiet (22%) i znacznym odsetkiem fortun pochodzących z dziedziczenia (49%).

**Jeśli chcesz przyjrzeć się danym bliżej, zapraszam do [interaktywnej wersji wizualizacji](https://public.flourish.studio/visualisation/23240788/)**. Możesz tam filtrować osoby według poziomu majątku oraz sprawdzić szczegółowe informacje o każdej z nich - imię i nazwisko, kraj pochodzenia, wartość i źródło majątku oraz miejsce zamieszkania.

<p align="center">
    <a>
        <img src="assets/23 - Miliarderzy - beeswarm.png" width="700">
    </a>
</p>


**Rozkład geograficzny** również ujawnia ciekawe zależności.

Różne części świata specjalizują się w odmiennych gałęziach biznesu:
* **Azja dominuje w produkcji** - aż 60,8% miliarderów z tej branży pochodzi z tego kontynentu.
* **Europa to głównie moda i handel detaliczny** - 37,3% osób działających w tej branży to europejczycy.
* **Ameryka Północna skupia się na finansach (26,4%) oraz technologii (18,6%)** - dwóch sektorach, które jednocześnie odpowiadają za największy łączny majątek na świecie.

Na poziomie **krajów** (analizując 17 państw z największą liczbą miliarderów) wyraźnie widać lokalne specjalizacje:
* USA, Wielka Brytania i Brazylia - dominują finanse i inwestycje,
* Chiny i Niemcy - produkcja,
* Włochy i Francja -  moda i handel detaliczny,
* Indie i Szwajcaria -  ochronie zdrowia,
* Rosja - energetyka,
* Honkong i Singapur - nieruchomości.



<br>

## Dalsze kroki

Powyższa analiza opiera się na danych z listy Forbes z jednego momentu w czasie (stan na 10.04.2025), ale **wiele ważnych pytań wciąż pozostaje otwartych**. By je pogłębić, warto rozważyć rozszerzenie zbioru danych zarówno o informacje historyczne, jak i o dodatkowe wskaźniki makroekonomiczne.

* **Jak zmienia się lista miliarderów w czasie?** <br>
Czy jako globalne społeczeństwo bogacimy się coraz bardziej? A może lista odzwierciedla rosnącą koncentrację majątku w rękach nielicznych? Analiza porównawcza rok do roku pozwoliłaby zaobserwować wpływ takich zjawisk jak pandemia COVID-19, wojna w Ukrainie czy rozwój nowych technologii na liczbę miliarderów i ich łączny majątek.

* **W jakim wieku miliarderzy trafiają na listę?** <br> 
Czy można wyznaczyć „moment przełomowy” w karierze, który prowadzi do ekstremalnego bogactwa? Jak długa i stroma jest ścieżka do miliarda — i czy różni się w zależności od płci, branży lub regionu?

* **Kobiety na liście , czy ich udział rośnie?** <br>
Czy w ostatnich latach zwiększa się liczba miliarderek - zwłaszcza tych, które zbudowały majątek samodzielnie? Czy zmienia się branżowy i geograficzny rozkład ich obecności?

* **Emigracja: przed czy po zdobyciu miliarda?** <br>
W analizie zauważalna była znaczna migracja do Szwajcarii, Hongkongu, Singapuru czy Monako. Ale czy miliarderzy przenoszą się tam po osiągnięciu majątku (np. ze względów podatkowych), czy może te miejsca rzeczywiście sprzyjają budowaniu fortun?

* **Jakie znaczenie mają warunki makroekonomiczne kraju pochodzenia?** <br>
Dodanie wskaźników takich jak poziom edukacji, długość życia, inflacja, system podatkowy czy PKB pozwoliłoby zbadać, czy istnieje zależność między warunkami społeczno-ekonomicznymi a prawdopodobieństwem znalezienia się na liście Forbes. Kilka możliwych kierunków analizy:
    * Czy wyższy poziom edukacji przekłada się na większy odsetek self-made miliarderów?
    * Czy bogatsze kraje „produkują” więcej miliarderów - czy raczej tylko kumulują majątek?
    * Czy wysokie podatki lub inflacja wpływają na strukturę fortun lub decyzje migracyjne?








<br></br>
***

Dziękuję za Twoją uwagę! 🫶️

<!--
[Kolejny temat ➔ *Samobójstwa w Polsce - jak zmieniała się sytuacja w latach 1999-2024?*]()
-->

[Powrót do README #52wykresy2025](https://github.com/ElaWajdzik/Ongoing_Projects/tree/main/%2352wykresy2025)


<!--
https://www.forbes.com/real-time-billionaires/#3865b2243d78

## Wykres x-x: tytuł

opis

Kluczowe pytania na które szukałam odpowiedzi: 
* to
* tamto
 
<br>


### Czy wiesz, że...
 tekst tekst 

tekst tekst


### Przygotowane wizualizację:
* **wykres linowy** - opis
* **taki** - o tym

Wszystkie wizualizacje zostały przygotowane w programie **Datawrapper**, dodatkowo w programie **Canva** wprowadziłąm zmianę czcionki i koloru. Aby przejśc do interaktywnej wersji wykresów, kliknij w obrazek. 

<br>

<p align="center">
    <a href="https://www.datawrapper.de/_/gdikt/">
        <img src="assets/01 - Miasta - zmiana liczby ludności.png" width="600">
    </a>
</p>

***

-->