# Capítulo 4: Programação Estruturada

## Resumo
Neste capítulo, o autor explora a origem e os fundamentos da programação estruturada, começando pelas contribuições de Edsger Wybe Dijkstra. Ele destaca a importância desse paradigma na decomposição funcional e na criação de módulos testáveis, enquanto aborda a evolução histórica e as restrições impostas pela programação estruturada.

## Pontos Principais:
  - **Prova:**   
    Dijkstra identificou a dificuldade de programadores lidarem com a complexidade dos sistemas e propôs a aplicação de uma disciplina matemática baseada em provas. Ele percebeu que estruturas simples de controle, em oposição ao uso irrestrito de goto, permitiam decompor problemas em unidades comprováveis.

  - **Declaração Go To Considerada Prejudicial:**  
    A famosa carta de Dijkstra enfatizou os problemas do uso indiscriminado de goto, marcando o início de uma abordagem mais disciplinada na programação.

- **Decomposição Funcional:**   
    A programação estruturada promove a decomposição funcional, permitindo que problemas complexos sejam subdivididos em funções de alto nível.

  - **Testes:**
    Dijkstra observou que "os testes mostram a presença, não a ausência, de bugs," reforçando a necessidade de criar módulos que possam ser testados de maneira eficaz.

## Conclusão do Autor:
  - A programação estruturada é fundamental para a criação de unidades de código testáveis e bem definidas.
  - No nível arquitetural, a decomposição funcional continua sendo uma prática essencial para modularidade e testabilidade.
  - A programação estruturada serve como base para as disciplinas mais amplas e restritivas que serão estudadas nos capítulos seguintes.

## Reflexões Pessoais
- A programação estruturada foi um divisor de águas ao introduzir práticas que reduziram a complexidade no desenvolvimento de software.
- A eliminação do uso irrestrito de `goto` e a promoção da decomposição funcional permitiram uma abordagem mais científica e previsível no desenvolvimento.
- Embora a "prova formal" de Dijkstra não tenha sido amplamente aplicada, sua ênfase na criação de módulos comprováveis continua influenciando as melhores práticas.

## Aplicação Prática
Para aplicar os conceitos deste capítulo:

1. **Decomposição Funcional:**
    - Analise problemas complexos e decomponha-os em funções de alto nível com responsabilidades claras.
    - Evite funções monolíticas e excessivamente longas.
2. **Testabilidade:**
    - Estruture o código para garantir que cada módulo ou função possa ser testado isoladamente.
    - Adote práticas de teste como TDD (Test-Driven Development) para validar comportamento.
3. **Disciplina Estrutural:**
    - Evite desvios arbitrários no fluxo de execução.
    - Utilize estruturas de controle claras e previsíveis (ex.: if, while, for).
## Próximo Passo
O próximo capítulo aborda a **Programação Orientada a Objetos**, explorando como este paradigma complementa a programação estruturada e promove a modularidade e a abstração.