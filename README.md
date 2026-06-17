# HackTheBox — Writeups

Repositório com writeups das máquinas resolvidas no HackTheBox Starting Point. Cada solução documenta o raciocínio completo: reconhecimento, exploração e aprendizados — não apenas os comandos usados.

**Repositório complementar:** [web-security-labs](https://github.com/Andrey-Soares8/web-security-labs) — 24+ writeups de vulnerabilidades web (PortSwigger Academy)

---

## Progresso Atual

| Tier | Máquinas Resolvidas | Status |
|---|---|---|
| **Starting Point Tier 0** | 5 / 8 | 🟡 Em andamento |
| **Starting Point Tier 1** | 0 | ⏳ Próximo |
| **Starting Point Tier 2** | 0 | ⏳ Planejado |

**Total: 5 máquinas resolvidas**

---

## Starting Point — Tier 0

| # | Máquina | Serviço | Writeup |
|---|---|---|---|
| 1 | Meow | Telnet | ✅ Concluído |
| 2 | Fawn | FTP | ✅ Concluído |
| 3 | Dancing | SMB | ✅ Concluído |
| 4 | Redeemer | Redis | [📄 Ver writeup](Starting-point/Tier-0/redeemer.md) |
| 5 | Explosion | RDP | ✅ Concluído |

---

## Metodologia

Toda máquina segue essa estrutura:

1. **Reconhecimento** — nmap, identificação de serviços e versões
2. **Enumeração** — exploração do serviço encontrado
3. **Exploração** — acesso inicial e captura da flag
4. **Aprendizados** — o que a máquina ensinou de novo

---

## Skills Demonstradas

- Reconhecimento com nmap (`-sV`, `-sC`, `-Pn`, `-p`)
- Acesso a serviços sem autenticação (Telnet, FTP anônimo, Redis, SMB)
- Enumeração de bancos Redis (`INFO`, `KEYS *`, `GET`)
- Leitura de compartilhamentos SMB sem credencial
- Documentação técnica com contexto, comandos e análise de impacto

---

## Ferramentas

nmap · redis-cli · ftp · smbclient · rdesktop · Kali Linux
