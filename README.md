Captura de Temperatura e Umidade
Este projeto Python captura dados de temperatura e umidade usando a API OpenWeatherMap e salva o histórico em um arquivo Excel.

Funcionalidades
Captura temperatura e umidade da cidade configurada.
Salva os dados em um arquivo Excel (histórico).
Interface gráfica simples com Tkinter.
Abre a página de previsão do tempo no navegador.

Bibliotecas
requests: Permite fazer requisições HTTP para interagir com APIs web, como a OpenWeatherMap, para obter dados.
openpyxl: Fornece ferramentas para ler e escrever arquivos Excel (.xlsx), permitindo armazenar os dados capturados.
datetime: Oferece funcionalidades para trabalhar com datas e horários, útil para registrar o momento da captura dos dados.
tkinter: Cria interfaces gráficas (GUIs) simples para interação com o usuário, como botões e janelas.
webbrowser: Permite abrir páginas web no navegador padrão do sistema, usado para exibir a previsão do tempo no navegador.

Configuração
Instale as bibliotecas: pip install requests openpyxl
Obtenha sua chave da API OpenWeatherMap e substitua em API_KEY.
Altere a variável CIDADE para a cidade desejada.
O arquivo Excel padrão é historico_temperatura.xlsx.

O link da previsão do tempo padrão é: "https://www.google.com/search?q=previs%C3%A3o+do+tempo+s%C3%A3o+paulo&sca_esv=bf6563b3cfaca2c5&sxsrf=AHTn8zpqSQIrygJITJiW7gi980bsEDfriA%3A1743190033859&ei=EfjmZ6eYNMv-5OUP_o7gkAg&oq=previs%C3%A3o+do+tempo+s%C3%A3o+paulo&gs_lp=Egxnd3Mtd2l6LXNlcnAiHXByZXZpc8OjbyBkbyB0ZW1wbyBzw6NvIHBhdWxvKgIIADIKECMYgAQYJxiKBTIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABDIFEAAYgAQyBRAAGIAEMgUQABiABEjBIVCdA1iSGHABeAGQAQCYAb0BoAGnCaoBBDAuMTC4AQHIAQD4AQGYAgugAugKwgIHECMYsAMYJ8ICChAAGLADGNYEGEfCAhMQLhiABBiwAxhDGMgDGIoF2AEBwgIEECMYJ8ICCBAAGIAEGLEDmAMAiAYBkAYLugYECAEYCJIHBTEuOS4xoAfqTrIHBTAuOS4xuAe-Cg&sclient=gws-wiz-serp"

Como Executar
Execute o script Python.
Clique em "Capturar Dados" na interface.

Comandos Git
git init: Inicializa um novo repositório Git no diretório atual.
git add .: Adiciona todas as alterações do diretório atual à área de preparação (stage) para o próximo commit.
git commit -m "Mensagem": Registra as alterações preparadas no repositório com uma mensagem descritiva.
git remote add origin URL: Adiciona um repositório remoto (no GitHub) para onde as alterações serão enviadas.
git push -u origin master: Envia as alterações do branch master local para o repositório remoto. O -u configura o rastreamento para futuras operações de push/pull.

