# Oefening 9: Geavanceerde Transities & Keyframes

## Opdracht

1. Maak een element dat bij hover (of click) een transitie ondergaat: van kleur, grootte, positie etc.
2. Maak een element met een continue keyframe-animatie (bijv. een spinner of lopende tekst).
3. Experimenteer met `@keyframes`, `animation-timing-function`, `transition-timing-function`, `transform`, etc.

## Tips

- `transition: all 0.5s ease;` voor hover-transities.
- `@keyframes spin { from {transform: rotate(0);} to {transform: rotate(360deg);} }`
- Zorg voor `animation: spin 2s linear infinite;`
