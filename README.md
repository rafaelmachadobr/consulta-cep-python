# Aplicação Python para consulta de CEP
Essa aplicação é um simples programa em Python que faz uma requisição à API da ViaCEP (https://viacep.com.br/) para consultar informações de endereço a partir de um CEP (Código de Endereçamento Postal) fornecido pelo usuário. Além disso, a aplicação utiliza o framework PySimpleGUI para exibir essas informações em uma interface gráfica amigável.

## Pré-requisitos
Para rodar essa aplicação, é necessário ter o seguinte instalado em sua máquina:

- Python 3.6 ou superior
- O módulo **"requests"** para fazer requisições HTTP
- O framework PySimpleGUI para criar a interface gráfica

Para instalar essas dependências, basta usar o gerenciador de pacotes do Python, o **"pip"**, da seguinte maneira:

```pip install requests PySimpleGUI```

## Como usar
Para usar essa aplicação, basta seguir os seguintes passos:

1. Clone ou faça o download desse repositório em sua máquina
2. Abra o terminal e navegue até o diretório onde o arquivo **"app.py"** está localizado
3. Execute o arquivo com o comando ```python app.py```
4. Na janela que abrir, digite o CEP desejado e clique no botão "Consultar"
As informações de endereço correspondentes ao CEP fornecido serão exibidas na tela

## Observações

- Caso o CEP fornecido seja inválido ou não exista, uma mensagem de erro será exibida
- A API da ViaCEP utilizada nessa aplicação é gratuita, mas possui limitações de uso. Caso essas limitações sejam ultrapassadas, a aplicação poderá apresentar erros ou lentidão durante a consulta de CEPs.
