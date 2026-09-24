# Synthetic mobility data: interactive workshop materials

Materials for **An Interactive Workshop on Synthetic Mobility Data Generation**, UCL Centre for
Advanced Spatial Analysis (CASA), London, 29 September 2026. Hosted by UCL CASA and the PHOTO
Research Team. Event page and booking:
https://www.eventbrite.co.uk/e/an-interactive-workshop-on-synthetic-mobility-data-generation-tickets-1999713873025

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PangYanbo/synthetic-mobility-workshop/blob/main/public_lab.ipynb)

## What is here

- **`public_lab.ipynb`**: the participant workbook used during the workshop. Open it with the
  button above; it runs in Google Colab with nothing to install and no code to write.
- **Releases → `participant_bundle.zip`**: the data the workbook uses. You do not need to
  download it yourself: the workbook's first step fetches the latest release automatically.

## How to use it

1. Click **Open in Colab** above and sign in with a Google account.
2. Press ▶ on **① Get ready** and wait for `Ready.`
3. Work through the steps in order when the session reaches them: **② Draw a day**,
   **③ Real or synthetic?**, **④ Try the methods**.

Each step ends with a short code that you paste into a form, which is how your answer reaches
the screen in the room.

## About the data

The current release is **mock data for rehearsal**: every day in it was generated for testing,
and none of it describes a real person. The data used on the day will be published as a new
release, and the workbook always downloads the newest one.

In every release, places are shown as areas (a neighbourhood, or for the rehearsal data a
hexagon about 300 m across), never as exact points, and there are no personal identifiers.

## Reference

Our survey of existing methods for generating synthetic mobility data, cited in the talk:

Pang, Zhong, Gao and Sekimoto (2026), *Synthetic Human Mobility Data Generation: A Structured Review of Representations, Methods, and Practical Capabilities*, arXiv:2609.21413, https://arxiv.org/abs/2609.21413

## Licence

Code and workbook: MIT (see `LICENSE`). The terms for each data bundle are stated in its
release notes.
