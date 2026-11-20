# Behavioral and Forensic Analytics-Based Insider Threat Detection System for Banking Environments

An end-to-end, local, **academic prototype** that analyses employee activity logs from a *simulated* bank and
helps a human analyst find, prioritise and investigate potentially suspicious insider activity.

> **All default data is synthetic.** No real bank, employee or customer data is used or required. Alerts are
> prioritisation aids that require human review; a high risk score never establishes that someone is malicious.

## What it does
`activity logs → validation → employee baselines → 10 rules + Isolation Forest → event correlation → risk score (0-100) → explainable alerts → forensic timeline → analyst notes/disposition (SQLite) → reports + evaluation`


