# Task 4: Setup and Use a Firewall on Windows

## Objective
Configure and test basic Windows Firewall rules to allow or block network traffic.

## Tools Used
- Windows Defender Firewall with Advanced Security
- Command Prompt (netsh)

## Steps Performed
1. Opened Windows Defender Firewall.
2. Accessed Windows Defender Firewall with Advanced Security.
3. Viewed the existing Inbound Rules.
4. Created a new inbound rule to block TCP port 23 (Telnet).
5. Verified the firewall rule using the `netsh advfirewall` command.
6. Deleted the test rule to restore the original firewall configuration.

## Command Used
```cmd
netsh advfirewall firewall show rule name="Block Telnet Port 23"
```

## Outcome
Successfully created, verified, and removed a firewall rule blocking inbound traffic on TCP port 23. This demonstrated how Windows Firewall filters network traffic and improves system security.

## Conclusion
Windows Defender Firewall helps protect systems by controlling incoming and outgoing network traffic. Creating firewall rules allows administrators to block unwanted connections and enhance network security.
