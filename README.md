# CS 580 Module <MODULE_NUMBER> Activity <ACTIVITY_NUMBER>: <ACTIVITY_TITLE>

- **Course context:** CS 580: Deep Learning, AI Concentration, MSCS, SNHU  
- **Audience:** Enrolled students and faculty  
- **Status:** Living repository for course use  
- **Zotero Collection:** [<MODULE_ACTIVITY_COLLECTION_NAME>](https://www.zotero.org/groups/6498006/cs/collections/<TODO_ID>/collection)  
- **Last revised:** <MONTH DAY, YEAR>

---

## About This Activity

This activity introduces <CORE_TOPIC_OR_SKILL_AREA> used in deep learning workflows. You will use <FRAMEWORK_OR_TOOL>, course resources, and the starter notebook to complete a structured activity focused on <PRIMARY_TASK_OR_PROBLEM>.

### Part One: <PART_ONE_TITLE>

In this part of the activity, you will:

- <TASK_OR_REQUIREMENT_1>
- <TASK_OR_REQUIREMENT_2>
- <TASK_OR_REQUIREMENT_3>
- <TASK_OR_REQUIREMENT_4>

### Part Two: <PART_TWO_TITLE>

In this part of the activity, you will:

- <TASK_OR_REQUIREMENT_1>
- <TASK_OR_REQUIREMENT_2>
- <TASK_OR_REQUIREMENT_3>
- <TASK_OR_REQUIREMENT_4>

### Part Three: <PART_THREE_TITLE>

In this part of the activity, you will:

- <TASK_OR_REQUIREMENT_1>
- <TASK_OR_REQUIREMENT_2>
- <TASK_OR_REQUIREMENT_3>
- <TASK_OR_REQUIREMENT_4>

### Why This Matters

<BRIEF_PARAGRAPH_EXPLAINING_WHY_THIS_ACTIVITY_MATTERS_IN_DEEP_LEARNING_OR_AI_PRACTICE>

This activity builds foundational skills for later work in:

- <RELATED_SKILL_OR_TOPIC_1>
- <RELATED_SKILL_OR_TOPIC_2>
- <RELATED_SKILL_OR_TOPIC_3>
- <RELATED_SKILL_OR_TOPIC_4>
- <RELATED_SKILL_OR_TOPIC_5>

---

## Getting Started

### Codio VM

1. In D2L Brightspace, navigate to the **Codio** learning module (Course Menu > Learning Modules > Codio).
2. Click on the **CS-580 Deep Learning** link.
3. Start the Codio virtual machine.
4. Click on the **Assignment Resources** folder on the desktop.
5. Click on the **Module <MODULE_NUMBER> Assignments** folder.
6. Click on the **<CODIO_ACTIVITY_FOLDER_NAME>** folder.
7. Open the starter notebook (`.ipynb` file) with either:
   1. Jupyter Notebook *or*
   2. Visual Studio Code (VS Code)

### Locally

Do **NOT** download the assignment ZIP file directly from D2L Brightspace unless necessary. Instead, follow these instructions to simplify setup and version control:

0. If needed, set up your system for deep learning [(Activity 0-1)](https://github.com/cs580dl/cs580_activity_0-1).
1. Fork this repository to your GitHub account.
2. Clone your forked repository to your local machine.
3. Create and activate a Python virtual environment.
4. Install the required packages:

   ```bash
   python -m pip install -r requirements.txt
   ```

5. Open the starter notebook (`.ipynb`) using your preferred Jupyter environment, such as Jupyter Notebook, JupyterLab, or VS Code.

### On the Web

TODO: Add instructions for Google Colab and Kaggle Notebooks when available.

---

## Submitting Your Work

1. Save your completed notebook to your SNHU OneDrive or local machine.
2. In D2L Brightspace, navigate to the **Assignments** section (Course Menu > Assignments).
3. Click on the **<MODULE_ACTIVITY_TITLE_IN_D2L>** link.
4. Upload your completed notebook (`.ipynb`) or Python script (`.py`).
5. Click the **Submit** button to finalize your submission.

---

## Repository Structure

This repository structure follows best practices for organizing deep learning workflows, including separation of data, notebooks, source code, model artifacts, logs, results, and documentation.

For this activity, you primarily need the starter notebook (`<STARTER_NOTEBOOK_FILENAME>.ipynb`), the `requirements.txt` file, and this README file. The additional folders demonstrate how larger deep learning projects are commonly organized in professional and research environments.

```text
cs580_activity_<MODULE>-<ACTIVITY>/
├── configs/                  # YAML/JSON files for activity or experiment settings
├── data/
│   ├── raw/                  # Original, immutable dataset files
│   ├── interim/              # Intermediate data artifacts, if needed
│   ├── processed/            # Final model-ready datasets
│   └── external/             # Third-party datasets or downloaded resources
├── logs/                     # Training logs, run logs, or experiment records
├── models/
│   ├── checkpoints/          # Saved model checkpoints
│   └── final/                # Final trained model artifacts, if applicable
├── notebooks/                # Jupyter notebooks for experimentation
├── results/                  # Tables, figures, predictions, or evaluation outputs
├── src/                      # Main source code
│   ├── __init__.py
│   ├── data.py               # Dataset loading and preparation logic
│   ├── model.py              # Model-building logic
│   ├── train.py              # Training workflow
│   ├── evaluate.py           # Evaluation and reporting logic
│   └── utils.py              # Helper utilities
├── tests/                    # Unit tests
├── .gitignore                # Ignore datasets, environments, logs, and generated artifacts
├── <STARTER_NOTEBOOK>.ipynb  # Starter notebook for the activity
├── README.md                 # Repository documentation
└── requirements.txt          # pip dependencies
```

---

## Activity Requirements

You will complete a deep learning workflow using <FRAMEWORK>, the starter notebook, and the activity guidelines and rubric.

Your work should address the following major areas:

### <REQUIREMENT_AREA_1>

* <REQUIREMENT_1>
* <REQUIREMENT_2>
* <REQUIREMENT_3>
* <REQUIREMENT_4>

### <REQUIREMENT_AREA_2>

* <REQUIREMENT_1>
* <REQUIREMENT_2>
* <REQUIREMENT_3>
* <REQUIREMENT_4>

### <REQUIREMENT_AREA_3>

* <REQUIREMENT_1>
* <REQUIREMENT_2>
* <REQUIREMENT_3>
* <REQUIREMENT_4>

### <REQUIREMENT_AREA_4>

* <REQUIREMENT_1>
* <REQUIREMENT_2>
* <REQUIREMENT_3>
* <REQUIREMENT_4>

### Justification and Reflection

* Explain your key design, modeling, preprocessing, or evaluation decisions.
* Connect your decisions to the dataset, task, model, or results.
* Use evidence from your code outputs, tables, plots, or metrics to support your conclusions.
* Cite any sources used to support borrowed ideas, definitions, or technical decisions.

---

## Recommended Workflow

A typical workflow for this activity may include:

1. Review the activity guidelines and rubric.
2. Open the starter notebook.
3. Read all instructions and TODO comments before writing code.
4. Set up the notebook environment.
5. Load or access the required dataset.
6. Inspect the dataset structure and key properties.
7. Prepare the data for modeling.
8. Build, configure, or select the required model.
9. Train, test, or evaluate the model as directed.
10. Record important metrics, outputs, plots, or observations.
11. Analyze the results.
12. Justify your conclusions using evidence from the activity.
13. Add citations and references for any borrowed ideas or sources.
14. Restart the kernel and run all cells before submitting your final work.

---

## Use of Artificial Intelligence (AI) to Generate Content

This supplemental course resource contains content created with the help of AI tools. AI-generated content has been reviewed and refined by the course instructor to improve clarity, organization, and instructional quality.

If you use AI tools while completing this activity, follow the official SNHU AI usage guidelines and properly acknowledge their use within your submission.

Useful SNHU resources include:

* [SNHU Student Generative AI Guide](https://snhu.ink/StudentGenAIGuide)
* [Shapiro Library: Citing Artificial Intelligence](https://snhu.ink/CitationAndAI)
* 
