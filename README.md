
```markdown
# URL Shortener

A simple Python-based project that shortens long URLs into compact, shareable links.

## Features

- Shortens long URLs into manageable and shareable links.
- Built using Python for easy customization and deployment.
- Lightweight and fast.

## Requirements

- Python 3.x
- Pip (Python Package Manager)
- Pipenv (for managing virtual environments and dependencies)

## Installation

### Windows

1. **Download and Install Python**:
   - Download Python from the official website: [Python.org](https://www.python.org/downloads/)
   - Make sure to check the box for adding Python to the system `PATH` during installation.

2. **Install pipenv**:
   ```bash
   pip install pipenv
   ```

3. **Clone the repository**:
   ```bash
   git clone https://github.com/akashbhaskar2011/URL_Shortner.git
   cd URL_Shortner
   ```

4. **Install the required dependencies**:
   ```bash
   pipenv install --dev
   ```

5. **Activate the virtual environment**:
   ```bash
   pipenv shell
   ```

6. **Run the project**:
   ```bash
   python manage.py runserver
   ```

### MacOS

1. **Install Homebrew** (if not already installed):
   Open your terminal and run:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install Python**:
   ```bash
   brew install python
   ```

3. **Install pipenv**:
   ```bash
   pip install pipenv
   ```

4. **Clone the repository**:
   ```bash
   git clone https://github.com/akashbhaskar2011/URL_Shortner.git
   cd URL_Shortner
   ```

5. **Install the required dependencies**:
   ```bash
   pipenv install --dev
   ```

6. **Activate the virtual environment**:
   ```bash
   pipenv shell
   ```

7. **Run the project**:
   ```bash
   python manage.py runserver
   ```

### Ubuntu

1. **Install Python and Git**:
   Open your terminal and run the following commands:
   ```bash
   sudo apt update
   sudo apt install python3 python3-venv python3-pip git
   ```

2. **Install pipenv**:
   ```bash
   pip install pipenv
   ```

3. **Clone the repository**:
   ```bash
   git clone https://github.com/akashbhaskar2011/URL_Shortner.git
   cd URL_Shortner
   ```

4. **Install the required dependencies**:
   ```bash
   pipenv install --dev
   ```

5. **Activate the virtual environment**:
   ```bash
   pipenv shell
   ```

6. **Run the project**:
   ```bash
   python3 manage.py runserver
   ```

## Usage

1. After running the project, open your browser and go to:
   ```
   http://127.0.0.1:8000
   ```

2. Enter a long URL and hit "Shorten" to get your shortened URL.

## Contributing

Feel free to contribute to this project by submitting a pull request. Please ensure that your changes are well-documented and tested.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```

This version now reflects the usage of `pipenv` for managing dependencies across different environments (Windows, MacOS, and Ubuntu). Let me know if you'd like any further modifications!
