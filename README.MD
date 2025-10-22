# RetireChain – PoC Validation (Completed 10.22.25)

**Purpose:**  
This repository contains the public proof summary for RetireChain’s Proof of Concept (PoC), completed on October 22, 2025.  
The project validates that financial contribution and deferral events can be securely validated, hashed (SHA-256 + salt), and immutably written to Solana Devnet in under 6 seconds with zero PII exposure.

## Highlights
- 50 valid events tested (100% success)
- Avg confirmation: ~5.2s
- Avg cost per transaction: 0.000005 SOL
- Memo format: `v1|event_type|base58(hash)|unix_ts`
- Environment: Solana Devnet (RPC-based validation)

## Artifacts
- Validation summary (PDF): [`/docs/RetireChain_PoC_Validation_Summary_Clean.pdf`](./docs/RetireChain_PoC_Validation_Summary_Clean.pdf)
- Sample input: [`/samples/events.sample.json`](./samples/events.sample.json)
- Sample output: [`/reports/report.sample.json`](./reports/report.sample.json)

## Notes
- Full implementation, scripts, and logs are kept in a **private** repository.
- All transactions executed on **Solana devnet**.
- No employer systems, names, or proprietary materials were used.

## Contact
For collaboration inquiries: [your email here]
