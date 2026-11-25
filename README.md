# Before Care

**Know what you need and what you could owe, before your appointment.**

Before Care is a phone-friendly web app for patients. Once an appointment is set, it shows:

- whether the service needs **prior authorization**, **precertification** (planned hospital stay), or a **referral**
- an **estimated cost**: what goes toward the deductible, copay, coinsurance, and what the plan pays
- whether the patient has **already met their deductible**, and how much would be left after the visit
- warnings for **out-of-network** care
- a **"what to ask" script** for calls to the insurer and the provider's office
- options **if the cost is more than the patient can pay**
- a plain-language **glossary**
- a **callback request** form (demo only: nothing is sent or saved)

Available in **English, Spanish, and French**.

> **Demo only.** All plans and prices are made-up samples. This is not real coverage information and not medical, legal, or financial advice.

## Why

Most coverage problems surface after care: the claim is denied, the patient receives an unexpected bill, and almost no one appeals. Before Care moves that information to before the appointment, in plain language, so patients can fix problems or plan for costs before they become medical debt.

## Designing for the patients who need it most

A patient-facing tool can shift the work of navigating coverage onto people with limited health literacy, limited English proficiency, or limited digital access. Before Care tries to reduce that risk:

- plain language, no unexplained insurance terms
- three languages, with a language switcher at the top
- large text and tap targets, works on any phone browser, no account or download
- a ready-made script, so patients know exactly what to ask
- a callback option, so a person can explain costs instead of the screen

## How the estimate works

For in-network care on the sample plans:

1. **Copay services** (primary care and specialist visits on plans with copays): the patient pays the copay; the deductible does not apply.
2. **Other services**: the patient pays toward the remaining deductible first, then coinsurance on the rest.
3. The total is **capped** at what is left of the yearly out-of-pocket maximum.

Out of network: the HMO sample covers nothing; the other samples use a separate deductible, higher coinsurance, and show a possible extra bill (balance billing).

## What a real version would need

- the patient's actual plan, benefits, and year-to-date deductible from the insurer
- the insurer's real prior-authorization rules and negotiated prices, through the cost-estimate tools health plans must offer
- a secure, private way to handle patient information
- testing with patients, including patients with limited English or health literacy

## Run it

It is one file, `index.html`. Open it in any browser, or publish it with GitHub Pages (Settings → Pages → Deploy from a branch → `main` / root).

## Author

**Myriam Sagbohan** · Brown University · Data Science, Policy, Governance, and Society
