# Login Form Bypass

Login Form Bypass is a Python-based tool designed to bypass login forms using a list of known default credentials. This tool can be useful during penetration testing and security assessments to identify vulnerable login forms that can be exploited using default or weak credentials.

## Features

- Bypass login forms using a list of known default credentials
- Support for multi-threading to speed up the process
- Customizable settings for target URL, number of threads, and timeout
- Easy to use with a simple command line interface

## Requirements

- Python 3.x
- `requests`

## Installation

1. Clone this repository:
```
git clone https://github.com/bdunlap9/LoginFormBypass.git
```

2. Install the required packages using `pip`:
```
pip install -r requirements.txt
```

## Usage

To use the LoginFormBypass tool, run the script with the required arguments:

```
python login_form_bypass.py -u http://example.com/login -t 10 -o output.txt
```

- `-u` or `--url`: Target login form URL
- `-t` or `--threads`: Number of threads (default: 5)
- `-o` or `--output`: Output file to store successful login attempts

For more detailed usage instructions, run the script with the `-h` or `--help` flag:

```
python login_form_bypass.py --help
```

## Disclaimer

This tool is intended for educational purposes and legal penetration testing only. The creator of this tool does not take any responsibility for any illegal activities performed using this tool. Use it responsibly and with permission from the target system owners.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
