## Windows Admin Shares

MITRE ATT&CK Technique: [T1077](https://attack.mitre.org/wiki/Technique/T1077)

Input:

    cmd.exe /c "net use \\<computer_name>\ipc$ P@ssw0rd1 /u:<domain>\Administrator"

Input:

    cmd.exe /c "net use \\<computer_name>\admin$ P@ssw0rd1 /u:<domain>\Administrator"

Input:

    cmd.exe /c "net use \\<computer_name>\c$ P@ssw0rd1 /u:<domain>\Administrator"
