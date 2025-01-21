# Oefening 10: 3D Flip Card (Geavanceerd)

## Opdracht

1. Bouw een kaart die 3D omklapt bij hover of klik.
2. Gebruik `perspective`, `transform-style: preserve-3d`, en `rotateY(180deg)`.
3. Zorg dat de overgangen soepel verlopen. Gebruik `backface-visibility: hidden;` zodat de achterkant niet doorschemert.
4. Maak het nog realistischer met een "schaduw" of "licht" effect bij het draaien.

## Tips

- `perspective: 1000px;` op de container.
- `.card { transition: transform 0.8s; transform-style: preserve-3d; }`
- `.card-front, .card-back { backface-visibility: hidden; position: absolute; }`
- Mogelijk wil je de flip activeren op :hover, :focus of via checkbox-hack.
