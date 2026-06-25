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

## What's in the pack

| File | What it is |
|------|-----------|
| **Contoso_Live_Prompt_Script.docx** | The presenter/runner script — exact copy-paste prompts for the Researcher agent, the Analyst agent, combining their output into a brief, and creating + connecting an agent in Agent Builder. |
| **Contoso_Outage_Restoration_Tracker.xlsx** | Fictional storm-outage data (Outage Log + auto-calculating Summary). The Analyst agent reads this. |
| **Contoso_Storm_Response_Playbook.docx** | A fictional procedures document — restoration priorities, roles, cadence, FAQ. The Researcher agent and your custom agent ground on this. |
| **Contoso_Storm_Restoration_Brief_TEMPLATE.docx** | The one-page brief structure the agent fills. |

## The scenario

Contoso Energy is a fictional utility serving five regions — **Contoso North, South,
East, Central, and West**. A storm has caused outages, and you need to (1) understand
the data, (2) produce a daily restoration brief, and (3) build a reusable agent that
does it on demand.

## How to use it (≈ the flow in the prompt script)

1. **Researcher agent** → read the Playbook → get the restoration approach + brief structure.
2. **Analyst agent** → read the Outage Tracker → get the numbers (it can run Python on the data).
3. **Combine** → in the same chat, turn the structure + numbers into a one-page brief.
4. **Agent Builder** → paste the provided "describe your agent" prompt to create
   **Storm Response Brief Builder**.
5. **Connect documents** → add the Playbook, Template, and Tracker as the agent's
   **Knowledge**; turn on Code Interpreter.
6. **Test & share** → run the test prompts, then share the agent to Teams.

Open `Contoso_Live_Prompt_Script.docx` and copy each prompt directly.

## Notes

- **No web search required.** Every demo grounds only on the included files, so it works
  even where web grounding is unavailable.
- **No coding required.** Agent Builder is no-code.
- To give an agent a file, attach it in the chat box or reference it from your
  OneDrive/SharePoint — you don't need to open Excel or Word.

## License

Released under the [MIT License](LICENSE). Use, adapt, and share freely with attribution.
