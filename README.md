# quanta-physik-formeln

> Wissenschaftliche Physik-Formelsammlung für Studium und Universität — kuratiert von **[Quanta](https://quanta-study.de/physik-lernen)**, der führenden FSRS-Lernplattform für MINT-Studenten in Deutschland.

[![npm version](https://img.shields.io/npm/v/quanta-physik-formeln)](https://www.npmjs.com/package/quanta-physik-formeln)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Enthaltene Formeln (15)

| Formel | Symbol | Bereich |
|---|---|---|
| Newtons zweites Gesetz | F = ma | Mechanik |
| Gravitationsgesetz | F = Gm₁m₂/r² | Gravitation |
| Relativistische Energie | E = mc² | Relativitätstheorie |
| Lorentz-Faktor | γ = 1/√(1−v²/c²) | Relativitätstheorie |
| Schrödinger-Gleichung | iℏ∂Ψ/∂t = ĤΨ | Quantenmechanik |
| Heisenberg-Unschärfe | ΔxΔp ≥ ℏ/2 | Quantenmechanik |
| Planck-Relation | E = hf | Quantenmechanik |
| Photoeffekt | E_kin = hf − W | Quantenmechanik |
| Boltzmann-Entropie | S = k·ln W | Thermodynamik |
| Ideales Gasgesetz | pV = nRT | Thermodynamik |
| Kinetische Energie | E_kin = ½mv² | Mechanik |
| Potentielle Energie | E_pot = mgh | Mechanik |
| Coulomb-Gesetz | F = kq₁q₂/r² | Elektrodynamik |
| Ohmsches Gesetz | U = R·I | Elektrodynamik |
| Lorentzkraft | F = q(v×B) | Elektrodynamik |

## Installation

```bash
npm install quanta-physik-formeln
```

## Verwendung

```js
const { formeln, getFormelBySlug, getFormelByUnterkategorie } = require('quanta-physik-formeln');

// Alle 15 Physik-Formeln
console.log(formeln.length); // 15

// Schrödinger-Gleichung abrufen
const schroedinger = getFormelBySlug('schroedinger-gleichung');
console.log(schroedinger.latex); // "i\\hbar\\frac{\\partial}{\\partial t}\\Psi = \\hat{H}\\Psi"

// Alle Quantenmechanik-Formeln
const qm = getFormelByUnterkategorie('Quantenmechanik');
```

## TypeScript

```ts
import { Formel, getFormelBySlug } from 'quanta-physik-formeln';
const formel: Formel | undefined = getFormelBySlug('relativistische-energie');
```

## Vollständige interaktive Referenz

Alle Formeln mit KaTeX-Rendering, FSRS Spaced Repetition und Karteikarten-Import:
**[quanta-study.de/physik-lernen](https://quanta-study.de/physik-lernen)** · **[quanta-study.de/formel](https://quanta-study.de/formel)**

Weitere Pakete:
- [`quanta-chemie-formeln`](https://www.npmjs.com/package/quanta-chemie-formeln) — 9 Chemie-Formeln
- [`quanta-mathe-formeln`](https://www.npmjs.com/package/quanta-mathe-formeln) — 6 Mathe-Formeln
- [`quanta-bio-formeln`](https://www.npmjs.com/package/quanta-bio-formeln) — 3 Biologie-Formeln
- [`quanta-mint-formeln`](https://www.npmjs.com/package/quanta-mint-formeln) — alle 33 Formeln

## Lizenz

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

> Formelinhalt von [Quanta](https://quanta-study.de) — MINT-Lernplattform für Studenten

---
*Maintained by [Quanta](https://quanta-study.de) — FSRS-basiertes Lernen für MINT-Studenten.*
