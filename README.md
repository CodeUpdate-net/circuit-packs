# Daily Circuit level packs

Signed level packs for Daily Circuit, served by GitHub Pages at
`https://codeupdate-net.github.io/circuit-packs/packs/`.

These files are **published output only**. Packs are built and signed in the app repository
(`scripts/pack.mjs build`), and its `Packs` workflow publishes `packs/` here on a `pack-*` tag.
Do not edit them by hand: the app verifies every pack's ECDSA P-256 signature against the public key it
ships with and ignores anything that does not verify.
