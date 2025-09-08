## 🔹 Tipos de Testes

No universo de Quality Assurance (QA), a garantia da qualidade de software vai muito além da simples execução de testes. Cada aplicação possui necessidades específicas, e é fundamental compreender quais tipos de testes aplicar em cada situação para assegurar que o produto final seja confiável, funcional e atenda às expectativas do usuário.

Nesta seção do portfólio, abordarei os principais tipos de testes utilizados na prática de QA, explicando seus objetivos, aplicações e importância no ciclo de desenvolvimento de software. A ideia é demonstrar como cada teste contribui para a detecção de erros, melhoria da performance e entrega de soluções de qualidade.

### - Testes Funcionais

Começaremos abordando os Testes Funcionais, esses testes são importantes, porque ajudam a identificar, de modo mais rápido e eficiente, problemas relacionados aos requisitos de sistema dos softwares. Além disso, focam nas especificações de acordo com a usabilidade do cliente, bem como não faz suposições sobre a estrutura do sistema.

Sabendo da importância dos testes funcionais, vale saber conhecer os seus métodos e como aplicá-los:

Tabela de decisão: Método útil para documentar regras que o sistema terá que cumprir. Assim, essas regras surgem a partir de análises da especificação funcional. Além disso, a identificação de regras de negócio também ajuda a definir as regras para o funcionamento do sistema. Sendo assim, a tabela de decisão tem combinações de verdadeiro e falso para a entrada de informações e para as ações que surgem de cada combinação.

Partição de equivalência: Ocorre a segregação de dados de teste, dividindo-os em diversas partições, chamadas de classes de dados de equivalência. Como o comportamento dos dados em cada partição devem se comportar da mesma forma, é necessário aplicar o teste em apenas uma condição. Por isso, caso uma condição não funcione de maneira correta, nenhuma outra vai funcionar conforme o esperado. Sendo possível encontrar classes de equivalência válidas e inválidas.

Casos de uso: Método que descreve as interações entre os atores, os quais podem ser tanto outros sistemas quanto os usuários. Lembrando que existem condições prévias que os atores precisam atender para que o software funcione adequadamente. Essa técnica termina com condições que consistem nos resultados observáveis, bem como no estado do sistema após ser executado.

Análise do valor limite: Utiliza testes nos limites entre partições. Assim, esse método envolve limites mínimos, máximos, externos e internos, e também valores de erro e valores típicos. Pode constatar erros nos limites dos valores de entrada, fornecendo uma seleção de casos que tenham valores limitantes. Deste modo, a técnica utiliza o pretexto de que se um software não apresenta erros para os valores específicos, então ele vai funcionar adequadamente para quaisquer valores entre os limites.

### - Teste de unidade

Dedica-se a verificar as funcionalidades do software de forma individual. A intenção é garantir que elas passem por testes pelo menos uma vez, com isso, a maior vantagem do teste de unidade é a prevenção de falhas, já que analisa cada uma das funcionalidades.

### - Teste de componentes

Como o próprio nome sugere, esse teste analisa os componentes do software de forma separada, de acordo com as especificações e estrutura de cada funcionalidade. Esses componentes reference as integrações de unidades do software e a interface.

### - Teste de integração

Quando for necessário testar múltiplas unidades juntas para ver se integradas umas às outras funcionam corretamente podemos escrever testes de integração. Um exemplo de teste de integração é ver se um formulário de login funciona (se o componente ''button'' junto com ''input'' e ''form'' vão chamar sua callback se os valores de entrada são válidos).

### - Teste de sistema

O teste de sistema acontece logo após a finalização do sistema. Assim, é possível analisar cada um dos componentes e funcionalidades. O intuito é fazer uma avaliação do software, para atestar que as descrições dos elementos do sistema ocorreram de acordo com as especificações.

### - Teste de aceitação

O objetvio desse teste é verificar se o sistema funciona corretamente, cumprindo as especificações dos requisitos do software. Ele serve para analisar se o software atua de acordo com as regras de negócios determinadas pelo cliente.

### - Teste de regressão

Testa se algo mudou em relação ao que já estava funcionando corretamente, ou seja, é voltar a testar segmentos já testados após uma mudança em outra parte do software. Os testes de regressão devem ser feitos tanto no software quanto na documentação.

### - Testes exploratórios

São uma abordagem de teste em que o testador atua como um ''explorador'' do software, investigando e avaliando o sistema de forma ativa. O testador utiliza sua experiência, conhecimento do domínio e habilidades técnicas para identificar possíveis defeitos e comportamentos inesperados do software.

### - Teste de segurança

Valida a proteção do sistema contra invasões ou acesso não autorizado a informações.

### - Teste de desempenho

Valida o tempo de resposta do sistema para determinadas operações, ferramentas utilizadas: JMeter, Cypress, Selenium e outras.

### - Teste E2E(Ponta a ponta)

Esses testes vão testar se uma funcionalidade completa da sua aplicação está de acordo, idealmente sem nenhum mock utilizado. A ideia é replicar ao máximo a experiência do usuário, como se fosse um robô no lugar dele fazendo as mesmas tarefas e vendo se é possível ou não completar de forma correta.

### - Testes automatizados

Os testes automatizados acontecem como scripts ou programas, com o intuito de colocar o sistema em prática, para testar as funcionalidades e verificar se tudo está de acordo com as especificações dos requisitos. Dessa forma, o maior benefício desse teste é a possibilidade de repeti-los de forma fácil a qualquer momento. Além disso, implementá-lo ajuda a reduzir o tempo de trabalho e, consequentemente, as chances de erros na execução.





