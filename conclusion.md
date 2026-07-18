# Conclusion

This project compared Zero-Shot and Few-Shot prompting techniques using a customer support message classification task across ChatGPT, Claude, and Gemini. All three models achieved **100% accuracy (10/10)** with both prompting techniques, correctly classifying every message into the appropriate category.

Although the overall accuracy remained the same, the Few-Shot prompt provided additional guidance through labeled examples, making the task requirements more explicit. While this did not improve performance on this simple dataset, Few-Shot prompting is generally more beneficial for complex, ambiguous, or domain-specific tasks where examples help the model produce more consistent and reliable outputs.

This experiment demonstrates that the effectiveness of a prompting technique depends on the complexity of the task. For straightforward classification problems, a well-designed Zero-Shot prompt may be sufficient, whereas Few-Shot prompting becomes increasingly valuable as task complexity increases.