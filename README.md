# example-project

## Setup Instructions

### Step 1: Install Miniforge

Run this command in your terminal:

```bash
wget -O Miniforge3.sh "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"
bash Miniforge3.sh -b -p "${HOME}/conda"
source "${HOME}/conda/etc/profile.d/conda.sh"
```

### Step 2: Create Conda Environment

Create the environment from the `environment.yml` file:

```bash
conda env create -f environment.yml
```

### Step 3: Activate the Environment

```bash
conda activate myenv
```

### Step 4: Verify Installation

```bash
python --version
```

## Quick Start

Once your environment is set up, you can start developing!

```bash
# Activate environment
conda activate myenv

# Deactivate when done
conda deactivate
```
