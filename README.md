Captura de Temperatura e Umidade com Histórico em Excel
Este projeto em Python utiliza a API OpenWeatherMap para capturar dados de temperatura e umidade de uma cidade específica e armazena esses dados em um arquivo Excel para histórico. Além disso, possui uma interface gráfica simples usando Tkinter para facilitar a captura dos dados.

Funcionalidades
Captura de Temperatura e Umidade: Utiliza a API OpenWeatherMap para obter a temperatura e umidade atuais da cidade configurada.
Histórico em Excel: Salva os dados capturados (data, hora, temperatura e umidade) em um arquivo Excel, criando um histórico das medições.
Interface Gráfica: Possui uma interface gráfica simples com um botão para iniciar a captura dos dados e exibir os resultados.
Abertura de link da previsão do tempo: Abre a página da previsão do tempo no navegador padrão do usuário.
Bibliotecas Utilizadas
requests: Para fazer requisições HTTP à API OpenWeatherMap.
openpyxl: Para trabalhar com arquivos Excel (ler e escrever).
datetime: Para obter a data e hora atuais.
tkinter: Para criar a interface gráfica.
webbrowser: Para abrir o link da previsão do tempo no navegador padrão.
Configuração
Chave da API OpenWeatherMap:
Você precisará de uma chave da API OpenWeatherMap. Substitua "d647b955ad05576e80db1a9b4ab86b35" pela sua chave na variável API_KEY.
Cidade:
Altere a variável CIDADE para a cidade desejada. Exemplo: "São Paulo, BR".
Arquivo Excel:
O arquivo Excel para armazenar o histórico é definido pela variável ARQUIVO_EXCEL. O padrão é "historico_temperatura.xlsx".
URL da previsão do tempo:
O link da previsão do tempo é definido pela variável URL_PREVISAO. O padrão é "https://www.google.com/search?q=previs%C3%A3o+do+tempo+s%C3%A3o+paulo&sca_esv=bf6563b3cfaca2c5&sxsrf=AHTn8zpqSQIrygJITJiW7gi980bsEDfriA%3A1743190033859&ei=EfjmZ6eYNMv-5OUP_o7gkAg&oq=previs%C3%A3o+do+tempo+s%C3%A3o+paulo&gs_lp=Egxnd3Mtd2l6LXNlcnAiHXByZXZpc8OjbyBkbyB0ZW1wbyBzw6NvIHBhdWxvKgIIADIKECMYgAQYJxiKBTIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEjBIVCdA1iSGHABeAGQAQCYAb0BoAGnCaoBBDAuMTC4AQHIAQD4AQGYAgugAugKwgIHECMYsAMYJ8ICChAAGLADGNYEGEfCAhMQLhiABBiwAxhDGMgDGIoF2AEBwgIEECMYJ8ICCBAAGIAEGLEDmAMAiAYBkAYLugYECAEYCJIHBTEuOS4xoAfqTrIHBTAuOS4xuAe-Cg&sclient=gws-wiz-serp".
Como Executar
Instale as bibliotecas:
Abra o terminal e execute:
Bash

pip install requests openpyxl
Execute o script Python:
Execute o arquivo Python do projeto. A interface gráfica será aberta.
Capturar Dados:
Clique no botão "Capturar Dados" na interface gráfica para obter a temperatura e umidade atuais e salvar no arquivo Excel.
Comandos Git Utilizados
git init: Inicializa um novo repositório Git.
git add .: Adiciona todos os arquivos do projeto à área de preparação.
git commit -m "Mensagem do commit": Commita as alterações com uma mensagem descritiva.
git remote add origin URL_DO_REPOSITÓRIO: Adiciona o repositório remoto (GitHub).
git push -u origin master: Envia as alterações para o repositório remoto.
Estrutura do Código
capturar_temperatura(): Função que obtém os dados da API e chama a função salvar_dados().
salvar_dados(): Função que salva os dados no arquivo Excel.
Interface Tkinter: Cria a interface gráfica com um botão para iniciar a captura.
