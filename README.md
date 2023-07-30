# PEF (Portable Executable Fudifier)

PEF (Portable Executable Fudifier) is a powerful tool developed by the infrlabs team to address the issue of false positives in virustotal, chrome, windows defender, and other security systems when compiling Python files to PE (Portable Executable). This script has been created and maintained by the main developers, spaze99 and Grind420.

## Features

- **Elimination of False Positives:** PEF employs advanced techniques to modify the generated binary, ensuring that the resulting executable remains completely undetectable (FUD) by various security systems.
- **Python to PE Compilation:** Automates the process of converting Python scripts into Windows-compatible executables.
- **Privacy and Security:** PEF is designed to safeguard user privacy and security by preventing the generated binary from being flagged as malware or malicious software.
- **VirusTotal AutoCheck:** PEF is in charge, when fudify, to upload the file automatically to VirusTotal and return you the link together with the detects it has, not everything depends on PEF, your file can't have 67/67 detects either, it is in charge to eliminate the most known ones.

Under development:

- **Our own package:** We are currently working on developing our own package so that it can be used via pip without the need for additional downloads.

## Usage

1. Clone the repository to your local machine.
2. Run `pef.exe`
3. Complete the required inputs
4. Wait 2 to 3 minutes for the binary of your file to be modified and... voilà!

## Support and Contribution

PEF is currently a closed-source project, but the infrlabs team is open to considering open-sourcing it in the future, depending on the level of community support and the necessary security measures.

If you encounter any issues or have suggestions for improvement, please feel free to create an issue or reach out to us through Telegram: [t.me/spaze99](https://t.me/spaze99).

## Disclaimer

The PEF tool is intended for legal and ethical use only. The developers and contributors are not responsible for any misuse or illegal activities conducted with this tool. Please use it responsibly and adhere to the laws and regulations of your jurisdiction.

## Legal Notice

Please note that while PEF aims to make compiled files undetectable by certain security systems, it does not guarantee complete invisibility or immunity to all security measures. The tool is provided as-is, without any warranty. Users are responsible for their actions and should use PEF responsibly and at their own risk.