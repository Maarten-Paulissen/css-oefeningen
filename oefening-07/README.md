# Oefening 7: CSS Custom Properties (Variables)

## Opdracht

1. Definieer in :root enkele variabelen, bijvoorbeeld --primary-color en --secondary-color.
2. Gebruik deze variabelen voor knoppen, teksten, achtergrond, enz.
3. Maak minimaal twee verschillende klassen (bijv. .btn-primary en .btn-secondary) die van deze variabelen gebruikmaken.
4. Experimenteer met een "dark mode" door variabelen te herdefiniëren in een .dark-theme container of @media query.

## Tips

- `:root { --primary-color: #3498db; }`
- `background-color: var(--primary-color);`
- Je kunt variabelen ook in nested elementen overschrijven.
