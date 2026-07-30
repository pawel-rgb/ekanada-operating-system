# eKanada Operating System

Minimalny fundament operacyjny dla pracy nad Polską Szkołą eKanada, kampanią Folklorama oraz materiałami marketingowymi i drukiem.

## Documentation
- [Dokumentacja repozytorium](./docs/README.md)

## Struktura folderów
- `knowledge-base/` - wiedza robocza i zasady.
- `campaigns/` - osobne pakiety dla kampanii, np. `2026-folklorama/`.
- `templates/` - szablony briefów i materiałów.
- `workflows/` - prosty opis procesu pracy.
- `references/` - oryginalne dokumenty źródłowe.
- `prompts/` - gotowe prompty robocze.
- `assets/` - zasoby źródłowe.
- `automation/` - miejsce na skrypty i przyszłe automatyzacje.
- `output/` - eksporty, pliki do druku, social i archiwum.

## Jak rozpocząć nową kampanię
1. Utwórz folder kampanii w `campaigns/`.
2. Dodaj brief.
3. Przygotuj treść roboczą.
4. Przejdź przez review.
5. Przenieś zaakceptowane materiały do `approved/` i `final/`.

## Gdzie umieszczać materiały
- Treści robocze: `campaigns/<nazwa>/drafts/`
- Materiały do weryfikacji: `campaigns/<nazwa>/review/`
- Materiały zatwierdzone: `campaigns/<nazwa>/approved-copy/`
- Pliki źródłowe: `campaigns/<nazwa>/source-assets/`
- Pliki finalne: `campaigns/<nazwa>/final/`
- Eksporty do druku: `output/print/`
- Eksporty social: `output/social/`

## Status MVP
MVP jest w fazie fundamentu dokumentacyjnego. Nie zawiera jeszcze API, n8n ani rozbudowanych automatyzacji.

## System Architecture
Przepływ pracy:

`references`
↓
`knowledge-base`
↓
`prompts`
↓
`campaigns`
↓
`output`

- `references` przechowuje oryginalne materiały źródłowe.
- `knowledge-base` zawiera opracowaną wiedzę operacyjną.
- `prompts` trzyma gotowe prompty do pracy nad treściami i materiałami.
- `campaigns` przechowuje pakiety kampanii i ich wersje robocze, zatwierdzone oraz finalne.
- `output` zawiera eksporty końcowe do druku, web i archiwum.
