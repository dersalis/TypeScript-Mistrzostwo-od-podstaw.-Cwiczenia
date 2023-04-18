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

1. Napisz funkcję, która zsumuje wszystkie liczby parzyste z przedziału od 1 do podanej liczby.

Oto szczegółowy opis kroków do wykonania zadania w języku TypeScript:

1. Zdefiniuj funkcję o nazwie `sumEvenNumbersInRange`, która przyjmie jeden argument typu number o nazwie `n`.
2. Zadeklaruj zmienną `sum` i przypisz jej początkową wartość 0.
3. Utwórz pętlę `for`, która będzie iterować po liczbach od 1 do `n`.
4. Wewnątrz pętli `for` sprawdź, czy aktualna liczba jest parzysta. Można to zrobić przez sprawdzenie reszty z dzielenia przez 2. Jeśli reszta z dzielenia wynosi 0, to liczba jest parzysta.
5. Jeśli aktualna liczba jest parzysta, dodaj ją do zmiennej `sum`.
6. Po zakończeniu pętli `for`, zwróć wartość zmiennej `sum`.

Oto kod funkcji `sumEvenNumbersInRange` w języku TypeScript:

```typescript
function sumEvenNumbersInRange(n: number): number {
  let sum = 0;
  for (let i = 1; i <= n; i++) {
    if (i % 2 === 0) {
      sum += i;
    }
  }
  return sum;
}
```

Funkcja ta przyjmuje jedną liczbę `n` i zwraca sumę wszystkich liczb parzystych z przedziału od 1 do `n`.
