# Hello World com Docker

<p>
  <a href="https://www.linkedin.com/in/paulodelia/">
      <img alt="Paulo D'Elia" src="https://img.shields.io/badge/-paulodelia-important?style=flat&logo=Linkedin&logoColor=white" />
   </a>
  <a href="https://github.com/paulohdelia/fullcycle-desafio-docker/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/paulohdelia/fullcycle-desafio-docker?color=important">
  </a> 
  <img src="https://img.shields.io/github/languages/count/paulohdelia/fullcycle-desafio-docker?color=important&style=flat-square">
</p>

Este é o primeiro desafio da semana Dev FullCycle, e serve como uma leve introdução para nos acostumar a usar Docker. 

Como o próprio nome do desafio sugere, é apenas um "Hello World" do Docker, mas que para quem está tendo a primeira experiência com Docker (eu mesmo 😅) está sendo muito valioso.

Para utilizar a imagem que fiz:
```bash
# Baixe a imagem
docker pull paulohdelia/fullcycle-desafio-docker

# Depois é só rodar
docker run paulohdelia/fullcycle-desafio-docker 
```

E por fim acesse pelo navegador pelo http://localhost:8080

Caso não saiba como configurar o docker, recomendo dar uma olhada no vídeo citado nas informações do desafio, e também este [vídeo do canal Fireship sobre Docker](https://www.youtube.com/watch?v=gAkwW2tuIqE)

## :book: Informações do desafio

Durante toda a Maratona utilizaremos containers como base de desenvolvimento bem como para produção. Logo, ter uma noção básica de Docker é mais do que necessário.

Nesse desafio, você terá de criar uma imagem docker que quando executada deverá expor a porta 8080 exibindo a mensagem: Eu sou Full Cycle.
Fique na liberdade para utilizar a tecnologia/linguagem de programação de sua escolha. Exemplo: você poderá criar uma simples aplicação usando Node.js com Express para exibir essa mensagem.
Gere o build da sua imagem, faça o push para o DockerHub e a informe no formulário abaixo.

Se você nunca teve nenhuma experiência com docker, recomendamos que assista a seguinte aula: https://www.youtube.com/watch?v=yb2udL9GG2U 
