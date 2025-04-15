# Installation Instructions

This guide will help you set up the environment for this project.

## Prerequisites

- Python 3.6 or higher
- pip (Python package installer)

## Setup Instructions

### 1. Create a Virtual Environment

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 2. Install Dependencies

With your virtual environment activated, install the required packages:

```bash
# Install packages listed in requirements.txt
pip install -r requirements.txt
```

### 3. Verify Installation

Verify that all packages were installed correctly:

```bash
pip list
```

### Deactivating the Environment

When you're done, deactivate the virtual environment:

```bash
deactivate
```