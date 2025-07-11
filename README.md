Markdown


# Projeto Janeiro Branco

![](https://www.gov.br/cetene/pt-br/assuntos/noticias/campanha-janeiro-branco-1/PapeldeParede.png)


Este projeto é uma aplicação web completa desenvolvida em apoio à campanha **Janeiro Branco**, Um mês para refletir, cuidar da mente e promover o bem-estar emocional, construindo uma sociedade mais saudável e feliz. A plataforma busca ser um canal de informação e, ao mesmo tempo, um espaço seguro e acolhedor para que pessoas possam deixar mensagens de apoio e solidariedade de forma anônima.

## 📜 Sobre a Campanha

A campanha "Janeiro Branco" é um movimento dedicado à conscientização sobre a importância da saúde mental e emocional. Ela busca prevenir doenças como ansiedade, depressão e pânico, que podem ser causadas pelo estresse, além de abordar outros transtornos de humor como esquizofrenia e transtorno bipolar.**Atendimento psicológico do HUB (Hospital Universitário de Brasília): Contato: (61) 3340-2314.** ou **Centro Universitário UDF: Oferece atendimento psicológico. Agendamento: (61) 3225-7724 / 99983-7555.**

## ✨ Funcionalidades

O projeto conta com as seguintes funcionalidades:

* **Página Informativa:** Uma página inicial que apresenta a campanha, explica a importância da Lei Maria da Penha e destaca os canais oficiais de denúncia.
* **Diario anônimo de progresso:** Compartilhe anonimamente seu progresso na luta contra os aspectos negativos da vida e incentive outras pessoas.
* **Formulário de Envio:** Um formulário simples e seguro para que qualquer pessoa possa ver sem saber quem é vc.

## 💻 Tecnologias Utilizadas

A aplicação foi construída utilizando um conjunto de tecnologias modernas, separando as responsabilidades entre o front-end, o back-end e o banco de dados.

* **Front-end (Interface do Usuário):**
    * `HTML5`: Para a estruturação semântica do conteúdo.
    * `CSS3`: Para a estilização, layout e design responsivo, seguindo a identidade visual do Agosto Lilás.
    * `JavaScript`: Para a interatividade e o carregamento dinâmico das mensagens no mural, consumindo a API do back-end.

* **Back-end (Lógica do Servidor):**
    * `Python 3`: Linguagem principal para toda a lógica da aplicação.
    * `Flask`: Um micro-framework leve e poderoso para criar o servidor web, gerenciar as rotas e a API.
    * `Django`:...

* **Banco de Dados:**
    * `SQLite 3`: Um banco de dados relacional baseado em arquivo, ideal para projetos de pequeno e médio porte pela sua simplicidade e por não necessitar de um servidor dedicado.

## 🚀 Como Executar o Projeto Localmente

Para rodar esta aplicação em seu ambiente de desenvolvimento, siga os passos detalhados abaixo.

### Pré-requisitos

Antes de começar, certifique-se de que você tem os seguintes softwares instalados em sua máquina:

* [Python 3.8+](https://www.python.org/downloads/)
* [Git](https://git-scm.com/) (para clonar o repositório)

### Passo a Passo para a Instalação

1.  **Clone o repositório:**
    Abra seu terminal e execute o seguinte comando para criar uma cópia local do projeto.
    ```bash
    git clone [https://github.com/SEU-USUARIO/projeto-Janeiro-Branco.git](https://github.com/SEU-USUARIO/projeto-Janeiro-Branco.git)
    ```
    *Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub.*

2.  **Acesse a pasta do projeto:**
    ```bash
    cd projeto-Janeiro-Branco
    ```

3.  **Crie e ative um ambiente virtual:**
    O uso de um ambiente virtual (venv) é uma boa prática para isolar as dependências do projeto.
    ```bash
    # No Windows
    python -m venv venv
    .\venv\Scripts\activate

    # No macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

4.  **Instale as dependências:**
    O arquivo `requirements.txt` contém as bibliotecas Python necessárias. Instale-as com um único comando.
    ```bash
    pip install -r requirements.txt
    ```

5.  **Inicialize o Banco de Dados:**
    Este comando executa o script `database.py` para criar o arquivo `mensagens.db` e a tabela correspondente. **Execute este passo apenas uma vez.**
    ```bash
    python database.py
    ```

6.  **Inicie o servidor Flask:**
    Agora, sua aplicação está pronta para ser executada!
    ```bash
    python app.py
    ```

7.  **Acesse a aplicação:**
    Abra seu navegador de internet e acesse a seguinte URL:
    [http://127.0.0.1:5000](http://127.0.0.1:5000)

Pronto! A aplicação estará rodando em sua máquina local.

## 📂 Estrutura de Pastas

```
agosto-lilas/
|-- app.py             # Arquivo principal do Flask (Back-end)
|-- database.py        # Script para criar o banco de dados
|-- static/            # Pasta para arquivos estáticos
|   |-- css/
|   |   `-- style.css  # Folha de estilos
|   `-- js/
|       `-- script.js  # Código JavaScript
|-- templates/         # Pasta para os templates HTML
|   |-- index.html     # Página inicial com o formulário
|   `-- diario.html     # Página para exibir as mensagens
|-- .gitignore         # Arquivo para ignorar arquivos no Git
|-- requirements.txt   # Dependências do Python
`-- README.md          # Este arquivo de documentação
```

---
Uma pequena tarefa com um grande objetivo para apoiar uma causa importante.
