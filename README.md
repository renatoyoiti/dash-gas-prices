# Configurando o Ambiente de Desenvolvimento

Este projeto utiliza Python e a biblioteca Dash para visualização de dados interativa. Para garantir um ambiente isolado e organizado, siga os passos abaixo para configurar o ambiente virtual e instalar as dependências.

## Requisitos

Antes de iniciar, certifique-se de ter instalado:
- Python (versão 3.12)
- pip (gerenciador de pacotes do Python)

## Criando e Ativando o Ambiente Virtual

1. Abra um terminal ou prompt de comando e navegue até a pasta do projeto.
2. Execute o comando abaixo para criar um ambiente virtual:

   ```sh
   py -3.12 -m venv .venv
   ```

3. Ative o ambiente virtual:
   - No Windows:
     ```sh
     .venv\Scripts\activate
     ```
   - No macOS/Linux:
     ```sh
     source .venv/bin/activate
     ```

## Instalando as Dependências

Com o ambiente virtual ativado, instale os pacotes necessários executando:

```sh
pip install -r requirements.txt
```

Caso ainda não tenha um arquivo `requirements.txt`, crie um e adicione os seguintes pacotes:

```
dash
plotly
pandas
dash-bootstrap-components
dash-bootstrap-templates
```

Em seguida, execute novamente o comando para instalar as dependências.

## Executando a Aplicação

Para iniciar o servidor Dash, execute:

```sh
python nome_do_arquivo.py
```

Substitua `nome_do_arquivo.py` pelo nome do seu arquivo principal.

## Desativando o Ambiente Virtual

Quando terminar de trabalhar no projeto, você pode desativar o ambiente virtual executando:

```sh
deactivate
```

