# Synthetic mobility data: interactive workshop materials

Materials for **An Interactive Workshop on Synthetic Mobility Data Generation**, hosted by the
UCL Centre for Advanced Spatial Analysis (CASA) and the PHOTO Research Team.
Tuesday 29 September 2026, 12:30 to 17:00, Maple House Room 216, 149 Tottenham Court Road, London.
Event page and booking:
https://www.eventbrite.co.uk/e/an-interactive-workshop-on-synthetic-mobility-data-generation-tickets-1999713873025

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PangYanbo/synthetic-mobility-workshop/blob/main/public_lab.ipynb)

## Overview

Real mobility data tells you where people go, and when. It is valuable for urban research and
hard to share. Synthetic mobility data is one attempt at a way round that: instead of releasing
records of real journeys, you train a model on them and generate days that belong to nobody. It
is a young idea, and it is not settled. How faithful the output really is, and how much of it
could safely be published, are both open questions.

This is an afternoon on those questions. Participants make some of this data, compare it with
real data, and help judge it.

| Time | Session |
|---|---|
| 12:30 | Lunch and set-up |
| 13:00 | **Welcome: why synthetic mobility data?** (talk) |
| 13:20 | **Hands-on I: generating a day by hand, and checking it against the data.** Invent one ordinary day in someone's life, what they do and roughly where; then see real observed days alongside the room's inventions. |
| 14:00 | **Talk: generating and evaluating synthetic human mobility data.** How synthetic days are produced, the main families of method in use today, and what is known about where each falls short. Streamed; can be booked on its own. |
| 15:00 | Break |
| 15:20 | **Hands-on II: trying the methods, and telling real from generated.** Generate days with each method on your own laptop and compare them; then a blind test, real days and generated ones side by side. |
| 16:00 | **Discussion: what is this data good for, and where are the limits?** In small groups: what you would use it for, and what has to hold before that use is acceptable. What each group decides is written down and goes into the project's record of what may eventually be published. |

Bring a laptop. No coding, no preparation and no prior knowledge are needed: everything runs in a
browser, and every step is something you click.

## What is here

- **`public_lab.ipynb`**: the participant workbook used during the workshop. Open it with the
  button above; it runs in Google Colab with nothing to install and no code to write.
- **Releases → `participant_bundle.zip`**: the data the workbook uses. You do not need to
  download it yourself: the workbook's first step fetches the latest release automatically.

## How to use it

1. Click **Open in Colab** above and sign in with a Google account.
2. Press ▶ on **① Get ready** and wait for `Ready.`
3. Work through the steps in order when the session reaches them: **② Draw a day**,
   **③ Try the methods**, **④ Real or synthetic?**.

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
