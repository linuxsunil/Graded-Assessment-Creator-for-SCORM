# 🗺️ Roadmap & Suggested Edits

As a "non-coder" project built through AI collaboration, this roadmap invites the community to help refine the tool's core logic.

## 🚀 v1.1 Priority: Weighted Scoring ⚖️
To move from "one point per question" to a weighted system, the following edits are suggested for `GA_14_2.html`:

1.  **Parser Update (`parseQ` function):** 
    *   Modify the regex to recognize a weight tag at the end of a question stem, such as `[W:5]`.
    *   Update the `qs.push` object to include a `weight` property (defaulting to 1 if not specified)[cite: 2].
2.  **Logic Update (`showResults` function):**
    *   Introduce `totalEarnedPoints` and `maxPossiblePoints` variables.
    *   Instead of `score++`, calculate the score by adding the specific weight of correctly answered questions[cite: 2].
3.  **UI Update:** 
    *   Display the weight of each question in the **QA Preview** panel so testers can verify point distribution[cite: 2].

## 🛠️ Long-Term Enhancements
| Feature | Description |
| :--- | :--- |
| **Matching Questions** | Add logic to handle "Drag to Match" interactions within the single-file HTML structure. |
| **Base64 Media** | Enable users to drag-and-drop images that are converted to Base64 strings for 100% offline SCORM packaging. |
| **Local LLM Support** | Integration with tools like Ollama to generate questions locally without ever hitting a cloud API. |
| **Extended xAPI** | Deeper tracking of specific distractor choices to provide better learning analytics in the LRS[cite: 2]. |

## 🐞 Bug Reporting
If you find a tracking error or a parsing glitch, please open an Issue with a sample of the text that caused the error.