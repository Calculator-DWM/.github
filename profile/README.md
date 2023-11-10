# Calculator-DWM 2023-2
## By:
- Érick Santos Marçal
- Luccas Castro de Souza
- Luiz Filipe de Souza Alves

## Índice:
- [Repositório front-end](#repositório-front-end)
    - [Iniciar Localmente o repositório front-end](#iniciar-localmente-o-repositório-front-end)
- [Repositório back-end](#repositório-back-end)
    - [Iniciar Localmente o repositório back-end](#iniciar-localmente-o-repositório-back-end)
- [Repositório OP](#repositório-op)
    - [Iniciar Localmente o repositório OP](#iniciar-localmente-o-repositório-op)
- [Links e Logs](#links-e-logs)
    - [Links](#links)
    - [Logs](#logs) 
  
## Repositório front-end:
**Nome:** calculator_vue <br>
**Deploy:** Vercel <br>

### Iniciar Localmente o repositório front-end:
O primeiro passo é clonar o repositório, isto pode ser feito pelo seguinte comando:
**HTTPS**
```bash
  git clone https://github.com/Calculator-DWM/calculator_vue.git
```

**SSH**
```bash
  git clone git@github.com:Calculator-DWM/calculator_vue.git
```

Depois, você deve entrar no respositório local do projeto com o seguinte comando:
```bash
  cd calculator_vue
```

Após isso, você deve instalar as dependências com o seguinte comando: 
```bash
  npm install
```

Com isto, você poderá iniciar o servidor de desenvolvimento com o seguinte comando:
```bash
  npm run dev
```

Que comecem os testes!

## Repositório back-end:
**Nome:** calculator_express <br>
**Deploy:** OnRender <br>

### Iniciar Localmente o repositório back-end:
O primeiro passo é clonar o repositório, isto pode ser feito pelo seguinte comando:
**HTTPS**
```bash
  git clone https://github.com/Calculator-DWM/calculator_express.git
```

**SSH**
```bash
  git clone git@github.com:Calculator-DWM/calculator_express.git
```

Depois, você deve entrar no respositório local do projeto com o seguinte comando:
```bash
  cd calculator_express
```

Após isso, você deve instalar as dependências com o seguinte comando: 
```bash
  npm install
```

Com isto, você poderá iniciar o servidor de desenvolvimento com o seguinte comando:
```bash
  npm start
```

## Repositório OP:
**Nome:** .github <br>
**Deploy:** OnRender <br>
**Banco de Dados:** PostGreeSQL <br>
### Iniciar Localmente o repositório OP:
- O primeiro passo para ter um repositório OP no seu computador local é instalar o PostGreeSQL, para isto, é necessário primeiramente instalar o PgAdmin na sua máquina, conforme seu sistema operacional, no seguinte link:<br>
[Download](https://www.pgadmin.org/download/)<br>
Então, você poderá apertar em new host e configurar seu próprio host, o padrão é usar como porta 5432 e o seu host pode ser o localhost, para que você tenha um banco de dados próprio na sua máquina.<br>

- **Caso seja necessário, siga o tutorial a seguir:**
[Tutorial](https://www.youtube.com/watch?v=Z-CA88-2qwI)
Créditos aos autores.

- Agora que você possui um repositório local, você deve renomear o arquivo env.example para .env, então você deve entrar no arquivo e configurar sua conexão conforme o seu host, usuário, senha e porta, a configuração padrão é:
```bash
    DB_HOST= localhost
    DB_PORT= 5432
    DB_DATABASE=nome_do_db
    DB_USERNAME= root
    DB_PASSWORD=password_do_db
```
- Agora você pode rodar o projeto com banco de dados.

## Links e logs:
### Links:
Para acessar o Deploy Online, acesse o seguinte link:<br>
[Deploy](https://calculator-vue-zeta.vercel.app/)

### Logs:
Os logs do aplicativo se encontrarão na pasta:<br>
```src/logs/express.log```
