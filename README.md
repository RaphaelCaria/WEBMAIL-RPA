# 📥 RPA - Download Automático de Anexos de E-mail

Script em **Python** que realiza a automação de leitura de e-mails e download de anexos de forma contínua. Ideal para ambientes que recebem documentos importantes por e-mail (exames, relatórios, pedidos, etc.), otimizando o tempo manual com integração direta à caixa de entrada.

## 🔧 Tecnologias Utilizadas

- Python 3.x  
- `imaplib` (acesso a e-mails via IMAP)  
- `email` (manipulação de mensagens)  
- `os`, `shutil` (manipulação de arquivos e pastas)  
- Outlook / Gmail / Zimbra (qualquer provedor com suporte IMAP)

## 🧠 Funcionalidades

- Conexão com servidores de e-mail via protocolo IMAP
- Leitura de mensagens não lidas ou filtradas por remetente/assunto
- Download de todos os anexos encontrados para uma pasta específica
- Organização dos arquivos por data, tipo ou remetente (opcional)
- Possível integração com outros RPAs para pós-processamento

---
