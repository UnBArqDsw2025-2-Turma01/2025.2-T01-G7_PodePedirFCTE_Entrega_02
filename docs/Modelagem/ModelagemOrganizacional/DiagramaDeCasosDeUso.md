# Diagrama de Casos de Uso

## Introdução

Diagramas de casos de uso são geralmente chamados de diagramas de comportamento, eles são utilizados ​​para descrever um conjunto de ações (conhecidas por casos de uso) que um ou mais sistemas devem/podem executar em colaboração com um ou mais usuários externos do sistema (atores) [1]. Cada caso de uso deve fornecer algum resultado observável e valioso para os atores ou outras partes interessadas do sistema [1].

## Componentes do Diagrama de Casos de Uso

| **Nome do Componente** | **Significado** | **Representação** |
| :--------------------- | : ------------- | : --------------- |
| Barreira do sistema | A barreira do sistema é representada por um retângulo para separar os casos de uso que são internos do sistema dos atores que são externos do sistema [2]. | <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-barreira.png" title="Componente estado" width=auto> |
| Casos de uso | Um caso de uso descreve uma função que o sistema deve performar para atingir o objetivo do usuário; ele deve gerar um resultado observável que seja valioso para o usuário do sistema [3]. | <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-caso-de-uso.png" title="Componente de inicio" width=auto>  |
| Atores | Um ator representa um papel de um usuário que interage com o sistema que está sendo modelado; ele pode ser um usuário humano, uma organização, uma máquina ou qualquer outro sistema externo [3]. | <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-ator.png" title="Componente final" width=auto>  |
| Relação de inclusão | Uma relação de inclusão é uma relação direcionada entre dois casos de uso, utilizada para mostrar que o comportamento do caso de uso incluído (a adição) é inserido no comportamento do caso de uso que o inclui [4].| <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-include.png" title="Componente final" width=auto>  |
| Representação de extensão | A extensão é um relacionamento direcionado que especifica como e quando o comportamento definido no caso de uso de extensão — geralmente suplementar e opcional — pode ser inserido no comportamento definido no caso de uso estendido [5].| <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-extend.png" title="Componente final" width=auto>  |
| Relação de generalização | A generalização entre casos de uso é semelhante à generalização entre classes: o caso de uso filho herda propriedades e comportamento do caso de uso pai, podendo inclusive substituir seu comportamento [6].| <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-generalizacao.png" title="Componente final" width=auto>  |
| Pontos de extensão | Um ponto de extensão é um recurso de um caso de uso que identifica um ponto no comportamento do caso de uso onde esse comportamento pode ser estendido por algum outro caso de uso (extensível) [6].| <img class="card-img img-fluid rounded" src="./DiagramaDeCasosDeUso/Componentes/representacao-pontos-de-extensao.png" title="Componente final" width=auto>  |

<font size="3">Autor: [Luiz Guilherme](https://github.com/luizfaria1989), 2025.</font>

# Diagrama Produzido
<div style="width: 640px; height: 480px; margin: 10px; position: relative;"><iframe allowfullscreen frameborder="0" style="width:640px; height:480px" src="https://lucid.app/documents/embedded/570ecf74-6248-4340-b38f-22b754ed6db6" id="UeKSK8r~XTxZ"></iframe></div>

<img src="./DiagramaDeCasosDeUso/diagrama-caso-de-uso.png" alt="Diagrama de Casos de Uso" style="max-width:100%; height:auto;">
<div align="center">
  <font size="3">Figura 1 – Diagrama de Casos de Uso do sistema PodePedir</font>
</div>

## Quadro de Participações

| **Membro da equipe** | **Função** |
| :------------- | :--------- |
| [Luiz](https://github.com/luizfaria1989) | Documentação da página de diagrama de casos de uso |
| [Gabriela](https://github.com/gaubiela) | Documentação da página de diagrama de casos de uso |
| [Ana Joyce](https://github.com/anajoyceamorim) | Revisão da documentação da página de diagrama de casos de uso |
| [Ana Clara](https://github.com/anabborges) | Autora do diagrama |
| [Ana Joyce](https://github.com/anajoyceamorim) | Autora do diagrama |
| [Fábio](https://github.com/fabinsz) | Autor do diagrama |
| [Gabriela](https://github.com/gaubiela) | Autora do diagrama |
| [Guilherme Storch](https://github.com/storch7) | Autor do diagrama |
| [Luiz Guilherme](https://github.com/luizfaria1989) | Autor do diagrama |
| [Nathan](https://github.com/Nathan-bs) | Autor do diagrama |
| [Rodrigo](https://github.com/rodrigoFAmaral) | Autor do diagrama |

## Aplicação no projeto

O diagrama de casos de uso será utilizado como ferramenta central para representar as interações entre os atores externos e o sistema PodePedirFCTE. Ele nos permitiu visualizar de forma clara e objetiva quais funcionalidades o sistema deve oferecer e quais perfis de usuário interagem com cada parte do fluxo [1][2][3].

A modelagem foi feita com base nos três principais atores: Aluno (Cliente), Fornecedor (Restaurante) e Entregador, para funções de gestão. Cada caso de uso foi desenhado com foco em entregar valor direto aos usuários [1].

No que se refere ao processo de análise de informações para confecção do artefato, foram levados em consideração os seguintes pontos da primeira entrega:

- [Design Sprint](https://unbarqdsw2025-2-turma01.github.io/2025.2-T01-G7_PodePedirFCTE_Entrega_01/#/./Base/design-sprint/1.1.DesignSprint), com foco na etapa de [prototype](https://unbarqdsw2025-2-turma01.github.io/2025.2-T01-G7_PodePedirFCTE_Entrega_01/#/./Base/design-sprint/1.1.5.Prototype) e [BPNM](https://unbarqdsw2025-2-turma01.github.io/2025.2-T01-G7_PodePedirFCTE_Entrega_01/#/Base/bpmn/1.3.ModelagemBPMN):  Expressam as relações entre atores, bem como suas interações com os protótipos produzidos e seus objetivos finais ao utilizar a plataforma. O diagrama de caso de uso foi obtido por meio da abstração das principais funcionalidades dos atores ao longo do fluxo principal de atividades da plataforma.

---

# Referência Bibliográfica

> [1] UML Diagrams Org. *Use Case Diagrams*. Disponível em: [https://www.uml-diagrams.org/use-case-diagrams.html](https://www.uml-diagrams.org/use-case-diagrams.html). Acesso em: 21 set. 2025.  

> [2] IBM. *Creating use case diagrams*. Disponível em: [https://www.ibm.com/docs/en/rational-soft-arch/9.6.1?topic=diagrams-creating-use-case](https://www.ibm.com/docs/en/rational-soft-arch/9.6.1?topic=diagrams-creating-use-case). Acesso em: 21 set. 2025.  

> [3] IBM. *Use case diagrams*. Disponível em: [https://www.ibm.com/docs/en/rational-soft-arch/10.0?topic=diagrams-use-case](https://www.ibm.com/docs/en/rational-soft-arch/10.0?topic=diagrams-use-case). Acesso em: 21 set. 2025.  

> [4] UML Diagrams Org. *Use case «include» relationship*. Disponível em: [https://www.uml-diagrams.org/use-case-include.html](https://www.uml-diagrams.org/use-case-include.html). Acesso em: 21 set. 2025.  

> [5] UML Diagrams Org. *Use case «extend» relationship*. Disponível em: [https://www.uml-diagrams.org/use-case-extend.html](https://www.uml-diagrams.org/use-case-extend.html). Acesso em: 21 set. 2025.  

> [6] UML Diagrams Org. *Use case generalization*. Disponível em: [https://www.uml-diagrams.org/use-case.html#generalization](https://www.uml-diagrams.org/use-case.html#generalization). Acesso em: 21 set. 2025.  