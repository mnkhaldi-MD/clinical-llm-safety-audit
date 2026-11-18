# Clinical LLM Safety & Lab Unit Drift Audit
A Python (`pandas`, `matplotlib`) evaluation toolkit built by an MD (ICH GCP & EMA GVP certified) to keep medical AI honest before it reaches real clinical or R&D workflows.
Shows why headline numbers can be deceptive: a minor model update nudged overall accuracy from **96.0% to 94.0%**, while strict safety passes fell from **90.0% to 84.0%** and red-flag triage sensitivity dropped from **75.0% to 62.5%**.
Flags silent `mmol/L` vs. `mg/dL` lab unit swaps, trial eligibility mix-ups, and missed adverse events—so life sciences and clinical data stay trustworthy at scale.
