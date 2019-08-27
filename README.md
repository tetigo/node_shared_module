# node_shared_module
A simple node module to be shared between my projects (not npm but here github)


- Criar projeto no github, de preferência já com readme.md.
- Clonar o projeto local.
- npm init no mesmo diretório onde foi clonado. 
- Vai ser criado o package.json já com os atalhos para o repositório GIT !!!
- Importante: no package a tag main vai estar com index.js, isso deve manter.
- Criar esse arquivo index.js com a funcionalidade a ser compartilhada no module.exports.
- Comitar e subir para o github essa alteração.
- Pronto. Já dá pra importar em nossos projetos.
-------------------
- Para testar.
- Criar outro projeto em outro diretório.
- npm init para criar outro package.json
- A url do github vai ser usada como dependencia do nosso projeto. 
- Instalar usando npm install --save <endereco_do_github>
- Vai ser criada uma dependencia no package.json com o nome que colocamos no github.
- Pronto. Só usar com require('nome_do_modulo').

