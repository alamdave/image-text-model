# Image-text-model

A exploratory project to classify text to pictures.

## Prerequisites

- **Git**: Ensure you have Git installed on your system. You can download it from [git-scm.com](https://git-scm.com/).

- **Python3**: This project requires Python 3.1 or later. You can check if Python3 is installed by running `python3 --version` in your terminal. If it's not installed, follow the steps below.

## Installation

### Step 1: Clone the Repository

Clone the project repository using Git:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Step 2: Install Python3

#### macOS

You can use Homebrew to install Python3:

```bash
brew install python3 python3-pip python3-venv
```

#### Ubuntu/Linux

Use the package manager to install Python3:

```bash
sudo apt update
sudo apt install -y python3 python3-pip python3-venv python-is-python3
```

#### Windows

Download and install Python3 from the official [Python website](https://www.python.org/downloads/).

### Step 3: Create a Virtual Environment

Create a virtual environment to isolate project dependencies. Here, we're using `venv`, which comes with Python.

```bash
python3 -m venv nenv
```

### Step 4: Activate the Virtual Environment

#### macOS/Linux

Activate the virtual environment using the following command:

```bash
source venv/bin/activate
```

#### Windows

Activate the virtual environment using the following command:

```bash
.\venv\Scripts\activate
```

Once activated, your terminal prompt should change to indicate that you are now working inside the virtual environment.

### Step 5: Install Dependencies

Install the necessary packages using `pip` and the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### Step 6: Verify Installation

You can verify that everything is set up correctly by running a test script or checking the installed packages:

```bash
pip list
```

### Step 7: Deactivate the Virtual Environment

Once you're done with your work, you can deactivate the virtual environment:

```bash
deactivate
```

## Additional Notes

- Ensure you have the latest version of `pip` by running `pip install --upgrade pip` if necessary.
- You can update the `requirements.txt` by running `pip freeze > requirements.txt` after installing or upgrading packages.

## Troubleshooting

- If you encounter any issues during installation, ensure that your Python3 path is correctly set and that your virtual environment is activated.
- If you receive permission errors during package installation, ensure you are not using `sudo` with `pip install` when inside a virtual environment.

## License

...
