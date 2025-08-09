# UStAI Dataset Repository

This repository contains the dataset and summary files related to the research titled "Leveraging LLMs for User Stories in AI Systems: UStAI Dataset".

## Files Included

1.  **`summery.csv`**
    * **Description**: This file provides a summary of the included AI systems. It gives an overview of the systems from which the user stories were extracted or generated.

2.  **`complete UStAI dataset.csv`**
    * **Description**: This file contains the unannotated full dataset of user stories. It includes the raw user stories before any annotation or quality assessment.

3.  **`UStAI annotated.csv`**
    * **Description**: This file contains the annotated part of the dataset. The annotations are based on the Quality User Story (QUS) framework, which assesses the quality of user stories across various criteria.

### Column Headers in `UStAI-24.csv`

The `UStAI-24.csv` file includes the following columns, with annotations based on the QUS framework:

* **`Unnamed: 0`**: An index column, typically generated during data processing.
* **`Id`**: A unique identifier for each user story.
* **`LLM`**: Indicates the Large Language Model used to generate or process the user story, if applicable.
* **`role_shorten`**: A shortened version of the role associated with the user story (e.g., 'As a...', 'The system as a...').
* **`User story`**: The actual user story text.
* **`Non-Functional Requirements`**: Any non-functional requirements explicitly stated or implied by the user story.
* **`Implied ethical needs`**: Ethical considerations or needs that are implied by the user story.
* **`atomic`**: (QUS Syntactic Criterion) Indicates whether the user story describes one and only one feature.
* **`minimal`**: (QUS Syntactic Criterion) Indicates whether the user story contains only the essential information without unnecessary details.
* **`Conceptually sound`**: (QUS Syntactic Criterion) Indicates whether the user story is semantically correct and makes logical sense.
* **`Problem-oriented`**: (QUS Syntactic Criterion) Indicates whether the user story focuses on a problem to be solved rather than a specific solution.
* **`Unambiguous`**: (QUS Semantic Criterion) Indicates whether the user story has only one clear interpretation.
* **`Conflict-free`**: (QUS Semantic Criterion) Indicates whether the user story contradicts other user stories or requirements.
* **`Conflict-free, us`**: (QUS Semantic Criterion - User Story) Indicates the source of conflict and conflicting user stories.
* **`Estimatable`**: (QUS Semantic Criterion) Indicates whether the user story is detailed enough to allow for a reasonable effort estimation for implementation.
* **`Independent`**: (QUS Semantic Criterion) Indicates whether the user story is self-contained and can be implemented independently of other user stories.
* **`Unique`**: (QUS Semantic Criterion) Indicates whether the user story is distinct and not a duplicate of another existing user story.
* **`Unique, us`**: (QUS Semantic Criterion - User Story) Indicates the user stories that are duplicates or almost duplicate.
* **`Meas-ends relation`**: (QUS Pragmatic Criterion) Indicates whether the user story clearly links to a measurable end or objective.
* **`Meas-ends relation, us`**: (QUS Pragmatic Criterion - User Story) Indicates the user stories with means-ends relations.

## Citation

If you use this dataset in your research or work, please cite the following paper:

```bibtex
@inproceedings{10.1145/3727582.3728689,
author = {Yamani, Asma and Baslyman, Malak and Ahmed, Moataz},
title = {Leveraging LLMs for User Stories in AI Systems: UStAI Dataset},
year = {2025},
isbn = {9798400715945},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {[https://doi.org/10.1145/3727582.3728689](https://doi.org/10.1145/3727582.3728689)},
doi = {[https://doi.org/10.1145/3727582.3728689](https://doi.org/10.1145/3727582.3728689)},
booktitle = {Proceedings of the 21st International Conference on Predictive Models and Data Analytics in Software Engineering},
pages = {21–30},
numpages = {10},
keywords = {User stories, large language models, quality requirements, requirements elicitation, requirements generation},
location = {Trondheim, Norway},
series = {PROMISE '25}
}
