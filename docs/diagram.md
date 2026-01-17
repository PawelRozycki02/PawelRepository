# Schemat Działania Aplikacji

```mermaid
graph TD
    A[Start aplikacji] --> B{Czy ustawiono cel?}
    B -- Nie --> C[Ustaw wagę i cel dzienny]
    B -- Tak --> D[Ekran główny]
    C --> D
    D --> E[Dodaj napój]
    E --> F{Cel osiągnięty?}
    F -- Tak --> G[Wyślij gratulacje!]
    F -- Nie --> D
    G --> H[Koniec dnia / Statystyki]