# Can a language model read the numbers in an ICU chart?

Project page for the MD6329 Deep Learning for Healthcare AI mini-project.

## About the page

A blog-style write-up of one question: should we fine-tune a large language model built for health records, or train a small model from scratch? We compared Llemr-v1, a 7-billion-parameter EHR language model, with a 0.29-million-parameter event encoder on a standard benchmark, predicting in-hospital death from the first 48 hours in the ICU (PhysioNet 2012).

- **Result.** The small model scores a higher test AUROC (0.882 against 0.795) and trains about 150 times faster.
- **Diagnostics.** Three probes ask how each model uses the measured values, and point to how numbers enter a language model as the likely cause.
- **Contents.** Question, Approach, Results (two interactive charts with table views), Takeaways, LecTrace presentation and Report.
- **Links.** The top of the page links to the [LecTrace presentation](https://goaustin.github.io/LecTrace_MD6329_miniproj/#/?trace=01_icu_mortality), a step-by-step walkthrough of the model, and to the full report (PDF).

## How to access

**Online:** <https://goaustin.github.io/MD6329_miniproj_page/>. No sign-in is needed.

**Locally:** the page is a single self-contained file with no build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

The Inter font loads from Google Fonts and falls back to system fonts if it is blocked.
