# SafeNest Advisory — Knowledge Repository

Schema v2.4 · April 2026 · Confidential — Advisor Use Only

## Repository Structure

grid/
  SafeNest_DataInput_Grid_v2.4.docx
  — Airtable field-by-field entry guide. 79 fields, all groups.

prompts/
  SafeNest_DataInput_Prompt_v2.4.docx
  — Full AI scoring prompt. Upload project docs + paste this prompt into Claude.

  SafeNest_DeepResearch_GenerationPrompt.txt
  — Generates the buyer-facing Deep Research Report HTML from Airtable data.

  SafeNest_ComparisonReport_GenerationPrompt.txt
  — Generates the 3-project Advisor Comparison Report HTML from buyer profile + data.

reports/
  SafeNest_DeepResearch_FINAL.html
  — Buyer Due Diligence Report template (reference copy).
  — Includes: Score Gauge, Luxury Index, Risk Radar, 13 sections, timestamp.

  SafeNest_ComparisonReport_FINAL.html
  — Advisor Comparison Report template (reference copy).
  — Includes: Profile Match Cards, Chip Table, SafeNest Verdict, 3-score headers.

schema/
  SafeNest_Schema_v2.4.docx
  — Complete schema specification. All formulas, field types, scoring methodology.

## How to Generate a Report

1. Open Airtable. Score a project using the Data Input Prompt.
2. Export the project record fields.
3. Open a new Claude conversation.
4. Paste the relevant Generation Prompt (Deep Research or Comparison).
5. Paste the Airtable field values into the [DATA INPUT] section.
6. Send. Claude generates the complete HTML file.
7. Save the HTML file. Share with buyer or present in advisory meeting.

## SafeNest Proprietary Scores

- SafeNest Score: weighted 8-parameter composite (0–10)
- Credit Rating: AAA to B (based on SafeNest Score)
- SafeNest Luxury Index™: 100-point product classification engine
  Pillars: Construction · Density · Amenities · Spatial Comfort · Infrastructure

## Version History

v2.4 (April 2026): Added Luxury Index™ engine (Group 8), 
  Corridor_Width_Ft, Door_Height_Ft, Land_Per_Unit_Sft formula.
  Deep Research and Comparison Reports finalized.
  Old Advisor_Dashboard and Buyer_Report retired.

v2.3: Added Product Physical Specs, Premium Features, Group 7.
v2.2: Core schema established.
