# HackTheBox Writeups

![HTB](https://img.shields.io/badge/HackTheBox-Starting%20Point-blue?style=for-the-badge&logo=hackthebox)
![Linux](https://img.shields.io/badge/Linux-Expertise-red?style=for-the-badge&logo=linux)
![Windows](https://img.shields.io/badge/Windows-Pentesting-blue?style=for-the-badge&logo=windows)

Repositório com **writeups detalhados** de todas as máquinas resolvidas no **Hack The Box**.

**Foco principal:** Enumeração completa, exploração realista, privilege escalation e documentação técnica de qualidade.

---

## Repositórios Complementares

- **[Web Security Labs](https://github.com/Andrey-Soares8/web-security-labs)** — PortSwigger Academy + Web Vulnerabilities

---

## Máquinas Resolvidas

### Starting Point — Tier 0
| Máquina     | Serviço              | Writeup |
|-------------|----------------------|--------|
| Meow        | HTTP                 | [📄 Ver writeup](Startint-point/Tier-0/1.Meow.md) |
| Fawn        | LDAP                 | [📄 Ver writeup](Startint-point/Tier-0/2.Fawn.md) |
| Dancing     | FTP                  | [📄 Ver writeup](Startint-point/Tier-0/3.Dancing.md) |
| Redeemer    | Redis                | [📄 Ver writeup](Startint-point/Tier-0/4.Redeemer.md) |

### Starting Point — Tier 1
| Máquina      | Serviço                    | Writeup |
|--------------|----------------------------|--------|
| Appointment  | HTTP / SQLi                | [📄 Ver writeup](Startint-point/Tier-1/1.Appointment.md) |
| Sequel       | MSSQL                      | [📄 Ver writeup](Startint-point/Tier-1/2.Sequel.md) |
| Crocodile    | Web / File Upload          | [📄 Ver writeup](Startint-point/Tier-1/3.Crocodile.md) |
| Responder    | LLMNR / NTLM               | [📄 Ver writeup](Startint-point/Tier-1/4.responder.md) |
| Three        | HTTP / AWS S3              | [📄 Ver writeup](Startint-point/Tier-1/5.Three.md) |

### Starting Point — Tier 2
| Máquina     | Serviço                       | Writeup |
|-------------|-------------------------------|--------|
| Vaccine     | PostgreSQL SQLi + sudo vi     | [📄 Ver writeup](Startint-point/Tier-2/1.Vaccine.md) |
| Oopsie      | Web / File Upload             | [📄 Ver writeup](Startint-point/Tier-2/2.Oopsie.md) |
| Archetype   | SMB / MSSQL (Windows)         | [📄 Ver writeup](Startint-point/Tier-2/3.Archetype.md) |
| Unified     | ?                             | [📄 Ver writeup](Startint-point/Tier-2/4.unified.md) |

## Metodologia Padrão

Todas as writeups seguem esta estrutura:

1. **Reconhecimento** (`nmap`, `whatweb`, `gobuster`, `ffuf`)
2. **Enumeração** detalhada
3. **Exploração / Foothold** (ganho de shell)
4. **Privilege Escalation** (user → root)
5. **Post-Exploitation** + Flags
6. **Aprendizados & Dificuldades**

---

## Skills Demonstradas

- SQL Injection avançada (PostgreSQL + `sqlmap`)
- Reverse Shell + estabilização de TTY
- Privilege Escalation via `sudo vi` (GTFOBins)
- Exploração de serviços mal configurados (Redis, SMB, FTP, AWS S3)
- Uso de Impacket (`mssqlclient`, `psexec`)
- Quebra de hashes (John the Ripper)
- Documentação técnica clara e organizada

---

## Ferramentas Utilizadas

`nmap` • `sqlmap` • `ffuf` • `gobuster` • `redis-cli` • `smbclient` • `ftp` • `Impacket` • `John` • `netcat` • Kali Linux

---

## Próximos Objetivos

- Máquinas **Easy** e **Medium** fora do Starting Point
- Aprofundar em Active Directory (BloodHound, Kerberoasting, etc.)
- Windows Privilege Escalation
- Criar writeups mais avançados com screenshots e comandos

---

**Quer contribuir ou dar feedback?**  
Abra uma **[Issue](https://github.com/Andrey-Soares8/HackTheBox/issues)** ou me envie mensagem!

---

**Feito com ☕ e muita persistência.**
