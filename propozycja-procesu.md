**Discalaimer**: jestem laikiem, jeśli chodzi o politykę, prawo i ekonomię. Nie wkładam jakiegoś specjalnego wysiłku w śledzenie sytuacji w elitach rządzących czy zmian w prawie poza zakresem bezpośrednio dla mnie znaczącym (kodeks ruchu drogowego, niektóre zapisy podatkowe, itp). 

Aktualna sytuacja polityczna i prawna pozostawia wiele do życzenia i jest momentami niepokojąca. Procesy legislacyjne są prowadzone chaotycznie, niestarannie i w ogromnym pośpiechu co prowadzi do wielu błędów. W przygotowywanym prawie pojawiają się zapisy o wątpliwej wartości lub wręcz szkodliwe. Czasami ciężko się oprzeć wrażeniu, że mają na celu osiągnięcie korzyści jednostek. Proponowane i wprowadzane zmiany ciężko śledzić, nie ma czasu na ich konsultowanie czy - w niektórych przypadkach - nawet uważne przeczytanie przed procedowaniem. Duże pakiety zmian partie wyciągają z szuflady nie dając społeczeństwu na zapoznanie się z nimi, zgłoszenie poprawek lub sprzeciwu. W przypadku szkodliwych zapisów - nie ma możliwości dowiedzenia, kto i kiedy owe zmiany wprowadził. 

Z powyższych obserwacji wynika propozycja wprowadzenia kilku bardzo prostych, tanich i otwartych rozwiązań technicznych pozwalających na ułatwienie śledzenia i zwiększenie przejrzystości i wiarygodności procesów legislacyjnych. Niejako przy okazji tworzone dokumenty byłyby łatwe do publikowania zgodnie z wytycznymi WCAG, a dzięki temu łatwe do przetwarzania maszynowego, w tym również na urządzeniach potrzebnych np. niedowidzącym.

Prawo jest swego rodzaju kodem opisującym zasady współżycia społecznego. Dlaczego nie skorzystać z gotowych i dobrze przetestowanych przez miliony użytkowników narzędzi wykorzystywanych do zarządzania kodem w procesie tworzenia oprogramowania?

Proponuję skorzystać z Git-a jako systemu do przechowywania dokumentów, śledzenia zmian i prowadzenia uzgodnień. Dokumenty należałoby tworzyć w dokumentach ze znacznikami markdown, wiki, html lub innymi, łatwo edytowalnymi w dowolnym prostym edytorze tekstowym, również przez interfejs webowy. Zmiany można podpisywać cyfrowo aby umożliwić określenie odpowiedzialności za wprowadzone zapisy.

Najważniejsze cechy:
- Git pozwala na rozproszoną pracę, każda komisja, klub czy nawet grupa obywateli może mieć własne repozytorium
- Git umożliwia łatwe śledzenie zmian i ich przeglądanie w kontekście dokumentu
- Git ma wbudowane mechanizmy pozwalające na podpisywanie cyfrowe commitów
- Git umożliwia łatwe udostępnianie repozytoriów, np na platformie GitHub
- Istnieją rozwiązania pozwalające na postawienie własnego publicznego repozytorium na infrastrukturze rządowej
- Git oferuje możliwość równoległej pracy nad różnymi propozycjami zmian (branche)
- Git daje możliwość łatwego i przejrzystego scalania zmian zaproponowanych w gałęziach
- Git umożliwia określenie praw do scalania - tylko np marszałek sejmu miałby prawo zatwierdzić scalenie do głównej gałęzi po przegłosowaniu przez zgromadzenie
- Git jest oprogramowaniem bardzo dobrze przetestowanym, które udowodniło swoją przydatność w ogromnej ilości dużych projektów informatycznych
- Pliki tekstowe umożliwiają łatwą publikację automatyczną i konwersję do innych formatów
- Użycie plików tekstowych zapobiega zjawisku tzw vendor lock-in - są niezależne technologicznie
- Język znaczników markdown czy wiki jest bardzo prosty do opanowania, dużo łatwiejszy niż formatowanie np. w MS Word
- Pliki tekstowe formatowane znacznikami umożliwiają dostęp niepełnosprawnym dzięki łatwości publikacji zgodnie z wytycznymi WCAG - w przeciwieństwie do używanych do publikacji plików PDF
- GnuPG lub podobny system szyfrowania asymetrycznego z kluczem publicznym umożliwi łatwo weryfikowalne podpisywanie wprowadzanych zmian

Jeśli wprowadzenie powyższych narzędzi i technologii zostałoby poparte ustawowym przymusem publikowania propozycji zmian w prawie w publicznie dostępnych repozytoriach w trakcie ich tworzenia dałoby to wymierne korzyści:
- zarówno politycy jak i obywatele mieliby możliwość łatwego i czytelnego śledzenia proponowanych zmian w prawie
- dałoby to czas na zapoznanie się z propozycjami, a nie procedowanie ich w biegu bez możliwości dobrego rozpoznania
- dałoby czas na ich weryfikację prawną 
- umożliwiłoby łatwe prowadzenie konsultacji społecznych
- znacząco zwiększyłoby się prawdopodobieństwo wykrycia i usunięcia błędów w tworzonym prawie.

Wszystkie wyżej wymienione postulaty da się wprowadzić przy relatywnie małych nakładach finansowych i organizacyjnych - wszystkie konieczne narzędzia już istnieją, są dostępne w modelu open source i są wszechstronnie przetestowane przez ogromną ilość użytkowników.

