# ADR-001 — Przyjęcie Project Instructions v1.1

**Data:** 2026-07-29  
**Status:** ACCEPTED  
**Właściciel:** 00 – Architecture  
**Zakres:** wszystkie czaty projektu ChatGPT eKanada Operating System

## Kontekst

Project Instructions v1.0 łączyły globalne zasady zachowania ChatGPT ze szczegółowymi standardami operacyjnymi, technicznymi, jakościowymi i produkcyjnymi.

Architecture Decision Review wykazał, że taki dokument był zbyt obszerny i łączył różne poziomy dokumentacji. Utrudniałoby to utrzymanie zasad, zwiększało ryzyko powtórzeń oraz prowadziło do potencjalnych sprzeczności pomiędzy ustawieniami projektu ChatGPT a dokumentacją repozytorium.

Przygotowano Project Instructions v1.1 jako krótszy, globalny kontrakt zachowania ChatGPT obowiązujący we wszystkich czatach projektu.

## Decyzja

Project Instructions v1.1 zostają przyjęte jako globalne instrukcje projektu ChatGPT **eKanada Operating System**.

Project Instructions mają zawierać wyłącznie trwałe zasady globalne dotyczące między innymi:

- celu projektu,
- roli 00 – Architecture,
- zakresów odpowiedzialności czatów,
- hierarchii źródeł prawdy,
- korzystania z repozytorium,
- granic autonomii AI,
- human-in-the-loop,
- bezpieczeństwa i poufności,
- Review i final approval,
- zgodności z profilem brandowym,
- minimalnej złożoności,
- dokumentowania decyzji architektonicznych.

Szczegółowe standardy, workflow, checklisty, profile brandowe, instrukcje techniczne, polityki operacyjne i szablony będą rozwijane oraz utrzymywane w repozytorium, a nie w Project Instructions.

Repozytorium jest trwałym źródłem dokumentacji projektu.

Samo ustalenie w rozmowie nie zmienia trwale architektury systemu. Decyzja architektoniczna zaczyna obowiązywać po zapisaniu i zatwierdzeniu jej w repozytorium.

## Uzasadnienie

Przyjęty podział:

- zwiększa skuteczność Project Instructions,
- ogranicza powtórzenia,
- ułatwia rozwój i wersjonowanie szczegółowych standardów,
- pozwala aktualizować dokumentację operacyjną bez częstych zmian ustawień projektu ChatGPT,
- rozdziela governance od wiedzy merytorycznej i instrukcji technicznych,
- umożliwia skalowanie systemu na Folkloramę i przyszłe projekty,
- ustanawia repozytorium jako trwałe miejsce zapisu decyzji.

## Konsekwencje

### Pozytywne

- Project Instructions pozostają krótkie i stabilne.
- ChatGPT otrzymuje jednoznaczne zasady globalne.
- Codex może korzystać ze szczegółowych instrukcji w `AGENTS.md`.
- Standardy i workflow mogą być rozwijane niezależnie.
- Zmiany architektoniczne będą miały trwały zapis.
- Knowledge Base może koncentrować się na zatwierdzonych faktach i wiedzy domenowej.

### Negatywne

- Konieczne jest utworzenie zestawu dokumentów w repozytorium.
- Należy utrzymywać spójne odnośniki między dokumentami.
- ChatGPT i Codex muszą wiedzieć, gdzie znajduje się właściwe źródło informacji.
- Dokumentacja wymaga właścicieli, wersjonowania i regularnego przeglądu.

## Alternatywy

### Alternatywa 1 — pozostawienie Project Instructions v1.0

Odrzucona ze względu na nadmierną długość, mieszanie poziomów dokumentacji i trudność utrzymania.

### Alternatywa 2 — umieszczenie wszystkich zasad w AGENTS.md

Odrzucona, ponieważ `AGENTS.md` jest przeznaczony dla Codex i agentów technicznych, a nie jako globalna instrukcja wszystkich czatów ChatGPT.

### Alternatywa 3 — przechowywanie decyzji wyłącznie w rozmowach

Odrzucona, ponieważ rozmowy nie zapewniają trwałego, jednoznacznego i wersjonowanego źródła prawdy.

## Powiązane obszary

- Project Instructions
- Architecture
- Governance
- AGENTS.md
- README.md
- Knowledge Base
- Review
- Codex
- Canva
- Automation
