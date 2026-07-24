# Law Firm Intake Leak Lab

An open-source calculator for modeling what happens between a new law-firm
inquiry and a retained client.

**[Open the live calculator](https://script.google.com/macros/s/AKfycbwRutKQWyl21yBJl_KmmctzzPEXB5POK6f83TLxbs5K_MTUhcE889TmsE91DJGekLij/exec)**

The project is sponsored by [Legal Growth OS](https://legalgrowthos.com/).
Sponsorship is disclosed because the calculator is intended to be useful,
auditable, and reusable—not disguised promotion.

## What it measures

```text
monthly inquiries
× meaningful-response rate
× consultation-booking rate
× client-retention rate
× average matter value
= modeled annual matter value
```

The calculator compares a firm's current response and booking rates with
user-selected target rates. It does not use a hidden industry average and it
does not collect visitor information.

## Why this exists

Law firms often treat lead generation as the whole growth problem. This project
focuses on the quieter operational losses after the inquiry arrives:

1. Was the inquiry captured?
2. Did the prospect receive a meaningful response?
3. Was a consultation actually booked?
4. Was the outcome tracked through retention?

For a practical implementation guide, see
[Law Firm Intake Conversion Optimization](https://legalgrowthos.com/law-firm-intake-conversion-optimization/).

## Published context

The external findings displayed in the calculator are context only; they are
not inputs to its model:

- [Clio's 2024 client-intake secret-shopper findings](https://www.clio.com/guides/client-intake-legal-trends/)
- [Hennessey Digital's 2024 Lead Form Response Time Study](https://hennessey.com/2024-law-firm-lead-form-response-time-study/)

## Repository contents

- `index.html` — standalone calculator that can be opened or hosted anywhere
- `METHODOLOGY.md` — definitions, formula, limitations, and a proposed open index
- `data/template.csv` — starter schema for anonymized, aggregate research

## Run it

Download the repository and open `index.html` in a modern browser. No build
step, account, analytics script, or API key is required.

## Limitations

This is an educational model, not a revenue forecast, legal advice, or a
guarantee of clients. Results depend entirely on the numbers entered. Practice
area, jurisdiction, qualification criteria, lead source, and collection rates
can materially change real outcomes.

## Contribute

Feedback from attorneys, intake teams, legal operations professionals, and
researchers is welcome. Open an issue describing which definition or handoff
you would change and why.
