# Weekly/Bi-Weekly Log

## Prompts
Following the [Rose/Bud/Thorn](https://www.panoramaed.com/blog/rose-bud-thorn-activity-and-worksheet#:~:text=%22Rose%2C%20Bud%2C%20Thorn%22%20is%20a%20mindful%20design%2D,day%2C%20week%2C%20or%20month.) model:

Week 2 — April 14–20, 2025

### Number of hours:

15 hours
6 hours: Model tuning, experimenting with dropout, hidden layers, and activation functions
4 hours: Running multiple training cycles to evaluate impact of architectural changes
5 hours: Adding softmax/sigmoid comparisons for binary classification

### Rose:
Seeing an accuracy boost from 82% to 85% after switching to GELU and smaller hidden layers was a big win.

### Bud:
Excited to finalize and export a reliable model that can be applied to real-world text data in the next week.

### Thorn:
Understanding how and when to switch from softmax to sigmoid for binary tasks took some clarification — documentation is not always clear for new practitioners.

### Additional thought
Saving model checkpoints at each stage allowed me to go back and compare performance across architectural variants.

Week 3 — April 21–27, 2025

### Number of hours:
15 hours
4 hours: Building a pipeline to run predictions on new CSV files
6 hours: Preparing cleaned output with predicted labels and exporting to CSV
5 hours: Writing scripts for easy loading, tokenizing, batching, and predicting

### Rose:
Building a general-purpose prediction pipeline that uses my trained model to label new data felt like the project coming full circle.

### Bud:
Looking forward to applying this model to multiple test sets and possibly visualizing class distributions.

### Thorn:
Had to troubleshoot unexpected dimension mismatches and tokenization edge cases (e.g., texts with strange encodings or long sequences).

### Additional thought
It's worth wrapping everything into a command-line script or notebook for future reuse.

Week 4 — April 28–May 5, 2025

### Number of hours:
15 hours
5 hours: Evaluating model performance on test sets and formatting classification reports
4 hours: Writing visual summaries (confusion matrix, confidence histogram)
6 hours: Drafting report for applying the model to external CSVs

### Rose:
Getting a polished PDF report with visuals and classification summaries really made the work feel complete and professional.

### Bud:
Looking ahead to refining the output labeling logic and possibly training on larger, more diverse datasets.

### Thorn:
Confusion matrix interpretation was initially tricky due to class imbalance — needed more nuanced evaluation than just accuracy.

### Additional thought
Make a checklist template for future classification projects: data prep, tokenization, architecture config, metrics, export pipeline.

---
