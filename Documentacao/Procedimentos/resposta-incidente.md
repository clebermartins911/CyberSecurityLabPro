# Procedimento de Resposta a Incidentes

## CyberSecurityLabPro

---

# 1. Objetivo

Este procedimento define as etapas para identificação, análise, contenção, tratamento e encerramento de incidentes de segurança dentro do ambiente CyberSecurityLabPro.

O objetivo é estabelecer uma resposta organizada, reduzindo impactos e garantindo a preservação das informações necessárias para investigação.

---

# 2. Identificação do Incidente

Um incidente pode ser identificado através de:

- Alertas do SOC.
- Análise de logs.
- Comportamento anormal do sistema.
- Detecção de vulnerabilidades.
- Relatos de usuários.
- Monitoramento de segurança.

Informações iniciais devem ser registradas:

- Data e horário.
- Máquina afetada.
- Usuário envolvido.
- Descrição do evento.
- Evidências iniciais.

---

# 3. Classificação do Incidente

Os incidentes devem ser classificados conforme o impacto:

## Baixa

Eventos sem impacto significativo.

Exemplos:

- Tentativas bloqueadas.
- Alertas falsos.
- Configurações incorretas.

## Média

Eventos que necessitam investigação.

Exemplos:

- Acesso suspeito.
- Alteração não autorizada.
- Malware detectado.

## Alta

Eventos com potencial impacto ao ambiente.

Exemplos:

- Comprometimento de máquina.
- Vazamento de informações.
- Persistência de invasor.

---

# 4. Contenção

Objetivo: limitar o impacto do incidente.

Ações:

- Isolar máquina afetada.
- Bloquear conexões suspeitas.
- Preservar evidências.
- Impedir propagação.

---

# 5. Coleta de Evidências

Devem ser coletados:

- Logs do sistema.
- Logs de rede.
- Arquivos suspeitos.
- Capturas de tela.
- Informações de processos.
- Dados de memória quando aplicável.

Toda evidência deve possuir:

- Identificação.
- Data e horário.
- Origem.
- Responsável pela coleta.

---

# 6. Análise

Durante a investigação devem ser avaliados:

- Como ocorreu o incidente.
- Quais sistemas foram afetados.
- Qual foi o método utilizado.
- Quais alterações foram realizadas.
- Possíveis indicadores de comprometimento.

---

# 7. Erradicação

Após identificar a causa:

- Remover ameaças.
- Corrigir vulnerabilidades.
- Atualizar sistemas.
- Alterar credenciais comprometidas.
- Aplicar melhorias de segurança.

---

# 8. Recuperação

Processo de retorno ao funcionamento normal:

- Restaurar serviços.
- Monitorar o ambiente.
- Confirmar ausência de ameaças.
- Validar segurança do sistema.

---

# 9. Encerramento

Todo incidente deve gerar:

- Relatório final.
- Evidências organizadas.
- Linha do tempo dos eventos.
- Medidas corretivas.
- Lições aprendidas.

---

# 10. Integração com SOC e Forense

O processo deve integrar:

SOC:

- Detecção.
- Alertas.
- Classificação.

Blue Team:

- Contenção.
- Correção.
- Defesa.

Forense:

- Coleta.
- Análise.
- Laudo técnico.

---

# Controle de Versão

Projeto: CyberSecurityLabPro

Documento:
Procedimento de Resposta a Incidentes

Versão:
1.0
