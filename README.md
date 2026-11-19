# Australian compliance checker: Privacy Act 1988, CPS 230 and CPS 234

An interactive page that tells an Australian organisation whether the **Privacy Act 1988** and APRA's **CPS 230 Operational Risk Management** (July 2026) and **CPS 234 Information Security** (July 2019) apply to it, and why, with a section or paragraph reference for every step.

**Try it:** https://arturkats.github.io/au-compliance-checker/

## What it does

### Privacy Act 1988

- Works through who the Act covers: Australian Government agencies, organisations with an Australian link (s 5B), the $3 million small business exemption (ss 6D, 6DA) and its exceptions (s 6D(4), (9)), small businesses covered for particular activities (s 6E), and opting in (s 6EA).
- Gives three separate results: the Australian Privacy Principles, the Notifiable Data Breaches scheme (Part IIIC, including tax file numbers held by small businesses), and the statutory tort for serious invasions of privacy (Schedule 2), which reaches everyone.
- Flags the employee records exemption (s 7B(3)), the automated decision-making disclosures that start on 10 December 2026 (APPs 1.7–1.8), and the Children's Online Privacy Code.

### CPS 230 and CPS 234

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

- [Privacy Act 1988](https://www.legislation.gov.au/C2004A03712/latest/text), Compilation No. 104, 4 June 2026 (C2026C00227)
- [Prudential Standard CPS 230 Operational Risk Management](https://www.legislation.gov.au/F2026L00475/latest/text), July 2026 (F2026L00475)
- [Prudential Standard CPS 234 Information Security](https://www.legislation.gov.au/F2018L01745/latest/text), July 2019 (F2018L01745)

## Roadmap

Essential Eight, ISO/IEC 27001, ISO 31000, NIST CSF 2.0 and PCI DSS.

## Disclaimer

An educational tool, not legal advice. Confirm your position with the standards themselves, guidance from APRA or the OAIC, or a qualified adviser.
