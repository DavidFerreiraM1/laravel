# Sobre o Projeto

Projeto criado com Laravel, no qual possui também o nginx, redis e mysql, e todo o ambiente se encontra configurado com Docker.
[Clieque Aqui](https://hub.docker.com/r/davidferreiram1/laravel-dev) para acessar a imagem criada do projeto no docker hub.

<br />
<br />

### Executar o projeto

---

-   Faça o clone ou o download do projeto
-   Na raiz do projeto execute o comando - `$ sudo docker-compose up -d `

<br />

#### **Atenção**

-   Certifique de ter o docker e o docker-compose instalados no seu computador
-   Caso não possua as devidas permissões para leitura escrita e alteração de arquivos dentro do diretório do projeto, podem ocorrer algumas falhas na tentativa do docker de subir os containers da aplicação.
-   A instrução de recuperar as dependências do projeto está chamada dentro de entrypoint.sh, o docker irá subir o container mas o composer irá continuar recuperando as dependências e executará as demais instruções do script em **background**, dependendo da sua conexão com a internet esse processo pode levar alguns minutos. Para acompanhar o processo execute o comando `$ sudo docker logs app` periodicamente até está certificado que o processo irá ter terminado.
    <br />
    <br />

### Mais Informações

---

-   A versão do docker utilizada no desenvolvimento - **v19.03.13** - **build 4484c46d9d**
-   A versão do docker compose utilizada no desenvolvimento - **v1.25.0**

<br />
<br />

### Autor

---

-   David Ferreira
