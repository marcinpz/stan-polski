# Zasady pracy

1. Preferuj źródła pierwotne: GUS, Eurostat, NBP, akty prawne, oryginalne publikacje i teksty autorów.
2. Oddzielaj dane od interpretacji. Każdy wpis ma pole `type`: `fact`, `trend`, `hypothesis`, `claim`, `topic`, `person` albo `source`.
3. Fakt liczbowy musi zawierać okres, jednostkę, zakres, status danych, datę weryfikacji i link.
4. Trend opisuje metodę porównania i nie udaje związku przyczynowego.
5. Hipoteza przedstawia dowody za, dowody przeciw i możliwe alternatywne wyjaśnienia.
6. Cytat wymaga autora, dzieła/wystąpienia, daty, kontekstu i źródła tekstu.
7. Nie przepisuj danych z grafiki lub artykułu wtórnego, jeśli dostępna jest tabela źródłowa.
8. Aktualizacje nie usuwają starej wartości bez śladu; historię zachowuje Git.

## Statusy

- `seed` — temat do zbadania
- `research` — materiał w trakcie zbierania
- `review` — gotowy do kontroli źródeł
- `verified` — sprawdzony ze źródłem pierwotnym
- `outdated` — wymaga aktualizacji

## Linkowanie

Używamy względnych linków Markdown, np. `[Dzietność](dzietnosc.md)`, ponieważ działają zarówno na GitHubie, jak i w Obsidianie. Nie używamy składni wikilinków `[[...]]`. Link tworzymy dopiero wtedy, gdy plik docelowy istnieje; planowane karty zapisujemy jako zwykły tekst.
