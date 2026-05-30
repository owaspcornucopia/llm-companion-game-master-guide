# PwnedNext - The OWASP Cornucopia LLM Companion Guide

<img src="/images/pwnednext.jpg" width="1000">

Through gamification, this OWASP Cornucopia LLM Companion Guide uses the OWASP Cornucopia Website App and Companion Edition to introduce developers and testers to threats, risks, and requirements related to AI design and development and teaches how to mitigate AI risks.
The game takes the participants through a provocative scenario where they have to identify AI threats by studying an insecure AI implementation. They need to ask themselves, "What can go wrong?" and "What are we going to do about it"? Furthermore, by playing, they will get to know which tests from the OWASP AI Test Guide (AITG) and OWASP AI Security Verification Standard (AISVS) need to be considered in order to responsibly develop AI applications.

## Assets

The following assets are available:

- Presentation: [odt](/presentation.odp), [pptx](/presentation.pptx), [pdf](/presentation.pdf)
- High-res A1 poster for team table top sessions: [illustrator](/A1-poster.ai). [pdf](/A1-poster.pdf)
- Vulnerable App: [AI Anti-Fraud 3.0](https://github.com/owaspcornucopia/llm-companion-scenario)
- Cheat Sheets (For game masters): [PwnedNext - LLM App Cheat Sheet](https://github.com/owaspcornucopia/cornucopia-cheatsheets-llm)
- Various Assets: [images](/images)

## Instructions

See the notes in the presentation for instructions on how to run this tabletop session.
The players will be allowed to inspect the source code and view the diagrams. There is an A1 poster that can be used as a print-out to help people into the session.
When playing with multiple teams, let one person on the team lead the session. This person will be the team's game master and will receive the link to the cheat sheet. Show the person the [QR code](/images/cheatsheets-qr-code-link.png) for the cheat sheets. 

## What This Game Scenario Covers

Because ISO 42001:2023 ensures transparency, fairness, and accountability in AI, training for developers and testers typically encompasses:

- AI Literacy and Concepts: Understanding how the AI models function, their limitations, and intended applications.
- AI Risk Management: Learning how to spot vulnerabilities and biases within models.
- Data Quality Management: Ensuring that training and testing data are secure, unbiased, and compliant with privacy regulations.
- (Not included yet) Ethical AI Principles: Prioritising human oversight, safety, and non-discrimination during the design and testing phases.

This training is made specifically to cover these needs.

## ISO 42001:2023

ISO 42001 operates as a broad, risk-based management framework that requires organisations to identify AI risks and ensure that all staff have the necessary competencies to execute their roles safely.
Instead of dictating a rigid training syllabus, the standard embeds learning and competence into its high-level clauses

- Clause 7.2 (Competence): Requires your organisation to determine the necessary competence of all people doing work under its control that affects your AI performance and safety.
- Clause 7.3 (Awareness): Mandates that personnel are aware of the AI policy, their contribution to the effectiveness of the AI Management System (AIMS), and the implications of not conforming with AIMS requirements.

## Annex A Controls

ISO includes 38 optional risk management controls covering the AI lifecycle. If an organisation's risk assessment identifies that an unskilled developer or tester poses a threat to AI safety (e.g., data poisoning, bias introduction), the organisation must design and implement the appropriate training "control" to mitigate that specific risk.

## OWASP Cornucopia and ISO 42001:2023

If you have customers that need to comply with the AI Act or you have or want to have a certificate that proves you have a proper AI risk management system that covers controls that allow you to develop and test AI functionality in a responsible way, then you need to implement the appropriate Annex A controls according to the ISO 42001 standard.
The following controls are applicable in this regard:

- A.6.2 (Responsible AI Design and Development): Developers must be trained on how to apply ethical and safe design patterns. They need to understand principles like transparency, fairness, and safety boundaries during coding.
- A.6.3 (Verification and Validation): Testers and QA engineers must be trained in AI-specific testing methods. This includes evaluating model accuracy, checking for algorithmic drift, testing against adversarial attacks, and verifying 
- A.4.2 (Human Resources) mandates that organisations must ensure they have access to adequate human resources with the necessary AI expertise to develop systems safely. Training programs for internal developers and testers are standard evidence used to fulfil this control.

## Disclaimer

ISO/IEC 42001 is an externally referenced standard and is not included in this repository or covered by the repository's license. Any references in this repository to ISO/IEC 42001, its clauses, or Annex A controls are provided for informational and educational purposes only.

This training material does not, by itself, make an organisation ISO/IEC 42001 compliant and should not be treated as certification, legal advice, or a complete implementation guide. At most, it may serve as a small supporting aid when considering and implementing some of the Annex A controls referenced in this README.

## License

This work is a derivative of OWASP Cornucopia, used under the Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license. 
This derivative work is also published under the same CC BY-SA 4.0 license.
While this license explicitly permits free commercial use, a significant amount of time and effort went into adapting and maintaining this resource.
If your organisation derives commercial value from this material (e.g., for internal training, client audits, or commercial services), we kindly request that you consider supporting our ongoing work with a [voluntary donation](https://owasp.org/donate/?reponame=cornucopia&title=OWASP+Cornucopia).

## Attribution

The idea is based on [Engineers & Exploits](https://github.com/northdpole/engineers-and-exploits-the-quest-for-security) - A Cornucopia workshop. 
