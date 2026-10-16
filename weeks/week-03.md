# Week 03 — Simple Pendulum

**Course:** PHY 210/215 Physics I Laboratory  
**Manual:** Wilson & Hernández-Hall, *Physics Laboratory Experiments*, 8th ed., Experiment 4.  
**Study first:** Read the complete original experiment, equipment notes, figures and data-report tables. These supplemental notes do **not** replace local instructions.

## Objectives and ideas

- Angle, mass, length, damping and period.

## Visual diagrams

These original conceptual diagrams summarize the physics and measurement workflow; refer to the manual's apparatus figures for actual component positions.

### Concept / apparatus relationships

```mermaid
flowchart TD
 A["Pivot"] --> B["String length + bob radius = L"]
 B --> C["Displace through small angle"]
 C --> D["Release without push"]
 D --> E["Time N oscillations"]
 E --> F["T = total time / N"]
 F --> G["Compare T = 2π√(L/g)"]
```

### Measurement and analysis map

```mermaid
flowchart LR
 A["Change angle"] --> D["Observe period"]
 B["Change mass"] --> D
 C["Change length"] --> D
 D --> E["Plot length against period squared"]
```

## Pre-lab equipment and preparation

Confirm that all listed apparatus is present and working, locate scales/reference positions, inspect strings/fasteners, and write your measurement plan. Bring calculator, notebook, ruler, and graph paper as needed. Record apparatus-specific instrument resolution.

## Lab procedure — teaching summary

Measure length pivot to bob center. For the angle study keep length and mass fixed and time repeated oscillations at several initial angles. Repeat with altered bob mass; vary string length for the length study; observe decreasing amplitude for damping.

## Equations, sample data, and worked calculation

### Main equations

- Period: $T=t/N$
- Small-angle period: $T=2\pi\sqrt{L/g}$
- Linear form: $T^2=(4\pi^2/g)L$
- From $L$ versus $T^2$ graph: $g=4\pi^2(\text{slope})$

### Sample data table — illustrative values (not collected in class)

| Trial | Oscillations N | Time t (s) | T=t/N (s) |
| --- | --- | --- | --- |
| 1 | 20 | 28.3 | 1.415 |
| 2 | 20 | 28.4 | 1.420 |
| 3 | 20 | 28.5 | 1.425 |

### Sample calculation — Pendulum period and gravity

Mean period $\bar T=(1.415+1.420+1.425)/3=1.420\ \mathrm{s}$. For $L=0.500\ \mathrm{m}$, $g=4\pi^2L/T^2=4\pi^2(0.500)/(1.420)^2=\mathbf{9.79\ m/s^2}$. The small-angle equation is less accurate at large release angles.

**Student reminder:** These values are examples for practice, **not** the manual's original measurements or a filled official report. Use your actual readings, the laboratory manual's specified tables, and the required units.

## Recording and analysis

Record N oscillations and total time, compute period. Plot length dependence as the assigned axes specify; if L versus T², g = 4π² × slope.

Always preserve raw trial-by-trial readings before averaging. Use the manual's own report tables and attach graphs/calculations as requested. Discuss reasonable sources of systematic and random uncertainty.

## Safety and common mistakes

Release without pushing, use small angles for theory, and avoid timing only a single oscillation.

## Preparation video

- [Find demonstrations for this week's topic on YouTube](https://www.youtube.com/results?search_query=simple%20pendulum%20mass%20angle%20length%20damping%20physics%20lab) — **search-results link**, not a pre-screened specific video. Verify the apparatus and method before following a demonstration.
## Pre-lab thinking questions

1. Which physical quantity is controlled and which quantity is measured in this experiment?
2. What instrument reading is the largest source of uncertainty?
3. Which graph or equation allows you to test the theory?
4. What would a meaningful discrepancy between measured and predicted results tell you?

---

**Source note:** Written as original class guidance based on the manual's topic and available procedures; examples, simplified formulas and teaching advice may go beyond the exact lab handout. Consult the manual for the authoritative setup and report requirements.
