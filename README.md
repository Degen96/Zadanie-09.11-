# Zadanie-09.11-
//Zadania do opracowania
    //1. W jaki sposób możem w js zadeklarować zmienną jako pusty obiekt.
//Użyj dwóch znanych modyfikatorów "let" i "const" i opisz różnicę między nimi
 //Wpisując np Ver, const lub let n = null zadeklarujemy zmienną jako pustą.
//Różnica między let a const jest taka, że słowo kluczowe let deklaruje zmienną w zasięgu bloku,
//wraz z opcjonalnym zaincjalizowaniem wartością. 
//Słowo kluczowe const deklaruje stałe w zasięgu bloku, 
//podobne do słowa kluczowego let , ale nie można zmienić wartości tej stałej. 
//Deklaracja const tworzy referencję typu read-only do wartości.

    //2. Jakie znasz typ zmiennch w JSON. Wbierz czer z nich i opisz ich zastosowanie.

//-Typ boolean może przyjmować dwie wartości: true albo false.
//-Typ Number jest unikatowym zjawiskiem w językach programowania. 
//Może zarówno przechowywać liczbę całkowitą, jak i liczbę zmiennoprzecinkową. 
//-String to typ zmiennej, w której przechowywane są ciągi znaków. 
//Definiowanie ciągu znakowych następuje poprzez umieszczenie go w cudzysłowie ""
//-Typ Undefined to inaczej typ nieokreślony. Posiada jedną wartość w formie literału: undefined. 
//Typ ten jest automatycznie nadawany podczas deklarowania zmiennych.

    //3. Mając zadeklarowane dwie zmienne boolowskie isAuthorized oraz isClicked wyświetl paragrf 
//z opisem operacja udana jeśli obie są ustawione jako true i paragraf z opisem operacja nieudana 
//w przeciwnym wypadku.
//isAuthorized isClicked 



    //4. Jw. ale teraz wyświetl operacja udana gry WŁĄCZNIE JEDNA z nich jest true.



    //5. 



    //6.Za pomocą +:
    var string_1 = "To jest";
	var string_2 = "tekst";
	alert(string_1 + ' ' + string_2
    //Innym sposobem łączenia stringów w jeden jest skorzystanie z metody concat()
 var s1 = 'a';
 var s2 = 'b';
 var s3 = 'c';
 var s = s1.concat(s2, s3); // 'abc'

    //7.
    const tab = []; 

    const tab2 = [1, 2, 3, 4]; 
    
    const tab3 = ["to", "jest", "test"]; 


    var pos = 1, n = 3;

var usunieteElementy = to.splice(pos, n);
var usunieteElementy = test.splice(pos, n);

    //8.




    //9.Klasy w Javascript zostały wprowadzone w ECMAScript 2015 jako lukier składniowy (ang. syntactic sugar) dla istniejącego, 
    //opartego na prototypach modelu dziedziczenia. 
    //Klasy wprowadzają znacznie prostszą i bardziej czytelną składnię do tworzenia obiektów i dziedziczenia.


    //10.Konstruktor jest specjalną metodą tworzenia i inicjowania obiektu utworzonego w klasie
    //Konstruktor umożliwia zdefiniowanie inicjalizacji obiektu, która musi się wykonać, 
    //zanim będzie można wywołać metody obiektu. 
    //Klasa ValidationError nie musi mieć niestandardowego konstruktora, 
    //ponieważ domyślny konstruktor wywołuje konstruktor klasy Error .

    //11.Słowo kluczowe static definiuje statyczną metodę lub właściwość klasy. 
    //Statyczne metody to często funkcje służące na przykład do tworzenia czy klonowania obiektów, 
    //a statyczne właściwości są użyteczne do cache'ów, stałej konfiguracji lub innych właściwości, 
    //które nie muszą być powielane w instancjach.




    //12. Proces komunikacji w HTTP:
    //-DNS Lokup
    //-Ustaowieni połączenia TCP
    //-Wysłanie żądania HTTP
    //-oczekiwanie na odpowiedź serwera
    //-Odebranie pierwszego pakietu serwera.
    //-Odebanie drugiego segmentu CP z flagą PSH
    //-Klient odpowiada pakietem ACK co drugi segment z serwera
    //-Po odebraniu danch klient wysyła pakiet FIN do zakończenia połączenia TCP

    //W momencie zatwierdzenia adresu wpisanego w pasku przeglądarki
    //HTTP używa metody POST

    //DELETE - USUŃ, POST - utwórz NOWY rekord PATCH - aktualizacja/modyfikacja
