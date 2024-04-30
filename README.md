# Diagrama Model-View-Controller
## Análise e Definição do Escopo
<b> Principal Objetivo:</b> A página web será construída com ajuda do framework Sails.js e desenvolvida em HTML, CSS e JavaScript. O objetivo principal é garantir funcionalidade e simplicidade, para que o usuário tenha facilidade e intuitividade no uso da plataforma.

&nbsp;&nbsp;&nbsp;&nbsp; O banco de dados, o backend e o frontend se comunicarão de maneira efetiva por meio do ORM (Object-Relational Mapping) do Sails.js, que é responsável por gerenciar o acesso e manipulação dos dados. 

&nbsp;&nbsp;&nbsp;&nbsp; Oferecemos, nesta aplicação, para o usuário final, um site responsivo, com integração facilitada para novos recursos e funcionalidades, além de adaptabilidade.


<b> Principais Módulos, Funcionalidades e Recursos:</b> 

&nbsp;&nbsp;&nbsp;&nbsp; - Autenticação de Usuários: Registro de novos usuários, login e logout de usuários, controle de acesso às funcionalidades da plataforma.

&nbsp;&nbsp;&nbsp;&nbsp; - Feed:
Publicação de ideias, classificação e filtragem de ideias por categorias ou tags, pesquisa avançada por ideias.

&nbsp;&nbsp;&nbsp;&nbsp; - Comunidade:
Catálogo de ONGs cadastradas, visualização de informações detalhadas sobre cada ONG (missão, projetos e formas de contato), recursos para os usuários se engajarem com as ONGs, como doações e voluntariado, listagem de projetos para replicação, detalhes sobre cada projeto, incluindo objetivos, metodologia e recursos necessários.

## Diagrama
&nbsp;&nbsp;&nbsp;&nbsp; Para o diagrama da nossa aplicação, pensamos em dividi-lo em duas partes: uma para a Landing Page e seus conteúdos, e outra para a plataforma em si.
### Diagrama da Landing Page
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo está o diagrama da nossa página inicial (Landing Page):
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Landing Page</sub><br><br>
<img src = "assets/MVC .drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp; Aqui, o usuário só terá interação de input ao fazer login e cadastro. Em todas as outras páginas, nossa API só responderá a listagens (requisições GET) e chamadas de endpoint para o frontend.

### Diagrama da Plataforma
&nbsp;&nbsp;&nbsp;&nbsp; Aqui está o diagrama da nossa plataforma:
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Plataforma</sub><br><br>
<img src = "assets/MVC Plataforma.drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp;Uma vez dentro da plataforma, o usuário terá a possibilidade de fazer diversos tipos de interação com o banco de dados, desde postagens até visualizações do feed, busca e filtragem de ONGs, projetos similares e usuários com interesses semelhantes.




