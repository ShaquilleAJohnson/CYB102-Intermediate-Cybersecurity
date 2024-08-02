
### README.md

```markdown
# Blue Team Defense Lab: Identifying a Rogue User

## Summary of Lab Exercises

In this lab, you will play the role of a Blue Team member tasked with identifying the source of nefarious activity within a company. Specifically, you will analyze network packets, DHCP logs, and security logs to pinpoint the rogue user who sent sensitive information within the organization. By following the steps outlined in each exercise, you will be able to trace the suspicious activity to a specific user and host device, ultimately identifying the perpetrator.

### 👥 Exercise 1: Find the IP Address

**Objective**: Identify the source IP address from which the suspicious email activity originated.

**Steps and Completion**:
1. **Open SMTP.pcap in Wireshark**: Load the packet capture file into Wireshark.
2. **Apply Display Filter for SMTP Protocol**: Filter packets by the SMTP protocol.
3. **Refine Display Filter for SMTP FROM**: Further filter packets to show only those with the sender's email address.
4. **Identify the Source IP Address**: Note the source IP address from the remaining packet, identified as `10.10.1.4`.

### 👥 Exercise 2: Correlate IP Address with Host Device

**Objective**: Correlate the identified IP address with the host device using DHCP logs.

**Steps and Completion**:
1. **Open the DHCP.txt File**: Open the DHCP log file in a text editor.
2. **Find the IP Address**: Search the log for the IP address `10.10.1.4` and locate the matching entry:
   ```
   10,04/19/23,12:11:27,Assign,10.10.1.4,USER2,3B:3F:E2:95:2F:89
   ```
   - This entry shows that the IP address `10.10.1.4` was assigned to the host device `USER2` at 12:11:27 PM.

### 👥 Exercise 3: Identify Logged-in User

**Objective**: Identify the user logged into the host device at the time of the suspicious activity using account security logs.

**Steps and Completion**:
1. **Open the Security_log.rtf File**: Open the security log file in a word processor.
2. **Search for Log Entries Around the Time of the Incident**: Search for entries around April 19th, 2023, at 12:50 PM.
3. **Identify the User Logged into USER2**: Find logon and logoff events for `USER2`:
   ```
   Date: 2023-4-19 12:11:13
   Event ID: 4624
   Task Category: Logon
   User: John Doe
   Computer: USER2
   ...
   Date: 2023-4-19 12:56:14
   Event ID: 4634
   Task Category: Logoff
   User: John Doe
   Computer: USER2
   ```
   - These entries indicate that John Doe was logged into `USER2` from 12:11:13 PM to 12:56:14 PM.

## Summary of Findings

- **Exercise 1**: The suspicious SMTP activity was traced to the source IP address `10.10.1.4`.
- **Exercise 2**: This IP address was correlated to the host device `USER2` using the DHCP log.
- **Exercise 3**: The security log revealed that John Doe was logged into `USER2` during the time of the suspicious activity.

These steps confirmed that the rogue activity originated from `USER2`, with John Doe being the logged-in user during the incident.
```
