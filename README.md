📞 Automação de Atendimento via WhatsApp com Zoho CRM e Group Atendimento

Descrição:
Este projeto implementa a automação de envio de mensagens via WhatsApp integrado ao Zoho CRM e à API do Group Atendimento. 
O objetivo é facilitar o envio de mensagens personalizadas para contatos, além de criar novos atendimentos automaticamente na plataforma Group Atendimento.

Funcionalidades:
Validação de dados de contato: Verifica se os dados necessários (nome, telefone, produto de interesse, etc.) estão preenchidos no Zoho CRM.
Customização de mensagens: Substitui variáveis como nome do contato, produto de interesse e SDR responsável no template de mensagem.
Criação automática de atendimentos: Integração com a API do Group Atendimento para iniciar novos chats com base no número de telefone e enviar mensagens personalizadas.
Gestão de logs: Registra o status do envio das mensagens e eventuais erros para facilitar o monitoramento.

Estrutura do Projeto:
Deluge Script: Código que realiza toda a automação dentro do Zoho CRM, integrando com a API do Group Atendimento.
API do Group Atendimento: Conexão e autenticação com a plataforma para criação de novos chats e envio de mensagens.

Pré-requisitos:
Antes de utilizar este projeto, você precisará:

Zoho CRM: Configurado com campos personalizados para armazenar dados de clientes e leads.
API Group Atendimento: Acesso à API para manipulação de usuários e envio de mensagens via WhatsApp.
Tokens de Autenticação: Acesso aos tokens de API fornecidos pelo Group Atendimento.
Templates de WhatsApp: Criar templates de mensagens no Zoho CRM para serem enviados automaticamente.
