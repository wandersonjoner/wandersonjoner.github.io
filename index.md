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
Carreira desenvolvida na area de Tecnologia da Informacao desde 2002, com ampla experiencia em suporte e atendimento ao usuario, manutenção especializada em computadores, implantacao, manutenção de sistemas e implementacao de melhorias. Desenvolvendo trajetoria em empresas multinacionais de grande porte. Ofereço forte atuação na construção de solucoes, desenvolvendo e corrigindo aplicacoes com arquitetura REST desenvolvida com Spring, tenho dominio do mapeamento do ciclo de vida dos objetos, teste do verbos POST,GET, PUT e DELETE com PostMan, Query com Criteria, migracao com Flyway, Maven, GitHub. Sistemas alinhados aos objetivos da empresa, também dou aula de Informática Basica para o Trabalho no Projeto Bolsa Futuro do Estado de Goias e dou aulas para a Plataforma de Cursos On-line / Presencial, The Future Escola de Tecnologia da Informacao (Montagem e configuracao, Word, Excel, compactar arquivos, navegacao segura na internete etc.).
Desenvolvedor de Sistemas nas Linguagens Java EE, JavaScript, Angular 2, MYSQL.

### Java com a Tecnologia REST criando aplicacoes RESTful com Spring FrameWork
  Segue alguns Sistemas Desenvolvidos em Java que estão no GitHub:
    - Inventario de Computadores https://github.com/wandersonjoner/inventario-computadores
    - Controle de Alunos https://github.com/wandersonjoner/ApiRESTful
    - Seguranca com OAUTH https://github.com/wandersonjoner/Oauth, também video explicativo no youtube https://www.youtube.com/watch?v=Pp1Ipg2vi70&t=331s

### Support or Contact
E-Mail: wandersonjoner@hotmail.com
Cel / WhatsApp: 61 99301-2360
Samambaia Norte – Brasilia – DF, CNH: B.
GitHub : https://github.com/wandersonjoner
Linkedin: https://www.linkedin.com/in/wanderson-joner-silva-cruz-8900ab48/
Meu Canal de Cursos no Youtube: https://www.youtube.com/channel/UCm77ojeCNi9rdgxFoP4SXEw/videos?view_as=subscriber
