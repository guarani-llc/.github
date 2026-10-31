<!--
  Organization profile of Guarani LLC on GitHub (guarani-llc/.github, profile/README.md).
  The images in assets/ are rendered by tools/gh-profile.mjs in the guarani-llc.com repository.
  Image URLs are absolute on purpose: the GitHub mobile app renders this file without resolving relative paths.
  House rules: no em or en dashes, figures only inside instruments labelled as sample data.
-->

<a href="https://guarani-llc.com/en/"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/banner.svg" width="100%" alt="Guarani AI, private beta. Verify the code. Route the models. Run the devices. Clear the release."></a>

<p align="center">
  <a href="https://guarani-llc.com/en/"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/badge-site.svg" height="28" alt="Site: guarani-llc.com"></a>
  <a href="https://guarani-llc.com/en/docs"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/badge-status.svg" height="28" alt="Status: private beta"></a>
  <a href="https://www.nvidia.com/en-us/startups/"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/badge-nvidia.svg" height="28" alt="Member of the NVIDIA Inception program"></a>
  <a href="https://www.bestpractices.dev/en/projects/16112"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/badge-openssf.svg" height="28" alt="Guarani Verify Action: OpenSSF Best Practices passing"></a>
  <img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/badge-location.svg" height="28" alt="Based in Albuquerque, NM">
</p>

<p align="center">
  <b>Guarani AI</b> by Guarani LLC: autonomous software quality, multi-agent security verification and enterprise LLM gateway infrastructure. Three modules that each work alone and, together, give every release one explained verdict.
</p>

> [!NOTE]
> Guarani AI is in **private beta**. Trial workspaces are provisioned on request: [request a trial](mailto:sylvain@guarani-llc.com?subject=Guarani%20AI%20trial%20request). The instruments on this page show sample data.

## Platform

### Guarani Verify

[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/16112/badge)](https://www.bestpractices.dev/en/projects/16112)

The [Guarani Verify GitHub Action](https://github.com/guarani-llc/guarani-verify-action) has earned the OpenSSF Best Practices Passing badge. [View the action on GitHub Marketplace](https://github.com/marketplace/actions/guarani-verify-ai-security-pr-review).

<a href="https://guarani-llc.com/en/#platform"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/verify.svg" width="100%" alt="Guarani Verify, sample review: SAST, DAST, architecture and API contract stages, one authorization finding with a proposed patch, triaged by five reasoning agents. Verdict HOLD."></a>

**Autonomous multi-agent PR and security verification.** Deterministic static and dynamic analysis runs first, then frontier reasoning agents (Claude Opus 5.5, Claude Fable 5.1, GPT-6 Sol, DeepSeek V4.1, Qwen3.8) audit each pull request in real time.

- **SAST and DAST with triage.** Every security finding is ranked by reachability and impact, and arrives with a synthesized patch.
- **Architecture compliance.** Layer rules, API contracts and breaking-change detection across polyglot monorepos.
- **Isolated execution.** Reviews run in isolated environments. No training on customer code, prompts or outputs, and retention you configure.

### Guarani Mesh

<a href="https://guarani-llc.com/en/#platform"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/mesh.svg" width="100%" alt="Guarani Mesh, sample data: traffic share and latency for Azure OpenAI, Amazon Bedrock, Gemini and open-weight GPUs, spend by team against daily budgets, a regional failover and a prefix cache hit."></a>

**High-throughput enterprise LLM gateway.** One OpenAI-compatible endpoint for every model your teams and agents call, engineered for low-latency agentic pipelines.

- **Multi-provider routing and automatic failover** across Azure OpenAI, Amazon Bedrock, Google Gemini and open-weight models on dedicated GPU and RDU clusters.
- **Semantic and prefix caching** for recurring repository contexts and CI/CD traces.
- **Telemetry and cost governance.** Per-agent token accounting, per-team budgets, rate limits and schema enforcement.

### Guarani Mobile CI

<a href="https://guarani-llc.com/en/#platform"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/mobile-ci.svg" width="100%" alt="Guarani Mobile CI, sample run: sign-in, search, checkout and payment sheet journeys on Pixel 8, iPhone 15 and Galaxy S24, one hold resolved by retry. Verdict CLEARED."></a>

**Autonomous real-device QA runners.** End-to-end tests and UI verification on physical Android and iOS device fleets, started from the pipelines you already run.

- **Real device pools** allocated per run, from GitHub Actions or GitLab CI.
- **Parallel UI and regression suites** with Appium, Espresso, XCUITest and Maestro.
- **Flaky test detection** with retry and quarantine, plus video, device logs and network traces on every result.

## One verdict per release

<a href="https://guarani-llc.com/en/#architecture"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/trace.svg" width="100%" alt="Sample trace: a pull request flows through Guarani Verify, Guarani Mesh and Guarani Mobile CI into the policy engine, which returns one release verdict, CLEARED."></a>

Versioned policy rules turn the findings of all three modules into a single release verdict, posted to the pull request as a check with its reasons. The same findings under the same policy always produce the same verdict.

## Works with

| Layer | Integrations |
| --- | --- |
| Code and CI | GitHub, GitLab, [Guarani Verify Action](https://github.com/marketplace/actions/guarani-verify-ai-security-pr-review) (GitHub Actions), GitLab CI |
| Model providers | Azure OpenAI, Amazon Bedrock, Google Gemini, open-weight models on dedicated GPU and RDU clusters |
| Reasoning agents | Claude Opus 5.5, Claude Fable 5.1, GPT-6 Sol, DeepSeek V4.1, Qwen3.8 |
| Devices | Physical Android and iOS device fleets |
| Deployment | Multi-tenant cloud with isolated tenants in US or EU regions, or a dedicated VPC on Azure, AWS or Google Cloud |
| Interfaces | REST API (`api.guarani-llc.com/v1`, beta), [@guarani-ai/cli](https://www.npmjs.com/package/@guarani-ai/cli), [@guarani-ai/sdk](https://www.npmjs.com/package/@guarani-ai/sdk) (TypeScript) and [guarani-ai](https://pypi.org/project/guarani-ai/) (Python) |

## Public interfaces and status

- [Documentation](https://guarani-llc.com/en/docs) and [OpenAPI 3.1 specification](https://guarani-llc.com/openapi.json)
- [Guarani Verify on GitHub Marketplace, v1.0.2](https://github.com/marketplace/actions/guarani-verify-ai-security-pr-review)
- [OpenSSF Best Practices Passing](https://www.bestpractices.dev/en/projects/16112)
- [npm CLI: @guarani-ai/cli](https://www.npmjs.com/package/@guarani-ai/cli)
- [npm SDK: @guarani-ai/sdk](https://www.npmjs.com/package/@guarani-ai/sdk)
- [PyPI: guarani-ai](https://pypi.org/project/guarani-ai/)
- [System status](https://status.guarani-llc.com) and [status JSON](https://status.guarani-llc.com/status.json)

The public packages connect to the private beta API using a provisioned
workspace token. Installing a package does not provision service access.
The organization's CI token exercises a deterministic integration contract
fixture. Its `CLEARED` response includes `execution_mode: ci_contract_fixture`
and `analysis_performed: false`; it is not a code analysis or security approval.

## Security and disclosure

Encryption in transit and at rest. Processing in US or EU regions, chosen per workspace. No training on customer code, prompts or outputs. Audit trails and evidence exports for SOC 2 and ISO 27001 programs.

To report a security issue in Guarani software, coordinate a disclosure or discuss an enterprise deployment, write to **[sylvain@guarani-llc.com](mailto:sylvain@guarani-llc.com)**. Please include the affected component, the steps to reproduce and the impact you observed.

<br>

<a href="mailto:sylvain@guarani-llc.com?subject=Guarani%20AI%20trial%20request"><img src="https://raw.githubusercontent.com/guarani-llc/.github/main/profile/assets/next-release.svg" width="100%" alt="Verify your next release. Your repository, awaiting clearance. Request a trial."></a>

<p align="center"><sub>© 2026 Guarani LLC. Based in Albuquerque, NM. · <a href="mailto:sylvain@guarani-llc.com">sylvain@guarani-llc.com</a> · <a href="https://guarani-llc.com/en/">guarani-llc.com</a></sub></p>
<p align="center"><sub>Product and model names belong to their respective owners.</sub></p>
