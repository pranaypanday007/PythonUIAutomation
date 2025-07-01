Python UI Automation

A Python-based UI automation framework for efficient and maintainable browser testing. This project leverages Selenium WebDriver, PyTest, and the Page Object Model (POM) design pattern to deliver robust automated test coverage.

## 🚀 Features

- **Selenium WebDriver** for browser automation (Chrome, Edge, etc.)
- **PyTest** for test execution and reporting
- **Page Object Model (POM)** for scalable test design
- **Data-driven testing** using Excel and CSV files
- **Reusable utilities** for streamlined automation
- **Sample scripts** to demonstrate various automation techniques

## 📁 Project Structure

PythonUIAutomation/
│
├── data/ # Test data files (Excel, CSV, etc.)
├── pageObjects/ # Page Object classes
├── pythonBasics/ # Basic Python code samples
├── pythonSel/ # Selenium demo scripts
├── pythonSelenium/ # Combined automation scripts
├── reports/ # Test execution reports
├── utils/ # Utility scripts
├── calendars.py # Calendar widget automation
├── demoBrowser.py # Browser interaction examples
├── ed.py # Edge browser scripts
├── excelDemo.py # Excel handling demo
├── main.py # Main entry point for automation
├── pytest.ini # PyTest configuration
└── upload.py # File upload automation

markdown

## 🛠️ Getting Started

1. **Clone the repository**
    ```bash
    git clone https://github.com/pranaypanday007/PythonUIAutomation.git
    cd PythonUIAutomation
    ```

2. **Set up a virtual environment (recommended)**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4. **Run tests**
    ```bash
    pytest
    ```

## 📝 Usage

- Update test data files in the `data/` directory as required.
- Add or modify Page Object classes in `pageObjects/`.
- Use `main.py` or PyTest to execute test suites.

## 📊 Reports

Test execution reports are generated in the `reports/` directory. Open the relevant report file in your browser for details.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have suggestions or improvements.

## 📄 License

This project is licensed under the MIT License.

---

*Developed and maintained by Pranay Panday.*
