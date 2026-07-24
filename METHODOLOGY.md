# Open methodology: measuring law-firm intake reliability

## Purpose

This project measures where law-firm inquiries may be lost between first
contact and retained client. The model uses only the values entered by the user.

- [Live calculator](https://script.google.com/macros/s/AKfycbwRutKQWyl21yBJl_KmmctzzPEXB5POK6f83TLxbs5K_MTUhcE889TmsE91DJGekLij/exec)
- [Legal Growth OS](https://legalgrowthos.com/)

## Core formula

```text
Expected matter value =
monthly inquiries
× meaningful-response rate
× consultation-booking rate
× client-retention rate
× average matter value
```

The opportunity displayed is the difference between the current scenario and
the user-selected target scenario, annualized over 12 months.

## Definitions

- **New inquiry:** A distinct potential-client contact from a call, form,
  email, chat, text, or referral.
- **Meaningful response:** A reply that acknowledges the matter and provides a
  usable next step; a generic automated receipt alone does not count.
- **Booked consultation:** A consultation placed on a calendar with a defined
  date and time.
- **Retained client:** A prospect who completes the firm's engagement
  requirements.
- **Average matter value:** A conservative estimate of collected revenue per
  newly retained matter.

## Published context

The calculator displays external research as context, not as hidden inputs:

- [Clio's 2024 client-intake secret-shopper findings](https://www.clio.com/guides/client-intake-legal-trends/)
- [Hennessey Digital's 2024 Lead Form Response Time Study](https://hennessey.com/2024-law-firm-lead-form-response-time-study/)

## Limitations

- The output is illustrative, not a revenue forecast.
- Conversion rates vary by practice area, jurisdiction, qualification
  criteria, lead source, and collection rate.
- Responsiveness may correlate with outcomes without being the sole cause.
- Firms should use expected collected revenue, not headline case value.
- Nothing here is legal advice or a guarantee of clients.

## Proposed Legal Intake Reliability Index

A future quarterly index could accept voluntary, anonymized firm-level data and
publish only aggregate quartiles when a category has a sufficient sample.
Every release should disclose its collection window, sample size, definitions,
exclusions, and limitations.

The starter schema is in `data/template.csv`. It contains no real firm or client
information.

## Feedback requested

For people who manage law-firm intake: which handoff is hardest to measure
accurately—meaningful response, booked consultation, or retained client? Open a
GitHub issue with the definition you would change before this becomes a
benchmark.
