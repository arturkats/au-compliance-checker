# APRA applicability checker: CPS 230 and CPS 234

An interactive page that tells an Australian organisation whether APRA's **CPS 230 Operational Risk Management** (July 2026) and **CPS 234 Information Security** (July 2019) apply to it, and why, with paragraph references for every step.

**Try it:** https://arturkats.github.io/au-compliance-checker/

## What it does

- Asks up to five plain-English questions: type of organisation, foreign branch status, Head of a group, written APRA adjustments, and (for everyone else) whether you provide services to an APRA-regulated client.
- Gives a separate result for each standard, with the reasoning paragraph by paragraph and a summary of the key obligations.
- Covers three outcomes:
  1. **Directly regulated**, with the scope narrowed to Australian branch operations for foreign ADIs, Category C insurers and EFLICs (para 3).
  2. **Not regulated, but affected through the contract**: material service providers face the clauses, monitoring and APRA access rights in CPS 230 paras 52–61, and anyone managing a client's information assets faces the third-party checks in CPS 234 paras 16, 22 and 28.
  3. **Not affected.**
- Handles the July 2026 changes: the new numbering and the exempt service provider categories (CPS 230 para 57 and its Attachment).
- Explains defined terms (ADI, NOHC, Head of a group and others) when you point at or tap them.

## How you use it

Rest your pointer on an answer and it fills up. After 5 seconds it's chosen. Rest on **Previous** for 2 seconds to go back, or on an earlier answer to change it. A dwell only starts when the pointer moves, so a new question appearing under a resting cursor never chooses itself.

Click, tap and keyboard all work too. You can set the hover time to 3 seconds or turn it off. Light and dark mode follow your system setting.

## Built with

One self-contained `index.html` (HTML, CSS and plain JavaScript). There's no build step and no server, and nothing you enter leaves your browser.

## Sources

- [Prudential Standard CPS 230 Operational Risk Management](https://www.legislation.gov.au/F2026L00475/latest/text), July 2026 (F2026L00475)
- [Prudential Standard CPS 234 Information Security](https://www.legislation.gov.au/F2018L01745/latest/text), July 2019 (F2018L01745)

## Roadmap

Privacy Act 1988, Essential Eight, ISO/IEC 27001, ISO 31000, NIST CSF 2.0 and PCI DSS.

## Disclaimer

An educational tool, not legal advice. Confirm your position with the standards themselves, APRA's guidance or a qualified adviser.
