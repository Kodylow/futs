# Cashu FUTs (Fedimint Usage & Technology Sketches)

These documents are an exploration into unifying Cashu's NUT protocol specifications with Fedimint's ecash implementation. 

The goals of this exercise are to:

1. Document Fedimint's ecash implementation to facilitate using, handling, and storing Fedimint Ecash tokens in a similar (potentially compatible) way to Cashu tokens by 3rd party software.
2. Identify and document overlaps between Cashu and Fedimint ecash encodings and protocols for a common specification.
3. Identify and document differences between Cashu and Fedimint ecash encodings and protocols to spark discussion and development toward future versions of Cashu and Fedimint.

The FUTs are organized to mirror the single-sig Cashu NUTs as closely as possible, with 3 additional FITs (Fedimint Implementation Technical Summaries) to introduce Fedimint's modular architecture, federated consensus model, and `Transaction` primitive which fundamentally differ from Cashu and may be unfamiliar to some readers.

The FUTs can be read independently and should be approachable for anyone familiar with Cashu's NUT specifications.

## FUT Sketches

| # | Description | Done | 
|--- | --- | --- |
| [FUT-00][./futs/FUT-00] | Cryptography and Models          | - |
| [FUT-01][./futs/FUT-01] | Mint public keys                 | - |
| [FUT-02][./futs/FUT-02] | Keysets and keyset IDs           | - |
| [FUT-03][./futs/FUT-03] | Swapping tokens                  | - |
| [FUT-04][./futs/FUT-04] | Minting tokens                   | - |
| [FUT-05][./futs/FUT-05] | Melting tokens                   | - |
| [FUT-06][./futs/FUT-06] | Mint info                        | - |
| [FUT-07][./futs/FUT-07] | Token state check                | - |
| [FUT-08][./futs/FUT-08] | Overpaid Lightning fees          | - |
| [FUT-09][./futs/FUT-09] | Deterministic backup and restore | - |
| [FUT-10][./futs/FUT-10] | Spending conditions              | - |
| [FUT-11][./futs/FUT-11] | Pay-To-Pubkey (P2PK)             | - |
| [FUT-12][./futs/FUT-12] | DLEQ proofs                      | - |

## Fedimint Implementation Technical Summaries

| # | Description | Done |
|--- | --- | --- |
| [FIT-01][./fits/FIT-01.md] | Consensus Mechanism   | - |
| [FIT-01][./fits/FIT-01.md] | Module Architecture   | - |
| [FIT-02][./fits/FIT-02.md] | Transaction Primitive | - |

