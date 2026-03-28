# CBT Case Conceptualization: Therapist Self-Assessment Tool

An interactive self-assessment tool for cognitive-behavioral therapy (CBT) therapists to evaluate their case conceptualization competencies across three core areas, based on the competency framework from Chapter 8 of *Collaborative Case Conceptualization* (Kuyken, Padesky, & Dudley, 2008).

**Live tool:** [andreifoldes.github.io/case-conceptualization/cbt-self-assessment.html](https://andreifoldes.github.io/case-conceptualization/cbt-self-assessment.html)

## What It Assesses

The tool covers 75 competency items organized into three domains, each rated at Novice, Intermediate, and Advanced levels:

| Domain | Items | Description |
|--------|-------|-------------|
| **8.1 Collaborative Empiricism** | 32 | Skills for empirical collaboration with clients during conceptualization |
| **8.2 Levels of Conceptualization** | 31 | Knowledge across descriptive, explanatory, and predisposing/protective levels |
| **8.3 Client Strengths** | 12 | Competencies for incorporating strengths into conceptualizations |

## Rating Scale (0-5)

| Rating | Description |
|--------|-------------|
| 0 | Absence of declarative knowledge |
| 1 | Minimal declarative knowledge |
| 2 | Good declarative knowledge but little procedural skill |
| 3 | Good declarative knowledge with moderate procedural skill |
| 4 | Good declarative knowledge and good procedural skill with many but not most clients |
| 5 | Thorough declarative understanding integrated with flexible procedural skill |

## Features

- **Interactive rating** with color-coded buttons (red/amber/green)
- **Radar chart** visualizing scores across 9 dimensions
- **Summary report** with strengths, growth areas, and profile interpretation
- **Dual view** toggling between dimension-level and item-level analysis
- **Auto-advance** to next tab when all items in current tab are rated
- **LocalStorage** persistence (ratings survive page refresh)
- **CSV export** of all ratings with timestamps
- **Print-optimized** A4 single-page layout
- **Mobile-friendly** with duplicated navigation tabs
- **Zero dependencies** (single HTML file, Chart.js via CDN)

## Usage

Open `cbt-self-assessment.html` in any modern browser. No installation or server required.

Alternatively, use the hosted version at the link above.

## Reference

Kuyken, W., Padesky, C. A., & Dudley, R. (2008). *Collaborative Case Conceptualization: Working Effectively with Clients in Cognitive-Behavioral Therapy*. Guilford Press.

## License

MIT
