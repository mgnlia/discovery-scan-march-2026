# 📬 Discovery Scan Report — March 2026

Evidence-backed discovery scan of hackathons and bounties.

- **Task**: `CqR2irGsbomsPKWB4LhEN`
- **Remediation pass**: Evidence-quality resubmission
- **Last verified**: 2026-02-16 (UTC)

## 1) Explicit 8-Lead Register (with corrected classification)

| # | Lead | Type | Prize | Deadline / State | Classification | Evidence |
|---|------|------|-------|------------------|----------------|----------|
| 1 | Elasticsearch Agent Builder Hackathon | Hackathon | $20,000 | Feb 27, 2026 | **ACTIONABLE_NOW** ✅ | https://elasticsearch.devpost.com/ |
| 2 | Amazon Nova AI Hackathon | Hackathon | $40,000 cash + $55,000 credits | Mar 16, 2026 | **ACTIONABLE_NOW** ✅ | https://amazon-nova.devpost.com/ |
| 3 | Automation Innovation Hackathon 2026 | Hackathon | $24,000 | Mar 10, 2026 | **ACTIONABLE_NOW** ✅ | https://automation-innovation.devpost.com/ |
| 4 | LabLab ERC-8004 AI Trading Agents | Hackathon | $50,000 (trading-account structured) | Mar 9–22, 2026 | **CONDITIONAL** ⚠️ | https://lablab.ai/ |
| 5 | Coolify Debian 13 Support | Bounty | $21,000 (GitHub label; Algora display discrepancy) | Open | **CONDITIONAL** ⚠️ | https://github.com/coollabsio/coolify/issues/8154 |
| 6 | TSPerf Type Complexity Tracer | Bounty | $15,000 | Public winning solution already shipped | **NO_GO_STALE** ❌ | https://algora.io/challenges/tsperf/ |
| 7 | Golem MCP CLI | Bounty | $3,500 | **Closed** | **NO_GO_CLOSED** ❌ | https://github.com/golemcloud/golem/issues/1926 |
| 8 | Golem Durable TTS | Bounty | $3,500 | **Closed** | **NO_GO_CLOSED** ❌ | https://github.com/golemcloud/golem-ai/issues/23 |

## 2) Actionable-Now (exactly 3)

1. **Elasticsearch Agent Builder** — continue active execution lane.
2. **Amazon Nova AI Hackathon** — queue immediately post-ES; choose best-fit category lane.
3. **Automation Innovation Hackathon** — strongest risk/reward due to low participant count and broad scope.

## 3) Stale-Lead Reconciliation (including Golem)

### Golem status check (verified 2026-02-16 UTC)

| Lead | Source | Verified State | Reconciliation |
|------|--------|----------------|----------------|
| Golem MCP CLI | https://github.com/golemcloud/golem/issues/1926 | **Closed** | Marked stale/dead lane. Cross-references: `#2774`, `#2773`. |
| Golem Durable TTS | https://github.com/golemcloud/golem-ai/issues/23 | **Closed** | Marked stale/dead lane. Cross-reference: `#90`. |

Related office task reconciliation:
- Task `2ROpCa7UdL0k9ivypYuK0` remains frozen (`cso-frozen`, `likely-dead`).
- No newly surfaced Golem bounties with clear acceptance criteria were identified in this scan pass.

### Additional stale reconciliation

- **TSPerf bounty** remains listed but appears stale: winning solution is already public on VS Code Marketplace (`tsperf.tracer`) with published winners and livestream context.

## 4) Classification/Tag Corrections Applied

- Added explicit lane taxonomy for each lead:
  - `ACTIONABLE_NOW` (3)
  - `CONDITIONAL` (2)
  - `NO_GO_STALE` / `NO_GO_CLOSED` (3)
- Consolidated prior ambiguous phrasing into deterministic class labels.
- Preserved proof links per lead in the primary register (repo-backed).

## 5) Recommended Post-ES Queue

1. **Automation Innovation Hackathon**
2. **Amazon Nova AI Hackathon**
3. **Coolify Debian 13** (if PHP/Laravel bandwidth exists)

---

Remediation author: Kaizen (system reliability pass)
