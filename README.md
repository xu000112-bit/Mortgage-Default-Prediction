# Mortgage Default Prediction

### Machine Learning in Finance | Interactive Teaching Demonstration

**[▶ View the interactive presentation](https://xu000112-bit.github.io/Mortgage-Default-Prediction/)**

## Overview

How can a lender use borrower information to estimate the probability of mortgage default? And when several machine learning models produce different probabilities, how should we decide which model is more useful?

This undergraduate-level teaching demonstration uses **mortgage default prediction** as an accessible introduction to machine learning in finance. It connects financial intuition to predictive modeling, explains the logic behind several common algorithms through animated visuals, and introduces practical ways to evaluate model performance.

The goal is not simply to produce a prediction, but to help students ask three important questions: **Who is riskier? How accurate are our probability forecasts? Can we trust the predicted probabilities?**

## Learning Objectives

By the end of the lesson, students should be able to:

- Explain why mortgage lenders estimate a borrower's **probability of default (PD)**.
- Identify examples of borrower and loan characteristics that can help predict credit risk.
- Describe the intuition behind **logistic regression**, **decision trees**, **random forests**, and **XGBoost**.
- Recognize **AlexNet** and **ResNet** as broader milestones in the development of machine learning and deep learning.
- Distinguish between **AUC** (risk ranking), **Brier score** (probability prediction error), and **calibration** (reliability of predicted probabilities).
- Explain why an individual's true default probability is not directly observable and why model evaluation requires observed outcomes across borrowers.

## Lesson Roadmap

| Topic | Key idea |
| --- | --- |
| Mortgage lending and credit risk | Why predicting default matters |
| Financial variables and historical data | Turning borrower information into model inputs |
| Logistic regression | From a linear score to a predicted probability |
| Decision trees | Learning rules from data |
| Random forests | Combining many trees to improve predictions |
| AlexNet and ResNet | Broader developments in deep learning |
| XGBoost | Sequentially improving predictions |
| AUC, Brier score, and calibration | Evaluating model discrimination and probability reliability |

## Interactive Presentation and Q&A

The presentation includes animated explanations and an interactive review dashboard. At the end of the lesson, **click any of the 12 topic tiles** to revisit the corresponding section during questions and discussion.

**Navigation**

- **Arrow keys:** Move through presentation segments.
- **Space:** Play or pause the current animation.
- **Click a review tile:** Jump to the selected topic.
- **Q:** Return to the review dashboard.
- **Back to Review:** Return to the review dashboard using the on-screen button.
- **F11:** Enter or exit browser full-screen mode (on supported desktop browsers).

For the best experience, use a recent version of Chrome or Edge on a desktop or laptop. Allow the videos a moment to load when jumping between sections.

## How It Was Built

The animations were created with [Manim](https://www.manim.community/) and [Manim Slides](https://github.com/jeertmans/manim-slides), then exported as a browser-based presentation powered by [Reveal.js](https://revealjs.com/). A lightweight HTML/JavaScript navigation layer provides the clickable Q&A dashboard without changing the underlying rendered animations.

## Repository Structure

```text
Mortgage-Default-Prediction/
├── index.html                  # Interactive browser presentation
├── Mortgage_Default_assets/    # Reveal.js assets and rendered video clips
└── README.md                   # Project documentation
```

You can view the lesson directly through **[GitHub Pages](https://xu000112-bit.github.io/Mortgage-Default-Prediction/)**. To run it locally, download or clone the repository, keep `index.html` next to the complete `Mortgage_Default_assets/` folder, and open `index.html` in a modern browser.

---

