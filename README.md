# Lee Bender

I build and evaluate ML systems, define how they are monitored in production, and structure how they get launched across teams.

This portfolio shows both hands-on model development and how I make technical decisions and tradeoffs when operating ML systems.

Most of this work is intentionally scoped to show decision-making, not just implementation.

My work focuses on three areas:
- building and evaluating ML systems
- defining how models are monitored and operated after deployment
- driving how ML systems get delivered across teams

This portfolio is intentionally structured to show both hands-on technical work and system-level thinking.

## Start Here

If you only look at one repo, start with:
- [network-attack-detection](https://github.com/benderla/network-attack-detection)

Then use these based on role:
- Data Science: [network-attack-detection](https://github.com/benderla/network-attack-detection)
- AI/ML Platform: [ml-model-monitoring](https://github.com/benderla/ml-model-monitoring)
- TPM: [ml-anomaly-detection-system-launch](https://github.com/benderla/ml-anomaly-detection-system-launch)

## Portfolio Map

| Repo | Purpose | What is implemented | What is conceptual | Best use in interviews |
|---|---|---|---|---|
| [network-attack-detection](https://github.com/benderla/network-attack-detection) | Anomaly detection project using network traffic data | Data prep, feature engineering, model training, evaluation, API layer, Docker, tests, experiment artifacts | Not production hardening | Data Science, ML fundamentals, model evaluation |
| [ml-model-monitoring](https://github.com/benderla/ml-model-monitoring) | Monitoring approach for ML systems after deployment | Drift detection examples, monitoring concepts, alerting workflow | Full production monitoring stack | AI/ML Platform, reliability, operational thinking |
| [ml-anomaly-detection-system-launch](https://github.com/benderla/ml-anomaly-detection-system-launch) | TPM-style launch planning for an ML system | Planning structure, launch framing, delivery artifacts | Live system not deployed | TPM, cross-functional delivery, launch management |
| [ml-platform-architecture](https://github.com/benderla/ml-platform-architecture) | Reserved for future platform architecture work | None today | Platform architecture artifacts | Not a primary repo today |

## What This Portfolio Proves

### Data Science
- feature engineering and data preparation
- anomaly detection using network traffic data
- model evaluation and threshold tuning
- practical tradeoffs between precision, recall, and false positives

### AI/ML Platform
- monitoring concepts for deployed ML systems
- data drift and alerting patterns
- operational ownership after model release
- system-level thinking beyond notebook-only work

### Technical Program Management
- launch planning for ML systems
- dependency and risk thinking
- coordination across technical and non-technical functions
- translating technical work into execution structure

## What Is Real vs. What Is Conceptual

Implemented today:
- a working anomaly detection project with code, evaluation, API, and documentation
- monitoring examples and incident-thinking artifacts
- launch planning structure for an ML system

Conceptual or partial today:
- full production deployment at scale
- complete platform architecture implementation
- enterprise-grade orchestration and observability

I keep that distinction explicit because I would rather be clear than overclaim.

## Best Questions These Repos Help Me Answer

- How did you choose and evaluate a model?
- What would you monitor after deployment?
- How would you detect drift or model degradation?
- How would you launch this system across multiple teams?
- Where is the line between implemented work and design work?

## Repositories

### [network-attack-detection](https://github.com/benderla/network-attack-detection)
Best repo for technical depth.
- anomaly detection using the CIC-IDS2017 dataset
- feature engineering, model evaluation, threshold tuning
- API layer and Docker support
- strongest repo for technical interviews

### [ml-model-monitoring](https://github.com/benderla/ml-model-monitoring)
Best repo for AI/ML platform discussions.
- monitoring concepts for deployed ML systems
- drift detection and alerting examples
- useful for conversations about post-deployment ownership

### [ml-anomaly-detection-system-launch](https://github.com/benderla/ml-anomaly-detection-system-launch)
Best repo for TPM discussions.
- ML system launch framing
- program structure, risks, and execution planning
- useful for cross-functional delivery discussions

## What This Portfolio Is Not

- not a claim of a production-scale ML platform
- not a large distributed system running in a live enterprise environment
- not a substitute for commercial production experience

It is intentionally scoped to show how I think, build, and make tradeoffs across ML systems.

## Known Gaps and Next Steps

- The anomaly detection model is not deployed in a live environment
- Monitoring is demonstrated with examples, not a full production pipeline
- Platform architecture is not fully implemented

If extended, next steps would include:
- deploying the model behind a persistent service
- adding real-time monitoring with alerting hooks
- defining a full data and model lifecycle pipeline

## LinkedIn

- https://linkedin.com/leroy_mccoy/