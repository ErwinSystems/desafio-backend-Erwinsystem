# desafio-backend-Erwinsystem

o desafio consistirá em criar uma Api simples sobre <b>revistas em Quadrinhos</b> usando as tecnologias Typescript/Javascript e MongoDB, usando como principais libs express e jwt, o dev deverá conectar a Api a um banco não relacinal MongoDB(não há necessidade de hospedar um banco de dados, você pode usa-lo em sua própria maquina).
a api precisará ter um CRUD, usando os métodos http GET,POST,PUT,DELETE, os dados deverão:

- ser lidos (pelo metodo get)
- editados por usuarios autenticados (pelo metodo put)
- criados por usuarios autenticados (pelo metodo post)
- deletados por usuarios autenticados (pelo metodo delete)

a autentificação deve ser feita por JSON WEB TOKEN, e os usuários devem possuir senha e nome, a forma como os dados das revistas devem ser retornados é:
<pre>
{
  titulo: "berserk",
  volumeUnico: false,
  volume: 1,
  autor:"kentaro miura",
  ano: 1988,
  imgLink: "https://pm1.narvii.com/6878/c9dfa149f26bc6f676e18837a96c2bd05721892er1-724-1024v2_hq.jpg"
}
</pre>
fazer fork desse repositório e ao finalizar, faça um pull request para ser avaliado.
