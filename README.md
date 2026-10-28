<div align="center">

# SciSims
### Explore science through interactive experiments

Browser-based physics simulations and India rainfall visualizations, built with HTML, CSS, and JavaScript.

[**Explore SciSims →**](https://scisims.mixify.co.in/) · [Browse Experiments](#experiments--reports) · [Report an Issue](https://github.com/scisims12/scisims/issues) · [Support](https://ko-fi.com/scisims)

</div>

---

## About

SciSims makes scientific ideas easier to explore through animations, interactive controls, and visual explanations. Try quantum experiments, compare atomic models, explore concepts associated with Einstein, and inspect rainfall reports—all in a web browser.

The repository currently includes a landing page and **six experiment or report pages**. It is a collection of static web pages, with no package installation or build step required.

## Experiments & Reports

| Experience | What you can explore | Open |
| --- | --- | --- |
| **Einstein’s Universe** | Photoelectric effect, mass–energy equivalence, twin paradox, gravitational lensing, Brownian motion, and spacetime | [Launch](https://scisims.mixify.co.in/einstein_experiments.html) |
| **Double-Slit Experiment** | Switch between wave, single-particle, and observer modes to explore interference | [Launch](https://scisims.mixify.co.in/double_slit_experiment.html) |
| **Photoelectric Effect** | Adjust frequency and intensity controls and observe the visual response | [Launch](https://scisims.mixify.co.in/photoelectric_effect_simulation.html) |
| **Rutherford Gold Foil** | Compare Thomson’s plum-pudding model with Rutherford’s nuclear model; pause, reset, and adjust animation speed | [Launch](https://scisims.mixify.co.in/rutherford_gold_foil_experiment.html) |
| **India Rainfall: 2000–2024** | Explore the historical rainfall report and its monsoon explanations | [View report](https://scisims.mixify.co.in/india_rainfall_report_25years.html) |
| **India Rainfall: 2026 Forecast** | Explore the report’s forecast presentation and stated methodology | [View report](https://scisims.mixify.co.in/india_rainfall_report_2026_prediction.html) |

**Start here:** [SciSims homepage](https://scisims.mixify.co.in/)

## Features

- Interactive physics demonstrations with visual feedback.
- Adjustable controls and animation modes across selected experiments.
- Dedicated pages for each topic, linked through shared navigation.
- Canvas-based animations and custom page styling.
- Historical rainfall and forecast report pages.
- Static hosting through GitHub Pages.

## Try It

1. Open the [live website](https://scisims.mixify.co.in/).
2. Choose an experiment or report.
3. Adjust the available controls and compare what changes.
4. Read the accompanying explanations to connect the visuals with the concept.

For example, compare wave and observer modes in the double-slit demo, or switch atomic models in the Rutherford experiment.

## Technology

| Layer | Implementation |
| --- | --- |
| Structure | HTML |
| Presentation | CSS embedded in individual pages |
| Interaction | JavaScript embedded in individual pages |
| Simulation graphics | HTML Canvas |
| Typography | Google Fonts |
| Hosting | GitHub Pages |

There is no Node.js application, package manifest, or compilation workflow in the current repository.

## Run Locally

### Option 1: Open a page directly

Clone or download the repository and open `index.html` in your browser.

### Option 2: Use a local web server

With Git and Python 3 installed:

```bash
git clone https://github.com/scisims12/scisims.git
cd scisims
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000). On Windows, you can use `py -m http.server 8000` if `python` is unavailable.

Stop the server with **Ctrl+C**.

External fonts and third-party scripts require an internet connection. Core page files are stored in this repository.

## Repository Structure

```text
scisims/
├── README.md
├── index.html
├── einstein_experiments.html
├── double_slit_experiment.html
├── photoelectric_effect_simulation.html
├── rutherford_gold_foil_experiment.html
├── india_rainfall_report_25years.html
└── india_rainfall_report_2026_prediction.html
```

Each experiment or report is a standalone HTML file containing its own styles and JavaScript.

## Scientific Scope & Data

The simulations are simplified educational visualizations. Their animations and controls should be interpreted as teaching aids rather than validated numerical research models.

The rainfall pages reference these sources:

- [India Meteorological Department](https://mausam.imd.gov.in/)
- [Rainfall in India — data.gov.in](https://data.gov.in/catalog/rainfall-india)
- [IMD Pune](https://imdpune.gov.in/)

These references do not establish that every displayed value has been independently verified. Check the original datasets, units, coverage, and methodology before using report figures in other work.

The **2026 forecast page is a project forecast presentation**, not a live weather service or an official IMD forecast. Its predictions should not be treated as observed rainfall totals.

## Contributing

Improvements to scientific explanations, accessibility, mobile layouts, simulation behavior, and data documentation are welcome.

1. [Open an issue](https://github.com/scisims12/scisims/issues) describing the problem or proposed improvement.
2. Fork the repository and create a branch.
3. Make a focused change using the existing HTML, CSS, and JavaScript structure.
4. Check the affected page in a browser, including its controls, navigation, and narrow-screen layout.
5. Submit a pull request explaining the change and how you checked it.

For changes to scientific formulas or rainfall figures, include a reliable source and describe any assumptions. There is currently no automated test suite; browser checks are needed for interactive behavior.

## Improvement Roadmap

The following are proposed improvements, not completed features:

- [ ] Add screenshots or short demo recordings.
- [ ] Document equations, assumptions, and units for each simulation.
- [ ] Record rainfall dataset versions and reproducible calculation steps.
- [ ] Improve keyboard controls and accessibility.
- [ ] Add automated checks for links and JavaScript behavior.
- [ ] Extract shared navigation and styling where useful.
- [ ] Choose and add an explicit license.

## Maintainer & Links

Created and maintained by **Priyanshu Sharma**.

| Link | Destination |
| --- | --- |
| Live SciSims | [scisims.mixify.co.in](https://scisims.mixify.co.in/) |
| Source code | [scisims12/scisims](https://github.com/scisims12/scisims) |
| GitHub profile | [scisims12](https://github.com/scisims12) |
| Portfolio | [portfolio.mixify.co.in](https://portfolio.mixify.co.in/) |
| LinkedIn | [Priyanshu Sharma](https://www.linkedin.com/in/priyanshu-sharma-a59293241/) |
| Support the project | [Ko-fi](https://ko-fi.com/scisims) |
| Bugs & suggestions | [GitHub Issues](https://github.com/scisims12/scisims/issues) |

## License

No license file is currently included. Public availability does not by itself grant permission to reuse, modify, or redistribute the code. Contact the maintainer about reuse until an explicit license is added.
