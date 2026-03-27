# Swafe Mitigation Review, Round 2

Prize pools are outlined [in the Round 1 mitigation review repo](https://github.com/code-423n4/2026-03-swafe-mitigation). Wardens must participate in all rounds to be eligible for awards. 

Refer to the [Warden guidelines for C4 mitigation reviews](https://code4rena.notion.site/Guidelines-for-C4-mitigation-reviews-ed10fc5cfbf640bd8dcec66f38b343c4) for details on multi-round mitigation reviews. 

- Starts March 30, 2026 20:00 UTC 
- Ends April 1, 2026 20:00 UTC

## Important note 

Each warden must submit a mitigation review for *every* individual item listed in the `Scope` section below. **Incomplete or insufficient mitigation reviews will not be eligible for awards.**

## Scope

### Mitigation of Low Severity Issues

Mitigations of Low Severity issues listed here will be considered in-scope:

| Fix | Mitigation of | Notes | 
| ----------- | ------------- | ----------- |
| [swafe-lib PR 151](https://github.com/swafe-io/swafe-lib/pull/151) | [S-210: Invalid guardian shares bypass threshold after voting, causing panic or wrong recovery key during reconstruction ](https://code4rena.com/audits/2025-11-swafe/submissions/S-210) |      | 
| [Commit `b273100`](https://github.com/swafe-io/swafe-lib/pull/157/changes/b2731006aa5f4a8fe6eb86b12e175db0ee0690bd) | [S-867: Secrets Not Zeroized on Drop - Memory Disclosure Risk](https://code4rena.com/audits/2025-11-swafe/submissions/S-867) |   | 
| [Commit `f030a11`](https://github.com/swafe-io/swafe-lib/pull/156/changes/f030a1178be35b5cd9b5b1ca04926fff1045fe4d) | [S-475: Critical API-Sanity Violation: Shamir Share Generation Allows t > n, Producing Unrecoverable Secrets](https://code4rena.com/audits/2025-11-swafe/submissions/S-475) |    

## Out of Scope
All other issues arising from the Swafe audit and/or the preceding mitigation review.
