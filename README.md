# Copilot Agent Demo Pack — No-Code Agent Chaining (Contoso sample)

**PUBLIC sample content — free to reuse under the MIT License.**

A self-contained, hands-on demo set for learning how to chain Microsoft 365 Copilot
prebuilt agents and build your own no-code agent in **Copilot Chat + Agent Builder** —
aligned to the themes of course **MS-4019, *Transform your everyday business processes
with agents***.

Everything here uses a fictional electric utility, **Contoso Energy**, and **fictional
sample data**. There is no real company data in this repository.

> ⚠️ **Disclaimer:** All names, regions, figures, and procedures are invented for
> training. "Contoso" is Microsoft's standard fictitious-company name. Nothing here
> represents any real organization's data or emergency procedures.

---

## Scenarios

### Scenario 1 — Storm Response Brief Builder

Contoso Energy is a fictional utility serving five regions — **Contoso North, South,
East, Central, and West**. A storm has caused outages, and you need to (1) understand
the data, (2) produce a daily restoration brief, and (3) build a reusable agent that
does it on demand.

**How to use it (≈ the flow in the prompt script):**

1. **Researcher agent** → read the Playbook → get the restoration approach + brief structure.
2. **Analyst agent** → read the Outage Tracker → get the numbers (it can run Python on the data).
3. **Combine** → in the same chat, turn the structure + numbers into a one-page brief.
4. **Agent Builder** → paste the provided "describe your agent" prompt to create
   **Storm Response Brief Builder**.
5. **Connect documents** → add the Playbook, Template, and Tracker as the agent's
   **Knowledge**; turn on Code Interpreter.
6. **Test & share** → run the test prompts, then share the agent to Teams.

Open `Contoso_Live_Prompt_Script.docx` and copy each prompt directly.

### Scenario 2 — Outage Response Advisor

During outages, dispatchers and field staff need fast, consistent answers to one question:
"what do we do right now?" The procedures live across six standard operating procedures (SOPs).

The **Outage Response Advisor** agent reads the SOP library and, for any situation an
operator describes, returns the right procedure — immediate actions first, then the steps,
safety notes, and escalation thresholds — always citing which SOP it used.

**How to use it:**

1. **Agent Builder** → paste the agent description from `Contoso_Outage_Agent_Instructions_and_Scenario.docx`.
2. **Connect documents** → add all six SOP files as Knowledge sources.
3. **Test** → use the sample prompts (downed line, major storm, critical-care customer, etc.)
   to demonstrate the agent searching the correct SOP and leading with safety.

The SOP library covers:

| SOP | Title |
|-----|-------|
| SOP-01 | Localized / Single-Circuit Outage |
| SOP-02 | Major Storm / Widespread Outage |
| SOP-03 | Downed Conductor / Public-Safety Hazard |
| SOP-04 | Substation / Equipment Failure |
| SOP-05 | Critical-Care / Life-Support Customer Outage |
| SOP-06 | Planned Outage & Switching (Maintenance) |

---

## 📥 Downloads

| File | Scenario | Download |
|------|----------|----------|
| **Contoso_Live_Prompt_Script.docx** | 1 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Live_Prompt_Script.docx) |
| **Contoso_Outage_Restoration_Tracker.xlsx** | 1 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_Restoration_Tracker.xlsx) |
| **Contoso_Storm_Response_Playbook.docx** | 1 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Storm_Response_Playbook.docx) |
| **Contoso_Storm_Restoration_Brief_TEMPLATE.docx** | 1 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Storm_Restoration_Brief_TEMPLATE.docx) |
| **Contoso_Outage_Agent_Instructions_and_Scenario.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_Agent_Instructions_and_Scenario.docx) |
| **Contoso_Outage_SOP_01_Localized_Outage.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_SOP_01_Localized_Outage.docx) |
| **Contoso_Outage_SOP_02_Major_Storm.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_SOP_02_Major_Storm.docx) |
| **Contoso_Outage_SOP_03_Downed_Line_Public_Safety.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_SOP_03_Downed_Line_Public_Safety.docx) |
| **Contoso_Outage_SOP_04_Substation_Equipment_Failure.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_SOP_04_Substation_Equipment_Failure.docx) |
| **Contoso_Outage_SOP_05_Critical_Care_Customer.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_SOP_05_Critical_Care_Customer.docx) |
| **Contoso_Outage_SOP_06_Planned_Outage_Switching.docx** | 2 | [⬇ Download](https://github.com/AndrewConniff/ContosoEnergyAgentDemo/raw/main/Contoso_Outage_SOP_06_Planned_Outage_Switching.docx) |

---

## Notes

- **No web search required.** Every demo grounds only on the included files, so it works
  even where web grounding is unavailable.
- **No coding required.** Agent Builder is no-code.
- To give an agent a file, attach it in the chat box or reference it from your
  OneDrive/SharePoint — you don't need to open Excel or Word.

## License

Released under the [MIT License](LICENSE). Use, adapt, and share freely with attribution.
