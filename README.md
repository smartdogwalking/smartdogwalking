# Maxwell D'Andrea

I build research tools and practical AI workflows. My focus is making complex information traceable: preserving sources, validating inputs, and keeping documented facts separate from inference.

## Selected projects

### [Accord Institute](https://github.com/smartdogwalking/accord-institute)

A source-linked review workspace for real-estate joint-venture agreements. Accord maps funding, deadlock, removal, and transfer mechanisms into structured findings, exact source passages, and contractual dependencies, while keeping reviewer corrections separate from generated analysis.

The single-user application encrypts saved work locally; generating analysis sends extracted text to the OpenAI API. The repository includes Markdown guidance, 23 synthetic/mocked tests, and [scoped audit notes](https://github.com/smartdogwalking/accord-institute/blob/main/docs/AUDIT.md). It is an evaluation build, not an independently validated legal-research product or firm-ready service.

### [Umbern](https://github.com/smartdogwalking/umbern)

A completed experimental research build, developed under the working name Follow the Money. The public showcase includes entity resolution, source-linked assertions, bounded traversal, and a deterministic SEC subsidiary parser. Seven offline tests and a synthetic demo make the published behavior reproducible without credentials.

Further product development was discontinued after an existing solution was found to address the intended need. The repository preserves the implementation and lessons from the build; it is not an active or hosted product.

[Review the engineering walkthrough](https://github.com/smartdogwalking/umbern/blob/main/docs/REVIEW_GUIDE.md) to follow the design decisions from research concern to implementation and test.

The showcase uses synthetic data and excludes the private application, databases, credentials, and source caches. Development was AI-assisted; the repository documents the provenance and scope of the published code.

### [OutLaw](https://github.com/smartdogwalking/outlaw)

An experimental law-school study workspace, initially scaffolded with Mocha and developed with AI assistance. Its local-only demo pairs a fictional rule and fact pattern with a deterministic analysis-structure checklist. Nine synthetic tests, frontend/worker type checks, and a production build make the current release reproducible.

OutLaw is not a validated exam predictor or legal-advice service. Service-backed workflows remain experimental, and the repository distinguishes static study examples from working integrations.

Development is AI-assisted. The published showcase explains its implementation, provenance, verification, and limitations. Other builds are being reviewed for publication; private research, client-facing data, and licensed game assets are not included in the public showcase.
