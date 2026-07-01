# MakeMensagemFWT

## 🤖 Como Funciona a Automação

O script executa um fluxo automatizado dividido em três etapas principais:

### 1. Busca do Arquivo
* O sistema vasculha o Google Drive para localizar a planilha correspondente à **data atual**.
* A busca e o gatilho de execução ocorrem nos horários programados de disparo: **09:00** e **14:00**.

### 2. Disparo de Mensagens
* Assim que a planilha do dia é identificada, a automação realiza o envio das mensagens personalizadas para os turistas listados.

### 3. Relatório e Log de Status
* Ao final do processo, o sistema faz uma verificação dos destinatários.
* É gerada uma marcação detalhada identificando:
  * **Envios realizados com sucesso.**
  * **Envios que falharam**, registrando uma atualização automática com o motivo exato pelo qual não foi possível enviar a mensagem (ex: número inválido, erro de conexão, etc.).
