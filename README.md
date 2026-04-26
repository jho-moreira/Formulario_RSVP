# Sistema de Automação para Eventos:  RSVP 🎁✅

Este projeto consiste em uma solução Full Stack simplificada para gestão de convidados, integrando uma interface web (Front-end) a um serviço de automação de e-mails via Google Apps Script (Back-end/RPA).

## 🚀 Tecnologias Utilizadas
* **HTML5 & CSS3**: Interface responsiva customizada com a paleta **Azul Serenity** e fontes modernas.
* **JavaScript (Vanilla)**: Lógica de filtragem em tempo real para listas de mais de 200 convidados e manipulação de requisições assíncronas via `Fetch API`.
* **Google Apps Script**: Camada de automação (Backend-as-a-Service) que processa dados e dispara notificações via Gmail.
* **GitHub Pages**: Hospedagem da aplicação.

## 🛠️ Funcionalidades
* **RSVP Inteligente**: Campo de busca otimizado para localização rápida de nomes em listas extensas.
* **Seleção em Colunas**: Layout adaptativo para facilitar a visualização em dispositivos móveis e desktop.
* **Confirmação Multi-seleção**: Permite que o usuário confirme a presença de toda a família de uma só vez.
* **Automação de E-mail**: Notificação instantânea para o organizador a cada nova interação com o formulário.

## ⚙️ Arquitetura do Fluxo
1. O convidado acessa a interface via **GitHub Pages**.
2. O formulário coleta os dados e os envia via método `POST` (URLSearchParams).
3. O **Google Apps Script** recebe a requisição, formata a mensagem e utiliza o serviço `MailApp` para o envio.
4. O usuário recebe um feedback visual de sucesso na tela sem necessidade de recarregar a página.

## 👨‍💻 Autor
Desenvolvido por **Jhordane Moreira **
*Estudante de Pós-graduação em Análise e Desenvolvimento de Sistemas (PUC Minas).*
