1. Nazwa projektu: AR-Shooter-Prototype
Gatunek: Shooter z perspektywy pierwszej osoby (FPP) w rozszerzonej rzeczywistości (AR).

Platformy docelowe: Smartfony z systemem iOS i Android.

2. Wizja i cel
Celem prototypu jest stworzenie w pełni działającej pętli rozgrywki w AR, która pokaże, jak wciągająca może być walka z wirtualnymi przeciwnikami w realnym świecie.

3. Mechanika rozgrywki
3.1. Inicjalizacja gry
Po uruchomieniu, aplikacja używa kamery, aby automatycznie przeskanować otoczenie w poszukiwaniu płaskich powierzchni (podłogi, stoły).

Po wykryciu powierzchni, na ekranie pojawi się wirtualny celownik, który wskaże, gdzie można umieścić pierwszy portal. Użytkownik dotyka ekranu, by rozpocząć grę.

3.2. Pojawianie się wrogów
W losowych miejscach na wykrytych powierzchniach pojawiają się portale teleportacyjne.

Z portali wyłania się pojedynczy typ wroga — mały, prosty potwór, który powoli porusza się w kierunku gracza.

3.3. Walka
Celowanie: Gracz celuje, obracając telefon w realnym świecie. Celownik na ekranie zawsze wskazuje środek.

Strzelanie: Wystrzał następuje po dotknięciu ekranu. Każdy strzał powoduje wibracje telefonu oraz efekt wizualny i dźwiękowy.

Okluzja: Wrogowie będą wchodzić za realne przedmioty w pokoju i częściowo znikać (ich widoczność będzie blokowana przez niewidzialne wirtualne przeszkody).

3.4. System zdrowia i punktacja
Wróg ma punkty zdrowia. Gracz musi trafić go kilka razy, aby go pokonać.

Po pokonaniu wroga, gracz otrzymuje punkty. Po pewnym czasie pojawi się nowy przeciwnik.

Gra kończy się, gdy potwór dotrze do gracza.

4. Interfejs użytkownika (UI) i dźwięk
UI: Interfejs jest minimalistyczny. Na ekranie widoczny jest tylko celownik oraz licznik punktów.

Dźwięk: Dźwięki strzału, teleportacji i chodu potwora mają być dźwiękiem pozycyjnym, co pomoże graczowi zorientować się, skąd nadchodzi zagrożenie, nawet gdy go nie widzi.

5. Modele i grafika
Przeciwnik: Jeden typ wroga, z prostymi animacjami.

Efekty wizualne: Błysk teleportacji, efekt strzału i eksplozja wroga po pokonaniu.

To GDD skupia się na stworzeniu minimum funkcjonalnego projektu, który można przetestować i pokazać. Jest to pierwszy, ale najważniejszy krok w kierunku stworzenia większej gry.
