# ybdn-ei/.github

Socle commun des workflows GitHub Actions de l'organisation `ybdn-ei`.
Dépôt public : il ne contient que des workflows réutilisables, aucun code ni secret.

- `.github/workflows/rust-ci.yml` : format, Clippy, documentation, tests et MSRV d'une crate
  Rust, appelé par `workflow_call` depuis chaque dépôt (voir ses entrées en tête du fichier).
