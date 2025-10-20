📘 Literature Review — Microfinance on Linea: A Blockchain-Based Lending Platform
1. Introduction

Microfinance has been a cornerstone for poverty alleviation and financial inclusion since the 1970s. Institutions such as Grameen Bank and Kiva pioneered lending models that allow small, collateral-free loans for low-income individuals, primarily women, to start micro-enterprises. Despite their social impact, these institutions continue to face structural limitations—high operating costs, manual verification, and lack of scalability—that make ultra-small loans (US $10–50) uneconomical (Coli et al., 2021).

At the same time, global DeFi (Decentralized Finance) protocols have demonstrated new ways to automate credit using smart contracts. Yet these systems remain designed for crypto-asset traders rather than real-world borrowers. This literature review surveys existing microfinance approaches, their digital transformations, and how blockchain-based solutions—particularly using Linea’s zkEVM—can close the remaining inclusion gap.

2. Traditional & Digital Microfinance Landscape

Traditional MFIs.
Coli et al. (2021) found that many MFIs in Latin America rely on in-person verification and manual ledgers, which inflate administrative costs and delay approvals. For every micro-loan, up to 40 % of costs may come from staff visits, paper management, and repayment monitoring.

Digital Microfinance.
New fintech players—Tala, Branch, M-Pesa micro-credit, Jumo—have digitized loan origination and risk scoring. Mukala (2024) notes that African MFIs integrating mobile money achieved faster disbursement and broader reach but remain dependent on centralized credit bureaus and mobile-network operators. These intermediaries still control data, producing new single points of failure and trust concerns.

Key challenges repeatedly identified across the literature:

| Challenge                 | Description                                                          | Source                     |
| ------------------------- | -------------------------------------------------------------------- | -------------------------- |
| High administrative cost  | Manual verification & small loan sizes make operations unsustainable | Coli et al. (2021)         |
| Trust & transparency gaps | Borrowers/donors lack visibility into fund usage                     | Mukala (2024)              |
| Limited access            | Informal-sector workers excluded from credit scoring                 | Adegbite (2024)            |
| Slow approvals            | Paperwork and human intermediaries delay disbursement                | Kumarathunga et al. (2022) |


These issues provide the foundation for testing blockchain-enabled transparency and automation.

3. Blockchain & DeFi Applications to Lending

Blockchain in Microfinance.
Early research (Kumarathunga et al., 2022) proposed smart-contract microfinance models for farmers, where loan release is tied to predefined conditions—such as proof of seed purchase—to curb misuse. The Inter-American Development Bank (IDB) pilot (Coli et al., 2021) confirmed blockchain’s ability to streamline record-keeping and build digital borrower identities, although large-scale implementation remains untested.

DeFi Lending Models.
Aave, Compound, and Goldfinch showcase permissionless lending pools governed by algorithms. However, Aramonte et al. (2022) emphasize that such systems require over-collateralization (typically 150 % of the loan), limiting participation to wealthy crypto-holders. Chiu et al. (2023) further demonstrate that DeFi lending can be fragile—when collateral prices fall, liquidations cascade, exposing systemic risk.

Formal modeling by Bartoletti & Lipparini (2025) presents a game-theoretic view of lending protocols, showing how loan-to-value ratios and incentive design shape stability. Kumar (2023) extends these insights to SMEs, developing an Ethereum-based peer-to-peer lending framework. These studies highlight DeFi’s technical maturity but also its misalignment with micro-finance’s social objectives.

4. Research Gap & Rationale for Linea

Collectively, the literature indicates that:

Traditional MFIs → Inclusive but costly, opaque, and slow.

DeFi → Efficient but exclusive, over-collateralized, and volatile.

Digital MFIs → Improved reach but still centralized.

Thus, there is no system that combines inclusion, automation, and transparency for ultra-low-value loans.

Linea’s zkEVM architecture offers a middle path:

Low gas fees enable US $10–50 transactions economically.

Zero-knowledge proofs ensure data privacy while maintaining verifiable transparency.

EVM compatibility allows integration with existing DeFi tooling (Metamask, Solidity).

A blockchain-powered microfinance platform on Linea could decentralize the lending pool, automate disbursements and repayments via smart contracts, and record every transaction on-chain for tamper-proof auditing. Borrowers would need only a wallet or mobile app—no bank account—to access credit globally.

5. Synthesis & Future Direction

The reviewed studies demonstrate strong theoretical support for combining microfinance principles with DeFi infrastructure. The key to success lies in careful protocol design: ensuring under-collateralized lending can still manage risk through identity attestations, group guarantees, or tokenized reputation systems.

Week 9 will extend this foundation into a System Architecture and Design Blueprint, specifying:

Smart-contract modules for loan issuance and repayment;

Tokenomics of the lending pool;

Integration with Linea’s zk-proof verification;

On-chain governance and audit mechanisms.

6. References (APA 7)

Adegbite, A. (2024). The role of blockchain technology in enhancing financial inclusion. IOSR Journal of Economics and Finance, 15(5 Ser. 7), 19–28. https://www.researchgate.net/publication/385213238

Aramonte, S., Doerr, S., Huang, W., & Schrimpf, A. (2022). DeFi lending: Intermediation without information? BIS Bulletin No. 57. https://www.bis.org/publ/bisbull57.pdf

Bartoletti, M., & Lipparini, E. (2025). A theory of lending protocols in DeFi. arXiv:2506.15295. https://arxiv.org/abs/2506.15295

Chiu, J., Ozdenoren, E., Yuan, K., & Zhang, S. (2023). On the fragility of DeFi lending. Bank of Canada Staff Working Paper 2023-14. https://www.bankofcanada.ca/wp-content/uploads/2023/02/swp2023-14.pdf

Coli, P., Pflueger, C., & Campbell, T. (2021). Blockchain uses for microfinance institutions in the water and sanitation sector: Pilot study. Inter-American Development Bank. https://doi.org/10.18235/0003273

Kumar, D. (2023). A blockchain-based decentralized peer-to-peer lending framework for SMEs using Ethereum. ACM Proceedings. https://dl.acm.org/doi/10.1145/3659154.3659188

Kumarathunga, M., Calheiros, R. N., & Ginige, A. (2022). Sustainable microfinance outreach for farmers with blockchain cryptocurrency and smart contracts. International Journal of Computer Theory and Engineering, 14(1). https://www.ijcte.org/vol14/1304-CM3003.pdf

Mukala, P. (2024). On the digital transformation of microfinance institutions in Africa: Evidence and prospects. Journal of Economics and Technology Research. https://academicjournals.org/journal/JETR/article-full-text-pdf/551A2D972046
