# POC Stress Test

---

**Objetivo:**  
Desenvolver uma Prova de Conceito (POC) para avaliar a resistência e desempenho de uma pilha tecnológica específica sob condições de carga elevada.

**Componentes da Pilha Tecnológica:**

1. **Python:** A linguagem de programação principal do projeto, conhecida por sua versatilidade e ampla gama de bibliotecas disponíveis.
2. **Flask:** Um microframework web para Python, que será usado para criar a aplicação web. É leve e rápido, ideal para projetos de POC.
3. **SQLAlchemy:** Uma biblioteca ORM (Object Relational Mapper) para Python. Ela permite que os desenvolvedores interajam com bancos de dados usando o paradigma orientado a objetos.
4. **MySQL:** O sistema de gerenciamento de banco de dados relacional escolhido para este projeto. É amplamente utilizado, confiável e compatível com SQLAlchemy.
5. **Kubernetes:** Uma plataforma de código aberto para automatizar a implantação, escalabilidade e operações de aplicações em contêineres. Será usado para orquestrar e gerenciar os contêineres da aplicação, garantindo alta disponibilidade e eficiência.

**Metodologia:**

1. **Desenvolvimento:** Criação de uma aplicação web simples usando Flask, integrada ao MySQL através do SQLAlchemy.
2. **Contêinerização:** A aplicação e o banco de dados serão contêinerizados para garantir portabilidade e facilidade de implantação.
3. **Orquestração:** Utilização do Kubernetes para gerenciar a implantação e escalabilidade da aplicação.
4. **Teste de Stress:** Após a implantação, a aplicação será submetida a uma série de testes de carga para avaliar sua resistência e desempenho sob diferentes condições de estresse.

**Resultado Esperado:**  
Ao final do projeto, espera-se ter uma compreensão clara da capacidade de desempenho e resistência da pilha tecnológica escolhida, bem como quaisquer limitações ou áreas de melhoria identificadas.

---

Esta descrição oferece uma visão geral do projeto "POC Stress Test", detalhando sua finalidade, componentes e metodologia.