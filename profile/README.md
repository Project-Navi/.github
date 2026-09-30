# Project Navi

Open-source AI security. Zero trust architecture and mathematical governance.

We build security infrastructure for teams deploying AI systems - tools that make governance native to the development process, not an afterthought.

We don't compete with AI companies. We make their deployments safer. Our tools sit at the boundaries - between your model and untrusted input, between your code and production, between your repo and your first commit. We're infrastructure, not product.

---

## What We Ship

### [takens-formalization](https://github.com/Project-Navi/takens-formalization)
**Takens' theorem for generic pairs, machine-checked.** On a compact smooth d-manifold, the pairs (T, h) of a C² diffeomorphism and a C² observation whose delay map with 2d+1 coordinates is a C² embedding are **open and dense** in Diff²(M) × C²(M, ℝ). Also finite-regularity Sard (via a port of Moreira's theorem), exact finite-state horizons and ordinal codes. Lean 4 + Mathlib v4.34.1; **no `sorry`, standard axioms only**.

### [fd-formalization](https://github.com/Project-Navi/fd-formalization)
**Box-counting dimension of the (u,v)-flowers, machine-checked.** For 1 < u ≤ v, the Rozenfeld–Havlin–ben-Avraham flowers have dimension log(u+v)/log u: as the limit of their recurrences, as a log-ratio of the explicit graphs, and as a box-counting dimension over minimum box covers **at every resolving scale**. Lean 4 + Mathlib v4.34.1; **no `sorry`, standard axioms only**.

### [cd-formalization](https://github.com/Project-Navi/cd-formalization)
**Existence theory for the Creative Determinant** boundary value problem −ΔΦ = a|∇Φ| + bΦ − c(Φ₊)ᵖ. On finite weighted graphs, a positive solution is **fully proved**; the continuum results are conditional on explicit, documented elliptic hypotheses. Lean 4 + Mathlib v4.34.1; standard axioms only. Theory in the [paper](https://github.com/Project-Navi/navi-creative-determinant/blob/main/paper/creative_determinant.pdf).

### [navi-sanitize](https://github.com/Project-Navi/navi-sanitize)
Deterministic **input sanitization for untrusted text** in LLM pipelines. Strips homoglyphs, invisible Unicode, null bytes, template injection, and path traversal vectors. **Zero dependencies**. Python 3.12+. Live on [PyPI](https://pypi.org/project/navi-sanitize/).

---

## Trust & Security

- No trackers, no analytics
- Security contact: [security@projectnavi.ai](mailto:security@projectnavi.ai)
- Vulnerability disclosure: [projectnavi.ai/trust](https://www.projectnavi.ai/trust)
- PGP key: [`/.well-known/pgp-key.txt`](https://www.projectnavi.ai/.well-known/pgp-key.txt) (fingerprint: `402E C296 1A72 CBFF 63B8 FEE9 A42A 76A1 C696 FF08`)
- Machine-readable: [`/.well-known/security.txt`](https://www.projectnavi.ai/.well-known/security.txt)

---

## Contributing

PRs welcome. See [CONTRIBUTING.md](https://github.com/Project-Navi/.github/blob/main/CONTRIBUTING.md) for guidelines.

Questions? [legal@projectnavi.ai](mailto:legal@projectnavi.ai) for legal questions, [security@projectnavi.ai](mailto:security@projectnavi.ai) for security.

---

## License

Open source under MIT or Apache-2.0; each repository's LICENSE file says which.
Terms & Privacy: [projectnavi.ai/legal](https://www.projectnavi.ai/legal)

---

## Support Our Work

This project is community-funded. No venture capital, no corporate sponsors shaping the roadmap.

[Sponsor Project Navi on GitHub](https://github.com/sponsors/Project-Navi)

---

*Machine cognition, human values.*

> *The knowledge is free, the community is open. If you wish to support our mission, [buy a t-shirt](https://projectnavi.printful.me/).* 🐘
