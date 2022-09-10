# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:


Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

## Requisitos

Abaixo as tabelas detalham todos os requisitos funcionais e não funcionais do projeto de seguro para aparelhos celulares.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve conter e permitir ao usuário a realização de uma cotação de seguro de forma precisa e sem complexidade. | ALTA | 
|RF-002| A aplicação deve permitir que o usuário realize o seu cadastro a partir dos seus dados pessoais e os dados do seu smartphone (ano de fabricação, modelo, marca e tempo de uso).   | ALTA |
|RF-003| A aplicação deve permitir que o usuário acesse sua área do cliente a partir do uso de login e senha. | ALTA | 
|RF-004| A aplicação deve mostrar para usuários logados suas mensalidades a vencer (se houver um plano adquirido). | MÉDIA | 
|RF-005| A aplicação deve entregar a visualização das informações sobre a empresa e sua história ao usuário. | BAIXA | 
|RF-006| A aplicação deve permitir que os usuários cadastrados avaliem a qualidade do serviço prestado. | MÉDIA | 
|RF-007| A aplicação deve mostrar em sua tela inicial alguns tipos de coberturas que a empresa oferece. | BAIXA | 
|RF-008| A aplicação deve permitir ao usuário cadastrado que edite suas informações de cadastro pessoal. | MÉDIA | 
|RF-009| Após a realização da cotação, a aplicação deve direcionar o usuário diretamente para o whatsapp com algum atendente para finalizar a contratação do seguro. | ALTA | 
|RF-010| A aplicação deve mostrar os dados de contato da empresa para solicitação de assistência técnica imediata e transferir o usuário para o atendimento 24 horas (WhatsApp). | ALTA | 

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deverá ser responsivo permitindo a visualização em um mobile de forma adequada e compreensiva. | ALTA | 
|RNF-002| A aplicação deve ter bom nível de contraste entre os elementos da tela em conformidade. |  MÉDIA | 
|RNF-003| A aplicação deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) |  ALTA | 
|RNF-004| A aplicação não deve revelar nenhuma informação pessoal dos clientes como por exemplo o CPF |  MÉDIA | 
|RNF-005| A aplicação deve processar o calculo da cotação em até 5 segundos |  BAIXA | 
|RNF-006| A aplicação deve ser desenvolvida nas linguagens JavaScript, HTML, CSS. (Front-End) |  ALTA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| A aplicação deverá ser entregue no final do semestre letivo, não podendo extrapolar o mês de novembro. |
|02| A aplicação deve se restringir às tecnologias básicas da Web no Frontend e Backend.       |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho.       |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.


## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
