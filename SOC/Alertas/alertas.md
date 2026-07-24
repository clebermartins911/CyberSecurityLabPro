# Catálogo de Alertas SOC

## CyberSecurityLabPro

---

# 1. Objetivo

Este documento define exemplos de alertas que podem ser monitorados por uma equipe SOC dentro do laboratório.

Os alertas representam eventos que precisam de análise e classificação.

---

# 2. Alerta: Tentativa de Login Suspeito

## Descrição

Detecta múltiplas tentativas de autenticação inválida.

## Indicadores

- Muitas falhas de login.
- Usuário desconhecido.
- Origem incomum.

## Severidade

Média.

## Ações

- Verificar usuário.
- Analisar origem.
- Confirmar atividade legítima.

---

# 3. Alerta: Malware Detectado

## Descrição

Identificação de arquivo ou comportamento suspeito.

## Indicadores

- Processo desconhecido.
- Arquivo suspeito.
- Comunicação externa anormal.

## Severidade

Alta.

## Ações

- Isolar máquina.
- Coletar evidências.
- Realizar análise forense.

---

# 4. Alerta: Acesso Administrativo Suspeito

## Descrição

Uso de privilégios elevados fora do padrão.

## Indicadores

- Conta administrativa utilizada.
- Alteração de configurações.
- Criação de usuários.

## Severidade

Alta.

## Ações

- Validar autorização.
- Registrar evento.
- Investigar alterações.

---

# 5. Alerta: Comunicação de Rede Suspeita

## Descrição

Detecta conexões fora do comportamento esperado.

## Indicadores

- IP desconhecido.
- Domínio suspeito.
- Porta incomum.

## Severidade

Média/Alta.

## Ações

- Analisar tráfego.
- Bloquear comunicação se necessário.
- Registrar evidências.

---

# 6. Processo de Tratamento

Todo alerta deve possuir:

- Data e horário.
- Origem.
- Responsável pela análise.
- Classificação.
- Evidências.
- Resultado da investigação.

---

# 7. Integração SOC

Os alertas devem alimentar:

- Investigação.
- Resposta a incidentes.
- Relatórios.
- Base de conhecimento.

---

# Controle

Projeto:
CyberSecurityLabPro

Documento:
Catálogo de Alertas SOC

Versão:
1.0
