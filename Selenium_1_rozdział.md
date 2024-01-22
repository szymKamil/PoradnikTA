# Rozdział 1 - Wstęp do Selenium

## Czego potrzebujesz na wstępie? 
### Java
Testy automatyczne mają to do siebie, że stanowią formę większych lub mniejszych programów. Sądze, że nie popełniam tu błędu, skoro w sporej ilości  szkoleń dotyczących programowania z którymi miałem do czynienia "pierwszym programem" który tworzyłem było "Hello word!". W naszym przypadku korzystać będziemy z Javy. Czy niezbędny jest znajomość tego języka by przejść przez ten poradnik? Tak i nie. Wszystkie zagadnienia dotyczące testowania automatycznego (dalej TA) posatram się przybliżyć w maksymalnie uproszczony sposób. Nie będe jednak zatrzymywać się na każdym elemencie programowania, jak chociażby klasa w której umieszczamy testy, czy dlaczego piszemy "private static void main(String[] args)" by uruchomić kod. Zakładam jednak, że zainteresowana danym tematem osoba samodzielnie uzupełni swoją wiedzę w sieci. 
### IDE - Zintegrowane środowisko programistyczne
W przypadku tego poradnika korzystać będziemy z InteliJ. W moim krótkim doświadczeniu jest to najlepsze (i dedykowane) środowisko do pisania kodu w Javie. 
Nie znaczy to, ze jest to jedyne środowisko. Możesz korzystać także z Eclipse czy [Visual Studio Code](https://code.visualstudio.com/docs/java/java-testing). Robisz to jednak na własne ryzyko - w ogólnym działaniu IDE są do siebie podobne, jednak różnią się np. ustawieniami, interfejsem, itp. Jesli uznasz, że preferujesz inne IDE i poradzisz sobie samodzielnie na podstawie ogólnych wskazówek, to możesz to zrobić. Samemu, uszcząc się Selenium, zrezygnowałem z Eclipse (w którym prowadzone było szkolenie) własnie na rzecz InteliJ. 

* Pobieramy i instalujemy [InteliJ](https://www.jetbrains.com/idea/). Uwaga! Pobieramy Community Edition, który jest darmową wersją programu.
* Tworzymy nowy projekt (File -> New -> Project). Podajemy dowolną nazwę projektu, upewniamy się, że wybranym językiem jest Java, a sposób budowy projektu jest ustawiony na Maven. W oknie JDK wybieramy naszą wersję [JDK](https://www.oracle.com/pl/java/technologies/downloads/), którą mamy zainstalowaną w systemie. Zalecam wybór/pobranie 19. Jesteśmy już prawie gotowi do uruchomienia naszego pierwszego testu. 
![Sposób utworzenia nowego projektu](https://github.com/szymKamil/PoradnikTA/blob/main/Ilustracje/2024-01-22_11h50_27.gif) 

*** WebDriver 

