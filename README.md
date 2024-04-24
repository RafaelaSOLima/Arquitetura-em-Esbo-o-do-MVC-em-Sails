# Diagrama Model-View-Controller
## Análise e Definição do Escopo
<b> Principal Objetivo:</b> Essa aplicação web construída com ajuda do framework Sails.js tem como principal propósito estabelecer uma plataforma robusta e eficiente, em que a interação do usuário se dá por meio de uma interface desenvolvida com HTML, CSS e Javascript. Essa interface amigável e responsiva irá proporcionar uma experiência fluida ao usuário, permitindo uma navegação intuitiva e agradável.

&nbsp;&nbsp;&nbsp;&nbsp;Nos bastidores, essa interface interage de forma dinâmica com uma API backend desenvolvida em Node.js, de arquitetura MVC e framework Sails.js. Essa API, construída sobre uma arquitetura moderna e escalável, proporciona uma comunicação eficiente entre o front-end e o banco de dados PostgreSQL. Utilizando o poderoso sistema de ORM (Object-Relational Mapping) do Sails.js, a aplicação é capaz de gerenciar de forma eficaz e segura as operações de acesso e manipulação dos dados armazenados no banco.

&nbsp;&nbsp;&nbsp;&nbsp;Com essa arquitetura bem definida, a aplicação web oferece não apenas uma interface elegante e responsiva para os usuários finais, mas também uma base sólida e confiável para o desenvolvimento e manutenção contínua da plataforma. Além disso, a modularidade e extensibilidade do Sails.js permitem uma fácil integração de novos recursos e funcionalidades, garantindo que a plataforma possa crescer e se adaptar às necessidades em constante evolução dos usuários e do mercado.


<b> Principais Módulos, Funcionalidades e Recursos:</b> 
&nbsp;&nbsp;&nbsp;&nbsp; - Autenticação de Usuários: Registro de novos usuários, login e logout de usuários, controle de acesso às funcionalidades da plataforma.

&nbsp;&nbsp;&nbsp;&nbsp; - Feed:
Publicação de ideias, classificação e filtragem de ideias por categorias ou tags, pesquisa avançada por ideias.

&nbsp;&nbsp;&nbsp;&nbsp; - Comunidade:
Catálogo de ONGs cadastradas, visualização de informações detalhadas sobre cada ONG (missão, projetos e formas de contato), recursos para os usuários se engajarem com as ONGs, como doações e voluntariado, listagem de projetos para replicação, detalhes sobre cada projeto, incluindo objetivos, metodologia e recursos necessários.

## Diagrama
&nbsp;&nbsp;&nbsp;&nbsp; Para o diagrama da nossa aplicação, pensamos em quebrá-lo em duas partes: uma para a Landing Page e seus conteúdos e outra para a plataforma em si.
### Diagrama da Landing Page
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo, o diagrama da nossa página inicial (Landing Page):
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Landing Page</sub><br><br>
<img src = "assets/MVC .drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp; Aqui, o usuário só terá interação de input ao fazer login e cadastro. Em todas as outras páginas, nossa API só responderá à listagens (requisições GET) e a chamadas de endpoint para o frontend.

### Diagrama da Plataforma
&nbsp;&nbsp;&nbsp;&nbsp; Abaixo, o diagrama da nossa plataforma:
<div align="center" width="100%">
 <sub>Figura 1: Diagrama da Plataforma</sub><br><br>
<img src = "assets/MVC Plataforma.drawio.png " alt="image" width="80%" height="auto"></div>

&nbsp;&nbsp;&nbsp;&nbsp; Uma vez dentro da plataforma, o usuário terá a possibilidade de fazer diversos tipos de interação com o banco de dados, desde postagens até visualizações do feed e busca por ONGs, projetos parecidos e pessoas de interesses semelhantes.




