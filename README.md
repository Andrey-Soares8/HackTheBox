# HackTheBox Writeups

Repositório dedicado com todas as máquinas resolvidas do **HackTheBox**, writeups detalhados, metodologia e aprendizados.

**Foco:** Pentest prático, enumeração, exploitation e privilege escalation.

**Repositório complementar:** [web-security-labs](https://github.com/Andrey-Soares8/web-security-labs) — PortSwigger Academy + Web Vulnerabilities

---

## Progresso Atual

| Tier | Máquinas Resolvidas | Status |
|---|---|---|
| **Starting Point Tier 0** | 1+ | ✅ Concluído |
| **Starting Point Tier 1** | 2 | ✅ Concluído |
| **Starting Point Tier 2** | 1 | ✅ Concluído |
| **Machines (Retired)** | 0 | ⏳ Próximo |

**Total resolvido: 4 máquinas documentadas**

---

## Máquinas Resolvidas

### Starting Point — Tier 0

| Máquina | Serviço | Writeup |
|---|---|---|
| Redeemer | Redis | [📄 Ver writeup](Starting-point/Tier-0/redeemer.md) |

### Starting Point — Tier 1

| Máquina | Serviço | Writeup |
|---|---|---|
| Three | HTTP / AWS S3 | [📄 Ver writeup](Starting-point/Tier-1/three.md) |
| Vaccine | FTP / PostgreSQL | [📄 Ver writeup](Starting-point/Tier-1/vaccine.md) |

### Starting Point — Tier 2

| Máquina | Serviço | Writeup |
|---|---|---|
| Archetype | SMB / MSSQL (Windows) | [📄 Ver writeup](Starting-point/Tier-2/archetype.md) |

---

## Metodologia Padrão

Toda máquina segue esta estrutura:

1. **Reconhecimento** (Nmap, WhatWeb, Gobuster, FFUF)
2. **Enumeração** (Portas abertas, serviços, diretórios, usuários)
3. **Exploração / Foothold** (Ganho de acesso inicial)
4. **Privilege Escalation** (User → Root/System)
5. **Post-Exploitation** (Flags, evidências)
6. **Aprendizados**

---

## Skills Demonstradas

- Enumeração completa de redes e serviços (nmap, smbclient, ftp)
- Exploração de bancos NoSQL/cache mal configurados (Redis)
- Exploração de cloud storage mal configurado (AWS S3 buckets)
- SQL Injection com sqlmap (PostgreSQL) e obtenção de os-shell
- Reverse shell + estabilização de TTY
- Privilege escalation Linux via sudo misconfiguration (GTFOBins)
- Exploração de ambiente Windows/AD: SMB → MSSQL → xp_cmdshell → psexec
- Uso de Impacket (mssqlclient, psexec) para pentest em Active Directory
- Quebra de hashes (John the Ripper — ZIP, MD5)
- Documentação técnica completa com cadeia de exploração e mitigação

---

## Ferramentas

nmap · redis-cli · smbclient · ftp · sqlmap · John the Ripper · Impacket (mssqlclient, psexec) · netcat · Kali Linux

---

## Próximos Passos

- Concluir Starting Point Tier 0 (demais máquinas)
- Avançar para Machines normais (Easy/Medium) fora do Starting Point
- Explorar Active Directory mais a fundo (BloodHound, Kerberoasting)
- Documentar técnicas de Windows Privilege Escalation (WinPEAS)

---

Quer feedback? Pode abrir uma **Issue**!
