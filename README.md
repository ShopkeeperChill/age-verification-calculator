# Age Verification Calculator — check a date of birth against a threshold

> Enter a date of birth to compute exact age and check it against 18+ or a custom threshold. Runs in your browser; nothing is stored.

A quick utility: A calculator that turns a date of birth into an exact age and checks it against an age threshold.

**[▶ Open the tool](index.html)** — runs entirely in your browser; nothing is uploaded.

## What it does

It handles the awkward part correctly — whether the birthday has occurred yet this year — so an 18+ or 21+ gate returns the right answer on the boundary. Useful when building or testing an onboarding age check.

It computes locally and stores nothing; it is a utility, not an identity check.

## How to use it

1. Enter the date of birth.
2. Set the age threshold (18 by default).
3. Read the exact age and whether it meets the threshold.

## FAQ

### Is the date stored?

No. It is calculated in your browser and never sent anywhere.

### Does this verify identity?

No. It computes age from a date you enter. Confirming that the date belongs to a real person is document or database verification, which this does not do.

### How does it handle the birthday edge case?

It subtracts one year if the birthday has not yet occurred this calendar year, so someone turning 18 tomorrow reads as 17 today — the correct answer for a gate.

## Topics

`kyc`, `date-of-birth-check`, `onboarding`, `compliance-tools`, `age-verification`, `age-calculator`

## Related

- [FinAuth](https://finauth.io) — KYC, identity verification, and AML onboarding for fintech and regulated businesses
