# AGENTS.md

## Cel repozytorium
To repozytorium jest fundamentem operacyjnym eKanada Operating System dla:
- Polskiej Szkoły eKanada,
- kampanii Folklorama,
- produkcji treści, materiałów marketingowych i materiałów do druku.

## Hierarchia źródeł wiedzy
1. `knowledge-base/` jako główne źródło prawdy operacyjnej.
2. `campaigns/` jako źródło prawdy dla pojedynczych kampanii.
3. `templates/` jako szablony produkcyjne.
4. `workflows/` jako instrukcje procesu.
5. `assets/` jako katalog zasobów.

## Zasady
- Nie wymyślaj danych o eKanadzie.
- Jedynym źródłem wiedzy są dokumenty znajdujące się w folderze `knowledge-base`.
- Folder `references` zawiera materiały źródłowe i nie powinien być traktowany jako gotowa wiedza bez wcześniejszego opracowania.
- Agent nie może tworzyć faktów nieobecnych w `knowledge-base`.
- Braki oznaczaj jako `TODO: DO UZUPEŁNIENIA`.
- Nie modyfikuj zatwierdzonych treści bez zgody właściciela.
- Przed drukiem zawsze wykonaj kontrolę treści, układu i danych kontaktowych.
- Nie wprowadzaj API, automatyzacji n8n ani publikowania social media, jeśli nie zostało to osobno zlecone.

## Workflow
Stosuj kolejność:
`brief -> treść -> projekt -> review -> approved -> final`

## Wersje językowe
- Twórz wersję polską jako domyślną.
- Wersję angielską przygotowuj tylko wtedy, gdy brief, kampania lub materiał tego wymaga.
- Jeśli brak informacji językowej, wpisz `TODO: DO UZUPEŁNIENIA`.

## Nazwy plików
- Używaj małych liter.
- Stosuj myślniki zamiast spacji.
- Unikaj polskich znaków w nazwach plików.

## Zmiana treści
- Zatwierdzone treści w `approved/` i `final/` traktuj jako chronione.
- Zmiany wymagają wyraźnej zgody.

## Dokumentacja repozytorium
- Zatwierdzone instrukcje projektu znajdują się w `docs/governance/`.
- Decyzje architektoniczne dokumentuj w `docs/architecture/adr/`.
