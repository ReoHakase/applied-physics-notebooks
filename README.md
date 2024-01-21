# README.md

## Project Title: Statistical Analysis of Exam Scores

This project involves the statistical analysis of exam scores from a dataset. The analysis is performed using Python and various data analysis libraries.

### Project Structure

- [`README.md`](command:_github.copilot.openRelativePath?%5B%22README.md%22%5D "README.md"): This file, which provides an overview of the project.
- [`.devcontainer/`](command:_github.copilot.openRelativePath?%5B%22.devcontainer%2F%22%5D ".devcontainer/"): Contains files for setting up a development container in Visual Studio Code.
  - `Dockerfile`: Defines the Docker container in which the project runs.
  - `devcontainer.json`: Configuration for the development container.
- [`data/`](command:_github.copilot.openRelativePath?%5B%22data%2F%22%5D "data/"): Contains the dataset used in this project.
  - `exams.csv`: The dataset of exam scores.
- [`exam_scores_analysis_updated.ipynb`](command:_github.copilot.openRelativePath?%5B%22exam_scores_analysis_updated.ipynb%22%5D "exam_scores_analysis_updated.ipynb"): Jupyter notebook containing the main analysis code.
- [`example.ipynb`](command:_github.copilot.openRelativePath?%5B%22example.ipynb%22%5D "example.ipynb"): An example Jupyter notebook.
- [`poetry.lock`](command:_github.copilot.openRelativePath?%5B%22poetry.lock%22%5D "poetry.lock") and [`pyproject.toml`](command:_github.copilot.openRelativePath?%5B%22pyproject.toml%22%5D "pyproject.toml"): Configuration files for managing Python dependencies with Poetry.
- [`statistical-analysis.code-workspace`](command:_github.copilot.openRelativePath?%5B%22statistical-analysis.code-workspace%22%5D "statistical-analysis.code-workspace"): The Visual Studio Code workspace file for this project.
- [`.flake8`](command:_github.copilot.openRelativePath?%5B%22.flake8%22%5D ".flake8"): Configuration file for the flake8 Python linter.
- [`.gitignore`](command:_github.copilot.openRelativePath?%5B%22.gitignore%22%5D ".gitignore"): Specifies files and directories that Git should ignore.

### Setup

1. Clone this repository.
2. Open the project in Visual Studio Code.
3. Reopen the project in the development container (this requires the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension).
4. Install the Python dependencies with Poetry: `poetry install`
5. Open [`exam_scores_analysis_updated.ipynb`](command:_github.copilot.openRelativePath?%5B%22exam_scores_analysis_updated.ipynb%22%5D "exam_scores_analysis_updated.ipynb") and run the cells to perform the analysis.

### Analysis

The analysis involves comparing exam scores across different groups. The groups are defined by the parental level of education. The comparison is done using t-tests and the results are visualized with violin plots.

### Contributing

Contributions are welcome. Please open an issue to discuss your ideas before making changes.

### License

~~This project is licensed under the terms of the MIT license.~~