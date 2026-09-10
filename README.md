# Embed a UK Salary Calculator — One iframe, Always Current

> A single iframe snippet puts a working UK take-home pay calculator on your own site, with rates that update themselves each tax year.

Reference notes for the UK tax year **2026/27**, computed from HMRC's
published rates rather than copied from another site.

## How it works

```html
<iframe
  src="https://truetakehome.co.uk/embed/frame/"
  title="UK take-home pay calculator"
  width="100%"
  height="620"
  style="border:1px solid #e2e8f0;border-radius:8px"
  loading="lazy">
</iframe>
```

It is free, carries no tracking, and needs no key or account.

Because it loads from the source rather than copying a rate table into your page, it cannot go stale. When the April rates change the embed changes with them and you do nothing.

Useful for HR intranets, recruitment listings, accountancy sites and personal finance blogs.

## What this does not cover

An iframe will not inherit your site's fonts or colours. If you need it to match your design exactly, the [rates JSON](https://truetakehome.co.uk/rates.json) lets you build your own front end against the same figures.

## Use the calculator

**[Embed a UK Salary Calculator →](https://truetakehome.co.uk/embed/)**

Free, no sign-up, runs in your browser. Your figures are never sent anywhere.

## Related calculators

- [Payslip Checker UK](https://github.com/HadiDevLabx/uk-payslip-checker)
- [Tax Code Checker UK](https://github.com/HadiDevLabx/uk-tax-code-checker)
- [Tax Rebate Calculator UK](https://github.com/HadiDevLabx/uk-tax-rebate-calculator)
- [UK Salary Percentile Calculator](https://github.com/HadiDevLabx/uk-salary-percentile-calculator)

Full index: **[UK Tax & Take-Home Pay Guide](https://github.com/HadiDevLabx/uk-tax-and-take-home-pay-guide)** — twelve guides, twelve
worked salary examples and a reference table covering the whole UK system.

## Source and tax year

Figures are for the 2026/27 tax year, which runs 6 April 2026
to 5 April 2027, and were checked against
[gov.uk](https://www.gov.uk/guidance/rates-and-thresholds-for-employers-2026-to-2027) on 28 August 2026.

Rates change every April, and often at a Budget. Check the tax year a figure
belongs to before relying on it.

## Corrections

Found a wrong number? [Open an issue](../../issues) with the figure and a gov.uk
link. Tax errors are worth fixing quickly.

## Licence

[CC BY 4.0](LICENSE). Use it, quote it, fork it.
