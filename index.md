## Welcome to GitHub Pages
WANDERSON JONER SILVA CRUZ

OBJETIVO
Desenvolver e Reparar Sistemas de Informacao

Segue alguns Sistemas Desenvolvidos por mim em JavaScript, Java, Html, CSS etc. que estão online:
  
  - Detector de Rostos e Download Automático https://rostodetector.netlify.com/
  - Detector de Nudes https://nudesremove.netlify.com/
  - Atenas Assitente Pessoal https://atenas.netlify.com/
  - Mario Game https://mariogamejs.netlify.com/
  - Curso de Informática Básica para o Trabalho https://cursoinformatica.netlify.com/
  

```markdown
Servidor web em JavaScript

const express = require('express')
const path = require('path')
const app = express()
const port = process.env.PORT || 3000

const bodyParser = require('body-parser')
const pessoas = require('./routes/pessoas')

const mysql = require('mysql')
const connection = mysql.createConnection({
    host: '127.0.0.1',
    user: 'root',
    password: 'sua senha',
    database: 'nome do seu Banco de dados'
})

const dependencies = {
    connection
}

app.use(bodyParser.urlencoded( { extended : false } ))
app.use(express.static('public'))
app.get('/', (req, res)=> res.render('home'))
app.set('views', path.join(__dirname, 'views'))
app.set('view engine', 'ejs')
app.use('/pessoas', pessoas(dependencies))
connection.connect(()=>{
    app.listen(port, ()=> console.log('Listering on port:'+port))
})

```

Para mais detalhes [GitHub Wanderson Joner](https://github.com/wandersonjoner/crudpro).

###  RESUMO DE QUALIFICACÕES
Carreira desenvolvida na área de Tecnologia da Informação desde 2002, com ampla experiência em suporte e atendimento ao usuário, manutenção especializada em computadores, implantação, manutenção de sistemas e implementação de melhorias. Desenvolvendo trajetória em empresas multinacionais de grande porte. Ofereço forte atuação na construção de soluções, desenvolvendo e corrigindo aplicações com arquitetura REST desenvolvida com Spring, tenho domínio do mapeamento do ciclo de vida dos objetos, teste do verbos POST,GET, PUT e DELETE com PostMan, Query com Criteria, migração com Flyway, Maven, GitHub. Sistemas alinhados aos objetivos da empresa, também dou aula de Informática Básica para o Trabalho no Projeto Bolsa Futuro do Estado de Goiás e dou aulas para a Plataforma de Cursos On-line / Presêncial, The Future Escola de Tecnologia da Informação (Montagem e configuração, Word, Excel, compactar arquivos, navegação segura na internete etc.).
Desenvolvedor de Sistemas nas Linguagens Java EE, JavaScript, Angular 2, MYSQL.

### Java com a Tecnologia REST criando aplicacoes RESTful com Spring FrameWork
  Segue alguns Sistemas Desenvolvidos em Java que estão no GitHub:
    - Inventario de Computadores https://github.com/wandersonjoner/inventario-computadores
    - Controle de Alunos https://github.com/wandersonjoner/ApiRESTful
    - Seguranca com OAUTH https://github.com/wandersonjoner/Oauth, também video explicativo no youtube https://www.youtube.com/watch?v=Pp1Ipg2vi70&t=331s

### Support or Contact
E-Mail: wandersonjoner@hotmail.com
Cel / WhatsApp: 61 98487-1399
Santa Maria Sul – Brasilia – DF, CNH: B.
GitHub : https://github.com/wandersonjoner
Linkedin: https://www.linkedin.com/in/wanderson-joner-silva-cruz-8900ab48/
Meu Canal de Cursos no Youtube: https://www.youtube.com/channel/UCm77ojeCNi9rdgxFoP4SXEw/videos?view_as=subscriber
