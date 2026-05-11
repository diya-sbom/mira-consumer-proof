# MIRA v1.0 — Verified Dependency Foundation

All current behaviors, verification contracts, canonical examples, BIL ledger, hash chaining, and CI enforcement are frozen.

## Key Guarantees

- PASS / FAIL decisions deterministic
- Canonical receipts defined
- Protected output enforced
- Receipt → BIL ledger append
- Hash-chain continuity
- Independent ledger verification
- External repository dependency verified
- Branch protection requires verification

## Rule

No valid MIRA receipt → no accepted execution, state, or merge.

Future changes must be additive and versioned.
