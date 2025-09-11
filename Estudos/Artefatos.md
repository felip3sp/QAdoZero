# 🧾 Artefatos de teste

Os artefatos de teste são parte essencial do processo de qualidade de software. Eles podem ser compreendidos tanto dentro do SDLC (Ciclo de Vida do Desenvolvimento de Software), como entregáveis do projeto, quanto dentro do STLC (Ciclo de Vida do Teste de Software), como registros criados especificamente durante a execução dos testes.

Esses artefatos incluem documentos como plano de teste, casos de teste, relatórios de defeitos e métricas de execução. Sua função é registrar quais testes foram realizados, como foram conduzidos e quais resultados foram encontrados, permitindo transparência, rastreabilidade e acompanhamento do progresso.

Além de facilitar o gerenciamento e a revisão do trabalho de teste, eles servem como evidência formal do processo de QA, garantindo que o produto final atenda aos requisitos de negócio e seja entregue com qualidade.

---

### Estratégia de teste

Estratégia de teste é um documento de alto nível (documento estático) que descreve a abordagem de teste, incluindo os objetvios, recursos, cronograma e escopo das atividades de teste. Geralmente é desenvolvido por um gerente de projeto. É um documento que captura a abordagem de como testamos o produto e atingimos os objetivos. Fornece fácil compreensão de destinos, ferramentas, técnicas, infraestrutura e tempo de atividades de teste que devem ser executadas. É usado para identificar todos os fatores de risco que podem surgir durante o teste e a solução apropriada para reduzir ou mitigar o risco. A estratégia de teste geralmente é derivada do Formato de Especificação de Requisitos de Negócios. Para desenvolver essa estratégia, há vários pontos que precisam ser lembrados, como:

- Qual é o objetivo principal do teste?
- Quais diretrizes precisam ser seguidas?
- Quais requisitos são necessários (funcionais, cenários de teste, recursos, etc)?
- Quais são os papéis e responsabilidades de cada função e do gerente do projeto?
- Quais são os diferentes níveis de teste?
- Qual será o principal entregável desse teste?
- Quais riscos existem em relação ao teste e ao projeto?
- Há métodos para resolver problemas que possam surgir?

---

### Plano de teste

O plano de teste é um documento detalhado que descreve o escopo do teste de software, a estratégia, os entregáveis, os riscos, os objetivos e as atividades. É uma abordagem sistêmica geralmente usada para o teste de aplicações de software. É essencial para garantir que exista uma lista inicial de tarefas e marcos no plano base, a fim de rastrear e identificar o progresso do projeto.
Diferente da estratégia de teste, o plano de teste é um documento dinâmico que serve como ponto de referência para a equipe de QA. Ele funciona como um ''mapa'' que explica como as atividades de teste serão realizadas no projeto.
Pontos principais a considerar:

- Qual é o propósito principal das atividades de teste?
- Qual é o escopo futuro dos testes (caminho a seguir)?
- Qual é a abordagem de teste (como será conduzido)?
- Quais recursos são necessários?
- Quais são os critérios de saída após a conclusão do teste?
- Como os riscos serão gerenciados?

---

### Cenário de teste

Um cenário de teste é uma declaração usada para descrever uma funcionalidade da aplicação que pode ser testada. Ele garante que o teste ponta a ponta de uma funcionalidade ou software está funcionando corretamente.
É derivado dos casos de uso e contém situações ou condições na aplicação a partir das quais vários casos de teste podem ser desenvolvidos. Também é chamado de Condição de Teste ou Possibilidade de Teste.
Um único cenário pode incluir vários casos de teste, ou seja, existe uma relação de um-para-muitos entre eles.

Diferença entre Cenário de teste e Caso de teste: o cenário é genérico, enquanto o caso é detalhado e contém passos, dados e resultados esperados.

---

### Caso de teste

O caso de teste é um documento detalhado que descreve os passos que ajudam na execução durante o teste. Ele contém o nome do caso de teste, pré-condições, passos/condições de entrada e os resultados esperados.
Casos de teste bem desenvolvidos ajudam a identificar ou rastrear problemas nos requisitos ou no design do software.
Eles representam um conjunto de condições ou variáveis sob as quais o testador verificará se o sistema em teste atende aos requisitos e funciona corretamente.
Para escrever um bom caso de teste, recomenda-se:

- Atribuir um ID único.
- Definir um nome claro e forte.
- Descrever detalhadamente o caso.
- Listar os passos de forma clara e concisa.
- Registrar os resultados esperados e/ou reais.

---

### Matriz de rastreabilidade

A matriz de rastreabilidade é um documento em forma de tabela que mostra os relacionamentos muitos-para-muitos entre requisitos e casos de teste. Ela garante transparência e completude no processo de testes, mapeando todos os requisitos do cliente com os casos de teste e identificando defeitos.

Tipos:
- Matriz de rastreabilidade direta (Forward)
- Matriz de rastreabilidade reversa (Backward)

Parâmetros comuns incluídos:
- ID do requisito
- Tipo e descrição do requisito
- Status do design e da execução do teste
- Casos de teste de sistema e unitários

---

### Relatório de teste de software

É o documento que descreve todas as atividades de teste. Ele fornece informações detalhadas sobre o status dos casos de teste, suítes de teste ou scripts de teste em um determinado escopo. O relatório de teste é necessário para representar os resultados de maneira formal e rápida, ajudando a identificar os resultados de forma objetiva.

Tipos:
- Relatório individual de teste
- Relatório de equipe

Eles podem ser gerados diariamente, após a conclusão do teste ou no fim do ciclo de testes.

---

### Relatório de defeitos (Bug Report)

O objetivo é registrar informações detalhadas (como ambiente, passos para reproduzir etc) sobre o defeito, facilitando a reprodução do bug pelos desenvolvedores.

