Aguinel Junior Bento da Silva - RM:564857
Eduardo Martins - RM:562259




#  Chatbot Integrado ao Telegram com IBM Watson Assistant

##  Objetivo

Desenvolver um **assistente virtual interativo no Telegram**, utilizando o **IBM Watson Assistant** para interações com o usuário. As respostas são baseadas em **opções clicáveis (Option Response)** e o fluxo é intermediado pelo **Node-RED**, que atua como ponte entre o Telegram e o Watson Assistant.

---

##  Descrição do Projeto

Este projeto foi desenvolvido como parte de um desafio acadêmico para a construção de uma **central de atendimento digital** baseada em chatbot. O objetivo é simular um atendimento automatizado que responda de forma fluida e contextual, oferecendo **opções de múltipla escolha** aos usuários por meio do Telegram.

---

##  Tecnologias Utilizadas

- [Telegram Bot API](https://core.telegram.org/bots/api)
- [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/)
- [Node-RED](https://nodered.org/) para orquestração do fluxo conversacional
- JSON para estruturação de mensagens e opções

---

##  Funcionamento

1. O usuário envia uma mensagem via Telegram.
2. O Node-RED recebe essa mensagem e a redireciona ao IBM Watson Assistant.
3. O Watson Assistant retorna uma **resposta do tipo "option"**, com botões clicáveis.
4. O Node-RED interpreta a resposta e envia as opções de volta ao usuário no Telegram.
5. Cada escolha do usuário redireciona a conversa de forma **contextual e lógica**, simulando um atendimento real.

---

##  Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/aguinelito/chatbot1.git


Exemplo de Fluxo
Usuário: "Olá"
→ Bot: "Bem-vindo! O que deseja?"
[ Agendar atendimento ] [ Falar com humano ] [ Sair ]
Cada opção leva a um fluxo diferente, com base na resposta contextual programada no Watson Assistant.

Autoria
Este projeto foi desenvolvido por Aguinel e Eduardo como parte da disciplina ChatBot no curso de ADS].
