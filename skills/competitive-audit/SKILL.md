---
name: competitive-audit
description: Audit competitor marketing and paid media for L1/blockchain competitors (Solana, Ethereum, Ripple/XRP, Canton, Sui, or any list the user gives). Use when the user says "/competitive-audit", "competitive audit", "audit competitors", "what is Solana's marketing doing", or asks for analysis of competitor campaigns, ads, or positioning.
---

# Competitive Audit

Analyze competitor marketing through the Avalanche "Built for Business" lens: who is winning institutional/enterprise mindshare, and where are the whitespace opportunities?

## Process

1. **Scope.** Default competitor set: Solana, Ethereum, Ripple/XRP, Canton, Sui. Confirm which ones (or accept the user's list) and the lookback window (default: last 90 days).
2. **Research each competitor with web search** (multiple searches per competitor — do not rely on memory; the space moves weekly):
   - Recent campaigns, brand launches, rebrands, taglines, hero messaging on their homepage
   - Paid marketing: OOH (billboards, airports), sponsorships, event presence, video ads, podcast/newsletter buys
   - Institutional positioning: partnership announcements with banks/asset managers, enterprise case studies, regulatory posture
   - Developer/ecosystem marketing: hackathons, grants, conference keynotes
   - Recent social posts and engagement signals (see /social-audit for a deeper social pass)
3. **Analyze per competitor**: positioning statement in one line; target audience; key campaigns with links; what's working (and evidence: engagement, press pickup, mindshare); what's not working; institutional credibility level.
4. **Synthesize**:
   - Positioning map: who owns "speed," "institutional," "consumer," "neutral/credible," etc.
   - Whitespace Avalanche can own, consistent with the pillars in `../../brand/messaging-framework-PRIVATE.md` (Best Technology Built for Business / Infrastructure Not Hype / Embedded Finance That Scales)
   - Threats to monitor; 3–5 recommended actions
5. **Deliver** as a structured report. Offer: local .md/.docx file, or a Google Doc if the user's Google Drive connector is available. For a battlecard format, the `sales:competitive-intelligence` skill (if installed) produces an interactive HTML battlecard — offer it as a bonus output.

## Grounding

- Avalanche's own claims must match `../../brand/avalanche-knowledge.md`; verify technical comparisons (finality, fees, throughput) against live docs (append `.md` to build.avax.network URLs).
- Be honest about competitor strengths — the audit is only useful if it's credible. Never fabricate campaign examples or metrics; if evidence is thin, say so.
