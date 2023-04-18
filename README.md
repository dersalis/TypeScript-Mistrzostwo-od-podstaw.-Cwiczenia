
# TypeScript: Mistrzostwo od podstaw. Ćwiczenia

Cześć! Witajcie w skrypcie z ćwiczeniami z języka programowania TypeScript - miejscu, gdzie możecie poznać ten wspaniały język i utrwalić swoją wiedzę dzięki praktycznym zadaniom. Jeśli jesteście początkującymi programistami lub posiadacie już doświadczenie w innych językach programowania, ale chcecie zdobyć nowe umiejętności, to jesteście we właściwym miejscu!

TypeScript to język programowania, który jest rozszerzeniem języka JavaScript i dodaje do niego statyczną analizę typów. To oznacza, że możecie uniknąć wielu błędów i problemy związanych z typami, co ułatwi Wam pracę i przyspieszy proces debugowania. TypeScript jest stosunkowo łatwy do nauki, a jego składnia jest bardzo podobna do JavaScriptu, co sprawia, że nauka tego języka jest bardzo przyjemna.

W naszym skrypcie znajdziecie wiele zadań, które pomogą Wam w praktycznym opanowaniu TypeScriptu. Będziecie mieli okazję nauczyć się podstawowych koncepcji, takich jak typy podstawowe i złożone, interfejsy, klasy i dziedziczenie. Będziecie mieli także okazję nauczyć się bardziej zaawansowanych tematów, takich jak moduły, generyki i dekoratory.

Jesteśmy pewni, że podczas wykonywania zadań nie tylko nauczycie się programowania w TypeScript, ale także zaczniecie go kochać! Dajcie nam znać, jeśli macie jakiekolwiek pytania lub sugestie. Powodzenia!

*Skrypt ten dedykuje moje Muzie - do dzieła Słodka!*

## Zadania

1. Napisz funkcję, która zsumuje wszystkie liczby parzyste z przedziału od 1 do podanej liczby.
2. Napisz program, który pobiera od użytkownika listę liczb i zwraca ich sumę.
3. Napisz funkcję, która przyjmuje jako argument napis i zwraca go w odwrotnej kolejności.
4. Napisz klasę, która reprezentuje koło i ma metody zwracające jego pole powierzchni oraz obwód.
5. Napisz program, który pobiera od użytkownika dwie liczby i wyświetla ich iloczyn.
6. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę posortowaną rosnąco.
7. Napisz program, który pobiera od użytkownika imię i wyświetla powitanie.
8. Napisz funkcję, która przyjmuje jako argument napis i zwraca true, jeśli jest on palindromem, false w przeciwnym przypadku.
9. Napisz klasę, która reprezentuje książkę i ma pola tytuł i autor oraz metody zwracające te dane.
10. Napisz program, który pobiera od użytkownika trzy liczby i wyświetla je w kolejności od najmniejszej do największej.
11. Napisz funkcję, która przyjmuje jako argument napis i zwraca go w postaci odwrotnej, ale bez odwracania kolejności słów.
12. Napisz program, który pobiera od użytkownika listę liczb i zwraca ich średnią arytmetyczną.
13. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca sumę liczb znajdujących się na nieparzystych indeksach.
14. Napisz klasę, która reprezentuje punkt na płaszczyźnie i ma pola x i y oraz metody zwracające te wartości.
15. Napisz program, który pobiera od użytkownika zestaw liczb i wyświetla największą z nich.
16. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę zawierającą wszystkie elemeny tablicy pierwotnej, ale bez duplikatów.
17. Napisz program, który pobiera od użytkownika długość boku kwadratu i wyświetla jego pole powierzchni.
18. Napisz funkcję, która przyjmuje jako argument napis i zwraca go bez spacji.
19. Napisz klasę, która reprezentuje trójkąt i ma metody zwracające jego pole powierzchni oraz obwód.
20. Napisz program, który pobiera liczby od użytkownika, jedną po drugiej, aż użytkownik wprowadzi liczbę 0, po czym wyświetla sumę wprowadzonych liczb.

1. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę z dodanymi do nich ich indeksami.
2. Napisz program, który pobiera od użytkownika długość promienia i wysokość stożka i wyświetla jego objętość.
3. Napisz funkcję, która przyjmuje jako argument dwie tablice i zwraca tablicę z elementami obu tablic.
4. Napisz klasę, która reprezentuje punkt na przestrzeni trójwymiarowej i ma pola x, y i z oraz metody zwracające te wartości.
5. Napisz program, który pobiera od użytkownika napis i wyświetla go z zamienionymi miejscami pierwszą i ostatnią literą.
6. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę z liczbami unikalnymi oraz ich liczbą wystąpień.
7. Napisz program, który pobiera od użytkownika liczbę i wyświetla napis "parzysta" jeśli liczba jest parzysta, "nieparzysta" w przeciwnym przypadku.
8. Napisz funkcję, która przyjmuje jako argument napis i zwraca go bez powtórzeń.
9. Napisz klasę, która reprezentuje samochód i ma pola marka i rok produkcji oraz metody zwracające te dane.
10. Napisz program, który pobiera od użytkownika dwie liczby i wyświetla ich iloraz.
11. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę zawierającą tylko liczby dodatnie.
12. Napisz program, który pobiera od użytkownika liczbę i wyświetla jej silnię.
13. Napisz funkcję, która przyjmuje jako argument napis i zwraca go w postaci, w której pierwsza litera każdego wyrazu jest duża.
14. Napisz klasę, która reprezentuje prostokąt i ma pola długość i szerokość oraz metody zwracające te wartości.
15. Napisz program, który pobiera od użytkownika napis i wyświetla go w odwrotnej kolejności.
16. Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę zawierającą tylko liczby parzyste.
17. Napisz program, który pobiera od użytkownika liczbę i wyświetla informację, czy jest to liczba pierwsza.
18. Napisz funkcję, która przyjmuje jako argument obiekt typu Map i zwraca tablicę zawierającą klucze tej mapy.
19. Napisz klasę, która reprezentuje koło i ma pola promień oraz metody zwracające jego pole powierzchni i obwód.
20. Napisz program, który pobiera od użytkownika trzy liczby i wyświetla je w kolejności od największej do najmniejszej.


## Rozwiązania

### Zadanie 1
**Napisz funkcję, która zsumuje wszystkie liczby parzyste z przedziału od 1 do podanej liczby.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Zdefiniuj typ wejściowy funkcji, który określi, że funkcja przyjmuje pojedynczy parametr liczbowy o nazwie `n`, który będzie wyznaczał górną granicę przedziału liczb, które mają być zsumowane.

```typescript
function sumEvenNumbers(n: number): number {
  // ciało funkcji
}
```

3. Zadeklaruj zmienną `sum` i przypisz jej początkową wartość 0. Ta zmienna będzie służyć do przechowywania sumy liczb parzystych.

```typescript
function sumEvenNumbers(n: number): number {
  let sum = 0;
  // ciało funkcji
}
```

4. Napisz pętlę `for`, która będzie iterować po kolejnych liczbach od 1 do `n`. W każdej iteracji pętli sprawdź, czy aktualna liczba jest parzysta. Jeśli tak, dodaj ją do zmiennej `sum`.

```typescript
function sumEvenNumbers(n: number): number {
  let sum = 0;
  for (let i = 1; i <= n; i++) {
    if (i % 2 === 0) {
      sum += i;
    }
  }
  return sum;
}
```

5. Zwróć wartość zmiennej `sum` jako wynik działania funkcji.

6. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

7. Przetestuj funkcję, wywołując ją z różnymi argumentami i upewnij się, że działa poprawnie.

Gotowa funkcja powinna wyglądać następująco:

```typescript
function sumEvenNumbers(n: number): number {
  let sum = 0;
  for (let i = 1; i <= n; i++) {
    if (i % 2 === 0) {
      sum += i;
    }
  }
  return sum;
}
```


### Zadanie 2
**Napisz program, który pobiera od użytkownika listę liczb i zwraca ich sumę.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Zdefiniuj typ wejściowy programu, który określi, że program pobiera listę liczb. Aby to zrobić, możesz zadeklarować tablicę typu `number[]`.

```typescript
function sumNumbers(numbers: number[]): number {
  // ciało programu
}
```

3. Zadeklaruj zmienną `sum` i przypisz jej początkową wartość 0. Ta zmienna będzie służyć do przechowywania sumy liczb.

```typescript
function sumNumbers(numbers: number[]): number {
  let sum = 0;
  // ciało programu
}
```

4. Napisz pętlę `for`, która będzie iterować po każdej liczbie w tablicy `numbers`. W każdej iteracji pętli dodaj aktualną liczbę do zmiennej `sum`.

```typescript
function sumNumbers(numbers: number[]): number {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum;
}
```

5. Zwróć wartość zmiennej `sum` jako wynik działania programu.

6. Napisz funkcję, która pobiera od użytkownika listę liczb i przekazuje ją do funkcji `sumNumbers`. Aby pobrać listę liczb od użytkownika, można wykorzystać metodę `prompt` dla każdej liczby.

```typescript
function readNumbersFromUser(): number[] {
  const numbers: number[] = [];
  let userInput: string | null = prompt('Podaj liczbę (lub naciśnij Anuluj, aby zakończyć):');
  while (userInput !== null) {
    const parsedNumber = parseFloat(userInput);
    if (!isNaN(parsedNumber)) {
      numbers.push(parsedNumber);
    }
    userInput = prompt('Podaj liczbę (lub naciśnij Anuluj, aby zakończyć):');
  }
  return numbers;
}

const numbers = readNumbersFromUser();
const sum = sumNumbers(numbers);
console.log(`Suma liczb wynosi: ${sum}`);
```

7. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

8. Uruchom program w przeglądarce internetowej i wprowadź listę liczb. Program powinien zwrócić ich sumę.

Gotowy program powinien wyglądać następująco:

```typescript
function sumNumbers(numbers: number[]): number {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum;
}

function readNumbersFromUser(): number[] {
  const numbers: number[] = [];
  let
  ```


### Zadanie 3 
**Napisz funkcję, która przyjmuje jako argument napis i zwraca go w odwrotnej kolejności.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Zdefiniuj funkcję o nazwie `reverseString`, która przyjmuje jeden argument typu `string` i zwraca ten sam tekst w odwrotnej kolejności.

```typescript
function reverseString(text: string): string {
  // ciało funkcji
}
```

3. Zadeklaruj zmienną `reversedText` i przypisz jej początkową wartość `''`. Ta zmienna będzie służyć do przechowywania odwróconego tekstu.

```typescript
function reverseString(text: string): string {
  let reversedText = '';
  // ciało funkcji
}
```

4. Napisz pętlę `for`, która będzie iterować po każdym znaku w tekście, zaczynając od ostatniego i kończąc na pierwszym. W każdej iteracji pętli dodaj aktualny znak na początek zmiennej `reversedText`.

```typescript
function reverseString(text: string): string {
  let reversedText = '';
  for (let i = text.length - 1; i >= 0; i--) {
    reversedText += text[i];
  }
  return reversedText;
}
```

5. Zwróć wartość zmiennej `reversedText` jako wynik działania funkcji.

6. Wywołaj funkcję `reverseString` z przykładowym tekstem jako argument i wyświetl wynik działania funkcji w konsoli.

```typescript
const text = 'Hello, World!';
const reversedText = reverseString(text);
console.log(reversedText); // !dlroW ,olleH
```

7. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

8. Uruchom program w przeglądarce internetowej i sprawdź, czy funkcja działa poprawnie dla różnych tekstów.

Gotowa funkcja powinna wyglądać następująco:

```typescript
function reverseString(text: string): string {
  let reversedText = '';
  for (let i = text.length - 1; i >= 0; i--) {
    reversedText += text[i];
  }
  return reversedText;
}

const text = 'Hello, World!';
const reversedText = reverseString(text);
console.log(reversedText); // !dlroW ,olleH
```


### Zadanie 4
**Napisz klasę, która reprezentuje koło i ma metody zwracające jego pole powierzchni oraz obwód.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Zdefiniuj klasę `Circle`, która będzie reprezentować koło. Klasa ta powinna posiadać dwa prywatne pola `radius` (promień koła) oraz `pi` (wartość stałej π).

```typescript
class Circle {
  private radius: number;
  private pi: number = Math.PI;

  constructor(radius: number) {
    this.radius = radius;
  }
}
```

3. Dodaj dwie publiczne metody do klasy `Circle`, które zwracają pole powierzchni oraz obwód koła. Obliczanie pola powierzchni i obwodu będzie odbywać się na podstawie wartości pola `radius` oraz stałej `pi`.

```typescript
class Circle {
  private radius: number;
  private pi: number = Math.PI;

  constructor(radius: number) {
    this.radius = radius;
  }

  public getArea(): number {
    return this.pi * this.radius ** 2;
  }

  public getCircumference(): number {
    return 2 * this.pi * this.radius;
  }
}
```

4. Wywołaj konstruktor klasy `Circle` i utwórz obiekt reprezentujący koło o zadanym promieniu. Przypisz obiekt do zmiennej.

```typescript
const circle = new Circle(5);
```

5. Wywołaj publiczne metody `getArea()` oraz `getCircumference()` na utworzonym obiekcie i wyświetl wyniki w konsoli.

```typescript
console.log(circle.getArea()); // 78.53981633974483
console.log(circle.getCircumference()); // 31.41592653589793
```

6. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

7. Uruchom program w przeglądarce internetowej i sprawdź, czy klasa działa poprawnie dla różnych wartości promienia koła.

Gotowa klasa powinna wyglądać następująco:

```typescript
class Circle {
  private radius: number;
  private pi: number = Math.PI;

  constructor(radius: number) {
    this.radius = radius;
  }

  public getArea(): number {
    return this.pi * this.radius ** 2;
  }

  public getCircumference(): number {
    return 2 * this.pi * this.radius;
  }
}

const circle = new Circle(5);
console.log(circle.getArea()); // 78.53981633974483
console.log(circle.getCircumference()); // 31.41592653589793
```


### Zadanie 5
**Napisz program, który pobiera od użytkownika dwie liczby i wyświetla ich iloczyn.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Zaimportuj bibliotekę `readline-sync`, która umożliwi pobranie danych od użytkownika. Bibliotekę można zainstalować za pomocą menadżera pakietów `npm` przy użyciu polecenia `npm install readline-sync`.

```typescript
import * as readlineSync from 'readline-sync';
```

3. Wykorzystaj funkcję `question` z biblioteki `readline-sync`, aby pobrać dwie liczby od użytkownika i przypisz je do zmiennych.

```typescript
const firstNumber = readlineSync.question('Podaj pierwszą liczbę: ');
const secondNumber = readlineSync.question('Podaj drugą liczbę: ');
```

4. Skonwertuj pobrane dane z formatu tekstowego na format liczbowy, korzystając z funkcji `parseInt`.

```typescript
const firstNumber = parseInt(readlineSync.question('Podaj pierwszą liczbę: '));
const secondNumber = parseInt(readlineSync.question('Podaj drugą liczbę: '));
```

5. Oblicz iloczyn dwóch liczb i przypisz go do zmiennej.

```typescript
const product = firstNumber * secondNumber;
```

6. Wyświetl wynik w konsoli.

```typescript
console.log(`Iloczyn liczb ${firstNumber} i ${secondNumber} wynosi: ${product}`);
```

7. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

8. Uruchom program w przeglądarce internetowej i wprowadź dwie liczby. Program powinien zwrócić ich iloczyn.

Gotowy program powinien wyglądać następująco:

```typescript
import * as readlineSync from 'readline-sync';

const firstNumber = parseInt(readlineSync.question('Podaj pierwszą liczbę: '));
const secondNumber = parseInt(readlineSync.question('Podaj drugą liczbę: '));

const product = firstNumber * secondNumber;

console.log(`Iloczyn liczb ${firstNumber} i ${secondNumber} wynosi: ${product}`);
```


### Zadanie 6
**Napisz funkcję, która przyjmuje jako argument tablicę liczb i zwraca tablicę posortowaną rosnąco.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Zdefiniuj funkcję, która będzie przyjmować jako argument tablicę liczb.

```typescript
function sortArray(array: number[]): number[] {
  // kod funkcji
}
```

3. Wykorzystaj metodę `sort()` na tablicy, aby posortować liczby rosnąco.

```typescript
function sortArray(array: number[]): number[] {
  return array.sort((a, b) => a - b);
}
```

4. Wywołaj funkcję i przetestuj jej działanie, np. w ten sposób:

```typescript
const numbers = [5, 2, 9, 7, 1, 8];
console.log(sortArray(numbers)); // [1, 2, 5, 7, 8, 9]
```

Gotowa funkcja powinna wyglądać następująco:

```typescript
function sortArray(array: number[]): number[] {
  return array.sort((a, b) => a - b);
}

const numbers = [5, 2, 9, 7, 1, 8];
console.log(sortArray(numbers)); // [1, 2, 5, 7, 8, 9]
```

5. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

6. Uruchom program w przeglądarce internetowej i przetestuj jego działanie. Funkcja powinna zwracać posortowaną tablicę rosnąco.


### Zadanie 7
**Napisz program, który pobiera od użytkownika imię i wyświetla powitanie.**

1. Stwórz nowy plik TypeScript z rozszerzeniem `.ts` w wybranej lokalizacji na swoim komputerze.

2. Wykorzystaj funkcję `prompt()` do pobrania imienia od użytkownika. Wyświetl komunikat z prośbą o podanie imienia w oknie dialogowym.

```typescript
const name = prompt("Podaj swoje imię:");
```

3. Zdefiniuj zmienną przechowującą powitanie, np. "Witaj" + imię użytkownika.

```typescript
const greeting = `Witaj ${name}!`;
```

4. Wyświetl powitanie na stronie internetowej lub w konsoli.

```typescript
console.log(greeting);
```

5. Zapisz plik i skompiluj go do JavaScripta przy użyciu kompilatora TypeScript. Można to zrobić z poziomu terminala lub za pomocą dostępnych narzędzi zintegrowanych z edytorem kodu.

6. Uruchom program w przeglądarce internetowej lub w konsoli i przetestuj jego działanie. Program powinien poprosić użytkownika o podanie imienia i wyświetlić powitanie zawierające to imię.


### Zadanie 8
**Napisz funkcję, która przyjmuje jako argument napis i zwraca true, jeśli jest on palindromem, false w przeciwnym przypadku.**

Oto kroki, jakie należy wykonać, aby napisać funkcję w języku TypeScript, która sprawdza, czy podany napis jest palindromem:

1. Zdefiniuj funkcję, która przyjmuje jako argument napis.

```typescript
function isPalindrome(str: string): boolean {
  // kod funkcji
}
```

2. Usuń białe znaki z napisu przy użyciu metody `replace()` i wyrażenia regularnego. Skonwertuj napis na małe litery za pomocą metody `toLowerCase()`, aby uniknąć problemów z rozróżnianiem wielkości liter.

```typescript
const cleanedStr = str.replace(/\s/g, "").toLowerCase();
```

3. Utwórz nowy napis, który jest odwróconą wersją pierwotnego napisu, używając metody `split()` do podzielenia napisu na pojedyncze znaki, a następnie metody `reverse()` i `join()` do odwrócenia kolejności i połączenia z powrotem.

```typescript
const reversedStr = cleanedStr.split("").reverse().join("");
```

4. Porównaj napis pierwotny i odwrócony, używając operatora równości `===`. Jeśli są one równe, zwróć wartość `true`, w przeciwnym razie zwróć `false`.

```typescript
return cleanedStr === reversedStr;
```

5. Pełny kod funkcji będzie wyglądał następująco:

```typescript
function isPalindrome(str: string): boolean {
  const cleanedStr = str.replace(/\s/g, "").toLowerCase();
  const reversedStr = cleanedStr.split("").reverse().join("");
  return cleanedStr === reversedStr;
}
```

6. Przetestuj funkcję, wywołując ją z różnymi argumentami i sprawdzając, czy zwraca poprawne wartości. Funkcja powinna zwrócić `true` dla napisów będących palindromami, takich jak "kajak" czy "radar", a `false` dla napisów, które nimi nie są, takich jak "programowanie" czy "hello world".


### Zadanie 9
**Napisz klasę, która reprezentuje książkę i ma pola tytuł i autor oraz metody zwracające te dane.**

Oto kroki, jakie należy wykonać, aby napisać klasę w języku TypeScript, która reprezentuje książkę i ma pola tytuł i autor oraz metody zwracające te dane:

1. Zdefiniuj klasę `Book`.

```typescript
class Book {
  // kod klasy
}
```

2. Dodaj prywatne pola klasy, które będą przechowywać tytuł i autora.

```typescript
class Book {
  private title: string;
  private author: string;
  // pozostały kod klasy
}
```

3. Dodaj konstruktor, który będzie przyjmował tytuł i autora jako argumenty i ustawiał je jako wartości prywatnych pól.

```typescript
class Book {
  private title: string;
  private author: string;

  constructor(title: string, author: string) {
    this.title = title;
    this.author = author;
  }
  // pozostały kod klasy
}
```

4. Dodaj publiczne metody `getTitle()` i `getAuthor()`, które będą zwracać odpowiednio tytuł i autora książki.

```typescript
class Book {
  private title: string;
  private author: string;

  constructor(title: string, author: string) {
    this.title = title;
    this.author = author;
  }

  public getTitle(): string {
    return this.title;
  }

  public getAuthor(): string {
    return this.author;
  }
}
```

5. Przetestuj klasę, tworząc nowy obiekt `Book` i wywołując metody `getTitle()` i `getAuthor()` na tym obiekcie. Na przykład:

```typescript
const myBook = new Book("Harry Potter", "J.K. Rowling");
console.log(myBook.getTitle()); // "Harry Potter"
console.log(myBook.getAuthor()); // "J.K. Rowling"
```

6. Gotowe! Teraz możesz użyć klasy `Book` do przechowywania informacji o książkach i pobierania ich tytułów i autorów w programie.


### Zadanie 10
**Napisz program, który pobiera od użytkownika trzy liczby i wyświetla je w kolejności od najmniejszej do największej.**

Oto kroki, jakie należy wykonać, aby napisać program w języku TypeScript, który pobiera od użytkownika trzy liczby i wyświetla je w kolejności od najmniejszej do największej:

1. Użyj metody `prompt()` do pobrania trzech liczb od użytkownika.

```typescript
const num1 = prompt("Podaj pierwszą liczbę:");
const num2 = prompt("Podaj drugą liczbę:");
const num3 = prompt("Podaj trzecią liczbę:");
```

2. Skonwertuj pobrane wartości napisowe na liczbowe przy użyciu funkcji `parseInt()`.

```typescript
const num1 = parseInt(prompt("Podaj pierwszą liczbę:"));
const num2 = parseInt(prompt("Podaj drugą liczbę:"));
const num3 = parseInt(prompt("Podaj trzecią liczbę:"));
```

3. Utwórz tablicę, zawierającą te trzy liczby.

```typescript
const numbers = [num1, num2, num3];
```

4. Wywołaj metodę `sort()` na tej tablicy, aby posortować jej elementy.

```typescript
numbers.sort();
```

5. Wyświetl posortowane liczby za pomocą metody `console.log()`.

```typescript
console.log(numbers);
```

6. Gotowe! Teraz użytkownik może wprowadzić trzy liczby, a program wyświetli je posortowane od najmniejszej do największej. Możesz również dodać dodatkowe instrukcje, aby wyświetlić wynik w bardziej czytelny sposób.


