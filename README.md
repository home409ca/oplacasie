# OpłacaSię 2.0.0

Gotowa aplikacja na telefony ARM z Androidem 14 lub nowszym. Kalkulator promocji, porównywarka oraz prywatny magazyn i sprzedaż. Pakiet instalacyjny ma 23.71 MB, poniżej limitu 25 MB. Własna baza, zdjęcia i kopie to osobne dane użytkownika.

## Publikacja

1. W publicznym repozytorium „oplacasie” otwórz Releases → Draft a new release.
2. Utwórz tag **v2.0.0**, wybierz domyślną gałąź (np. main), tytuł **OpłacaSię 2.0.0**.
3. Do załączników wydania dodaj **OplacaSie-2.0.0.apk** i **OplacaSie-2.0.0.sha256** z tej paczki. Nie przesyłaj ZIP-a zamiast APK.
4. Nie oznaczaj jako pre-release. Opublikuj przez Publish release i ustaw jako najnowsze stabilne wydanie.
5. Samo umieszczenie APK w głównej liście plików repozytorium nie wystarcza — aplikacja odczytuje załączniki Releases.

W aplikacji, w Ustawienia → Aktualizacje, wpisz **TWÓJ_LOGIN/oplacasie**, zastępując TWÓJ_LOGIN rzeczywistym loginem właściciela GitHub. Przykład: adres https://github.com/jan-kowalski/oplacasie oznacza wpis **jan-kowalski/oplacasie**. Można też wkleić pełny adres głównej strony repozytorium, bez /releases i bez nazwy pliku APK.

Na starszej wersji opublikowane v2.0.0 zaoferuje pobranie. Na wersji 2.0.0 ten sam numer prawidłowo oznacza aktualną wersję. Instaluj jako aktualizację, bez odinstalowania poprzedniej aplikacji. Pakiet i podpis zachowano.

## Zmiany

- Magazyn, partie zakupowe, średnia ważona kosztu, sprzedaż i zwroty, korekty oraz archiwum.
- Lokalne skanowanie EAN-13, EAN-8, UPC-A/E, Code 128; ręczne produkty i wiele kodów.
- Zoptymalizowane zdjęcia, prywatne statystyki, publiczne oferty PDF/PNG.
- Prywatna kopia i odtwarzanie bazy ze zdjęciami. Kopii ZIP z telefonu nie publikuj — zawiera prywatne dane finansowe.
- Zachowane dotychczasowe funkcje kalkulatora i OCR; migracja bazy bez usuwania historii.

APK przeznaczony dla telefonów ARM64/ARM32, nie emulatorów x86. 122 testy komputerowe zaliczone; nie wykonano testu na fizycznym telefonie. Nie potwierdzono działania realnego aparatu i zewnętrznych aplikacji udostępniania.

Ta paczka ma wyłącznie APK, SHA-256 i README. Nie zawiera kodu, klucza podpisu, prywatnej bazy ani zdjęć użytkownika. Nie wymaga pliku latest.json ani serwera poza publicznym GitHub Releases.
