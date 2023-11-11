# SMTP Server Scanner

This simple SMTP server scanning tool allows you to test a list of SMTP servers for connectivity. It checks whether a connection can be established using the provided credentials and saves the details of live SMTP servers to a file.
## Screenshot
![Alt Text](https://raw.githubusercontent.com/Aymen-XH/Smtp-Checker/main/Screenshot.png)
## How to Use

1. **Download the Executable:**
   - Download the latest release from the [Releases](https://github.com/Aymen-XH/Smtp-Checker) page.

2. **Run the Executable:**
   - Double-click on the `smtp checker.exe` file to launch the application.

3. **Enter the SMTP List File:**
   - When prompted, enter the path to the text file containing your SMTP server configurations (e.g., `smtp_servers.txt`).

4. **View Results:**
   - The application will display the progress and status of each SMTP server being tested.
   - Live SMTP servers will be saved to `live.txt` in the same directory as the executable.

## Input File Format

- The input file should contain one SMTP server configuration per line in the following format: `server:port:login:password`.

## Notes

- Ensure that you have the necessary permissions to run the executable and access the specified input file.
- Use this tool responsibly and only on servers that you have explicit permission to test.


---
