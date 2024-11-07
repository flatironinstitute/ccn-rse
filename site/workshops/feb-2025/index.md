---
layout: home
---

![image](/assets/jan2025-banner.svg)

# Flatiron CCN Software Workshop, February 2025

Due to popular demand for the [January 2025 workshop](../jan-2025), the Flatiron Center for Computational Neuroscience has added a second session of its workshop on using open source packages to analyze neural data, happening in February 2025! This workshop is intended for neuroscientists who originally applied for the January workshop and are based in NYC.

Over the course of this two-day workshop, we will teach you how to use [pynapple](https://pynapple.org/) and [NeMoS](https://nemos.readthedocs.io) to analyze, model, and visualize neural data.

## <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" style="height: var(--base-font-size)"><!--!Font Awesome Free 6.6.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M215.7 499.2C267 435 384 279.4 384 192C384 86 298 0 192 0S0 86 0 192c0 87.4 117 243 168.3 307.2c12.3 15.3 35.1 15.3 47.4 0zM192 128a64 64 0 1 1 0 128 64 64 0 1 1 0-128z"/></svg> Where?

In person at the Flatiron Institute, 160 5th Ave, New York, NY 10010.

## 📆 When?

February 4 -- 6, 2025.

## 🤩 Interested?

Applications have closed. Watch [our website](/) for announcements of future workshops!

## Intended audience

- This workshop is intended for grad students and postdocs who are systems neuroscientists, i.e., who analyze electrophysiology or calcium imaging data.
- In order to make best use of the limited space in the workshop, we will prioritize accepting one applicant per lab.
- Applicants are expected to have basic familiarity with python:
  - They should have used python and standard scientific python libraries (e.g., numpy, matplotlib, scikit-learn).
  - They should be able to write their own functions to analyze and visualize data.
  - They are not expected to familiar with either pynapple or NeMoS.
- This workshop is intended for folks who are based in the New York City area. (We will host other workshops in other locations!)

## Important dates

- Applicants notified of acceptance by November 8
- Applicants must notify us of their attendance by November 18
- Workshop: February 4 to 6, 2025

## Logistics

- The workshop will take place at the Flatiron Institute Center for Computational Neuroscience in midtown Manhattan.
- We will accept approximately 30 attendees.
- Lunch will be provided.

## Workshop contents

Over the course of this workshop, attendees will learn how to use pynapple and NeMoS to explore and analyze electrophysiogical data, making use of real datasets. Users will:
- Use pynapple to represent neural data, taking advantage of the shared time axis to perform common manipulations.
- Use pynapple to characterize neural responses, e.g., compute tuning curves, cross-correlograms, power spectral densities.
- Use NeMoS to fit generalized linear models to spiking data, investigating functional connectivity and comparing among possible models.

To get a sense of the material we will cover, see our [workshop from FENS 2024](../fens-2024).

## Tentative schedule

| Day 0 (Tues, Feb 4)      |                                                                                         |
|--------------------------|-----------------------------------------------------------------------------------------|
| 1pm -- 2pm               | Welcome and networking lunch                                                            |
| 2pm -- 5pm               | Installation help                                                                       |
|--------------------------|-----------------------------------------------------------------------------------------|
| **Day 1 (Wed, Feb 5)**   | **pynapple**                                                                            |
|--------------------------|-----------------------------------------------------------------------------------------|
| 10 -- 11am               | Welcome and introduction to data standards                                              |
| 11 -- 11:30am            | Coffee break                                                                            |
| 11:30am -- 1pm           | Pynapple core                                                                           |
| 1 -- 2pm                 | Lunch                                                                                   |
| 2 -- 3:30pm              | Standard analyses in systems neuroscience, part 1: cross-correlations and tuning curves |
| 3:30 -- 4pm              | Coffee break                                                                            |
| 4 -- 5:45pm              | Standard analyses in systems neuroscience, part 2: signal processing                    |
| 5:45 -- 6pm              | [fastplotlib](https://github.com/fastplotlib/fastplotlib) advertisement                 |
|--------------------------|-----------------------------------------------------------------------------------------|
| **Day 2 (Thurs, Feb 6)** | **NeMoS**                                                                               |
|--------------------------|-----------------------------------------------------------------------------------------|
| 10 -- 11am               | Introduction to Generalized Linear Models (GLMs)                                        |
| 11 -- 11:30am            | Coffee break                                                                            |
| 11:30am -- 1pm           | Fitting a basic GLM to single neuron patch-clamp recordings                             |
| 1 -- 2pm                 | Lunch                                                                                   |
| 2 -- 4pm                 | Functional connectivity analysis of head-direction neurons                              |
| 4 -- 4:30pm              | Coffee break                                                                            |
| 4:30 -- 6pm              | Feature selection and model comparison                                                  |
| 6 -- 8pm                 | Concluding reception                                                                    |

## Speakers and TAs

{% assign speakers = "balzani,broderick,venditto,viejo,lewis,schomburg,skromne-carrasco,tanelus" | split: "," %}
{% include people_cards.html people=speakers %}