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

## 📊 Progresso Atual

| Tier                     | Máquinas | Status          |
|--------------------------|----------|-----------------|
| **Starting Point Tier 0**| Todas    | ✅ Concluído    |
| **Starting Point Tier 1**| Todas    | ✅ Concluído    |
| **Starting Point Tier 2**| Todas    | ✅ Concluído    |
| **Retired Machines**     | 0        | ⏳ Em breve     |

**Total:** 6+ máquinas documentadas

---

## Máquinas Resolvidas

### Starting Point — Tier 0
| Máquina     | Serviço          | Writeup |
|-------------|------------------|--------|
| Redeemer    | Redis            | [📄 Ver writeup](Starting-point/Tier-0/redeemer.md) |

### Starting Point — Tier 1
| Máquina     | Serviço                  | Writeup |
|-------------|--------------------------|--------|
| Three       | HTTP / AWS S3            | [📄 Ver writeup](Starting-point/Tier-1/three.md) |
| Vaccine     | FTP / PostgreSQL SQLi    | [📄 Ver writeup](Starting-point/Tier-1/vaccine.md) |

### Starting Point — Tier 2
| Máquina     | Serviço                  | Writeup |
|-------------|--------------------------|--------|
| Archetype   | SMB / MSSQL (Windows)    | [📄 Ver writeup](Starting-point/Tier-2/archetype.md) |

*(Vou atualizando conforme for resolvendo mais máquinas)*

---

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
