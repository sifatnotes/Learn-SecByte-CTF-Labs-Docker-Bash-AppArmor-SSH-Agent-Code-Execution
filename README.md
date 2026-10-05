# Learn-SecByte-CTF-Labs-Docker-Bash-AppArmor-SSH-Agent-Code-Execution
Hands-on cybersecurity and CTF labs covering Docker security, Bash race conditions, AppArmor jails, SSH agent hijacking, quoted-expression injection, Python pickle, PowerShell jails, R code execution, Python input, and LaTeX command execution.
```markdown
# Learn SecByte CTF Labs: Docker, Bash, AppArmor, SSH Agent & Code Execution

A practical collection of **cybersecurity labs**, **CTF labs**, and hands-on security exercises covering container security, Linux controls, race conditions, SSH agent security, command injection, serialization, restricted shells, and language-specific code execution.

These labs are useful for cybersecurity students, CTF players, penetration testers, security engineers, and learners studying Linux, container, application, and sandbox security.

## Lab Collection

### Docker & Container Security

- [Docker Talk Through Me](https://learn.secbyte.org/ctf/docker-talk-through-me)
- [Docker Sys Admins Docker](https://learn.secbyte.org/ctf/docker-sys-admins-docker)

### Linux, Bash & AppArmor Security

- [Bash Race Condition](https://learn.secbyte.org/ctf/bash-race-condition)
- [AppArmor Jail Medium](https://learn.secbyte.org/ctf/apparmor-jail-medium)
- [Bash Quoted Expression Injection](https://learn.secbyte.org/ctf/bash-quoted-expression-injection)

### SSH & Authentication Security

- [SSH Agent Hijacking](https://learn.secbyte.org/ctf/ssh-agent-hijacking)

### Python & Serialization

- [Python Pickle](https://learn.secbyte.org/ctf/python-pickle)
- [Python Input](https://learn.secbyte.org/ctf/python-input)

### Restricted Environments & Code Execution

- [PowerShell Basic Jail](https://learn.secbyte.org/ctf/powershell-basic-jail)
- [R Code Execution](https://learn.secbyte.org/ctf/r-code-execution)
- [LaTeX Command Execution](https://learn.secbyte.org/ctf/latex-command-execution)

## Categories

### 1. Docker & Container Security

The Docker labs focus on security issues around containerized environments and Docker administration. They are useful for understanding container boundaries, privileged operations, and the importance of secure Docker configuration.

### 2. Bash & Linux Security

**Bash Race Condition** and **Bash Quoted Expression Injection** explore security problems involving shell behavior, race conditions, and unsafe expression or input handling.

### 3. AppArmor & Sandboxing

**AppArmor Jail Medium** focuses on Linux application confinement and security boundaries. AppArmor is an important access-control mechanism for restricting what applications can access.

### 4. SSH Agent Security

**SSH Agent Hijacking** introduces a security scenario involving SSH agent access. It highlights why agent forwarding, socket permissions, and credential-handling practices matter.

### 5. Serialization & Input Security

**Python Pickle** and **Python Input** cover Python-specific input and serialization concepts that can become security-sensitive when untrusted data is processed.

### 6. Language-Specific Code Execution

**PowerShell Basic Jail**, **R Code Execution**, and **LaTeX Command Execution** provide examples of security concerns arising when applications process or execute language-specific input.

## Learning Path

A practical sequence for these **hands-on cybersecurity labs** is:

1. Begin with **Python Input** to understand application input handling.
2. Study **Bash Quoted Expression Injection** and **Bash Race Condition**.
3. Continue with **Python Pickle** to explore serialization security.
4. Study **AppArmor Jail Medium** to understand application confinement.
5. Explore **PowerShell Basic Jail** and **R Code Execution** for language-specific execution environments.
6. Practice **LaTeX Command Execution** to examine risks associated with interpreted input.
7. Finish with **SSH Agent Hijacking** and the Docker labs to broaden Linux and infrastructure-security knowledge.

## How to Use the Labs

- Use these labs only in authorized CTF and training environments.
- Review each lab's objectives and scope before testing.
- Focus on understanding the underlying security weakness rather than memorizing exploitation steps.
- Document inputs, application behavior, security boundaries, and observed results.
- For Docker labs, consider container isolation and least-privilege configuration.
- For Bash and injection labs, examine how untrusted input reaches an interpreter.
- For AppArmor, study how policy-based confinement limits application capabilities.
- For SSH agent exercises, consider secure agent usage and credential exposure.
- For serialization and code-execution labs, understand why processing untrusted data can become dangerous.

## Skills Covered

- Docker and container security
- Linux security
- Bash security
- Race-condition analysis
- AppArmor confinement
- SSH agent security
- Authentication security
- Command injection concepts
- Python input handling
- Python pickle security
- PowerShell sandbox concepts
- R code execution
- LaTeX command execution
- Application sandboxing
- Code-execution security
- Vulnerability assessment

## Difficulty

Difficulty information is only included where indicated by the supplied URLs. **AppArmor Jail Medium** explicitly suggests a medium difficulty level; other difficulty levels are not specified in the provided URLs. Check each individual lab page for current difficulty and requirements.

## Disclaimer

These resources are intended for authorized cybersecurity education, CTF practice, penetration testing training, and defensive security research. Do not apply techniques learned here against systems, applications, accounts, or networks without explicit authorization. This repository does not provide unauthorized access, leaked credentials, or real-world exploitation targets.
```
