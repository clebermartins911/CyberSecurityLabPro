# Arquitetura do CyberSecurityLabPro

## 1. Objetivo do Laboratório

O CyberSecurityLabPro é um ambiente de estudos prático em cibersegurança destinado ao treinamento de Red Team, Blue Team, SOC e Forense Digital.

O laboratório tem como objetivo simular ambientes reais de segurança da informação, permitindo estudar prevenção, detecção, resposta a incidentes e investigação.

---

# 2. Estrutura Geral

O laboratório será dividido nos seguintes módulos:

## Red Team

Responsável pelos testes autorizados de segurança.

Atividades:

- Reconhecimento.
- Análise de vulnerabilidades.
- Testes controlados.
- Documentação dos resultados.

---

## Blue Team

Responsável pela defesa do ambiente.

Atividades:

- Monitoramento.
- Hardening.
- Resposta a incidentes.
- Correção de vulnerabilidades.

---

## SOC

Centro de Operações de Segurança.

Responsável por:

- Receber alertas.
- Analisar eventos.
- Classificar incidentes.
- Gerar relatórios.

---

## Forense Digital

Responsável pela investigação.

Atividades:

- Coleta de evidências.
- Análise de artefatos.
- Criação de laudos.
- Linha do tempo dos eventos.

---

# 3. Ambiente Virtual

O laboratório será composto por máquinas virtuais:

| Máquina            | Função                 |
| ------------------ | ---------------------- |
| Kali Linux         | Red Team               |
| Windows            | Estação de usuário     |
| Ubuntu Server      | Servidor de testes     |
| Windows Server     | Active Directory       |
| Wazuh              | Monitoramento/SIEM     |
| Máquina vulnerável | Treinamento autorizado |

---

# 4. Rede do Laboratório

A rede será isolada para garantir segurança:

Internet
|
Firewall Virtual
|
Rede Interna do Laboratório
|
Máquinas Virtuais

---

# 5. Controle e Documentação

Todos os testes serão:

- Autorizados.
- Documentados.
- Registrados no Git.
- Acompanhados de evidências.

---

# 6. Evolução

O laboratório será expandido gradualmente com:

- SIEM.
- Threat Intelligence.
- Active Directory.
- Pentest Web.
- Análise Forense.
- Automação com scripts.
