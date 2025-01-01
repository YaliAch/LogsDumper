## Logs Dumper
A lightweight PowerShell script that extracts relevant logs for forensic investigation. 

This tool is designed to simplify the collection of key data, ensuring a comprehensive view of system activity.


## Script Features

1. **Event Log Collection**: 
   - Collects logs from critical sources such as Security, Application, System, and others.
   - Ensures operational event logs (e.g., PowerShell, Sysmon) are captured.

2. **Prefetch Files Copy**:
   - Copies all prefetch files for additional insights.

3. **Error Logging**:
   - Errors encountered during execution are logged to an `errors.log` file.

4. **Result Compression**:
   - Consolidates collected data into a ZIP archive for transport.



## How to Use
1. From the target machine, copy the script as plain text.
2. Open PowerShell with administrative privileges.
3. Paste the script into the PowerShell console and execute.

**Note**: Pasting the script directly into the PowerShell console is recommended for better results, as some EDRs may block `.ps1` scripting files.



## License

[MIT License](LICENSE)
