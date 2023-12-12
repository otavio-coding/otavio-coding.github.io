# Projeto de Automação WhatsApp Web com Selenium

## Visão Geral
Este é um projeto projetado para automatizar o processo de envio de mensagens pelo WhatsApp usando a interface web do WhatsApp. Essa ferramenta simplifica a tarefa de enviar mensagens em massa, aproveitando tecnologias de automação web e fornecendo uma interface gráfica fácil de usar.

<iframe width="613,5" height="336" src="https://www.youtube.com/embed/QSXwGWvc7hk" title="" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br/><br/>

## Principais Recursos
* **Envio de Mensagens sem Esforço**: Permite que os usuários enviem mensagens para vários contatos sem intervenção manual, simplificando o processo de comunicação.

* **Autenticação por Código QR**: A ferramenta lida com a autenticação por código QR, garantindo uma conexão perfeita entre o dispositivo do usuário e a interface web do WhatsApp.

* **Tratamento de Erros**: Mecanismos robustos de tratamento de erros fornecem aos usuários notificações claras em caso de problemas durante o processo de envio de mensagens.

* **Interface Gráfica Amigável ao Usuário**: A interface gráfica do usuário, construída usando Tkinter, oferece uma experiência simples, guiando os usuários pelos passos necessários.

## Design do Sistema
Para informações detalhadas sobre o design do sistema, consulte a [Documentação de Design do Sistema](https://drive.google.com/file/d/1lTF7eJ6Bhiz5L5TS6W0eebdYFm27YX3b/view?usp=sharing "https://drive.google.com/file/d/1lTF7eJ6Bhiz5L5TS6W0eebdYFm27YX3b/view?usp=sharing") 

## Como Funciona
1. **Configuração**: Os usuários podem personalizar as configurações por meio de um arquivo de configuração, definindo parâmetros como o arquivo CSV com detalhes de contato e a localização da mensagem a ser enviada.
2. **Autenticação por Código QR**: O programa abre a página web do WhatsApp, aguarda o usuário escanear o código QR e lida com o processo de autenticação. Ele armazena o perfil web do WhatsApp localmente, reduzindo a necessidade de escaneamentos repetidos em sessões futuras.
3. **Envio de Mensagens**: A ferramenta utiliza o Selenium WebDriver para enviar mensagens para números de telefone especificados, lidando com vários cenários, como números inválidos e disponibilidade de botões.
4. **Interface do Usuário**: A interface gráfica do usuário fornece uma experiência contínua, com frames guiando os usuários pelo processo e exibindo progresso e resultados.

## Capturas de Tela do Projeto
Frame 1: Iniciar o envio de mensagens
 
<img src="images/Frame1.jpg?raw=true"/>
 
Frame 2: Escanear novo código QR ou continuar

<img src="images/Frame2.jpg?raw=true"/>

Frame 3: Progresso e resultados

<img src="images/Frame3.jpg?raw=true"/>

## Futuras Melhorias
Este é um projeto em evolução e futuras melhorias podem incluir:
* A aplicação precisa de um nome.
* Aprimoramento de registro e relatório de erros.
* Suporte para outras plataformas de mensagens.
* Melhoria na interface do usuário e opções de personalização.
* Integração com serviços em nuvem para melhor escalabilidade.

## Comece Agora
Para começar com o script, faça o download do projeto no [GitHub](http://www.github.com/otavio-coding/whatsappweb-automation/ "http://www.github.com/otavio-coding/whatsappweb-automation/") e siga as instruções no arquivo README.

## Contribuição
A aplicação recebe contribuições da comunidade de código aberto. Se você tiver ideias para melhorias ou correções de bugs, sinta-se à vontade para enviar uma pull request no GitHub.

## Contato
Para perguntas ou feedback, você pode entrar em contato com o mantenedor do projeto em [otavio.a.f.97@gmail.com].

*Este programa não é afiliado ou endossado pelo WhatsApp.*
