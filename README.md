
---

## Aktualizacja promptów

Wszystkie prompty są w pliku `index.html` w tablicy `const DB = [...]` (ok. linia 200).

Każdy prompt ma strukturę:
```js
{
  id: 33,                        // unikalny numer
  cat: "Kategoria",              // widoczna w sidebarze
  title: "Tytuł promptu",
  difficulty: "beginner",        // beginner | intermediate | advanced
  prompt: `Treść promptu...`,
  tags: ["tag1", "tag2"]
}
```

Żeby dodać nową kategorię — wystarczy użyć nowej nazwy w polu `cat`. Sidebar generuje się automatycznie.

---

## Licencja

Projekt demonstracyjny. Prompty są przykładowe — dostosuj do własnych potrzeb.
