+++
title = "Pierwsze prototypy"
date = "2024-11-11T18:40:25+01:00"
author = "Przemysław Szafraniec"
+++

W ubiegłym tygodniu ogłosiliśmy, że jesteśmy w trakcie drukowania pierwszego prototypu naszego minisatelity. Niestety nie wszystko wyszło zgodnie z planem 😒

Okazało się, że pierwsza wersja miała kilka wad: nieodpowiednie odstępy między otworami na śruby (nasza płytka drukowana nie zmieściłaby się), zbyt grube ścianki (aż 5 mm!) oraz brak wystarczającej przestrzeni na montaż spadochronu (całość nie zmieściłaby się w [regulaminowych](https://esero.kopernik.org.pl/wp-content/uploads/2024/07/Regulamin-Konkursu-CanSat-2025.pdf#page=9) 115 mm).

{{< image src="/posts/2-first-prototypes/pomiar-1-2.jpg" position="center" style="max-height: 500px" >}}

Po pierwszej porażce projektowej od razu zabraliśmy się do pracy nad kolejną wersją obudowy, tym razem korzystając z bardziej precyzyjnych narzędzi dostępnych w programie FreeCAD. [Tryb sketch](https://wiki.freecad.org/PartDesign_Workbench) pozwolił nam używać rzeczywistych jednostek, zamiast posługiwać się współrzędnymi, wydłużyło to delikatnie czas pracy nad nowym prototypem ale wyeliminowało problem z odstępami na śruby.

W poprawionym modelu grubość sciany wyniosła ok. 2 mm a rozstaw otwórów tym razem był prawidłowy.

<span class="figure-container">
    {{< figure src="/posts/2-first-prototypes/pomiar-2-2.jpg" position="none" title="Średnica puszki" caption="Średnica puszki" style="max-height: 325px" >}}
    {{< figure src="/posts/2-first-prototypes/pomiar-3-2.jpg" position="none" title="Średnica wnętrza" caption="Średnica wnętrza" style="max-height: 325px" >}}
</span>

W obu wersjach spotkaliśmy się z tym samym problemem - nóżki, które zaprojektowaliśmy do zablokowania przykrywek w miejscu bardzo łatwo pękają przy nałożeniu na nie jakiejkolwiek siły. Na potrzeby testów przymocowaliśmy jedną klapkę taśmą aluminiową.

{{< image src="/posts/2-first-prototypes/porownanie-2.jpg" position="center" style="width: 668px" >}}

Dzięki modyfikacjom zauważyliśmy również znaczną redukcję masy obudowy — aż o 50%! Masa zmniejszyła się z 140 g do 70 g!

{{< image src="/posts/2-first-prototypes/porownanie-2-2.jpg" position="center" style="max-height: 500px" >}}

Już na dniach planujemy pierwsze testy spadochronowe, wszystkich zainteresowanych zapraszamy do dalszego śledzenia naszego bloga oraz strony na [Facebooku](https://www.facebook.com/profile.php?id=100064050254272).