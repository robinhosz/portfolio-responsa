# 🔛 Site Pessoal

Site pessoal responsivo para visualizar minhas habilidades, portfólio e objetivos profissionais.

### 📋 Pré-requisitos

Coisas iniciais que você precisa para rodar o projeto.

```
Uma IDE, Bootstrap, Python e o Framework Flask
```

### 🔧 Instalação

Exemplos passo-a-passo que informam o que você deve executar para rodar o projeto.

Quando você já estiver instalado a IDE o Python e o Bootstrap, vai precisar instalar o framework Flask pelo terminal. O processo de instalação de um pacote com o PIP em um projeto Python é bem simples. Basta utilizar o comando **pip install** seguido do nome do pacote que o próprio gerenciador se encarregará de baixá-lo e realizar sua instalação. Logo abaixo vai estar o comando a ser executado.

```
pip install Flask
```
Para funcionar o recebimento de email pelo formulário, vamos ter que instalar um outro pacote, chamado Flask-Mail

```
pip install Flask-Mail

```

E por ultimo para fazer as configurações de dotenv funcionarem é preciso instalar o python-dotenv com o seguinte comando abaixo.

```
pip install python-dotenv
```


## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/) - O framework web usado
* [Flask](https://flask.palletsprojects.com/en/2.0.x/) - O framework back-end
* [Heroku](heroku.com) - Ferramenta de deploy


## 🔧 Resolvendo possíveis bugs.

1.  ### 📧 <strong><em>Envio de Email</em></strong>
   Ao longo do desenvolvimento do site pessoal, tive diversos bugs em relação ao recebimento de emails. Notei que o gmail estava me dando diversos problemas de acesso e recebimento dos emails, bloqueando a plataforma de host de enviar as mensagens com a seguinte mensagem de error <strong>"Application Error".</strong> Isso parou de acontecer depois da troca de porta e email eletrônico.
   
![Application Error](https://user-images.githubusercontent.com/82779533/149251554-260fb094-2ec8-4a14-b1ec-ce00fd0ae849.png)

   
2. ### ⚙️ <strong><em>Config Vars</em></strong>
 Um outro problema que pode ocorrer em relação ao envio do formulário, é dar a seguinte mensagem de error <strong>"Error Pages".</strong> Isso pode ser erro das configurações das variaveis do heroku. Pois como você não fez o deploy da sua .env, onde fica o seu email e senha, o heroku não vai ter como acessar. Para resolver isso vai ter que criar duas configs vars em **"Settings"**, Uma do email e outra da senha.
 
 
![Config Vars](https://user-images.githubusercontent.com/82779533/149251448-b6725d6c-97f4-43da-8d36-75ca34779818.png)


