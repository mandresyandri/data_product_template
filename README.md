# Data Product Template

This repository provides a template for data science projects, leveraging Python 3.11 and Poetry for dependency management and packaging. It is designed to streamline the setup and development of data products.

## Features

- **Modular Structure**: Organized into separate components for analytics, machine learning, data pipelines, backend, frontend, and infrastructure.
- **Dependency Management**: Uses Poetry to manage dependencies and virtual environments.
- **Python 3.11 Compatibility**: Ensures compatibility with the latest Python features.
- **Scalability**: Supports API development, web dashboards, and production-ready deployment.

## Project Structure

```plaintext
.
├── LICENSE
├── README.md
├── analytics/         # Exploratory analysis, internal dashboards
├── data_pipeline/     # Data ingestion and transformation
├── machine_learning/  # ML/DL modeling and training
├── backend/           # API, services (FastAPI, Flask, etc.)
├── frontend/          # UI (React, Vue.js, Dash, Streamlit)
├── infrastructure/    # Deployment (Docker, CI/CD, Kubernetes, Terraform…)
```

## Getting Started

### Installation

To set up the development environment, run:

```bash
poetry install --no-root
```

### Adding Dependencies

To add additional dependencies or plugins, use:

```bash
poetry add <package_name>
```

### Setting Up the Interpreter in VS Code

If the Poetry virtual environment is not detected in VS Code, retrieve its path using:

```bash
poetry env info --path
```

Copy and paste the output into the Python interpreter settings in VS Code.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](./LICENSE) file for details.

