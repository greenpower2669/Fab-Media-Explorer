# Fab-Media-Explorer
 Media video explorer with miniatures creating

 # Best Practices for Prompting and Collaboration in Development

## Analysis of Prompting Method and Recommendations

**1. Integration of Fixes and Complete Code Rewrite**

**Best Practice:**
- When a fix or feature is requested, rewriting the code to integrate the modifications is an excellent method to ensure the code is coherent and functions as expected.

**Argumentation:**
- **Clarity and Coherence:** Rewriting the code allows for all modifications to be integrated coherently, ensuring all parts of the code align with the new features.
- **Documentation and Understanding:** Providing an ultra-precise description of the code after rewriting helps understand the code's functionality and facilitates future adjustments.

**Example:**
When a fullscreen feature was added, the code was rewritten to include this feature, with detailed explanations on each modified part.

---

**2. Reporting Console Anomalies**

**Best Practice:**
- Reporting console errors precisely and clearly helps identify and resolve issues more quickly.

**Argumentation:**
- **Effective Debugging:** Providing specific error messages allows targeting precisely where the code is problematic, facilitating debugging.
- **Clear Communication:** Explaining the context and conditions under which the error occurs helps understand the overall problem and find suitable solutions.

**Example:**
When a video loading error was reported (`index.html:328 [Violation] Added non-passive event listener`), it allowed correcting the addition of a passive event listener to improve page responsiveness.

---

**3. Precise Feedback During Tests**

**Best Practice:**
- Providing detailed feedback on the code's behavior after each test allows for targeted and effective adjustments.

**Argumentation:**
- **Continuous Improvement:** Precise feedback helps understand exactly what works or doesn’t, allowing for incremental and targeted adjustments.
- **Collaboration and Adjustments:** Clear feedback facilitates collaboration, ensuring modifications meet exact expectations.

**Example:**
When the mosaic mode did not work as expected, detailed feedback helped understand that videos were aligned in a single column instead of multiple, leading to a revision of the CSS and container behavior.

---

## Synthesis of Best Practices for Prompting

**1. Integration of Fixes and Complete Code Rewrite**
- **Method:** Rewrite the code entirely after each major modification.
- **Objective:** Ensure the overall coherence and functionality of the code.

**2. Reporting Console Anomalies**
- **Method:** Provide specific and detailed error messages.
- **Objective:** Facilitate debugging by precisely identifying issues.

**3. Precise Feedback During Tests**
- **Method:** Give detailed feedback on the code's behavior after each test.
- **Objective:** Allow targeted and effective adjustments to improve the code.

**4. Clear and Documented Communication**
- **Method:** Document each change in detail.
- **Objective:** Facilitate understanding and maintenance of the code.

**5. Active Collaboration**
- **Method:** Work closely together, sharing observations and ideas.
- **Objective:** Ensure modifications meet exact needs.

## Synthesis Table of Best Practices

| Practice                            | Method                                                      | Objective                                            |
|-------------------------------------|--------------------------------------------------------------|----------------------------------------------------|
| Integration of Fixes and Complete Code Rewrite | Rewrite the code after each major modification            | Ensure the coherence and functionality of the code  |
| Reporting Console Anomalies | Provide specific and detailed error messages        | Facilitate debugging by precisely identifying issues |
| Precise Feedback During Tests      | Give detailed feedback on the code's behavior      | Allow targeted and effective adjustments      |
| Clear and Documented Communication  | Document each change in detail             | Facilitate understanding and maintenance of the code |
| Active Collaboration                | Work closely together, sharing observations and ideas | Ensure modifications meet exact needs |

### Conclusion

Your method of prompting and collaboration is effective and well-structured. It promotes clear understanding, precise adjustments, and continuous improvement of the code. Integrating detailed documentation and communication practices further enhances this approach, ensuring fruitful collaboration and optimal results.

### Web App Notice

This web application works both on a server and locally, provided it is opened with a compatible browser. The features include:

- Opening local directories to display multimedia files.
- Displaying video thumbnails.
- Playing videos in a popup with advanced controls (fullscreen, pause/play, speed adjustment).
- Capturing thumbnails of videos being played.

Compatible browsers: Chrome, Edge, Firefox.

