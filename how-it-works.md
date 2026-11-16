# How ProofVault works (short version)

1. **Create.** The creator enters or pastes the deal. The app calculates the balance and, if milestones are used, the exact amount of each stage.
2. **Seal.** The terms and the creation time are turned into a SHA-256 fingerprint. The first characters become the reference code.
3. **Confirm.** The provider receives an email with a link and confirms with a one-time code sent to their address.
4. **Track.** Payments, delivery proofs, photos and notes are logged. Each entry's seal includes the previous seal.
5. **Check.** Every time the record is opened, the app recomputes the seals and compares them with the stored ones.
6. **Resolve.** If people disagree, either side can raise a dispute or share a view-only mediator link.

See the main README for the diagrams and the design decisions.
