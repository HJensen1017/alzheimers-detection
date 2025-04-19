# Alzheimer's Detection

## Running Locally

First reproduce the environment used to generate the code. Then select the created environment for your Jupyter kernel to run the code.

### Using `Conda`

If `conda` is installed on your machine already, you can simply run the following to recreate the environment. This creates a `conda` environment named `alzheimers` which you can select for your Jupyter notebook's kernel:

```python
conda env create -f environment.yml
```

### Using `venv`

If conda is not installed and `venv` is the preferred package manager, the `requirements.txt` file can be used:

**On Mac**

```sh
# Create the environment named venv
python3 -m venv venv

# Activate the environment
source venv/bin/activate

# Install required libraries
pip install -r requirements.txt
```

**On Windows (PowerShell)**

```powershell
# Create the environment named venv
python -m venv venv

# Activate the environment
.\venv\Scripts\Activate.ps1

# Install required libraries
pip install -r requirements.txt
```

After the environment has been recreated, select it to be used in the Jupyter notebook's kernel.
