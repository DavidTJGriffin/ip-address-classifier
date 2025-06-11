# IP Address Classifier

[![PyPI version](https://badge.fury.io/py/ip-address-classifier.svg)](https://pypi.org/project/ip-address-classifier/)

> A command-line tool to classify IPv4 addresses by class, scope (public/private), and validity.

## Description

This Python CLI analyzes a user-entered IPv4 address and returns its class (A–E), whether it's public, private, loopback, or invalid. It’s designed for students or IT learners who want to reinforce their understanding of networking fundamentals.

## Installation

### Recommended (via `pipx`)

```bash
pipx install ip-address-classifier
```

> ⚠️ If `ipclass` isn’t recognized after install, run:

```bash
pipx ensurepath
exec $SHELL  # or restart your terminal
```

### Or Manual (for development)

```bash
git clone https://github.com/YOUR_USERNAME/ip-address-classifier.git
cd ip-address-classifier
python ip_address_classifier.py
```

## Usage

```bash
ipclass
```

Follow the prompt in the terminal:
- Enter an IPv4 address in the format `X.X.X.X` (e.g., `192.168.1.1`)
- The program will tell you:
  - If it’s a valid address
  - Its class (A–E)
  - Whether it is public, private, or a loopback address

Example:
```
Enter address here: 10.0.0.1

10.0.0.1 is a class A private address.
```

## Tech Stack

- Python 3.12+
- Poetry for packaging
- No external dependencies

## Future Improvements

- [ ] Add CIDR block validation  
- [ ] Accept multiple addresses from a file  
- [ ] Refactor with regex and OOP structure  

## Contributing

1. Fork the project  
2. Create a feature branch (`git checkout -b feature/my-feature`)  
3. Commit your changes (`git commit -m 'Add feature'`)  
4. Push to your branch (`git push origin feature/my-feature`)  
5. Open a Pull Request

## Credits

Created by [David Griffin](https://github.com/DavidTJGriffin)

## License

This project is licensed under the MIT License.
