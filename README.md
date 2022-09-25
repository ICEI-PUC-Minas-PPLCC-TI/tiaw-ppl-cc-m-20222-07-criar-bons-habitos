# Informações do Projeto
`Como Criar Bons Hábitos`  

Ciências da Computação PUC-MINAS



## Participantes

Os membros do grupo são: 
- João Pedro Moura
- Lucas Galtieri
- Samuel Penido
- Júlia Sebastião
- Alvaro Tavares
- Gabriel Carlos

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução
>  A vida universitária e escolar demanda dos estudantes uma gestão de tempo e organização com os estudos. Levando em conta que aproximadamente 4% de toda a população >    do país sofre de TDAH ( transtorno do déficit de atenção com hiperatividade ) tornase ainda mais dificil o foco e organização com tarefas e estudos diários      >presentes na rotina de um universitario.
>  Uma rotina organizada, com boa gestão de tempo traz para o estudante uma constância maior em seus estudos, melhor aprendizado e convívio com as matérias. 



## Problema



> A desorganização e falta de gestão de tempo é um problema que afeta a vida da maioria das pessoas, pequenos atrasos, desvios de atenção e claro... redes sociais,
> podem te distrair por horas e passar em “um piscar de olhos”. Esses pequenos “atrasos” podem te tirar do objetivo por horas quando somadas no final do dia, causando > assim uma falsa sensação de falta de tempo, causando estresse, cansaço e falta de produtividade.

>
> **Links Úteis**:
> - [Objetivos, Problema de pesquisa e Justificativa](https://medium.com/@versioparole/objetivos-problema-de-pesquisa-e-justificativa-c98c8233b9c3)
> - [Matriz Certezas, Suposições e Dúvidas](https://medium.com/educa%C3%A7%C3%A3o-fora-da-caixa/matriz-certezas-suposi%C3%A7%C3%B5es-e-d%C3%BAvidas-fa2263633655)
> - [Brainstorming](https://www.euax.com.br/2018/09/brainstorming/)

## Objetivos



> Tendo em vista a problemática, o projeto tem como objetivo facilitar o aprendizado e organização da rotina estudantil, sabemos o quão puxada a rotina de estudos pode >  ser, e para isso buscamos desenvolver uma plataforma que irá auxiliar na rotina e organização para melhor aprendizado.
>
>  Objetivos específicos :
>  - Ajudar o estudante a se organizar melhor com seus horarios.
>  - Desenvolver uma agenda virtual com lembretes e dicas.
>  - Montar uma rotina e plano de estudo para o aluno.
>  - Ajudar o estudante a se preparar de forma constante nos estudos, tornando a rotina constante, pórem leve.
>  - Disciplina do aluno nos momentos de estudo com um cronograma único

> 
> **Links Úteis**:
> - [Objetivo geral e objetivo específico: como fazer e quais verbos utilizar](https://blog.mettzer.com/diferenca-entre-objetivo-geral-e-objetivo-especifico/)

## Justificativa

> De acordo com os dados fornecidos pelo MEC (Ministério da Educação) o brasil tem mais de 6,5 milhões de universitários. Levando como exemplo o curso de direito que   > hoje é o curso com mais alunos em todo o brasil, apenas 31,4% dos alunos que participaram da prova de Exame da Ordem Unificado 2021/2 (EOU) promovido pelo Conselho  > Federal da OAB foram aprovados (maior percentual de aprovação da história). Acreditamos que para tal feito ser conquistado pelo estudante foi-se necessário uma
> boa organização e disciplina em uma rotina de estudos.
>
> **Links Úteis**:
> - [Como montar a justificativa](https://guiadamonografia.com.br/como-montar-justificativa-do-tcc/)

## Público-Alvo

> Embora a organização seja algo benéfico para todas as aréas da vida e para todas as pessoas em busca de seus objetivos, nosso público alvo com esse trabalho são em  > específico os universitários de todas as faixas etárias e géneros que se encontram com dificuldade em organizar uma rotina de estudos por conta da falta de tempo,    > costume e até disciplina.
> 
> **Links Úteis**:
> - [Público-alvo: o que é, tipos, como definir seu público e exemplos](https://klickpages.com.br/blog/publico-alvo-o-que-e/)
> - [Qual a diferença entre público-alvo e persona?](https://rockcontent.com/blog/diferenca-publico-alvo-e-persona/)
 
# Especificações do Projeto

Durante o processo de entendimento e elaboração do projeto, foi visto que muitos alunos da PUC, universidade com a qual foi utilizada como parâmetro, ficavam muito perdidos com suas atividades e prazos de entrega de trabalhos, e portanto ficavam sobrecarregados. De tal forma, foi elaborado uma pesquisa com alunos da universidade, constatando esse apecto como padrão entre a maioria dos estudante, principalmete observando o seu agravamento com a pandemia, posto que a grande maioria dos alunos do primeiro semestre terminou seu ensino médio sob as circunstâncias de ensino remoto, e isso afetou o compromisso que têm com sua tarejas, visto que na pandemia passaram muito tempo dentro de suas casas, e com poucas obrigações que poderiam ser feitas a qualquer momento sem um controle.

Dessa forma, nessa seção, serpa abordado uma compreensão mais complexa sobre o assunto, utilizando de métodos de entendimento sobre nosso público alvo, através da elaboração de Personas, e seus repectivos mapas de empatia, Histórias de Usuários, além de formas de estabelecer o que for obrigatório em nosso produto final, atraváes da estipulação de Requisitos, os funcionasi e não funcionas, e de Restrições impostas sobre sua execução.

## Personas e Mapas de Empatia

1. **Pedro Santos** tem 22 anos, é um estudante de ciência da computação e não trabalha ainda. Demonstra dificuldade em conciliar tempo com relação às atividades acadêmicas que possui, perdendo a noção sobre prazos e quantidade de exercícios que tem que fazer. De tal forma, apresenta grande quantidade de ansiedade e estresse devido a uma má organização. Por isso, procura encontrar uma plataforma que consiga o ajudar a organizar seu tempo com relação aos conteúdos que tem que estudar e os compromissos que tem que cumprir.
<p align="center">
<img src="https://user-images.githubusercontent.com/113465962/192163081-6bbde266-ea55-40de-becd-2c8f47bdfdc7.jpg" width="700">
</p>

2. **Ana Costa** tem 18 anos, é uma estudante de direito e não trabalha ainda. Apresenta dificuldade em conciliar a quantidade semanal de tempo que ela deve colocar sobre seus estudos com relação ao tempo para seus momentos de lazer. De tal forma, demonstra bastante insegurança e ansiedade sobre o que faz, para além de uma grande quantidade de estresse. Busca conseguir organizar seus horários para que seu estilo de vida se torne mais leve e saudável, porém ainda efetivo.
<p align="center">
<img src="https://user-images.githubusercontent.com/113465962/192101118-861cab81-b163-4bf6-8def-7bfc416c22eb.jpg" width="700">
</p>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Pedro | Registrar minhas atividades e meus trabalhos | Não esquecer de fazê-los |
|Pedro | Organizar meu tempo de estudo | Otimizar meus estudos |
|Ana | Conseguir organizar meus horários para estudar durante o dia | Ter uma maior eficiência sem consumir todo o meu tempo |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Fazer um questionário para conseguir obter informações sobre os horários e forma de se organizar | ALTA | 
|RF-003| Organizar os horários de forma para ser a menor quantidade possível para ser feita por dia   | ALTA |
|RF-004| Disponibilizar informações sobre métodos de melhorar a estilo de vida | MÉDIA | 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O usuário deve conseguir utilizar a plataforma sem nenhum tipo de treinamento | ALTA | 
|RNF-002| Deve ter uma interface fluida e eficiente | ALTA | 
|RNF-003| Deve conseguir ser executado de forma adaptada tanto em computadores desktops quanto em dispositivos móveis como celulares e tablets | BAIXA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O desenvolvimento do site não pode ser delegado / terceirizado        |
|02| O projeto deverá ser entregue até o final do semestre |
|03| Não pode ser desenvolvido em um módulo de backend        |


# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
