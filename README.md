# Levantamento de Artilheiros do Brasileirão de 2022

## Descrição
Este projeto tem como objetivo coletar os dados dos artilheiros do futebol para a temporada de 2022. A partir dos dados, é possível calcular métricas como:
- o tempo médio que um jogador leva para marcar
- média de gols por jogo

## Tecnologias Usadas
**Python 3.x:** linguagem de programação utilizada para a coleta e análise dos dados
**Pandas:** biblioteca para manipulação e análise de dados
**Requests:** biblioteca para fazer requisições HTTP e interagir com a API
**.env:** arquivo de configuração para armazenar variáveis de ambiente, como a chave da API de forma segura

## Funcionalidade
O script do projeto realiza as seguintes ações:

**Coleta de dados:** utiliza a API da Football API para coletar informações sobre os artilheiros da temporada 2022
**Processamento dos dados:** organiza os dados em um DataFrame com informações dos jogadores, como nome, time, gols, idade, nacionalidade, partidas e minutos jogados
**Cálculo de tempo por gol:** calcula o tempo médio que cada jogador leva para marcar um gol, com base nos minutos jogados e gols marcados
**Cálculo da média de gol por jogo**: calcula a média de gols por jogo
**Exportação:** o DataFrame final pode ser exportado para um arquivo Excel

## Como Usar

### Pré-requisitos

Antes de executar o script, certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las usando o `pip`:

```bash
pip install pandas requests openpyxl python-dotenv
```bash

### Configuração do arquivo .env

Para acessar a API de Futebol, você precisa da chave da API. Crie um arquivo .env na raiz do seu projeto e adicione a chave da API da Football API:

```bash
API_KEY=YOUR_API_KEY_HERE


