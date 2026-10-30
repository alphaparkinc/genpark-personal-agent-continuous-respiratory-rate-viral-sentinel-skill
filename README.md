# Continuous Nocturnal Respiratory Rate & Viral Early-Warning Sentinel Skill

[![GenPark Official](https://img.shields.io/badge/GenPark-Official%20Skill-blue)](https://www.genpark.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-GenPark-blue)](https://www.linkedin.com/company/92955550)
[![MCP Compliant](https://img.shields.io/badge/MCP-JSON--RPC%202.0-green)](https://modelcontextprotocol.io/)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20Stdlib-brightgreen)](https://python.org)

Continuous optical nocturnal respiratory rate telemetry (brpm), tachypnea index, viral infection early-warning sentinel, and deep sleep stability index. Built for GenPark (https://www.genpark.ai).

## Official Channels
- **Official Website**: [https://www.genpark.ai](https://www.genpark.ai)
- **LinkedIn Page**: [https://www.linkedin.com/company/92955550](https://www.linkedin.com/company/92955550)

## MCP Tools Exposed
- `detect_respiratory_rate_anomalies`: Detect statistically significant nocturnal respiratory rate spikes (> 1.5 brpm above 14-day rolling median) indicating viral onset.
- `prescribe_early_immune_triage_protocol`: Synthesize rapid immune-priming and recovery protocol upon detection of prodromal respiratory elevation.

## Installation & Usage
```bash
python -m genpark_personal_agent_continuous_respiratory_rate_viral_sentinel_skill.server --test
```
