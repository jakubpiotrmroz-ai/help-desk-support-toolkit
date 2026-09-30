# Basic Network Troubleshooting

## Problem

User reports that the computer has no internet connection.

## Step 1 - Check IP configuration

Open Command Prompt (CMD) and run:

    ipconfig

For detailed information:

    ipconfig /all

## Step 2 - Test connectivity

Test connection to Google's DNS server:

    ping 8.8.8.8

## Step 3 - Test DNS

Run:

    nslookup google.com

## Step 4 - Test domain connectivity

Run:

    ping google.com

If ping to 8.8.8.8 works but ping to google.com does not, the problem may be related to DNS.

## Step 5 - Check the network path

Run:

    tracert google.com

## Basic troubleshooting checklist

- Check network cable / Wi-Fi connection
- Check IP configuration
- Test connectivity with ping
- Test DNS with nslookup
- Check network route with tracert
- Restart the network adapter
- Restart the computer if necessary
- Escalate the ticket if the problem cannot be resolved

## Escalation

If basic troubleshooting does not resolve the issue, document the steps already performed and escalate the ticket to the appropriate IT support team.

## Commands

| Command | Purpose |
|---|---|
| ipconfig | Check IP configuration |
| ipconfig /all | Display detailed network information |
| ping | Test connectivity |
| nslookup | Test DNS resolution |
| tracert | Check the network path |