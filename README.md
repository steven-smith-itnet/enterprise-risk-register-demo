# Enterprise Risk Register — ISO 31000 / NIST SP 800-30 (Demonstration)

A self-contained, single-page demonstration of an **enterprise risk register**
for an illustrative healthcare-technology organization handling PHI. It shows
the full risk-management lifecycle — and pairs the qualitative register with
**quantitative** analysis:

- **Asset inventory** and a 5×5 **Likelihood × Impact** scoring methodology.
- **Inherent vs. residual heat maps** and a filterable, expandable **risk
  register** (12 risks with mitigations, owners, controls, and % reduction).
- **Quantifying risk in code** — a **FAIR-style Monte Carlo** loss model in
  Python (Annualized Loss Expectancy, P90/P99), **SQL** analytics over the
  register, and **pandas** reporting/heat-matrix generation.

Aligned to **ISO 31000**, **NIST SP 800-30**, and the **FAIR** quantitative model.

## 🔗 Live demo

**https://itnet-steven-smith.github.io/enterprise-risk-register-demo/**

## About

The organization, assets, and risks are **fictional** and included only to
demonstrate methodology and deliverables.

## Tech

A single `index.html` — no build step, no dependencies. All styling and
interactivity (risk-level/category filters, expandable rows, heat maps, code
tabs) are inline vanilla HTML/CSS/JS, so it deploys anywhere static files are
served (GitHub Pages, S3/CloudFront, etc.).

## Run locally

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

---

Part of the portfolio of Steven Smith — Information Security Consultant.
