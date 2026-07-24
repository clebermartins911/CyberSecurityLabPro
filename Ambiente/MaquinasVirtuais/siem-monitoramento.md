# SIEM - Monitoramento do Laboratório

## CyberSecurityLabPro

---

# 1. Objetivo

O ambiente SIEM será responsável por coletar, armazenar e analisar eventos de segurança gerados pelas máquinas do laboratório.

O objetivo é simular um ambiente profissional de SOC (Security Operations Center).

---

# 2. Função no Laboratório

O SIEM será utilizado para:

- Coleta de logs.
- Monitoramento de eventos.
- Detecção de ameaças.
- Criação de alertas.
- Investigação de incidentes.
- Análise de comportamento.

---

# 3. Fontes de Logs

Máquinas enviando informações:

## Kali Linux

Eventos:

- Testes autorizados.
- Ferramentas de segurança.
- Atividades de análise.

---

## Windows Teste

Eventos:

- Log de usuários.
- Eventos do sistema.
- Tentativas de login.
- Alterações de configuração.

---

## Linux Server

Eventos:

- Acesso SSH.
- Serviços executados.
- Alterações no sistema.
- Logs de autenticação.

---

# 4. Ferramentas SIEM Possíveis

Ferramentas estudadas:

- Wazuh.
- ELK Stack.
- Splunk.
- Graylog.
- QRadar.

---

# 5. Arquitetura de Funcionamento

Fluxo:

Máquinas Virtuais

↓

Agentes de coleta

↓

Servidor SIEM

↓

Análise de eventos

↓

Alertas de segurança

↓

Resposta a incidentes

---

# 6. Alertas Monitorados

Exemplos:

- Muitas tentativas de login.
- Usuário suspeito.
- Alteração de arquivos importantes.
- Execução de programas incomuns.
- Comunicação de rede suspeita.

---

# 7. Integração com SOC

O SIEM será utilizado pelo analista para:

- Receber alertas.
- Investigar eventos.
- Classificar riscos.
- Criar relatórios.
- Registrar incidentes.

---

# 8. Segurança do Ambiente

Medidas:

- Rede isolada.
- Controle de acesso.
- Backups.
- Snapshots.
- Atualizações.

---

# 9. Status

Estado atual:

Documentação inicial criada.

Próxima etapa:

Instalação e configuração da plataforma SIEM no laboratório.
