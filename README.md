# DataScience

Maratona 2.0 do <a href="https://cienciadosdados.com/">Ciência de Dados</a>

Maquina Preditiva utilizando SVM

  - Nesse caso prático, nós precisamos construir um Sistema de classificação de Risco do cliente para aprovação de empréstimos.
  - Usaremos a base de dados "risco.csv" originada por meio dos dados da UCI Machine Learning. (Nesse portal a gente consegue 
        realizar o download de vários datasets reais de empresas de todo o Mundo. <a href="https://archive.ics.uci.edu/ml/index.php">link</a> )

Deploy

1° Realizar o download da ferramenta "Visual Studio Code" no link abaixo:
  - <a href="https://code.visualstudio.com/">VS Code</a>

2° Instalar a ferramenta: Clicar em "next" e "finish" (simples assim...)

3° Criar um diretório "app" no seu Drive "C"
  - Ex: C:\app

4° Fazer o Download da pasta "maratona" disponibilizada na página da maratona e via Canal no Telegram.

5° Salvar essa pasta dentro do diretório app.
  - Ex: C:\app\maratona
   Obs: dentro da pasta maratona temos 3 arquivos:
    -risco.csv - Nossa fonte de dados
    - app_risco.py - Nosso Aplicativo web
    - Sistema_Classificação_Risco.ipynb - Nosso Script de Criação da Máquina Preditiva

6° Abrir o VS Code e clicar no menu "File", depois "Open Folder" e vai navegar até o diretório "C:\app\maratona"

7° Vai no menu "terminal", depois "New Terminal". Perceba que vai abrir, lá embaixo, um terminal de comando, tipo o "CMD" (tela preta) do windows.

8° executar os seguinte comandos:
  - pip install plotly + tecla enter
  - pip install streamlit + tecla enter

9° Instalar o Anaconda
  - <a href="https://www.anaconda.com/products/individual">Anaconda</a>

10° Executar o comando de abertura (no terminal do VS Code), do nosso LINDO sistema:
  - streamlit run app_risco.py
    Obs: Nosso sistema vai abrir na WEB. Ver no seu navegador web.
