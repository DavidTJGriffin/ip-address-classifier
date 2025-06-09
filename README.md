# IP Address Classifier

> A command-line tool to classify IPv4 addresses by class, scope (public/private), and validity.

## Description

This Python script analyzes a user-entered IPv4 address and returns its class (A–E), whether it's public, private, loopback, or invalid. It’s designed for students or IT learners who want to reinforce their understanding of networking fundamentals.

## Installation & Setup

```bash
git clone https://github.com/YOUR_USERNAME/ip-address-classifier.git
cd ip-address-classifier
# Ensure Python 3 is installed
python ip_address_classifier.py
```

## Usage

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

- Backend: Python (Standard Library)
- Tools: Terminal / Command-Line

No external libraries or frameworks required.

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

MIT License © 2025 David Griffin  

Permission is hereby granted, free of charge, to any person obtaining a copy  
of this software and associated documentation files (the "Software"), to deal  
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included  
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
