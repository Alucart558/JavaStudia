# JavaStudia 📚

Repozytorium zawierające trzy podstawowe programy w Javie, które demonstrują kluczowe koncepty języka.

---

## 📋 Zawartość

### 1. **PierwszyProgram.java** - Hello World
Najprostszy program w Javie, który wypisuje tekst "Hello world !" na konsoli.

#### Opis:
- Definiuje klasę publiczną `PierwszyProgram`
- Zawiera metodę `main()` - punkt wejścia programu
- Wypisuje tekst za pomocą `System.out.println()`

#### Kluczowe koncepty:
- Nazwa pliku musi być identyczna z nazwą klasy publicznej
- Metoda `main()` jest statyczna i musi być publiczna
- Sygnatura metody: `public static void main(String[] argv)`

#### Kompilacja i uruchomienie:
```bash
javac PierwszyProgram.java   # Kompilacja do bytecode'u
java PierwszyProgram          # Uruchomienie programu
```

---

### 2. **Program2.java** - Nowoczesna składnia Java 25
Program demonstrujący nową, uproszczoną składnię metody `main()` z Java 21+.

#### Opis:
- Wykorzystuje `void main()` bez słowa kluczowego `public` i `static`
- Używa uproszczonego API wejścia/wyjścia (`IO.println()`)
- Wymaga Java 21+

#### Uwagi:
⚠️ **Ograniczenie**: Kod powinien działać w Java 25, ale nie działa w Java 21

#### Wymagania:
- Java 21 lub nowsza
- Włączone preview features (w nowszych wersjach)

---

### 3. **Program3.java** - Obiekty i Metody Instancji
Program demonstrujący:
- Tworzenie instancji klasy
- Metody prywatne
- Referencje do obiektów

#### Opis:
- Tworzy instancję klasy `Program3`
- Wywołuje metodę prywatną `sayHello()` na obiekcie
- Demonstruje różnicę między metodami statycznymi a instancji

#### Kluczowe koncepty:
- Metoda `main()` jest statyczna (działa bez instancji)
- Metoda `sayHello()` jest prywatna i instancyjna (wymaga obiektu)
- `new Program3()` tworzy nową instancję klasy

---

## 🎯 Cele edukacyjne

1. **PierwszyProgram** - Nauka podstawowej struktury programu Java
2. **Program2** - Poznanie nowszych możliwości Java
3. **Program3** - Zrozumienie programowania obiektowego

---

## 📖 Zasoby dodatkowe

- [Oficjalna dokumentacja Java](https://docs.oracle.com/en/java/)
- [Java Tutorial - The main Method](https://docs.oracle.com/javase/tutorial/getStarted/application/index.html)

---

**Autor**: Alucart558  
**Język**: Java (100%)
