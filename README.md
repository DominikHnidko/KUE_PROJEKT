# Elektroniczny stetoskop

## 📌 Opis projektu
Projekt przedstawia **elektroniczny stetoskop** przeznaczony do precyzyjnego odsłuchu i analizy dźwięków serca.  
Umożliwia on odsłuch w czasie rzeczywistym za pomocą słuchawek lub głośnika zewnętrznego.

Głównym celem systemu jest poprawa czytelności sygnału poprzez redukcję szumów i zakłóceń.

---

## ⚙️ Najważniejsze funkcje
- Odsłuch dźwięków serca w czasie rzeczywistym
- Wyjście audio przez słuchawki lub głośnik
- Wieloetapowa filtracja sygnału
- Redukcja:
  - zakłóceń sieciowych (50/60 Hz)
  - szumów otoczenia
  - częstotliwości spoza zakresu pracy serca
- Poprawa wykrywania szmerów sercowych

---

## 🔧 Przetwarzanie sygnału
System wykorzystuje zestaw filtrów analogowych i/lub cyfrowych:

- filtr pasmowo-przepustowy dla sygnału serca
- tłumienie niskich częstotliwości (ruch, drgania)
- tłumienie wysokich częstotliwości (szumy)
- redukcja zakłóceń sieciowych

---

## 🧠 Cel projektu
- edukacja w zakresie elektroniki i biomedycyny
- nauka przetwarzania sygnałów analogowych
- demonstracja zastosowania systemów embedded w medycynie

---

## 🛠️ Przykładowa implementacja sprzętowa
- mikrokontroler (np. STM32 / Arduino)
- analogowy tor wejściowy sygnału
- filtr pasmowy
- wzmacniacz audio
- wyjście na słuchawki lub głośnik

---

## 📊 Zastosowania
- edukacja w dziedzinie elektroniki biomedycznej
- nauka przetwarzania sygnałów
- eksperymenty z dźwiękami serca (nie diagnostyka)

---

## ⚠️ Uwaga
Projekt ma charakter **edukacyjny i eksperymentalny**.  
Nie jest urządzeniem medycznym i nie może być używany do diagnozy.

---

## 👨‍💻 Autor
Projekt studencki z zakresu systemów embedded i przetwarzania sygnałów.
