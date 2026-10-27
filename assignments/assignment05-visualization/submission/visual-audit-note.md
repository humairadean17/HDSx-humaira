## Plot Question

How does BMI differ by income groups across the NHANES survey cycle among adults aged 20-80? 

## Issues Checked

<!-- AI-EDIT(2026-06-11): SS-035 — worked example row added — needs review -->
The first row is a worked example of the expected shape — replace it with your own issue.

| Issue | Category | Why it matters | Correction |
|---|---|---|---|
|The original y axis did not state BMI units | Correctness | Measurement units are important to interpret values correctly  | Label changed to "Mean BMI (kg/m2) |
| Plot needs clear visual hierarchy between points and connecting lines | Design | Each point represents a group summary for one cycle | Made the lines thinner and the points larger to emphasize the observed group means |
| Connecting lines could be mistaken for changes in the same participants over time | Interpretation | The plot compares summaries across survey cycles rather than following individual participants | Added a caption explaining that lines connect group summaries, not individual participants |

## Final Caption

NHANES CSV snapshot. Points show unweighted mean BMI (kg/m²) within each income group and survey cycle for adults aged 20–80. Lines connect group summaries across cycles, not individual participants. 

## AI-Use Check

AI helped revise the plotting code, improve labels and caption wording, and draft the visualization audit. Verification completed such as running the document, checking CSV data, and running the codes. 