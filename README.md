# SRE Auxiliar Scripts

## Overview

This repository contains a collection of auxiliary scripts designed to assist with common tasks related to Site Reliability Engineering (SRE). These scripts aim to automate repetitive processes, enhance monitoring, and simplify system management tasks, making them an essential toolkit for SRE practitioners.

---

## Features

- **Automation:** Scripts to automate common SRE tasks like log analysis, resource monitoring, and deployment management.
- **Monitoring:** Tools to monitor system health, resource usage, and application performance.
- **Flexibility:** Modular scripts that can be customized for various environments and workflows.
- **Scalability:** Designed to support growing infrastructure needs.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Scripts](#scripts)
- [Examples](#examples)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

---

## Installation

### Prerequisites

- Python 3.8 or higher
- Required libraries (listed in `requirements.txt`)
- Basic understanding of shell commands and scripting

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/MBeatrizMS/sre-auxiliar-scripts.git
   cd sre-auxiliar-scripts
   ```

2. **Set Up a Virtual Environment (Optional but Recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Scripts

### Available Scripts

| Script Name       | Description                                |
|-------------------|--------------------------------------------|
| `log_analyzer.py` | Analyzes log files for patterns or errors. |
| `resource_monitor.py` | Monitors system resources like CPU, memory, and disk usage. |
| `deployment_helper.sh` | Automates deployment tasks and configuration management. |

---

## Examples

### Example 1: Analyzing Logs
Run the `log_analyzer.py` script to search for specific error patterns in log files:
```bash
python log_analyzer.py --log-file /var/log/app.log --pattern "ERROR"
```

### Example 2: Monitoring Resources
Use the `resource_monitor.py` script to monitor system resource usage in real-time:
```bash
python resource_monitor.py --interval 5
```

### Example 3: Automated Deployment
Execute the `deployment_helper.sh` script for deployment tasks:
```bash
bash deployment_helper.sh --deploy --env production
```

---

## Testing

### Run Unit Tests
Ensure the scripts are functioning as expected by running the unit tests:
```bash
python -m unittest discover tests/
```

### Test Coverage
Generate a test coverage report:
```bash
pytest --cov=src
```

---

## Contributing

We welcome contributions to enhance this repository! Follow these steps:

1. **Fork the Repository:** Click the "Fork" button at the top-right corner of the repository page.
2. **Clone Your Fork:**
   ```bash
   git clone https://github.com/<your-username>/sre-auxiliar-scripts.git
   cd sre-auxiliar-scripts
   ```
3. **Create a Feature Branch:**
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Commit Your Changes:**
   ```bash
   git add .
   git commit -m "Add feature description"
   ```
5. **Push Your Branch:**
   ```bash
   git push origin feature/your-feature-name
   ```
6. **Submit a Pull Request:** Go to your forked repository and click "Compare & pull request."

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this repository.

---

## Contact

For any questions or suggestions, feel free to open an issue in the repository or contact the repository owner.

---