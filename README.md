# Informações do Projeto
`Como Criar Bons Hábitos`  

Ciências da Computação PUC-MINAS



## Participantes

Os membros do grupo são: 
- João Pedro Moura
- Lucas Galtieri
- Samuel Penido
- Júlia Sebastião
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
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

A vida universitária e escolar demanda dos estudantes uma gestão de tempo e organização com os estudos. Levando em conta que aproximadamente 4% de toda a população do país sofre de TDAH ( transtorno do déficit de atenção com hiperatividade ) tornase ainda mais dificil o foco e organização com tarefas e estudos diários presentes na rotina de um universitario.

Uma rotina organizada, com boa gestão de tempo traz para o estudante uma constância maior em seus estudos, melhor aprendizado e convívio com as matérias. 

## Problema

A desorganização e falta de gestão de tempo é um problema que afeta a vida da maioria das pessoas, pequenos atrasos, desvios de atenção e claro... redes sociais, podem te distrair por horas e passar em “um piscar de olhos”. Esses pequenos “atrasos” podem te tirar do objetivo por horas quando somadas no final do dia, causando assim uma falsa sensação de falta de tempo, causando estresse, cansaço e falta de produtividade.

## Objetivos

Tendo em vista a problemática, o projeto tem como objetivo facilitar o aprendizado e organização da rotina estudantil, sabemos o quão puxada a rotina de estudos pode ser, e para isso buscamos desenvolver uma plataforma que irá auxiliar na rotina e organização para melhor aprendizado.

Objetivos específicos :
- Ajudar o estudante a se organizar melhor com seus horarios.
- Desenvolver uma agenda virtual com lembretes e dicas.
- Montar uma rotina e plano de estudo para o aluno.
- Ajudar o estudante a se preparar de forma constante nos estudos, tornando a rotina constante, pórem leve.
- Disciplina do aluno nos momentos de estudo com um cronograma único.

## Justificativa

De acordo com os dados fornecidos pelo MEC (Ministério da Educação) o brasil tem mais de 6,5 milhões de universitários. Levando como exemplo o curso de direito que hoje é o curso com mais alunos em todo o brasil, apenas 31,4% dos alunos que participaram da prova de Exame da Ordem Unificado 2021/2 (EOU) promovido pelo Conselho Federal da OAB foram aprovados (maior percentual de aprovação da história). Acreditamos que para tal feito ser conquistado pelo estudante foi-se necessário uma boa organização e disciplina em uma rotina de estudos.

## Público-Alvo

Embora a organização seja algo benéfico para todas as aréas da vida e para todas as pessoas em busca de seus objetivos, nosso público alvo com esse trabalho são em específico os universitários de todas as faixas etárias e géneros que se encontram com dificuldade em organizar uma rotina de estudos por conta da falta de tempo, costume e até disciplina.
 

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
|RF-001| Fazer um questionário para conseguir obter informações sobre os horários e forma de se organizar  | MÉDIA |
|RF-002| Cadastrar as tarefas a serem organizadas | ALTA |
|RF-003| Mostrar as terefas que foram cadastradas | ALTA |
|RF-004| Disponibilizar na home as tarefas que devem ser executadas no dia | MÉDIA | 
|RF-005| Possibilitar a alteração de dados já cadastrados em um perfil | MÉDIA | 
|RF-006| Apresentar um lembrete ao usuário de suas tarefas cadastradas | ALTA | 
|RF-007| Apresentar uma calendário que mostre as datas de entrega conforme elas sejam salvas de forma dinâmica | BAIXA | 
|RF-008| Mostrar os resultados obtidos no questionário feito | MÉDIA | 
|RF-009| Possibilitar uma pesquisa seguindo o nome cadastrado na tarefa | MÉDIA | 
|RF-010| Poaaibilitar uma pesquisa seguindo a matéria cadastrada na tarefa | MÉDIA | 

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

A Home-Page:
A nossa aplicação se dá num site, a Home-Page introduz as funcionalidades, aponta as vantagens de usar a nossa plataforma e introduz os alunos envolvidos. É a partir da home que se acessa as funcionalidades, mas antes o usuário precisa se logar ou então, se registrar caso não já não tenha um cadastro. É importante ressaltar que caso o usuário já esteja logado ele terá acesso direto ao ‘Painel de Controle’.

O Painel de Controle:
O painel de controle é a parte principal do site, é nele que o usuário adiciona suas matérias e tarefas. Essa etapa é a mais importante, pois é a partir das informações adicionadas pelo usuário que o cronograma de estudos será gerado. É no painel de controle que o usuário consegue saber sua progressão numa determinada matéria ou tarefa, através de um sistema visual de barras de progresso.

A aba ‘Hoje’:
A aba ‘Hoje’ é uma aba essencialmente de visualização. Toda a nossa aplicação parte do princípio de que a chave para não se deixar acumular muitas obrigações é a distribuição de uma determinada tarefa ao longo de seu prazo, realizando-a em pequenas partes diárias. Sendo assim, para que o aluno não se sinta sobrecarregado a aba hoje é uma das mais úteis, pois o aluno só terá que se preocupar com o que tem que ser feito naquele dia.

O resto:
O site conta com outras páginas auxiliares como o calendário, que mostra as atividades agendadas para todos os dias seguintes e a aba ajuda que auxilia o usuário a tirar máximo proveito das ferramentas do site.

## User Flow

![FLUXO DO USUARIO](https://user-images.githubusercontent.com/42350002/192174095-225e06b4-64a0-4395-ac9d-77a9a0c8e86d.png)

## Wireframes

Protótipos do Design/Layout da nossa aplicação:

![WIREFRAMES](https://user-images.githubusercontent.com/42350002/192174853-6f72714c-1f79-4999-bbb4-1a5aa4368104.png)

Protótipo interativo: https://marvelapp.com/prototype/65f324d/screen/88816196


# Metodologia

Para melhor elaboração do projeto, o grupo se utilizou de diversos encontros, que ocorreram através de "chamadas" no aplicativo Discord. Dessa forma, foi preenchido a idealização do trabalho, pelo processo de Design Thinking, em que todos os membro participaram, dando suas visões e opiniões sobre o problema a ser resolvido. Ademais, também foram observadas as etapas - o caminho - que serão necessárias para formular a solução, seguindo as restrições impostas no trabalho e as capacidades (habilidades) de cada um dos integrantes. Para tal, várias reuniões foram, para que fossem observados os avançoes de cada participante, a cada 2 dias, ou seja, eram feitas em dias alternados, com a participação de todos.

Assim sendo, nessa seção, será abordado a divisão de tarefas propostas e cumprídas pelos integrantes do grupo, assim como será apresentado as ferramentas utilizadas na concepção do trabalho.

## Divisão de Papéis

Durante o projeto, o grupo se redividiu em 2 duplas além de outras duas pessoas que fizeram seu trabalhos sozinhos.

A divisão foi:
- Dupla 1: João e Lucas → responsáveis pela elaboração do tópico Projeto de Interfaces, inlcuindo o uso de wireframes e fluxo do usuário.
- Dupla 2: Júlia e Álvaro* → responsáveis pela parte Especificação de Projetos, incluido fazer as pesquisas qualitativas e criar as personas.
- Gabriel → responsável pela divisão e formatação da apresentação.
- Samuel → responsável pela concepção da Introdução do documento, incluindo todos os seus tópicos internos.

## Ferramentas

As ferramentas utilizadas pelo grupo na elaboração do trabalhor foram as listadas abaixo.

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/app/board/uXjVPXoRt6Y=/ | 
|Repositório de código | GitHub | https://github.com/ICEI-PUC-Minas-PPLCC-TI/tiaw-ppl-cc-m-20222-07-criar-bons-habitos | 
|Protótipo Interativo | MavelApp ou Figma | https://marvelapp.com/prototype/65f324d | 

## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o [Git](https://git-scm.com/), sendo que o [Github](https://github.com) foi utilizado para hospedagem do repositório `upstream`.

O projeto segue a seguinte convenção para o nome de branchs:
 
- `master`: versão estável já testada do software
- `unstable`: versão já testada do software, porém instável
- `testing`: versão em testes do software
- `dev`: versão de desenvolvimento do software
 
Quanto à gerência de issues, o projeto adota a seguinte convenção para etiquetas:

- `bugfix`: uma funcionalidade encontra-se com problemas
- `enhancement`: uma funcionalidade precisa ser melhorada
- `feature`: uma nova funcionalidade precisa ser introduzida


# Projeto da Solução

## Tecnologias Utilizadas

| TIPO | NOME |
|------|------|
| Linguagem de marcação | HTML |
| Linguagem de estilo | CSS |
| Linguagem de programação | JavaScript |
| Framework | Bootstrap |
| Biblioteca | jQuery |
| IDE | Visual Studio Code |
| Versionamento de código | Git |
| Controle de versão compartilhado | GitHub |
| Hospedagem | GitHub Pages |

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

## Plano de Testes

| ID | CENÁRIO | REQUISITO RELACIONADO |
|----|---------|-----------------------|
| 01 | `Quiz` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-001 |
| 02 | `Cadastro de tarefas` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-002 |
| 03 | `Apresentação de terefas` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-003 |
| 04 | `Tela "HOJE"` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-004 |
| 05 | `Editar Perfil` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-005 |
| 06 | `Apresentaçã de lembretes` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-006 |
| 07 | `Apresentação de um calendário` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-007 |
| 08 | `Apresentação resultado do quiz` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-008 |
| 09 | `Pesquisa (filtro) por tarefa` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-009 |
| 10 | `Pesquisa (filtro) por matéria` <br><br> Passo a passo: <br> `1.` ---- <br> `2.` ---- <br> `3.` ---- <br> `4.` ---- <br><br> Após clicar no botão. | RF-010 |

## Registros de Testes

| ID | REQUISITO RELACIONADO | RESULTADO OBTIDO |
|----|-----------------------|------------------|
| 01 | RF-001 | Página Funcional |
| 02 | RF-002 | Página Funcional |
| 03 | RF-003 | Página Funcional |
| 04 | RF-004 | Página Funcional |
| 05 | RF-005 | Página Funcional |
| 06 | RF-006 | Página Funcional |
| 07 | RF-007 | Página Funcional |
| 08 | RF-008 | Página Funcional |
| 09 | RF-009 | Página Funcional |
| 10 | RF-010 | Página Funcional |

## Referências

A lista a seguir traz as referências utilizadas nesse trabalho. são elas :

- http://portal.mec.gov.br/component/tags/tag/32044-censo-da-educacao-superior#:~:text=O%20Brasil%20tem%206%2C5,173%20mil%20na%20p%C3%B3s%2Dgradua%C3%A7%C3%A3o.
- 
