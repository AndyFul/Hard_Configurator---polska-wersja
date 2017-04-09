#Hard_Configurator - polskie pliki pomocy i polskie menu. Nie jest to pełna polska wersja bo niektóre komunikaty są po angielsku (wbudowane w kod programu). 

W nowej wersji (Creators Update), Windows SmartScreen działa inaczej i odbija się to na opcji <Run As SmartScreen>. Forsowanie sprawdzania uruchamianych aplikacji przez SmartScreen w ustawieniu <Run As SmartScreen> = 'Administrator', nie działa. Co dziwne, działa w ustawieniu <Run As SmartScreen> = 'Standard User', a oba ustawienia różnią się tylko uprawnieniami.

Na chwilę obecną rekomendowane (bezpieczne) ustawienia to: 
<Run As SmartScreen> = 'Standard User'
<Hide 'Run As Administrator> = 'OFF'

W tych ustawieniach (przy aktywnych SRP), nowe pliki wykonywalne (np. pliki do zainstalowania) uruchamiamy z menu kontekstowego Eksploratora 2 razy :
(1) 'Run By SmartScreen', wtedy plik zostaje zablokowany, ale przedtem jest sprawdzany przez SmartScreen.
(2) 'Uruchom jako administrator' plik jest uruchamiany z uprawnieniami Administratora (nie jest blokowany przez SRP).

W punkcie (1) SmartScreen + SRP działają jak skaner antimalware drugiej opinii. 


1. Hard_Configurator jest przeznaczony do pracy w wersjach: Windows Vista i nowszych. Wykorzystuje wbudowane w system Windows ograniczenia związane z uruchamianiem plików mogących zawierać kod wykonywalny (programy, skrypty, itp.). 
 
2. Hard_Configurator nie pretenduje do miana samodzielnej ochrony komputera, jest uzupełnieniem standardowej ochrony antywirusowej. Minimalny sensowny zestaw powinien zawierać co najmniej skaner drugiej opinii (np. Hitman Pro). W Windows 8+ rolę skanera drugiej opinii może pełnić SmartScreen (opcja 'Run As SmartScreen' w Hard_Configuratorze).  
Ochrona oprogramowania komputera zwykle nie jest silniejsza niż sam system, więc ważne jest aby był on systematycznie aktualizowany, podobnie jak zainstalowane programy. 
Ważne jest również, aby używać bezpiecznej Przeglądarki Internetowej najlepiej z piaskownicą (Edge, Google Chrome, itp.), oraz Edytora Tekstu z wyłączonymi makrami. 

3. Po włączeniu zlecanych funkcji, użytkownik uzyskuje bardzo dobry, nie wymagający częstych interwencji, system zabezpieczeń. Ograniczenia wprowadzone przez Hard_Configuratora są tak dobrane aby nie były odczuwalne w codziennej pracy z komputerem. Praktycznie wszystkie zainstalowane w systemie programy da się uruchamiać tak jak zwykle, tj. klikając myszką lub wciskając klawisz Enter.  

4. Podczas dokonywania aktualizacji Windows i realizacji Harmonogramu Zadań (konserwacja systemu) nie ma potrzeby wyłączania zastosowanych ograniczeń. 
 
5. Nowe programy możemy instalować za pomocą opcji 'Uruchom jako administrator' (Windows Vista, Windows 7) lub 'Run As SmartScreen' (Windows 8+) w menu kontekstowym Eksploratora Windows. Programy pobrane za pomocą Przeglądarki Internetowej nie mogą być z niej bezpośrednio uruchamiane. Trzeba je najpierw zapamiętać, a następnie można je uruchomić z katalogu Pobrane, za pomocą opcji 'Uruchom jako administrator' lub 'Run As SmartScreen'. Aplikacje typu portable umiejscowione poza katalogami Windows i Program Files (oraz Program Files (x86) dla wersji 64 Bitowej Windows), mogą być dołączone do Białej Listy za pomocą Hard_Configuratora, a następnie uruchamiane jak zwykle.  

6. W codziennej pracy z komputerem skonfigurowanym z zalecanymi ustawieniami Hard_Configuratora, dobrze jest pamiętać poniższe zasady: 
* Zainstalowane programy uruchamiamy jak zwykle (lewy klik myszki lub klawisz Enter). 
* Dokumenty, pliki medialne, zdjęcia, itp. otwieramy jak zwykle (lewy klik myszki lub klawisz Enter). 
* Pliki instalacyjne programów z katalogu 'Pobrane' lub innego katalogu użytkownika, uruchamiamy zawsze klikając prawy przycisk myszki, wybierając następnie z menu kontekstowego Eksploratora Windows opcję 'Run As SmartScreen' (Windows 8+). W starszych wersjach Windows (Windows Vista, Windows 7), musimy użyć menu kontekstowego Eksploratora Windows dwukrotnie. Pierwszy raz wybieramy skanowanie pliku instalacyjnego przez program antywirusowy, a drugi raz aby wybrać 'Uruchom jako administrator'. 
* Jeśli plik instalacyjny programu będziemy chcieli uruchomić w zwykły sposób (lewy klik myszki lub klawisz Enter) to zostanie on zablokowany. Dotyczy to również wielu innych plików z kodem wykonywalnym - lista blokowanych typów plików, może być skonfigurowana w Hard_Configuratorze - domyślnie blokowane są typy plików, które były często wykorzystywane przez twórców złośliwego oprogramowania. 

7. Zasady bezpiecznego użytkownika.  

   Alerty Kontroli konta użytkownika. 
* Jeśli alert pojawia się gdy sami chcemy zainstalować nowy program, wybieramy 'TAK'. 
* Jeśli alert pojawia się gdy uruchamiamy zainstalowany, sprawdzony program, wybieramy 'TAK'. 
* W pozostałych przypadkach, zawsze w pierwszym odruchu wybieramy 'NIE', a następnie szukamy przyczyny, lub dzwonimy do bardziej doświadczonej osoby. 

   Alerty SmartScreen 
* Zawsze wybieramy 'Nie uruchamiaj' i staramy się sprawdzić program online (jeśli się na tym znamy), lub dzwonimy do bardziej doświadczonej osoby. Zawsze możemy też wybrać program alternatywny, który jest uznany, przez SmartScreen lub skaner drugiej opinii, jako bezpieczny. 

8. Ochrona Hard_Configuratora jest tym silniejsza im silniejszy (bardziej bezpieczny) jest system operacyjny. Najbardziej zyskują więc użytkownicy Windows 10, z różnych powodów:
* Popularne programy antywirusowe/antimalware mają czasami problemy z kompatybilnością, zwłaszcza po większych aktualizacjach Windows 10. 
* Windows Defender jest pełnoprawnym programem antywirusowym, począwszy od Windows 8. 
* Windows 10 posiada niezłą i bardzo bezpieczną przeglądarkę Edge oraz sporo niezłych i bezpiecznych Uniwersalnych Aplikacji.
* Systematycznie aktualizowany Windows 10, jest dosyć odporny na ataki wykorzystujące luki systemowe.

Tak więc, w Windows 10 można zbudować bardzo silną ochronę nie używając programów zabezpieczających (działających w tle) innych firm.
Hard_Configurator jest programem konfiguracyjnym, po dokonaniu konfiguracji można go zamknąć i jego procesy znikają z systemu. Całość ochrony przejmuje system Windows. Jedynie "Run As SmartScreen" jest na moment uruchamiany gdy użytkownik chce zainstalować nowy program.
