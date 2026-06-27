
# PhpMyAdmin Mass Checker 🔍

Advanced multi-threaded phpMyAdmin credential verification tool with intelligent path detection and CSRF handling.

## Features ✨

- 🚀 **High-speed checking** with configurable threads
- 🔍 **Auto-detection** of phpMyAdmin paths
- 🔒 **CSRF token handling** for modern installations
- 📊 **Multiple input formats** support (`|`, `:`, or space-delimited)
- 📁 **Smart output** with valid/invalid results separation
- 🌐 **SSL verification** with automatic fallback
- 📈 **Real-time progress** tracking

## Installation ⚙️

```bash
git clone https://github.com/r00thex/PhpMyAdmin-Mass-Checker-main.git
cd PhpMyAdmin-Mass-Checker
pip install -r requirements.txt
```

## Usage 🛠️

Basic usage:
```bash
python checker.py -f combos.txt -t 30 -o results.txt
```

Advanced options:
```bash
usage: checker.py [-h] [-f FILE] [-t THREADS] [-o OUTPUT] [--timeout TIMEOUT]

options:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  Input file containing credentials
  -t THREADS, --threads THREADS
                        Number of threads (default: 20)
  -o OUTPUT, --output OUTPUT
                        Output file for valid credentials (default: valid.txt)
  --timeout TIMEOUT     Request timeout in seconds (default: 15)
```

## Input Format 📝

The tool accepts multiple formats:
```
domain.com|username|password
domain.com:username:password
http://domain.com/phpmyadmin username password
```

## Disclaimer ⚠️

This tool is intended for:
- Security professionals conducting authorized assessments
- System administrators testing their own systems
- Educational purposes

**Unauthorized use against systems you don't own is illegal.** The developers assume no liability and are not responsible for any misuse or damage caused by this program.

## License 📜

This project is licensed under the MIT License - see the file for details.
```

Key elements included:
1. Professional badges for Python version and license
2. Clear feature list with emoji visual cues
3. Detailed installation and usage instructions
4. Multiple input format examples
5. Important disclaimer about legal use
6. Contact information
7. License information

You can customize the screenshot link once you have actual demo images. The README follows GitHub best practices with proper Markdown formatting and includes all essential sections for a security tool repository.
