# Web Vulnerability Scanner

This Python script is designed to detect various common web application vulnerabilities, including:

- **Cross-Site Scripting (XSS)**
- **SQL Injection (SQLi)**
- **Local File Inclusion (LFI)**
- **Remote File Inclusion (RFI)**
- **Command Injection (CMDi)**

It leverages the `mechanize` library to automate web browsing and form submissions, thoroughly scanning websites for potential security flaws. The script traverses the entire site, identifies input fields, and tests them using a set of predefined payloads. If any vulnerability is found, it is logged for further analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## How to Use

### Installation

1. Ensure you have Python 3 installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Install the required dependencies by running:

   ```bash
   pip install mechanize

3. Running the Script
Clone the repository and navigate to the project directory:

   ```bash
   git clone https://github.com/Lawxsz/web-scanner.git
   cd web-scanner

4. Run the script with the following command:

   ```bash

   python iris_scanner.py -u example.com

Comprehensive Scan:

Perform a more thorough scan by enabling comprehensive mode:

```bash
python script_name.py -u example.com -e
Verbose Logging:
```
Enable verbose logging to see more detailed output:

```bash
python script_name.py -u example.com -v
```
Cookies:

Provide cookies if required:

```bash
python script_name.py -u example.com -c name=value name2=value2
```
## Analyzing Results
After running the script, any detected vulnerabilities will be logged in the terminal. Review the output to understand the security issues found and take necessary actions to fix them.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## Contact

Telegram: t.me/lawxsz
t.me/lawxszchannel
