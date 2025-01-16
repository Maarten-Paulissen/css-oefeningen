# Oefening 4: Off-canvas Menu met Checkbox-hack

## Opdracht

1. Bouw een verborgen zijmenu (off-canvas) dat naar binnen schuift bij klik op een "Menu"-knop.
2. Gebruik de checkbox-hack: `<input type="checkbox" id="menu-toggle" />` + `<label for="menu-toggle">`.
3. Zorg dat het menu met een animatie (transition) opent en sluit.

## Tips

- Zet het menu eerst buiten beeld (`transform: translateX(-100%)`).
- Bij `#menu-toggle:checked ~ .side-menu { ... }` verplaats je het menu naar binnen.
- Style de menu-knop als een hamburgersymbool.
