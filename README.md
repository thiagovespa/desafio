# Desafio Técnico: Sistema de Gerenciamento de Tarefas

## Instruções Gerais

1. **Fork do Repositório:**
   - Para iniciar o desafio, realize um fork neste [repositório](https://github.com/thiagovespa/desafio).

2. **Commit no Fork:**
   - O desafio deve ser commitado no fork.

3. **Pull Request:**
   - Após a conclusão do desafio, por favor, solicite um pull request do fork para este repositório ;)

4. **Objetivo:**
   - O objetivo é você ter um feedback dos seus entregáveis e servir de referência para possíveis recrutadores e empresas.

---

## Desafio Técnico

### Visão Geral

O desafio técnico proposto envolve o desenvolvimento de um sistema de gerenciamento de tarefas. A seguir, você tem uma descrição geral do desafio e depois a descrição específica para cada perfil. Nem todas as informações estarão disponíveis aqui e você não precisa considerar todos os requisitos, use sua criatividade e descreva suas suposições.

**1. Introdução**

O Sistema de Gerenciamento de Tarefas (SGT) é uma aplicação destinada a organizar e facilitar o acompanhamento de atividades diárias para indivíduos e equipes. Este documento descreve os requisitos básicos para o desenvolvimento bem-sucedido do SGT.

**2. Requisitos Funcionais**

**2.1 Cadastro de Tarefas**
- O sistema deve permitir a criação de tarefas, incluindo título, descrição, status (pendente, em andamento, concluída), estimativa e prazo.
- Deve ser possível associar tarefas a projetos específicos.

**2.2 Atribuição de Responsabilidades**
- Os usuários devem poder atribuir tarefas a membros específicos da equipe.
- Cada tarefa deve exibir claramente o responsável pela sua execução.

**2.3 Priorização de Tarefas**
- O sistema deve oferecer a capacidade de atribuir prioridades a cada tarefa.
- As tarefas devem ser exibidas ordenadas de acordo com suas prioridades.

**2.4 Acompanhamento do Progresso**
- Deve ser possível marcar tarefas como concluídas.
- O sistema deve calcular e exibir o progresso geral do projeto com base nas tarefas concluídas.

**2.5 Categorização e Organização**
- Os usuários devem poder categorizar tarefas por projetos, datas ou prioridades.
- O sistema deve fornecer opções de filtragem e pesquisa para facilitar a localização de tarefas específicas.

**2.6 Colaboração**
- Os membros da equipe devem poder adicionar comentários e compartilhar arquivos relacionados a uma tarefa.
- O sistema deve notificar os usuários sobre atualizações nas tarefas.

**2.7 Automação de Lembretes**
- O sistema deve enviar lembretes automáticos para usuários sobre tarefas com prazos iminentes.
- Deve ser possível personalizar configurações de lembretes para cada usuário.

**3. Requisitos Não Funcionais**

**3.1 Interface Intuitiva**
- O sistema deve apresentar uma interface de usuário intuitiva e amigável.
- Deve ser acessível por meio de navegadores web e/ou dispositivos móveis.

**3.2 Desempenho**
- O SGT deve oferecer tempos de resposta rápidos, mesmo quando usado por grandes equipes e com grande volume de dados.

**3.3 Segurança**
- Os dados do sistema devem ser protegidos por meio de autenticação segura.
- Deve haver permissões de acesso para garantir a confidencialidade das informações.

**3.4 Escalabilidade**
- O sistema deve ser projetado para escalabilidade, podendo suportar o aumento no número de usuários e tarefas.

**4. Exemplo de uma possível tela do sistema**

```plaintext
=======================================================
          Sistema de Gerenciamento de Tarefas
=======================================================

Projeto: [Nome do Projeto]

-----------------------------------------------------------
| ID  | Título               | Status       | Responsável |
-----------------------------------------------------------
| 001 | Desenvolver Frontend | Em Andamento | João        |
| 002 | Implementar API      | Pendente     | Maria       |
| 003 | Testes de Usuário    | Concluída    | Ana         |
-----------------------------------------------------------

```

**4. Considerações Finais**

Este documento de requisitos serve como guia para o desenvolvimento do Sistema de Gerenciamento de Tarefas. Caso haja necessidade de informações adicionais ou se julgar necessário incluir algo, sinta-se à vontade para fazer suposições e documentá-las.

### Desafios por Perfil

### Analista de Requisitos

#### Descrição Específica:

Como Analista de Requisitos, o papel é criar uma especificação detalhada para o sistema de gerenciamento de tarefas. Isso deve incluir requisitos funcionais e não funcionais, bem como cenários de uso. Leve em conta diferentes atores, como usuários e administradores, e defina casos de uso para as principais funcionalidades.

Considere:
- Elaborar o Documento de Requisitos do Sistema (DRS), incluindo requisitos funcionais, requisitos não funcionais, casos de uso e diagramas de fluxo.
- Descrever cenários de uso e casos de teste derivados dos requisitos.
- Criar diagramas de fluxo de processos para representar visualmente a sequência de atividades e interações do sistema.
- Identificar pontos de integração com outros processos ou sistemas.
- Desenvolver protótipos de baixa fidelidade para validar conceitos e fluxos de trabalho com os usuários.

### Analista de Testes

#### Descrição Específica:

Como Analista de Testes, o foco é garantir a qualidade do sistema. Deve ser elaborado um plano de teste abrangente, incluindo testes de unidade, integração e sistema. Identifique casos de teste prioritários para cenários normais e situações de erro.

Considere:
- Desenvolver um plano de testes, incluindo estratégias, abordagens de teste, cronograma e recursos necessários.
- Definir critérios de aceitação para os testes.
- Criar casos de teste com base nos requisitos do sistema, cobrindo diferentes cenários de uso.
- Incluir casos de teste para verificar a funcionalidade, desempenho, segurança e outros requisitos não funcionais.
- Implementar casos de teste de acordo com o plano de testes.
- Avaliar a viabilidade da automação de testes e implementar scripts de teste automatizados quando apropriado.
- Documentar supostos defeitos encontrados durante os testes (para o desafio, use a criatividade).
- Descrever possíveis testes de desempenho para avaliar a capacidade do sistema sob diferentes cargas e condições.
- Descrever possíveis testes de segurança para identificar vulnerabilidades e garantir a proteção dos dados.

### Desenvolvedor Backend

#### Descrição Específica:

Como Desenvolvedor Backend, concentre-se na implementação da API RESTful utilizando uma tecnologia adequada (por exemplo, Java Spring Boot, .Net Framework ou tecnologia equivalente). Além dos requisitos gerais, priorize a eficiência e a segurança da API.

Considere:
- Projetar a arquitetura do backend, incluindo a estrutura de bancos de dados, APIs e lógica de negócios.
- Realizar tratamento de erros e exceções.
- Utilizar clareza e clean code no desenvolvimento da solução.
- Escolher tecnologias apropriadas para suportar os requisitos funcionais e não funcionais.
- Escrever código para implementar a lógica de negócios do SGT, garantindo que as funcionalidades se alinhem com os requisitos.
- Documentar claramente as APIs para facilitar o uso por parte dos desenvolvedores frontend.
- Projetar e implementar esquemas de banco de dados que atendam aos requisitos de armazenamento de dados do SGT.
- Desenvolver testes unitários para garantir que cada componente do backend funcione conforme esperado.

### Desenvolvedor Frontend/Mobile

#### Descrição Específica:

Como Desenvolvedor Frontend, a tarefa é criar um front-end adequado aos requisitos para interagir com a API. Utilize um framework moderno (por exemplo, React, Vue, Angular ou Mobile) e garanta uma interface de usuário intuitiva e atraente.

Considere:
- Realizar uso semântico do HTML, se for Web.
- Implementar uma boa estruturação do layout e tags CSS, se for Web.
- Desenvolver componentes reutilizáveis para promover a consistência na interface do usuário.
- Desenvolver um layout acessível (WCAG) e responsivo.
- Implementar testes de interface do usuário para garantir que a funcionalidade da interface seja consistente e sem erros.
- Utilizar mocks ou [APIs públicas](https://github.com/public-apis/public-apis).

### Desenvolvedor Fullstack

#### Descrição Específica:

Realize os desafios de backend e frontend.

Considere:
- Implementar uso de WebSocket.

### Analista UX/UI

#### Descrição Específica:

Como Analista UX/UI, concentre-se em redesenhar a interface de usuário do sistema, focando na usabilidade, acessibilidade e design responsivo. Realize pesquisas de usuário, crie wireframes e protótipos interativos. Utilize seus amigos e familiares para as pesquisas.

Considere:
- Conduzir pesquisas para compreender as necessidades, expectativas e comportamentos dos usuários.
- Avaliar a usabilidade do SGT por meio de testes de usabilidade, análise heurística e outros métodos.
- Criar personas representativas dos usuários finais do SGT, destacando suas características, necessidades e objetivos.
- Mapear jornadas do usuário para entender os fluxos e interações durante o uso do sistema.
- Criar wireframes e protótipos de baixa fidelidade para visualizar e testar conceitos de design.
- Desenvolver interfaces visuais atraentes e eficientes que atendam às necessidades e expectativas dos usuários.
- Garantir que o design seja responsivo, adaptando-se a diferentes tamanhos de tela e dispositivos.
- Integrar princípios de design acessível para garantir que o SGT seja utilizável por usuários com diferentes habilidades e necessidades.
- Documentar padrões de design e guidelines para garantir consistência na interface do usuário.

---

Ao completar este desafio, esperamos uma documentação sobre suas contribuições no projeto, pré-requisitos e suposições. Este desafio visa não apenas avaliar as habilidades técnicas, mas também a capacidade de pensar de forma estratégica considerando o sistema proposto. Boa sorte!
