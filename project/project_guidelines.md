# Project Guidelines

## Project overview
This project is the main applied component of the course. You will work in small groups to carry out an end-to-end data analysis in Python using a shared dataset provided in the course.

The goal is not only to build a model, but to develop a complete analytical workflow that connects:
- a clear question,
- sound data preparation,
- appropriate analysis and modeling,
- critical evaluation,
- and an evidence-based conclusion that supports a decision or recommendation.

The project is intentionally structured around a common workflow so that all groups work from the same backbone while still having room to formulate different questions and interpretations.

## Project format
- Work in groups (group size = 2 persons).
- All groups will use the same course dataset.
- Each group will define a specific analysis question or decision-oriented objective based on that dataset.
- The project will be completed in phases across the semester.
- Deliverables will include code, short written interpretations, and a final presentation or discussion component (to be specified by the course team).

## Main learning goals of the project
Through the project, you should demonstrate that you can:
- formulate a data analysis problem from a real context,
- prepare and validate a dataset for analysis,
- perform exploratory data analysis and communicate patterns clearly,
- build and assess baseline analytical or predictive models,
- interpret uncertainty, limitations, and assumptions,
- connect analytical results to a practical decision, recommendation, or risk-oriented conclusion,
- communicate your workflow clearly and reproducibly in Python.

## Core project principle
The project follows a simple principle:

**One dataset, many questions, one shared analytical structure.**

This means that all groups are expected to follow the same general workflow, but each group may focus on a different question, target variable, framing, or interpretation angle.

## What is fixed and what is flexible

### Fixed elements
The following elements are common to all groups:
- the dataset provided by the course,
- the overall project structure and milestones,
- the required minimum analytical steps,
- the expected format of deliverables,
- the assessment criteria.

### Flexible elements
The following elements are chosen by each group:
- the specific question to investigate,
- the target variable or outcome of interest,
- the precise cleaning and preprocessing choices (with justification),
- the choice of baseline and comparison methods from the material covered in class,
- the final interpretation and recommendation.

## Expected project workflow
All groups should organize their work around the following stages.

### Stage 1: Problem framing
Define the analytical question clearly.

Your group should:
- state the question in plain language,
- explain why the question matters,
- define the target or outcome of interest,
- identify the likely inputs and relevant features,
- state the intended use of the analysis (prediction, screening, prioritization, comparison, decision support, etc.),
- describe success criteria and any important assumptions.

### Stage 2: Data understanding and quality audit
Inspect the dataset before modeling.

Your group should:
- describe the available variables,
- identify data types and units where relevant,
- check for missing values, anomalies, duplicates, or inconsistent entries,
- note potential sources of uncertainty, bias, or measurement error,
- summarize any important limitations in the dataset.

### Stage 3: Data cleaning and preprocessing
Prepare an analysis-ready dataset.

Your group should:
- justify how missing values are handled,
- explain any filtering, recoding, joining, reshaping, or feature construction,
- document outlier handling if relevant,
- ensure the final dataset used for analysis is clearly defined,
- keep the preprocessing steps reproducible in code.

### Stage 4: Exploratory data analysis
Use visual and numerical summaries to understand the data.

Your group should:
- summarize distributions and key descriptive statistics,
- visualize relationships between variables,
- identify patterns, trends, clusters, or suspicious behavior,
- connect exploratory findings to the project question,
- avoid plotting for the sake of plotting: each figure should support an insight.

### Stage 5: Baseline analysis or modeling
Build at least one baseline approach appropriate to the question.

Depending on the project question, this may involve:
- a descriptive comparison,
- a regression model,
- a classification model,
- a threshold-based screening rule,
- or another analysis method covered in the course.

Your group should:
- explain why the chosen method is appropriate,
- implement it clearly in Python,
- state any assumptions,
- compare it to a simple baseline where relevant.

### Stage 6: Validation and critical evaluation
Evaluate the quality and reliability of your results.

Your group should:
- use a suitable validation strategy,
- report relevant performance measures,
- discuss overfitting, underfitting, or instability where relevant,
- examine errors or misclassifications,
- reflect on what the model does well and where it may fail.

### Stage 7: Interpretation, uncertainty, and decision relevance
Move beyond raw performance.

Your group should:
- interpret results in the context of the original question,
- discuss uncertainty and limitations,
- explain how assumptions may affect conclusions,
- describe what the analysis suggests for action, prioritization, or decision-making,
- distinguish clearly between what is supported by the data and what remains uncertain.

## Deliverables
The final deliverable structure may be adapted by the course team, but the project should generally include the following components.

### 1. Reproducible analysis notebook(s)
Submit one or more well-organized notebooks that:
- run in sequence,
- include explanatory markdown cells,
- clearly separate preprocessing, analysis, and interpretation,
- are readable by another student or instructor.

### 2. Short written milestone submissions
At different points in the semester, groups may be asked to submit short milestone outputs such as:
- a problem framing note,
- a data audit summary,
- preliminary EDA,
- a first baseline analysis,
- a reflection on validation and limitations.

### 3. Final synthesis
The final synthesis should communicate the project as a coherent story:
- What was the question?
- What data was used?
- What was done?
- What was found?
- How reliable are the findings?
- What conclusion or recommendation follows?

This may be submitted as a short report, presentation, or discussed in an oral format, depending on the course setup.

## Minimum expectations
A successful project must do more than produce a model or a plot.

At minimum, every project must:
- define a clear question,
- demonstrate evidence of data checking and cleaning,
- include meaningful EDA,
- implement at least one justified baseline method,
- evaluate results using appropriate metrics or criteria,
- discuss uncertainty and limitations,
- provide a conclusion tied to a practical decision or recommendation.

## Reproducibility and coding expectations
Your code should reflect good analytical practice.

Expectations include:
- clear variable names,
- modular and readable code,
- comments where needed,
- no hidden manual steps,
- reproducible preprocessing and analysis,
- plots with readable labels and units where relevant,
- explicit reporting of key choices.

If the course provides templates, starter notebooks, or coding conventions, follow them.

## Teamwork expectations
All group members are expected to contribute meaningfully.

Groups should:
- distribute tasks fairly,
- keep shared notes of decisions and responsibilities,
- ensure all members understand the final workflow,
- be prepared to explain and justify the project choices individually if asked.

## Common pitfalls to avoid
Avoid the following common problems:
- choosing a vague or overly broad question,
- jumping into modeling before understanding the data,
- reporting outputs without interpretation,
- using methods that are not justified by the question,
- presenting many plots without a clear narrative,
- ignoring uncertainty, bias, or data limitations,
- treating accuracy alone as the entire result,
- writing code that cannot be followed or reproduced.

## Recommended structure for the final submission
A practical final structure is:
1. Project title
2. Question and motivation
3. Data description and quality issues
4. Preprocessing decisions
5. Exploratory data analysis
6. Method(s)
7. Validation and results
8. Uncertainty and limitations
9. Decision-oriented interpretation or recommendation
10. Conclusion

## Assessment focus
The project will be evaluated based on the quality of the analytical process, not only on the final predictive performance.

Assessment will emphasize:
- clarity of problem formulation,
- soundness of data preparation,
- appropriateness of the chosen methods,
- quality of evaluation,
- depth of interpretation,
- handling of uncertainty and limitations,
- reproducibility and communication.

## Final note
A strong project is not the one with the most complex method. A strong project is one that shows clear reasoning, careful analysis, honest evaluation, and a well-supported conclusion.

Focus on building a coherent analytical story from question to evidence to conclusion.
