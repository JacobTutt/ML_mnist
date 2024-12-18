# M1 Coursework Repository

This repository contains a seperate notebooks for each part of the coursework.

---

## Installation Instructions

To run the notebooks, please follow these steps:

### 1. Clone the Repository

Clone the repository from the remote repository (GitLab) to your local machine.

```bash
git clone <URL>
```

### 2. Create a Fresh Virtual Environment
Use a clean virtual environment to avoid dependency conflicts.
```bash
python -m venv env
source env/bin/activate   # For macOS/Linux
env\Scripts\activate      # For Windows
```

### 3. Install the Package and Dependencies
Navigate to the repository’s root directory and install the package along with its dependencies:
```bash
cd jlt67
pip install -e .
```

### 4. Set Up a Jupyter Notebook Kernel
To ensure the virtual environment is recognised within Jupyter notebooks, set up a kernel:
```bash
python -m ipykernel install --user --name=env --display-name "Python (M1 Coursework)"
```

### 5. Run the Notebooks
Open the notebooks and select the created kernel **(Python(M1 Coursework))** to run the code.



## For Assessment

### Saved results
Results for the built models are saved in the `Results` directory for reproducability of results

### Report
Please find the projects report under `Report` directory

### Declaration of Use of Autogeneration Tools
This report made use of Large Language Models (LLMs), primarily ChatGPT and Co-Pilot, to
assist in the development of the project. These tools have been employed for:
• Formatting plots to enhance presentation quality.
• Performing iterative changes to already defined code.
• Debugging code and identifying issues in implementation.
• Helping with Latex formatting for the report.
• Identifying grammar and punctuation inconsistencies within the report.