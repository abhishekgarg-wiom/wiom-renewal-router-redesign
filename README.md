# Wiom OS — Customer Renewal & Router Recovery (Redesign)

A documentation-style, annotated prototype comparing the **live Figma flows** (CA June Sprint 2026) with the improvements required by the **Wiom Customer OS** doctrine. Two tabbed flows, each shown as a horizontal rail of annotated phone screens with per-screen OS rationale.

**▶ Live:** https://abhishekgarg-wiom.github.io/wiom-renewal-router-redesign/

## What's inside

Self-contained single HTML file (all Figma screens embedded as base64 — nothing to load). Dark documentation canvas, two tabs:

### 1. Renewal flow — 18 screens, 4 phases
Real Figma recharge journey + Continuity-OS safety-nets. Each screen carries colour-coded **source-OS tags** and a rationale card.
- **A · Reminder & recharge** — pre-expiry nudge, net-stopped nudge, duration picker, bill, payment
- **B · Payment outcome** — processing, success, success-in-chat, payment-pending (edge)
- **C · Pay via someone else (assisted payment)** — QR-to-helper, WhatsApp pay-for-me, wait-for-friend
- **D · Posture safety-nets** — reservation reframe (Normal), **Softened** (RS Fragile), **Recovery-first** (SQ + Recovery), verification window (Clarify-state), **AT_RISK → ARR** (resolution-not-sale), Passive-only

### 2. Router recovery flow — 13 screens, 3 phases
Real Figma router-pickup/refund journey + Exit-OS safety-nets, with a **reversibility timeline** (Calm / Bounded / Irreversible).
- **A · Happy path** (acted R15–R18, ₹300 full) — recall, return-method, UPI, self-drop, verified
- **B · Later windows** — late self-return (₹200), assisted pickup (₹200 w/ transparent breakdown), after partner TAT, edge: recovered-but-refund-pending
- **C · Exit-OS safety-nets** — SD-first recall, reversibility (recharge cancels recall), custody-with-proof, closure bookend

## OS coverage
Each flow opens with an **"OSes running on this flow"** strip. All 8 Customer OSes are applied where relevant: **Continuity, CM, SQ Driver, Recovery, RS, ARR, CIC, Exit** — postures authored by RS, broken-net suppression by SQ→Recovery, resolution (not retention) by ARR, tone by CIC (vulnerability, not value), obligations/memory by CM.

## Design fidelity
- Existing screens are the **actual Figma exports** (tagged *Current*), embedded untouched for pixel fidelity.
- New OS screens are hand-built in the app's own **व्योम chat** style with **Material Symbols Rounded** icons, brand `#D9008D`, no gradients on app content.
- Hindi-first throughout (the product is Hindi-first).

---
*Static prototype — illustrative. Built from the CA June Sprint 2026 Figma + the Wiom Customer OS specs (locked).*
