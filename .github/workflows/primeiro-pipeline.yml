name: Primeiro Workflow 
# em quais evenos de gatilhos quero que dispare meu script
on:
  push:
   branches:
    -developer
    -main
    -master
  pull_request:
    branches: [main, master]
# quais são ops trabalhos (fluxos) a serem executados pelo workflow

jobs:
   Primeiro-fluxo:
    name: job 1
     e este é o nome do fluxo de trabalho
    runs-on: ubuntu-latest
     e agora irei iniciar os passos do script 
     steps:
     -name: Passo 1
      run: echo "Executando o primeiro passo"
      Segundo-Fluxo:
    # esté é o nome do fluxo de trabalho
      name: Job2
    # para ser executado nesta maquina virtual linux
      runs-on: ubuntu-latest
    # agora irei incluir os passos do script 
      steps: 
       - name: Passo 4
         run: echo "Executando o quarto passo."
       - name: Passo 5
         run: echo "Executando o quinto passo."
       - name: Passo 6
         run: echo "Executando o sexto passo."   

  Terceiro-Fluxo:
    # esté é o nome do fluxo de trabalho
    name: Job3
    # para ser executado nesta maquina virtual linux
    runs-on: ubuntu-latest
    # agora irei incluir os passos do script 
    steps: 
      - name: Passo 7
        run: echo "Executando o setimo passo."
      - name: Passo 8
        run: echo "Executando o oitavo passo."
      - name: Passo 9
        run: echo "Executando o nono passo."
