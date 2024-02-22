# Desafio Ciência de Dados - Lighthouse - Indicium 

Este projeto é parte integrante do processo de seleção do programa Lighthouse da Indicium, que é um programa voltado para quem quer começar uma carreira na área de dados e já tem algum contato com o tema.

O desafio consiste em fazer a análise exploratória de dados de um dataset contendo dados de locação de Nova Iorque e a partir desses dados criar um modelo de Machine Learning capaz de prever o aluguel de um imóvel na região

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local.


### 📋 Pré-requisitos

- arquivo "teste_indicium_precificacao.csv" contendo os dados dos imóveis, disponível neste repositório.
- Jupyter Notebook ou Google Colaboratory

### 🔧 Instalação

A versão Python utilizada neste projeto foi a 3.11.5.

Este repositório conta com um arquivo requirements.txt que contém a relação da bibliotecas utilizadas no projeto e suas respectivas versões.

É possível instalar a versão específica do módulo utilizado através do código:  
*pip install nome_pacote==versão_desejada*  

Após a instalação é necessário reiniciar o Jupiter Notebook.

Também é possível instalar todas as bibliotecas na versão utilizada via prompt de comando no terminal através do código:  
*pip install -r requirements.txt*  
 
Caso você opte por utilizar este código no Google Colaboratory é necessário carregar o arquivo csv "teste_indicium_precificacao" no drive do google. Isto é possível acessando a aba arquivos, e selecionar a opção "fazer o upload para o armazenamento da sessão".

### ⚙️ Modelo de previsão de preço criado ao final do projeto

Este repositório conta com um arquivo pkl chamado "modelo_rfr_file". Em virtude da limitação de upload de arquivos do gitbub, este arquivo pode ser baixado em: https://drive.google.com/file/d/1Ooe-jJBVVp6rpRHxV_ZKhtUFuZXOsiDo/view?usp=sharing
Este arquivo contém o modelo treinado durante este projeto. Caso o seu intuíto seja somente utilizar o modelo para previsão de preços é possível carregá-lo em seu próprio notebook com o seguinte código:

*import pickle*  
*modelo_rfr = pickle.load(open('modelo_rfr_file.pkl', 'rb'))*  

Lembre-se de utilizar as normalizações necessárias para que o modelo interprete os seus dados de entrada corretamente.





