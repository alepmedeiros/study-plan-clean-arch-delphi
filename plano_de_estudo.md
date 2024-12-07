# Plano de Estudos: Arquitetura Limpa no Delphi

Este documento organiza o estudo do livro **Arquitetura Limpa**, de Robert C. Martin. O objetivo é compreender os conceitos apresentados, aplicá-los na prática com Delphi, e documentar resumos e exemplos práticos para cada capítulo.

---

## **Estrutura do Plano**

### Semana 1: Fundamentos e Filosofia
- **Capítulos:**   
  1. O que são Design e Arquitetura?  
  2. Um Conto de Dois Valores  
- **Objetivos:**
  - Compreender a diferença entre design e arquitetura.
  - Refletir sobre os dois valores do software: comportamento e estrutura.  
- **Tarefas Práticas:**
  - Criar um exemplo em Delphi que demonstre a separação de design e arquitetura.
  - Documentar como ambos impactam a manutenção e a evolução do sistema.

---

### Semana 2: Paradigmas da Programação - Parte I
- **Capítulos:**   
  3. Panorama do Paradigma  
  4. Programação Estruturada  
- **Objetivos:**
  - Revisar os paradigmas de programação e sua evolução.  
  - Aplicar conceitos de programação estruturada em Delphi.  
- **Tarefas Práticas:**
  - Implementar um fluxo estruturado usando Delphi.
  - Comparar programação estruturada com programação orientada a objetos.

---

### Semana 3: Paradigmas da Programação - Parte II
- **Capítulos:**    
  5. Programação Orientada a Objetos  
  6. Programação Funcional  
- **Objetivos:**
  - Explorar programação orientada a objetos (POO) e funcional.  
  - Aplicar conceitos básicos de funcionalidade imutável no Delphi.  
- **Tarefas Práticas:**
  - Criar classes e objetos utilizando POO em Delphi.
  - Experimentar lambdas e funções inline no Delphi.

---

### Semana 4: Princípios de Design - Parte I
- **Capítulos:**    
  7. SRP: O Princípio da Responsabilidade Única  
  8. OCP: O Princípio do Aberto/Fechado  
- **Objetivos:**
  - Compreender os primeiros princípios SOLID e aplicá-los em projetos reais.  
- **Tarefas Práticas:**
  - Refatorar uma classe existente para seguir SRP.
  - Implementar extensibilidade seguindo o princípio OCP.

---

### Semana 5: Princípios de Design - Parte II
- **Capítulos:**    
  9. LSP: O Princípio de Substituição de Liskov  
  10. ISP: O Princípio da Segregação de Interface  
  11. DIP: O Princípio da Inversão de Dependência  
- **Objetivos:**
  - Finalizar o estudo dos princípios SOLID.
  - Aplicar ISP e DIP em um projeto Delphi.  
- **Tarefas Práticas:**
  - Criar interfaces segregadas para diferentes responsabilidades.
  - Implementar injeção de dependência no Delphi.

---

### Semana 6: Princípios dos Componentes
- **Capítulos:**    
  12. Componentes  
  13. Coesão de Componentes  
  14. Acoplamento de Componentes  
- **Objetivos:**
  - Estudar como organizar componentes coesos e desacoplados.
  - Aplicar conceitos de coesão e desacoplamento em projetos reais.  
- **Tarefas Práticas:**
  - Modularizar um projeto Delphi existente.
  - Refatorar dependências entre componentes para minimizar acoplamento.

---

### Semanas 7 a 10: Arquitetura
#### Semana 7: Fundamentos da Arquitetura
- **Capítulos:**    
  15. O que é Arquitetura?  
  16. Independência  
- **Objetivos:**
  - Explorar o papel da arquitetura no desenvolvimento de software.
  - Entender como a independência torna sistemas mais flexíveis.  
- **Tarefas Práticas:**
  - Criar fronteiras de dependências em um projeto Delphi.

#### Semana 8: Fronteiras e Limites
- **Capítulos:**    
  17. Fronteiras: Estabelecendo Limites  
  18. Anatomia do Limite  
  19. Política e Nível  
- **Objetivos:**
  - Estabelecer limites claros na arquitetura.
  - Diferenciar políticas de implementação.  
- **Tarefas Práticas:**
  - Implementar camadas com limites definidos.

#### Semana 9: Arquitetura Limpa
- **Capítulos:**    
  20. Regras de Negócio  
  21. Arquitetura Gritante  
  22. Arquitetura Limpa  
- **Objetivos:**
  - Compreender e aplicar os princípios da Arquitetura Limpa.
- **Tarefas Práticas:**
  - Refatorar um projeto existente usando os conceitos de Arquitetura Limpa.

#### Semana 10: Casos Avançados
- **Capítulos:**    
  23. Apresentadores e Objetos Humble  
  24. Limites Parciais  
  25. Camadas e Limites  
  26. O Componente Main  
- **Objetivos:**
  - Explorar padrões e detalhes avançados de arquitetura.
  - Implementar apresentadores e limites parciais.  

---

### Semanas 11 a 12: Detalhes
#### Semana 11: Detalhes Técnicos
- **Capítulos:**    
  30. A Base de Dados é um Detalhe  
  31. A Web é um Detalhe  
  32. Frameworks são Detalhes  
- **Objetivos:**
  - Tratar bancos de dados, web e frameworks como detalhes na arquitetura.  
- **Tarefas Práticas:**
  - Criar abstrações para banco de dados e frameworks.

---

## **Recursos Adicionais**
- [Documentação oficial do Delphi](https://www.embarcadero.com)
- [Artigos sobre SOLID e Arquitetura Limpa](./recursos/solid.md)
- Diagrama de camadas: [arquitetura_limpa_diagrama.pdf](./recursos/arquitetura_limpa_diagrama.pdf)

---

## **Próximos Passos**
1. Crie as pastas no repositório:
   - `/capitulos` para resumos de cada capítulo.
   - `/projetos` para armazenar o código do projeto prático.
   - `/recursos` para referências e materiais adicionais.
2. Inicie com os resumos:
   - Documente o **Capítulo 1: O que são Design e Arquitetura?** usando o modelo sugerido.
3. Defina o projeto prático:
   - Escolha um domínio (ex.: sistema ERP).
   - Estruture as camadas e entidades principais.

---

Este plano serve como guia para organizar e acompanhar o estudo do livro. Atualize regularmente com reflexões, resumos e avanços no projeto prático.
