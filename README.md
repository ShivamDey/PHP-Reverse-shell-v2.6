# PHP Reverse Shell (v2.6)

This repository contains a PHP script for implementing a reverse shell connection. It is an updated version of the original script by Ivan Šincek. Please note that reverse shells have legitimate use cases in various contexts, such as system administration and security testing. However, they can also be used maliciously. Therefore, use this script responsibly and only on systems you have permission to access.

## Disclaimer

The use of this script is subject to certain legal and ethical considerations. It is essential to understand and comply with the following terms:

- This tool may be used for legal purposes only.
- Users take full responsibility for any actions performed using this tool.
- The author accepts no liability for any damage caused by this tool.

If you do not agree with these terms, do not use this tool.

## Features

- Works on Linux OS, macOS, and Windows OS.
- Provides non-blocking and blocking stream handling for various operating systems.
- Can be used for remote shell access.

## Usage

To use this script, follow these steps:

1. **Configure the Script:** Open the script in a text editor and configure the following variables according to your needs:
   - `$addr`: Set the IP address of the listening server where the reverse shell will connect.
   - `$port`: Specify the port number on which the reverse shell will connect.

2. **Upload the Script:** Upload the script to the target system where you want to establish a reverse shell connection. You can place it on a web server that runs PHP.

3. **Start a Listener:** On your listening server, set up a listener to accept the reverse shell connection. You can use tools like `netcat` or other reverse shell listeners.

4. **Execute the Script:** Access the script via a web browser or a similar method. The script will initiate the reverse shell connection to your listening server.

5. **Interact with the Shell:** Once the reverse shell is established, you can interact with the remote system as if you were using a terminal.

## Security Considerations

- **Legal and Ethical Use:** Ensure that you have proper authorization to use this script on a system. Unauthorized use may have legal consequences.

- **Secure Communication:** The communication between the script and the listening server is not encrypted. If used on a public network, consider using encryption or a VPN to secure the connection.

- **Error Handling:** The script has error handling for stream-related issues. However, it may terminate abruptly if any other issues occur. Use with caution.

---

**Note:** This script is provided for educational purposes and as a reference. Always use it in accordance with applicable laws and permissions. Unauthorized and malicious use is strongly discouraged.
