---
title: "TypeScript"
output: pdf_document
---
# TypeScript: Mistrzostwo od podstaw. Ćwiczenia
Ćwiczenia które pozwolą zapanować nad językiem TypeScript.

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

### Zadanie 1. 
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


### Zadanie 2. 
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