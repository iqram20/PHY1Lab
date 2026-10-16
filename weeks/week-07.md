# Week 07 — Centripetal Force

**Course:** PHY 210/215 Physics I Laboratory  
**Manual:** Wilson & Hernández-Hall, *Physics Laboratory Experiments*, 8th ed., Experiment 10.  
**Study first:** Read the complete original experiment, equipment notes, figures and data-report tables. These supplemental notes do **not** replace local instructions.

## Objectives and ideas

- Circular motion of spring-attached bob
- Period and spring tension.

## Visual diagrams

These original conceptual diagrams summarize the physics and measurement workflow; refer to the manual's apparatus figures for actual component positions.

### Concept / apparatus relationships

```mermaid
flowchart TD
 A["Bob mass m and orbit radius r"] --> B["Rotate: bob passes over pointer"]
 B --> C["Measure time t for N revolutions"]
 C --> D["Period T = t/N"]
 D --> E["Speed v = 2πr/T"]
 E --> F["Computed Fc = mv²/r"]
 F --> H["Compare two forces"]
 G["Stop rotor, hang M to balance spring: Fdirect = Mg"] --> H
```

### Measurement and analysis map

```mermaid
flowchart LR
 A["Table 1: baseline"] --> B["Table 2: vary bob mass"]
 B --> C["Table 3: vary orbit radius"]
 C --> D["Table 4: optional different spring"]
 D --> E["Three timings for each condition"]
```

## Pre-lab equipment and preparation

Confirm that all listed apparatus is present and working, locate scales/reference positions, inspect strings/fasteners, and write your measurement plan. Bring calculator, notebook, ruler, and graph paper as needed. Record apparatus-specific instrument resolution.

## Lab procedure — teaching summary

Weigh bob; adjust pointer radius from rotor axis; align hanging bob over pointer before attaching spring. Rotate shaft so moving bob passes over pointer, time ~25 revolutions at least 10 seconds, repeat 3 trials. Stop rotation, attach string over pulley opposite spring and add total hanging weights until bob is back at pointer.

## Main equations

- `${x}`
- `${x}`
- `${x}`
- `${x}`

Use SI units unless the manual specifically requests another unit. Show the substitution of measured values and label final units.

## Essential equations and worked example

### Main equations

- Period: $T=t/N$
- Speed: $v=2\pi r/T$
- Calculated force: $F_c=mv^2/r=4\pi^2mr/T^2$
- Stationary hanging calibration: $F_{\rm direct}=Mg$
- Percent difference: $\frac{|F_c-F_{\rm direct}|}{(F_c+F_{\rm direct})/2}\times100\%$

### Sample data table — illustrative values (not collected in class)

| Trial | Revolutions | Total time (s) | Period (s) |
| --- | --- | --- | --- |
| 1 | 25 | 19.8 | 0.792 |
| 2 | 25 | 20.0 | 0.800 |
| 3 | 25 | 20.2 | 0.808 |

### Sample calculation — Rotating bob and spring-force comparison

$\bar T=0.800\ \mathrm{s}$, with rotating bob $m=0.150\ \mathrm{kg}$ and $r=0.200\ \mathrm{m}$. Speed $v=2\pi(0.200)/0.800=1.571\ \mathrm{m/s}$. Thus $F_c=0.150(1.571)^2/0.200=\mathbf{1.85\ N}$. A **stationary** balancing hanger of total mass $M=0.190\ \mathrm{kg}$ gives $F_{\rm direct}=0.190(9.8)=\mathbf{1.86\ N}$. Never attach the hanging calibration weights while the device is rotating.

**Student reminder:** These values are examples for practice, **not** the manual's original measurements or a filled official report. Use your actual readings, the laboratory manual's specified tables, and the required units.

## Recording and analysis

Manual Tables 1–4: baseline, vary bob mass (+100 g or more), vary radius, optionally vary spring stiffness. For each: three times, period, speed, Fc, Mg and percent difference.

Always preserve raw trial-by-trial readings before averaging. Use the manual's own report tables and attach graphs/calculations as requested. Discuss reasonable sources of systematic and random uncertainty.

## Safety and common mistakes

Never leave hanging calibration weights attached during rotation. Wear eye protection, tighten locking screws and keep clear of counterweight.

## Preparation video

- [Find demonstrations for this week's topic on YouTube](https://www.youtube.com/results?search_query=Sargent%20Welch%20hand%20operated%20centripetal%20force%20spring%20bob%20experiment) — **search-results link**, not a pre-screened specific video. Verify the apparatus and method before following a demonstration.
### Additional filmed demonstration

- [Saint Mary's University: Centripetal Force](https://www.demos.smu.ca/demos/mechanics/144-centripetal-force) — related apparatus demonstration.

## Pre-lab thinking questions

1. Which physical quantity is controlled and which quantity is measured in this experiment?
2. What instrument reading is the largest source of uncertainty?
3. Which graph or equation allows you to test the theory?
4. What would a meaningful discrepancy between measured and predicted results tell you?

---

**Source note:** Written as original class guidance based on the manual's topic and available procedures; examples, simplified formulas and teaching advice may go beyond the exact lab handout. Consult the manual for the authoritative setup and report requirements.
