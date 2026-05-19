# PrompTY

Statyczna biblioteka promptów AI z wyszukiwarką i filtrami. Zero zależności, jeden plik HTML.

## Wrzucenie na GitHub Pages (3 minuty)

### 1. Utwórz nowe repozytorium

Wejdź na [github.com/new](https://github.com/new) i utwórz repo o dowolnej nazwie, np. `prompty`.  
Zaznacz **"Add a README file"** — dzięki temu repo od razu ma branch `main`.

### 2. Wgraj plik

W repozytorium kliknij **"Add file" → "Upload files"**, wgraj `index.html` i zatwierdź (*Commit changes*).

### 3. Włącz GitHub Pages

Przejdź do **Settings → Pages** (lewy sidebar).  
W sekcji *Branch* wybierz: **`main`** / **`/ (root)`** → kliknij **Save**.

### 4. Gotowe

Po chwili (30–60 sek) strona będzie dostępna pod:
```
https://<twój-login>.github.io/<nazwa-repo>/
```

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
