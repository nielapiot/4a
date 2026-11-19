# Minutnik – Projekt szkolny

Aplikacja webowa typu minutnik stworzona w ramach nauki programowania i tworzenia specyfikacji projektowych.

---

## 1. Rozbór promptu z pokazu

Oto rozbór przykładowego promptu użytego podczas lekcji na poszczególne kategorie:

- Stwórz prostą aplikację minutnika w HTML i JavaScript. -> [co ma powstać] i [jak]
- Aplikacja ma zawierać przyciski Start, Stop oraz Reset. -> [co ma powstać]
- Kod ma znajdować się w jednym pliku index.html. -> [jak]
- Minutnik musi poprawnie odmierzać czas w dół i zatrzymywać się na zerze. -> [po czym poznać, że skończone]

### Podsumowanie elementów promptu:
- Liczba linii „co ma powstać”: 3
- Liczba linii „jak”: 2
- Liczba linii „po czym poznać, że skończone”: 1

Wniosek: Elementów typu „po czym poznać, że skończone” było w tym prompcie najmniej.

---

## 2. Analiza zachowania aplikacji (Reset w środku przerwy)

- Co się dzieje? Po naciśnięciu przycisku reset w środku trwania przerwy, cały licznik cykli (wraz z głównym stanem odliczania) wraca do wartości początkowej.
- Czyja to decyzja? Jest to decyzja modelu AI, który wygenerował kod w taki sposób, aby przycisk resetu czyścił wszystkie zmienne stanu komponentu jednocześnie, zamiast obsługiwać oddzielnie resetowanie tylko bieżącego cyklu lub samej przerwy.
