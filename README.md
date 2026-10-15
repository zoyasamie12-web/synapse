# WorkForce Twin

WorkForce Twin is a browser-based workforce intelligence prototype. It uses a fictional employee and project dataset, transparent local calculations, and browser local storage. No server, build tools, API keys, or paid services are required.

## Run the prototype

Open `index.html` in a current version of Microsoft Edge, Google Chrome, or Firefox. The sample workforce is seeded into local storage on first launch. Changes stay in that browser profile; use **Reports and Settings → Restore demo data** to reset them.

The interface loads DM Sans and Space Grotesk from Google Fonts when a network is available. It falls back to local sans-serif fonts offline.

## Guided demo

Choose **Guided demo** on the overview, then advance through the nine-step workflow. The walkthrough moves through the Atlas Insights team recommendation, skill radar, synergy matrix, hypothetical specialist absence, ripple analysis, workload proposals, and resolution options. It does not silently modify saved assignments.

## Model notes

- Team match weights: skill fit 40%, availability 25%, experience 20%, and workload fit 15%.
- Capacity and availability are hard constraints for recommendations.
- Workload uses assigned project hours divided by availability-adjusted capacity.
- Skill risk uses active project requirements, maximum required proficiency, available qualified employees, and spare hours.
- Digital Twin and saved scenarios are hypothetical copies. Live assignments change only after an explicit approval action.
- CSV exports contain the current local records and calculated values.

All people and projects are fictional. Training catalogue entries are illustrative; the prototype does not estimate costs, durations, or guaranteed outcomes.