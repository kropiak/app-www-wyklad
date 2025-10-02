# Aplikacje WWW. Wykład #1


## 1. Czym jest aplikacja WWW/webowa/internetowa?

**Jest to aplikacja uruchamiana na serwerze, a dostęp do niej odbywa się przez przeglądarkę internetową bez konieczności instalacji na urządzeniu użytkownika.**

Aplikacją nazwiemy rozwiązanie, które wychodzi poza schemat klasycznej statycznej strony internetowej. Aplikacja dostarcza pewnej funkcjonalności, która poprzez technologie frontendowe pozwala na realizację pewnych zadań, które często były do tej pory realizowane poprzez aplikacje natywne.

Mogą to być aplikacje klasy CRM, portale społecznościowe z elementami komunikatorów, gry online, edytory tekstu, arkusze, klient e-mail i wiele innych.

> **Kilka wybranych cech aplikacji www:**
* uruchamiana na serwerze,
* architektura klient (przeglądarka) - serwer (serwer www + serwer aplikacji)
* komunikacja typu żądanie - odpowiedź,
* wymaga zazwyczaj (dla pełnej funkcjonalności) nieprzerwanego dostępu do Internetu,

> **Zalety aplikacji webowych**

* brak konieczności instalacji na urządzeniu, ale przede wszystkim aktualizacji do nowszych wersji (aktualizacja odbywa się centralnie czyli na serwerze),
* potencjalnie mniejszy koszt wytworzenia dla wielu różnych urządzeń klienckich, zwłaszcza całej gamy urządzeń mobilnych,
* większa dostępność ze względu na niskie wymagania (przeglądarka) aplikacji,
* stosunkowo łatwa adaptacja użytkownika do nowej aplikacji ze względu na podobieństwo aplikacji www i powszechność z korzystania z przeglądarek internetowych.


> **Wady aplikacji webowych**

* konieczność stałego dostępu do Internetu (o bolączkach można się przekonać zwłaszcza przy wypełnianiu i przesyłaniu rozległych formularzy), ale ta wada nie dotyczy aplikacji typu PWA (o nich za chwilę),
* ograniczone możliwości przechowywania danych z aplikacji lokalnie,
* potencjalnie mniejsza wydajność niektórych rozwiązań względem aplikacji natywnych,
* ograniczenia w dostępie do zasobów systemu operacyjnego i urządzeń lokalnych,
* konieczność dostosowania interfejsu do szerokiego spektrum urządzeń (wyświetlaczy) w ramach jednej aplikacji (brak aplikacji dedykowanych).

### A co z PWA (Progressive Web Applications)?

Aplikacje typu PWA, progresywne aplikacje webowe, są aplikacjami, które w pewnym stopniu łączą ze sobą cechy klasycznej aplikacji webowej oraz aplikacji natywnej.

> **Poniżej kilka z tych cech:**

* uruchamiane są w przeglądarce internetowej, ale wyglądają jakby były aplikacjami natywnymi,
* mogą być "zainstalowane" na urządzeniu klienckim (urządzenia mobilne, dekstop) i uruchamiane jak inne lokalne aplikacje bez konieczności wpisywania adresu w przeglądarce po raz kolejny,
* mogą pracować w trybie offline,
* wykorzystywane są znane już technologie takie jak HTML, CSS, JS,
* mogą korzystać z powiadomień push, systemu GPS, Bluetooth,
* nie wymagają tworzenia oddzielnych wersji dla różnych systemów operacyjnych,
* zawsze wykorzystują HTTPS.

## 2. Krótka historia aplikacji webowych.

> **rok 1989**

* Pierwsze propozycje projektu **World Wide Web** zaprezentowane przez **Tim'a Berners Lee** wewnątrz **CERN**.

> **rok 1991**

* zostaje uruchominy **pierwszy serwer webowy** w laboratorium  Stanford Linear Accelerator Center (SLAC) w stanie California (maszyna NeXT).
* Powstaje pierwsza strona internetowa (autor: **Tim Berners Lee**)
* **Tim Berners Lee** ogłasza światu projekt **World Wide Web**.
* **Tim Berners Lee** przedstawia szkic **pierwszej wersji języka HTML**.
* powstaje **protokół HTTP** (v0.9), który posiada tylko metodę GET


> **rok 1993**

* CERN po namowach uwalnia WWW dla wszystkich (wcześniej pobierano opłaty licencyjne).
* Powstaje **HTML 1.0**.
* Światło dzienne ujrzała przyjazna użytkownikom przeglądarka NCSA Mosaic z interfejsem graficznym.
* Powstaje interfejs CGI do komunikacji z serwerem WWW za pomocą języka HTML.

> **rok 1994**

* Powstaje serwis Yahoo!
* Pierwsza stabilna wersja języka Python została wydana.
* **Tim Berners Lee** ogłasza powstanie **World Wide Web Consortium (W3C)**
* Powstaje przeglądarka Netscape Navigator.

> **rok 1995**

* Pierwsze publiczne wydanie **PHP/FI** (Personal Home Page/Form Interpreter) w wersji 2.0, którego pierwsza nieoficjalna wersja powstała rok wcześniej za sprawą Rasmusa Lerdorfa.
* Powstała pierwsza wersja języka **JavaScript**. Twórcą jest **Brendan Eich**. (tu nieco więcej o historii JavaScript: https://www.w3schools.com/js/js_history.asp).
* Ogłoszona zostaje wersja 2.0 języka HTML.
* Powstaje przeglądarka Opera oraz Internet Explorer 1.0.
* Jeff Bezos uruchamian Amazon.com.

> **rok 1996**

* Firma Macromedia przejmuje technologię, którą nazwą później Macromedia Flash.
* powstaje **CSS (Cascade Style Sheet)**.
  
> **rok 1997**

* HTML 3.2.
* XML 1.0.
* XML-RPC.

> **rok 1998**

* Netscape przenosi swoją przeglądarkę do open source i powstaje Mozilla Organization (później Mozilla Foundation).
* CSS 2.0
* PHP 3.0
* Powstaje **Google**.

> **rok 1999**

* 24.12.1999 wychodzi wersja **HTML 4.01**.

> **rok 2000**

* powstaje zarys **Representational State Transfer (REST)** w pracy doktorskiej Roy'a Fielding'a.
* pęka bańka dotcomów.

> **rok 2001**

* 15.01.2001 - powstaje serwis **Wikipedia**.

> **rok 2002**

* Powstaje **AWS (Amazon Web Services)**.
* **JSON (JavaScript Object Notation)** zostaje zaprezentowany.

> **rok 2003**

* Przeglądarka **Safari** debiutuje.
* Powstaje **WordPress**.

> **rok 2004**

* Powstaje grupa **Web Hypertext Application Technology Working Group (WHATWG)** w opozycji do W3C i jej fokusowania się na rozwoju XHTML.
(Ian Hickson).
* Przeglądarka **Mozilla Firefox** debiutuje.
* Powstaje **Gmail**.

> **rok 2005**

* Debiutuje **Google Maps** oraz **YouTube**.
* Ogłoszono technologię **AJAX (Asynchronous Javascript and XML)**, Microsoft. Dała ona początek aplikacjom Rich Internet Application, znanych dzisiaj pod nazwą Single Page Application.
* **Webkit (Apple)** przechodzi w open source.
* Million DOlar Homepage (sprawdźcie sami!).
* Ruby on rails debiutuje.

> **rok 2006**

* powstaje pierwsza wersja **jQuery**.
* na świecie jest już ponad 100 000 000 stron internetowych.

> **rok 2008**

* 960.gs Framework.
* Debiutuje **Github**.
* Powstaje pierwsza wersja **Google Chrome**.
* Flexible Web Design, które jest początkiem ruchu w kierunku Responsive Web Design (artykuł Ethan'a Marcotte'a z roku 2010), który znamy do dziś.
* Szkic standardu **HTML 5** zostaje przedstawiony światu.

> **rok 2009**

* Debiutuje **Node.js**.

> **rok 2010**

* Powstaje **AngularJS**.

> **rok 2011**

* Framework **Bootstrap** debiutuje.
* Pojawia się technologia **WebSockets**.

> **rok 2012**

* Powstaje pierwsza wersja **TypeScript**.

> **rok 2013**

* Pierwsza wersja **React.js** zostaje zaprezentowana.


> **rok 2014**

* Debiutuje **Vue.js**.
* Sieć WWW liczy już ponad 1 000 000 000 stron internetowych.
* Standard **HTML 5 doczekał się upgrade'u oraz rekomendacji W3C**.

  
> **rok 2015**

* Wpis na blogu niejakiego Alexa Russell'a daje początek koncepcji **PWA (Progressive Web Applications)**.
* Po raz pierwszy ogłoszono prace nad technologią **WebAssembly**.

> **rok 2017**

* Adobe ogłasza koniec technologii Flash.
* Opublikowano pierwszą wersję WebAssembly.

> **rok 2019**

* WebAssembly otrzymało rekomendację W3C (w 2021 otrzymało również nagrodę Programming Languages Software Award)

> **teraz**
* rozwiązania oparte o AI potrafią wytwarzać większość mniej (to kwestia czasu) skomplikowanego kodu aplikacji webowych (ale i nie tylko).


Bardziej kompletna lista osadzona na osi czasu jest dostępna pod adresem: https://thehistoryoftheweb.com/timeline/.


## 3. Architektura aplikacji webowych.

Aplikacja webowa (ale dotyczy to również szerszego zakresu aplikacji) składa się zazwyczaj z trzech warstw aplikacji:

* **warstwa prezentacji (ang. frontend)** - jest to część, która odpowiada za interakcję użytkownika z aplikacją poprzez interfejs graficzny. Główne technologie to HTML, CSS oraz JavaScript.

* **warstwa logiki biznesowej (ang. backend)** - jest warstwa znajdująca sie po stronie serwera, która zawiera reguły działania aplikacji. Odpowiada za obsługę komunikatów z frontendu, ich przetwarzaniu, komunikacji z bazą danych i przekazanie wyników do aplikacji klienckiej.

* **warstwa dostępu do danych (bazy danych)** - system przechowywania i dostępu do danych.


Aplikacje webowe możemy również podzielić ze względu na modele architektoniczne.

Poniżej kilka popularnych rozwiązań architektonicznych:

* **architektura trójwarstwowa** - architektura, której składowe zostały opisane powyżej czyli frontend, backend i baza danych.

![3 warstwy](3_warstwy.svg)  
**Rysunek 1** - Architektura trójwarstwowa aplikacji webowej.

* **architektura mikrousług** - to podejście składa się z wyodrębnionych usług (np. usługa uwierzytelniania, usługa pamięci podręcznej, itp.), które zazwyczaj odpowiadają za jedną funkcję biznesową aplikacji. Takie podejście umożliwia bardziej dynamiczne skalowanie poszczególnych usług w zależności od potrzeb (np. obciążenia) dzięki takim rozwiązaniom jak konteneryzacja.

![](microservice_architecture_v2.png)  
**Rysunek 2** - Przykładowa architektura rozwiązania opartego o mikrousługi.

_źródło: https://atlassian.com_

* **architektura Web-Queue-Worker** - model wykorzystywany zazwyczaj w przypadku aplikacji, które obsługują długotrwałe i zasobożerne operacje, które tutaj realizowane są poprzez workera oraz kolejkę komunikatów.

* **architektura SPA (Single Page Architecture)** - aplikacja jednostronicowa (czasem nazywana jednoplikową, gdyż składa się z jednego pliku HTML), której zawartość jest przeładowywana z wykorzystaniem technologii AJAX i przypomina to pracę aplikacji natywnej.

**Monolit vs aplikacja oparta o mikrousługi**
---
### Aplikacja monolityczna

Aplikacja **monolityczna** charakteryzuje się samodzielnością działania (realizuje wszystkie usługi w ramach jednej aplikacji), chociaż może komunikować się z innymi systemamy zewnętrznymi. Składowe tej aplikacji są ze sobą znacznie sztywniej powiązane niż w przypadku aplikacji opartej o mikrousługi.


> **Główne zalety monolitu to:**

* **łatwiejsze wdrażanie i rozwój** - aplikacja stanowi jedną całość ułatwiając zarządzanie infrastrukturą oraz kodem,
* **mniejsze opóźnienia** - dzięki monolitycznej naturze nie ma konieczności komunikacji z wieloma usługami w celu obsługi żądania co skraca czas jego realizacji,
* **łatwiejsze testowanie** - podobnie jak przy zarzadzaniu kodem tak i tutaj rozproszona natura aplikacji powoduje konieczność przetestowania jej komponentów w rozproszonym środowisku,
* **niższe koszty infrastruktury** - ze względu na rozbudowaną architekturę mikrousług, jej konfiguracja może pociągnąć za sobą większe koszty infrastruktury w stosunku do monolitu.

> ‍**Główne wady monolitu to:**


* **kosztowne skalowanie** – konieczność skalowania całej aplikacji lub znacznej jej części w przypadku niewystarczającej wydajności,
* **problematyczna aktualizacja** – każda zmiana wymaga ponownego wdrożenia całości,
* **zmiany technologiczne** - zmiana technologii lub frameworka jest skomplikowana, ponieważ dotyka całego systemu,
* **potencjalne większe koszty awarii** - awaria aplikacji może powodować brak dostępu do całego systemu, co w przypadku mikrousług może zostać zredukowane poprzez większą redundancję poszczególnych jego składowych.


> **Skalowanie aplikacji monolitycznej**

Skalowanie aplikacji monolitycznej odbywa się w poziomie i polega na skalowaniu jednej lub wielu jej warstw. Zazwyczaj dotyczy to warstwy backend lub bazodanowej i polega na uruchomieniu kolejnej instancji tej warstwy w postaci serwera fizycznego lub maszyny wirtualnej.


Schematów skalowania jest co najmniej kilka. Przytoczę dwa poniżej.

**Skalowanie warstwy backend**

![](skalowanie_backend.svg)  
**Rysunek 3** - Przykład architektury systemu ze skalowaniem poziomym warstwy backend.

Tutaj mamy do czynienia ze skalowaniem tylko warstwy backend, która w porównaniu do warstwy frontend generuje zazwyczaj znaczne obciążenie dla serwera.
Takie rozwiązanie ma sens o ile tzw. "wąskim gardłem" całej aplikacji jest backend a nie baza danych.

**Skalowanie warstwy backend oraz warstwy bazy danych**

![](skalowanie_backend_i_baza.svg)  
**Rysunek 4** - Przykład architektury systemu ze skalowaniem poziomym warstwy backend oraz warstwy danych.

![](skalowanie_backend_i_baza_2.svg)  
**Rysunek 5** - Przykład architektury systemu ze skalowaniem poziomym warstwy backend.

Tu natomiast mamy do czynienia ze skalowaniem dwóch warstw - backendu oraz bazy danych. To rozwiązanie może być realizowane w kilku wariantach:
* serwer backend oraz oddzielny serwer bazy danych,
* serwer backend oraz bazy danych to jedna maszyna.

Oba te rozwiązania wymagają mechanizmu replikacji między serwerami bazy danych, który wprowadza dodatkową komplikację, ale i opóźnienie w dostępnie do danych.

**Skalowanie warstwy frontend**

Dzięki takim mechanizmom jak **pamięć podręczna (ang. cache)** można znacznie zredukować obciążenie serwera w kontekście serwowania **statycznej zawartości (pliki html, js, grafika, video)** co powoduje, że frontend podlega skalowaniu rzadziej. Często są tu wykorzystywane tzw. **CDN (Content Delivery Network)**, które dzięki replikacji zawartości statycznej pomiędzy wiele lokalizacji rozsianych na świecie pozwalają "skrócić drogę" tych danych do klienta co skutkuje skróceniem czasu pobrania danych oraz wprowadza redundancję danych.

### Aplikacja oparta o mikrousługi

Jak zostało już wspomniane aplikacja oparta o mikrousługi oferuje możliwość wyodrębnienia pewnych części systemu (aplikacji) do mniejszego komponentu (mikrousługi), która następnie może zostać osadzona w postaci lekkiego kontenera i zwielokrotniana jeżeli obciążenie systemu tego wymaga. To podejście umożliwia zwiększanie wydajności aplikacji w miejscach, które tego wymagają, a nie dla całej aplikacji. Może akurat potrzeba większej wydajności obsługi pamięci podręcznej, a nie systemu uwierzytelniania? 

Takie podejście wymaga oczywiście nieco więcej pracy niż w przypadku monolitu, gdyż należy wyodrębnić i zaprojektować te części aplikacji, które do takich mikrousług należy migrować.


> **Zalety aplikacji opartych o mikrousługi:**

* **łatwość skalowania** - jak już mikrousługi zostaną wyodrębnione i osadzone w postaci kontenerów w odpowiednim systemie ich orkiestracji to skalowanie można nawet zupełnie zautomatyzować określając pewne reguły tworzenia lub terminacji kolejnych instancji kontenerów,
* **aktualizacja technologiczna** - wprowadzenie zmian w ramach jednej usługi nie musi nieść za sobą konieczności zmian w innych częściach aplikacji,
* **elastyczność aktualizacji** - aktualizacje mogą być wdrażane stopniowo dla poszczególnych usług,
* **odporność na awarie** - dzięki redundancji oraz odpowiedniej konfiguracji awaria jednej usługi nie musi nieść za sobą niedostępności całej aplikacji,


> **Wady aplikacji opartych o mikrousługi:**

* **stopień skomplikowania** - takie aplikacje są zazwyczaj bardziej skomplikowane pod kątem architektury i wzajemnych powiązań i komunikacji między poszczególnymi usługami,
* **większe opóźnienia** - przez konieczność komunikacji między wieloma usługami opóźnienia mogą być większe niż w przypadku aplikacji monolitycznej,
* **koszty** - ze względu na większy stopień skomplikowania całej infrastruktury koszty wdrożenia oraz utrzymania takiej aplikacji mogą być wyższe, ale to zależy również tego czy skalowanie zostało odpowiednio zoptymalizowane względem podobnej wydajności aplikacji monolitycznej,
* **zarządzanie danymi** - problem synchronizacji danych między wieloma usługami może być dość skomplikowany do wdrożenia.

### 4. Kilka ciekawostek.

1. Jak wygląda aktualnie udział przeglądarek internetowych w rynku? Sprawdź: https://gs.statcounter.com/
2. Jaka technologia (oczywiście nie ma 100% pewności, że tylko te) została wykorzystana w danej stronie internetowej? Sprawdź: https://builtwith.com/
3. Które strony internetowe są najczęściej odwiedzanymi na świecie? A w Polsce? Sprawdź: https://www.semrush.com/website/top/ oraz https://www.similarweb.com/top-websites/
4. Milion dolarów! Wspomniana wcześniej strona: https://thehistoryoftheweb.com/the-power-of-the-pixel/ oraz nagroda za surfowanie po Internecie i wypełnianie formularzy: https://thehistoryoftheweb.com/they-offered-a-million-dollars-to-surf-the-web-somebody-won/
5. Inne spojrzenie na historię aplikacji webowych: https://www.matthewgerstman.com/tech/history-of-the-web/
6. Krótko o początkach całej historii prosto ze źródła: https://home.cern/science/computing/birth-web/short-history-web
7. Ankieta Stack Overflow odnośnie technologii webowych: https://survey.stackoverflow.co/2025/technology#1-web-frameworks-and-technologies
8. Nieco z innej beczki, ale warto wiedzieć skąd wziął się null pointer reference... https://en.wikipedia.org/wiki/Null_pointer#History


_&copy; Krzysztof Ropiak, 2025_