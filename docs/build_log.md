# AgentHack 2026 — Build Log

Solo participant: Alphin Shaju
Project: Indian Consumer Commission AI Case Manager
Track: Agentic Case Management
Started: May 19, 2026

---

## Daily progress

### 2026-05-19
- Set up UiPath Labs access, GitHub repo, Node.js, UiPath CLI (uip), Claude Code
- Installed all 21 UiPath skills into Claude Code via uip skills install --agent claude
- Rotated Platform Units API key

---

## Decisions made

- Track choice: Agentic Case Management — fits 3-agent orchestration around long-running consumer disputes
- Demo case: Priya's ₹14,499 Flipkart phone dispute — universal, evidence-rich, emotionally resonant
- Architecture: 3 agents (Intake, Evidence, Filing) + Maestro orchestrator + e-Daakhil RPA
- Language scope: English only for MVP; Tamil/Hindi as roadmap
- Build approach: Claude Code with UiPath skills doing scaffolding, manual review in Studio Web

---

## Problems hit

- uip CLI not found after install: confused uipath vs uip command name. The npm package is @uipath/cli but the binary is uip. Fixed by using correct command.

---

## Product feedback for UiPath

- Platform Units API key visible in plain text on licenses page. Suggestion: mask by default with a reveal button to prevent accidental exposure via screenshots or screen sharing.
- CLI command name uip differs from package name @uipath/cli — could be clearer in install docs.
