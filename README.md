# DESAFIO-QA-BEEDOO-2026

## 1. Análise da aplicação

A aplicação analisada consiste em um sistema simples de gerenciamento de cursos, permitindo que usuários realizem o cadastro, visualização e exclusão de cursos.

Cada curso pode conter informações como:

- Nome do curso
- Descrição
- Data de início
- Data de término
- Número de vagas
- URL da imagem de capa

O objetivo da aplicação aparenta ser permitir que administradores ou usuários registrem cursos disponíveis e visualizem essas informações em uma lista organizada.

---

# 2. Principais fluxos da aplicação

Durante a exploração da aplicação, foram identificados os seguintes fluxos principais:

### Cadastro de cursos
Permite inserir as informações de um novo curso através de um formulário.

### Listagem de cursos
Após o cadastro, os cursos são exibidos em formato de cartões contendo suas principais informações.

### Exclusão de cursos
Cada curso possui a opção de ser removido da lista através do botão **Excluir**.

---

# 3. Pontos críticos para teste

Durante a análise inicial, alguns pontos foram considerados mais críticos para validação:

- Validação de campos obrigatórios
- Consistência das datas (data de início e término)
- Integridade do número de vagas
- Validação de URLs
- Comportamento do sistema diante de entradas inválidas
- Tratamento de conteúdos maliciosos (HTML ou scripts)
- Comportamento da interface ao lidar com dados extremos
- Funcionamento correto da funcionalidade de exclusão

Esses pontos foram priorizados durante a criação dos cenários de teste.

---

# 4. Cenários e casos de teste

Com base na análise realizada, foram elaborados cenários de teste contemplando:

- Fluxo principal de cadastro de cursos
- Validação da listagem de cursos
- Cenários negativos
- Validação de campos
- Comportamentos inesperados do sistema

Os cenários e casos de teste foram documentados em uma planilha.

📄 **Planilha de Casos de Teste:**  
https://docs.google.com/spreadsheets/d/1I9Of0_7FeF3Nb7PBgPqCd0vBzQPjuoI-AirjNP6AF68/edit?usp=sharing

---

# 5. Execução dos testes

Todos os cenários definidos foram executados diretamente na aplicação.

Durante a execução foram registrados:

- Resultado obtido de cada teste
- Evidências da execução (prints)

📂 **Evidências dos testes:**  
https://drive.google.com/drive/folders/1NN7huDDYRp59GaUlcsSVZkiTPKjqi6gp?usp=drive_link

---

# 6. Bugs encontrados

Durante a execução dos testes foram identificados diversos problemas relacionados a:

- ausência de validação de campos obrigatórios
- aceitação de dados inválidos
- inconsistências na interface
- falha na funcionalidade de exclusão de cursos

Os bugs identificados foram documentados no arquivo:

📄 https://drive.google.com/file/d/1E4Ens5f1HrVqvHWvQ1jG7PmgyBIx6M3a/view?usp=drive_link

---

# 7. Considerações finais

A aplicação apresenta funcionalidades básicas para cadastro e visualização de cursos, porém foram identificadas diversas oportunidades de melhoria relacionadas principalmente à validação de dados e ao tratamento de entradas do usuário.

Recomenda-se a implementação de validações tanto no frontend quanto no backend, além de melhorias no controle da interface para garantir maior integridade dos dados e melhor experiência do usuário.
