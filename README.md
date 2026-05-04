# The problem

The International Monetary Fund (IMF) estimates the annual amount laundered globally at $800 billion to $2 trillion. Similarly, according to UNODC estimates cited by FATF on their latest 2024-2025 report, up to USD 2 trillion is laundered globally every year — and global asset recovery efforts still fall well short of addressing the estimated hundreds of billions in criminal proceeds circulating in the financial system annually.

Following the same FAFT report, only 53% of countries update their national risk assessments every 2–3 years, 80% face data collection challenges, and 35% report coordination failures due to limited political commitment — creating persistent blind spots that criminals exploit.

Fraud is now the #2 predicate crime worldwide. The latest round of FATF mutual evaluations found that fraud is cited in 89% of country reports (156 countries), making it the second most common crime feeding money laundering after corruption — and financial fraud is described as "one of the fastest growing threats on a global scale. Moreover, studies from ACFE show a direct correlation between economic downswings and fraudulent activity, which may be particularly relevant in the current economic and geopolitcal climate.

There is also a fast-growing loophole on virtual assets. With VA increasingly misused as channels for financial crime, global compliance remains dangerously low: implementation of FATF standards is significantly lower in the virtual asset sector than in traditional finance, and many jurisdictions have yet to regulate crypto service providers at all.

Money laundering remains a relevant problem worldwide, with a worrying financial impact. Additionally, we should remember that money laundering always involves a predicate crime with a direct impact on people's lives. Fighting money laundering is not only a financial issue, but also a social one.

# Michelle

**Michelle** is a personal self-training project focused on compliance, AML (Anti-Money Laundering), and fraud detection in financial services.

The name is a tribute to two remarkable Chilean women who broke barriers in male-dominated fields. The first is *Solange Michelle Berstein Jáuregui* — the first woman to preside over Chile's Comisión para el Mercado Financiero (CMF), appointed in 2022 under President Gabriel Boric. A Ph.D. in Economics from Boston University, she brought to the role a distinguished career spanning the Banco Central de Chile, the BID, and over a decade as Superintendent of Pensions — where she was instrumental in building Chile's solidarity pension pillar. Her tenure at the CMF was defined by a firm commitment to market transparency, institutional integrity, and financial consumer protection.

The second is *Michelle Bachelet*, Chile's two-time president and the first woman to hold that office, whose legacy of public service and leadership in traditionally male spaces remains a landmark in Latin American history.

Both embody the kind of rigor, public purpose, and boundary-breaking spirit this project aspires to reflect — even in its small, personal way.

# How

One of the core challenges of this project is data availability. Real-world AML and fraud data is highly sensitive — financial institutions are bound by strict confidentiality obligations, banking secrecy laws, and regulatory frameworks that make transaction-level data nearly impossible to access outside of a compliance or law enforcement context. The same applies to the algorithms and methodologies used in financial intelligence: detection logic, scoring models, and investigative workflows are deliberately kept non-public, as disclosing them would allow bad actors to reverse-engineer and evade them. This scarcity is not unique to Michelle — the lack of reproducibility and the absence of recognized benchmarks are widely acknowledged as a major issue in the fraud detection research field. This project therefore works within the constraints of what is openly available, accepting that some limitations in data realism are an inherent trade-off of studying this domain independently.

To work around these constraints, Michelle will rely on two main sources. The first is Kaggle, which hosts several public datasets covering credit card fraud, suspicious transaction patterns, and synthetic AML scenarios — useful for prototyping and benchmarking models. The second is the Fraud Detection Handbook, a reproducible, open-source reference published by researchers at the Université Libre de Bruxelles and Worldline Labs that covers the full ML pipeline for fraud detection, including class imbalance handling, validation strategies, feature engineering, and neural network architectures — making it a well-rounded foundation for this project.

As a data scientist coming from R, I'm using Positron quarto files to work on python while keeping a working environment that its familiar (thank you Posit).