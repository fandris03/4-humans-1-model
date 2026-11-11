##  AI Usage Documentation – Phase I

### 1. Purpose of AI assistance
Generative AI (ChatGPT) was used as an active assistant during the analysis of the original and fine-tuned YOLO11m models on the VisDrone dataset.

### 2. Key prompts used
- How can we compare the predictions of the original and fine-tuned YOLO11m models?
- How can we look at how well it detects small-object and busy scenes?
- How can we evaluate false positives, false negatives and true positives using ground-truth annotations?
- How can we visualize how each class has performed?
- How should we interpret the chnages in precision, recall and F1-score score?

### 3. Accepted suggestions
- Compare the models using the same images in the validation set.
- Analysing detection counts and confidence scores.
- Investigate how well small objects and busz scenes are detected.
- Evaluate predictions using ground-truth annotations.
- Create a comparison chart of the F1 score for each class.

### 4. Verification and corrections
The code and suggestions provided by the AI were checked to make sure they made sense in the context of the data, the notebook and the evaluation.

The six-image visual comparison and quantitative evaluation were used to verify the observations. Suggestions that would make us repeat what we ahd already done were not used.

### 5. Limitations of AI assistance
- Higher detection counts does not always mean the model is detecting better.
- Visual examples alone cannot establish whether additional detections are accurate.
- We need to evaluate using teh ground thruth to see if teh detections are accurate or false positive/missed detections.

### 6. Conclusion
AI assistance helped structure our investigation, implement visualizations and interpret model behaviour. Our final observations were based on the actual experimental outputs rather than AI suggestions alone.
