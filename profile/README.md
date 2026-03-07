# Project Navi

Open-source AI security. Zero trust architecture and mathematical governance.

We build security infrastructure for teams deploying AI systems - tools that make governance native to the development process, not an afterthought.

We don't compete with AI companies. We make their deployments safer. Our tools sit at the boundaries - between your model and untrusted input, between your code and production, between your repo and your first commit. We're infrastructure, not product.

---

## What We Ship

### [cd-formalization](https://github.com/Project-Navi/cd-formalization)
**Machine-verified proof** that self-sustaining coherence configurations exist in nonlinear elliptic PDE systems - formalizing, for the first time, the mathematical conditions under which autopoietic closure can emerge. Lean 4 against Mathlib v4.28.0. **Fifteen theorems proved, zero sorry (no unfinished proofs), 3000+ build jobs clean.** Where Mathlib lacks infrastructure (Schauder estimates, maximum principles, sub/super-solution theory), the axiom boundary is explicit and auditable via a **single typeclass**. Algebraic core proofs were synthesized using Aristotle (Harmonic) - human architecture, machine search, **compiler as final arbiter**. The underlying theory is in the [paper](https://github.com/Project-Navi/navi-creative-determinant/blob/main/paper/creative_determinant.pdf).

### [fd-formalization](https://github.com/Project-Navi/fd-formalization)
**Machine-verified proof** that the (u,v)-flower graph has hub distance u^g and log-ratio convergence to log(u+v)/log(u) - the quantity that equals box-counting fractal dimension in the physics literature (Rozenfeld, Havlin & ben-Avraham 2007). Lean 4 against Mathlib v4.28.0. **Zero sorry, zero custom axioms.** Explicit SimpleGraph construction with graph-theoretic distance proof. This is the ground truth that [navi-fractal](https://github.com/Project-Navi/navi-fractal) calibrates against.

### [navi-sanitize](https://github.com/Project-Navi/navi-sanitize)
Deterministic **input sanitization for untrusted text** in LLM pipelines. Strips homoglyphs, invisible Unicode, null bytes, template injection, and path traversal vectors. **Zero dependencies**. Python 3.12+. Live on [PyPI](https://pypi.org/project/navi-sanitize/).

### [grippy](https://github.com/Project-Navi/grippy-code-review)
AI-powered PR review agent with a **deterministic security rule engine**. Indexes your codebase into a **knowledge graph** for context-aware analysis. Runs security rules before the model touches the diff. Structured findings, severity scores, pass/fail verdicts. Works with any model.

### [navi-bootstrap](https://github.com/Project-Navi/navi-bootstrap)
Spec-driven repo scaffolding that ships CI, security scanning, code review, and release pipelines in a single command. Jinja2 engine with 7 template packs. **Define your standards once, apply them everywhere**. Python 3.12+. Live on [PyPI](https://pypi.org/project/navi-bootstrap/).

### [navi-fractal](https://github.com/Project-Navi/navi-fractal)
Audit-grade **fractal dimension estimator** for complex networks with refusal semantics - if the evidence for power-law scaling isn't there, you get a machine-readable refusal, not a meaningless number. Sandbox method with four quality gates: R² threshold, AICc model selection, curvature guard, slope stability. **Zero dependencies**. Calibrated against networks with exact analytical dimensions from [fd-formalization](https://github.com/Project-Navi/fd-formalization). Python 3.12+.

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

Questions? [legal@projectnavi.ai](mailto:legal@projectnavi.ai) for licensing, [security@projectnavi.ai](mailto:security@projectnavi.ai) for security.

---

## The Deeper Framework

The tools above are the entry point. Underneath them is a mathematical governance framework built on three foundations:

**Differential Symbolic Calculus (DSC)** - Measurement framework for detecting coherence-exploration coupling in dynamical systems. Instrumentation, not simulation.

**World Model Capital (WMC)** - Trust-allocation system adapting Recovery Capital frameworks from behavioral health to AI governance. Trust capital for machine cognition.

**Relational Emergent Ontology (REO)** - Philosophical foundation where intelligence is event, identity is rhythm, ethics is resonance.

You don't need to understand any of this to use the tools. But if you're curious: we started here because the principles that help people recover help systems stay whole. Our founder spent seven years in behavioral health research before building AI infrastructure, and that background shapes everything - from how we design trust boundaries to why we think governance should empower, not constrain.

---

## License

Dual license: AGPL-3.0 (open source) or commercial license.
Terms & Privacy: [projectnavi.ai/legal](https://www.projectnavi.ai/legal)

---

## Support Our Work

This project is community-funded. No venture capital, no corporate sponsors shaping the roadmap.

[Sponsor Project Navi on GitHub](https://github.com/sponsors/Project-Navi)

---

*Machine cognition, human values.*

> *The knowledge is free, the community is open. If you wish to support our mission, [buy a t-shirt](https://projectnavi.printful.me/).* 🐘
