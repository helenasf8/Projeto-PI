# Projeto Integrador - Modelo
*NexStudy*

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.
*Site para auxiliar nos estudos de jovens, com a possibilidade de organizar a rotina. Com ajuda interativa e IA próŕia para os estudos.*

**IMPORTANTE**: [**Cadastre seu projeto nesta planilha**](https://docs.google.com/spreadsheets/d/1bSb1-S9qOf46fNH8quyoFpcjcTuBMj_EdSPchOuFULY/edit?usp=sharing).

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:
- Arthur de Oliveira Fernandes ([link](https://github.com/ArtthurFernandes))
- Ana Luiza Köhler ([link](https://github.com/analuizakohler))
- Eloah da Costa ([link](https://github.com/elocosta))
- Eloisa de Oliveira Borges ([link](https://github.com/borgesselo))
- Helena da Silva Fortunato ([link](https://github.com/helenasf8))

Links do projeto:
-   [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   Backend: [Repositório](https://github.com/helenasf8/Back-NextStudy)
-   Frontend: [Repositório](https://github.com/helenasf8/Front-NextStudy)

**1.1 Modelos de Sistemas**

**Nessa parte a equipe deve escolher um dos modelos de sistemas para desenvolver o projeto. Ao escolher, escreva uma breve descrição do sistema e o motivo da escolha e pode apagar os outros modelos.**

**1.1.1 Ponto de Vendas (PDV)**

O sistema de Ponto de Vendas (PDV) é utilizado para registrar transações, controlar entradas e saídas e gerar relatórios financeiros. Adaptando esse modelo para o NexStudy, ele pode ser relacionado ao controle de uso da plataforma, como registro de acessos, utilização de funcionalidades e possíveis planos pagos.

**Exemplo: Controle de uso da plataforma NexStudy**

A empresa NexStudy oferece recursos como inteligência artificial, planejamento de tarefas e relatórios de desempenho. Com o crescimento da plataforma, os desenvolvedores perceberam a necessidade de entender melhor o comportamento dos usuários.

Assim, surge a ideia de implementar um sistema semelhante a um PDV, onde cada ação do usuário (como criar tarefas, usar a IA ou acessar relatórios) é registrada. Isso permite gerar relatórios sobre uso da plataforma, identificar quais funcionalidades são mais utilizadas e melhorar a experiência do usuário com base nesses dados.

**1.1.2 Empréstimo**

O sistema de Empréstimo é utilizado para controlar itens que são cedidos temporariamente, como livros ou equipamentos. No NexStudy, esse modelo pode ser adaptado para o gerenciamento de materiais de estudo, como conteúdos, exercícios e recursos disponibilizados aos alunos.

O sistema permitiria controlar quais materiais o aluno está utilizando, por quanto tempo e quais ainda precisam ser concluídos, funcionando como um “empréstimo de conhecimento”.

**Exemplo: Gerenciamento de materiais de estudo**

A plataforma NexStudy disponibiliza diversos materiais de apoio, como listas de exercícios, resumos e conteúdos personalizados. Com o aumento de usuários, tornou-se necessário organizar melhor o acesso a esses materiais.

Assim, o sistema passa a funcionar como um modelo de empréstimo, onde o aluno “retira” um conteúdo para estudo e o sistema acompanha seu progresso até a finalização. Isso permite controlar quais conteúdos estão em andamento, concluídos ou pendentes, além de gerar relatórios sobre o desempenho dos estudantes em cada material.

**1.1.3 Ordem de Serviço (O.S.)**

O sistema escolhido para o desenvolvimento do projeto foi o modelo de Ordem de Serviço (O.S.), adaptado para o contexto educacional. Tradicionalmente, esse tipo de sistema é utilizado para gerenciar serviços, clientes e o andamento de atividades. No caso do NexStudy, essa lógica será aplicada à organização de estudos, onde as “ordens de serviço” representam as tarefas e atividades acadêmicas dos estudantes.

Cada tarefa (como estudar um conteúdo, fazer exercícios ou revisar matéria) funcionará como uma ordem de serviço, contendo informações como prazo, prioridade, disciplina e status (pendente, em andamento ou concluída).

A escolha desse modelo foi feita porque ele atende diretamente ao principal objetivo do sistema: organizar tarefas e acompanhar o progresso do usuário de forma clara e eficiente.

**Exemplo: Organização das tarefas de estudo**

A equipe do NexStudy identificou que muitos estudantes têm dificuldade em manter uma rotina organizada de estudos. Para resolver isso, foi desenvolvido um sistema baseado em ordens de serviço.

Nesse sistema, cada atividade do aluno é registrada como uma tarefa com prazo e prioridade. O estudante pode acompanhar o andamento de suas atividades, enquanto o sistema gera relatórios de desempenho e sugere melhorias com base no progresso.

Isso permite uma gestão mais eficiente do tempo e das atividades, tornando o estudo mais organizado, produtivo e personalizado.

# 2. Situação Problema

-   **Introdução**: A empresa fictícia NexStudy é uma plataforma digital voltada para auxiliar estudantes na organização de seus estudos. Criada em 2026 por um grupo de jovens desenvolvedores e estudantes, a empresa tem como objetivo oferecer ferramentas como planejamento de tarefas diárias, inteligência artificial para apoio nos estudos e planilhas personalizadas. Atualmente, a equipe é composta por 5 pessoas, incluindo programadores, um designer e um responsável pelo suporte ao cliente. Mesmo sendo uma empresa digital, seu funcionamento envolve diversas etapas organizacionais para atender os usuários de forma eficiente.
-   **Situação-problema**: Atualmente, o funcionamento da NexStudy ocorre de maneira parcialmente organizada, porém ainda depende muito de processos manuais e pouco integrados. O ciclo começa quando um usuário acessa a plataforma e cria sua conta. Esse cadastro é armazenado em um sistema simples, mas ainda não possui integração completa com as demais funcionalidades. Após o cadastro, o aluno precisa configurar manualmente sua rotina de estudos, inserindo matérias, horários e tarefas. Como não há uma automatização eficiente, muitos usuários acabam desistindo nessa etapa por acharem o processo cansativo e pouco intuitivo. Além disso, a ausência de sugestões inteligentes dificulta a personalização do planejamento. Outro ponto importante é o uso da inteligência artificial. Atualmente, ela funciona de forma limitada, sendo acessada separadamente das demais ferramentas. Isso faz com que o aluno precise alternar entre diferentes áreas do site, tornando a experiência menos fluida e mais confusa. A comunicação com os usuários também apresenta falhas. O suporte é feito principalmente por e-mail e redes sociais, o que gera demora nas respostas e dificuldade no acompanhamento das solicitações. Não há um sistema centralizado para gerenciar dúvidas, feedbacks ou problemas técnicos. Além disso, o acompanhamento do progresso dos estudantes é pouco eficiente. Embora existam planilhas disponíveis, elas não são automaticamente atualizadas com base nas tarefas concluídas, exigindo que o próprio aluno faça esse controle manualmente. Isso reduz o engajamento e dificulta a análise do desempenho ao longo do tempo. Por fim, a empresa não possui um sistema estruturado de análise de dados dos usuários. Informações importantes, como frequência de uso, dificuldades comuns e taxas de desistência, não são devidamente coletadas ou analisadas, o que limita a melhoria contínua da plataforma.
-   **Conclusão**: Diante dessa análise, é possível identificar diversos problemas no funcionamento atual do NexStudy, como a falta de integração entre as ferramentas, processos manuais excessivos, baixa personalização e falhas no suporte ao usuário. Um software mais completo e bem estruturado poderia resolver esses problemas ao automatizar o planejamento de estudos, integrar a inteligência artificial às tarefas diárias, criar um sistema de acompanhamento de progresso em tempo real e centralizar o suporte ao cliente. Dessa forma, a plataforma se tornaria mais eficiente, intuitiva e atrativa para os estudantes, aumentando o engajamento e melhorando os resultados de aprendizagem.

# 3. Descrição da proposta

A proposta do sistema NexStudy é oferecer uma plataforma integrada de organização de estudos, cujo foco principal é auxiliar estudantes a planejarem, acompanharem e otimizarem sua rotina de aprendizagem de forma automatizada e inteligente. O software atuará diretamente nos problemas identificados anteriormente, especialmente na falta de integração entre ferramentas, na dificuldade de organização e na baixa personalização do estudo.

O sistema permitirá que o usuário crie sua conta e, a partir disso, tenha acesso a um ambiente unificado onde poderá organizar suas matérias, definir tarefas diárias e acompanhar seu progresso. Um dos principais diferenciais será a integração da inteligência artificial, que irá sugerir planos de estudo personalizados, ajudar na resolução de dúvidas e adaptar a rotina conforme o desempenho do aluno.

Dentro do software, será possível realizar ações como cadastrar e organizar tarefas, receber recomendações automáticas de estudo, acompanhar o progresso em tempo real, interagir com a inteligência artificial para tirar dúvidas e visualizar relatórios de desempenho. Além disso, o sistema buscará centralizar todas as funcionalidades em um único ambiente, evitando a necessidade de múltiplas ferramentas externas.

Dessa forma, a proposta do NexStudy é transformar o processo de organização dos estudos em algo mais simples, automatizado e eficiente, proporcionando uma experiência mais intuitiva e aumentando o engajamento e o desempenho dos estudantes.

# 4. Modelagem de Dados


<img width="1009" height="1043" alt="tab" src="https://github.com/user-attachments/assets/02db3f74-6b8b-41fd-88d8-fe065b39f6e3" />



# 4. Regras de negócio
(*Nessa parte a equipe deve descrever as regras de negócio que serão implementadas no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.*)

As **Regras de negócio** são orientações e restrições que ajudam a regular as operações de uma empresa. **Regras** foram criadas para **colaborar com o funcionamento**, seja da sociedade, de uma escola, de um jogo, etc. Não seria diferente nas organizações. Vamos abordar melhor sobre esse assunto. Entender o que são as regras de negócio, sua importância, como são aplicadas e
automatizadas na gestão por processo.

**4.1 O que são regras de negócio?**

Um negócio funciona por processos que, por sua vez, são formados por atividades relacionadas entre si.

As funções das áreas de compras, estoque, logística, finanças, vendas e marketing, por exemplo, compõem um processo de fornecimento de um produto ao cliente.

Dentro desses processos, existem regras que devem ser seguidas durante a execução das atividades, que ajudam a definir **COMO** as operações devem ser realizadas e gerenciadas, **POR QUEM**, **QUANDO**, **ONDE** e **POR QUÊ**.

Podemos dizer que as regras de negócio são **limites impostos às operações**, de forma que elas sigam corretamente em direção às políticas e aos objetivos da instituição.

**4.2 Regras para a criação de regras de negócio**

De maneira geral, as regras de negócio devem:
- Ser **simples**, isto é,  ter apenas uma função.
- Ser **completas**, com início, meio e fim.
- Ser possíveis de **mensurar** e **rastrear**.
- Estar em consonância com a **legislação**.
- Estar **atualizadas** e sempre **revisadas**.
- Refletir a **política** e os **valores** da organização.
- Ser **inteligíveis** para os colaboradores e envolvidos no processo.

**4.3 Por que ter regras de negócio?**

- **Padronização de processos:** padronizam os processos e auxiliam a fluirem de forma mais eficiente e automatizada.
- **Controle de processos:** auxiliam no controle de processos, pois falhas são identificadas e corrigidas mais rapidamente.
- **Tomada de decisão:** auxiliam na tomada de decisão e no cumprimento de estratégias pré-estabelecidas.

**4.4 Exemplos de regras de negócio**

- Em um controle de qualidade de granja, pode-se dizer que a cada 100 ovos impróprios para consumo, o lote será descartado.
- Em um banco, clientes com faturamento mensal de mais de R$ 25 mil e CPF sem restrições, serão atendidos pelo gerente Premium pessoa física.
- Para conclusão de licitações, devem ser feitos três orçamentos e o vencedor será sempre o de menor preço final.
- Em um processo de seleção de RH, o candidato só pode ser aprovado se tiver mais de 5 anos de experiência na área, diploma de pós-graduação, espanhol fluente e pretensão salarial abaixo de R$ 8.000,00.
- Em um processo de vendas, o vendedor só pode vender um produto se o cliente tiver mais de 18 anos, renda familiar acima de R$ 5.000,00 e não tiver restrições no CPF.
- Em um processo de compras, o fornecedor só pode ser contratado se tiver nota fiscal, certificado de qualidade e preço abaixo de R$ 10,00 por unidade.
- Em um processo de logística, o pedido só pode ser enviado se o cliente tiver mais de 18 anos, endereço de entrega no mesmo estado e não tiver restrições no CPF.

**4.5 Como escrever regras de negócio?**

- Número identificador.
- Nome da regra.
- Data de criação e data da última alteração para comparações e
controle.
- Nome dos Autores das versões.
- Número da versão (1, 2 etc).
- Dependências: insira o identificador das regras atreladas, às quais a regra em questão depende.
- Uma descrição detalhada para compreensão da regra.

**4.6 Exemplos de regras de negócio com formatação**

- **RN01 – Criação Comanda:** Para iniciar um atendimento no balcão, é necessário primeiro abrir uma nova comanda.
- **RN02 – Inserir Produtos Comanda:** Para inserir um produto na comanda, é necessário que o produto esteja cadastrado no sistema e que a quantia comprada seja acima de zero.
- **RN03 – Cadastro de Leitores:** Os leitores precisam fazer o cadastro para realizar o empréstimo.
- **RN04 – Realizar Empréstimo:** Para realizar o empréstimo, apenas leitores com cadastro e nenhuma multa em aberto.
- **RN05 – Registro de Empréstimo:** O gerente deve possuir acesso aos registros de empréstimos.
- **RN06 – Pagamento de Multa:** O leitor que passar de 15 dias com o livro deverá pagar a multa de um real por dia de atraso.
- **RN07 – Impressão de Orçamento:** Com as informações do
orçamento registradas, a atendente deve imprimir o orçamento e
repassar ao cliente para aprovação, e caso o cliente aprovar, a atendente deve solicitar a sua assinatura para aprovar a execução do serviço.
- **RN08 – Abertura de OS:** Com o atendimento aprovado pelo cliente, a atendente deverá inserir os dados do cliente e do orçamento em um novo documento, para registros internos, realizando a abertura da OS.
- **RN09 – Relatório de Fluxo de Caixa:** O relatório de fluxo de caixa será permitido somente para o administrador.

# 5. Requisitos funcionais
RF01: O sistema deve permitir o cadastro de usuário (dados: nome, e-mail, senha)
RF02: O sistema deve permitir edição de perfil(dados: nome, foto de perfil, senha)
RF03: O sistema deve permitir visualizar conteúdos por matéria (dados: nome da matéria, tópicos)
RF04: O sistema deve disponibilizar exercícios (dados: pergunta, alternativas, resposta correta)
RF05: O sistema deve exibir resolução detalhada (dados: passo a passo da resolução)
RF06: O sistema deve permitir definir metas diárias (dados: quantidade de exercícios, tempo de estudo)
RF07: O sistema deve registrar progresso do usuário (dados: atividades concluídas, data)
RF08: O sistema deve calcular sequência de estudos (streak)(dados: dias consecutivos de acesso)
RF09: O sistema deve atribuir pontos ao usuário (dados: pontos por atividade)
RF10: O sistema deve controlar níveis (dados: nível atual, pontos acumulados)
RF11: O sistema deve conceder conquistas (dados: nome da conquista, descrição)
RF12: O sistema deve fornecer feedback imediato (dados: resposta correta/incorreta, explicação)
RF13: O sistema deve permitir personalizar cronograma (dados: dias, horários, matérias)
RF14: O sistema deve organizar conteúdos por prioridade (dados: nível de dificuldade, importância , prazo de entrega )
RF15: O sistema deve permitir criação de tarefas (dados: título, descrição, prazo)
RF16: O sistema deve permitir organização em Kanban (dados: status da tarefa)
RF17: O sistema deve permitir anotações (dados: texto, matéria relacionada)
RF18: O sistema deve gerar planos de estudo com IA (dados: desempenho do usuário, matérias)
RF19: O sistema deve explicar conteúdos com IA (dados: pergunta do usuário)
RF20: O sistema deve gerar exercícios personalizados (dados: nível de dificuldade, tema)
RF21: O sistema deve resolver exercícios passo a passo (dados: questão fornecida pelo usuário)

# 6. Requisitos não funcionais

RNF01: O sistema deve ter tempo de resposta de até 3 segundos.
RNF02: O sistema deve garantir segurança dos dados dos usuários.
RNF03: O sistema deve utilizar criptografia para senhas.
RNF04: O sistema deve possuir interface intuitiva e de fácil uso.
RNF05: O sistema deve estar disponível 24/7.
RNF06: O sistema deve suportar múltiplos usuários simultâneos.
RNF07: O sistema deve ser escalável.
RNF08: O sistema deve permitir manutenção e atualização contínua.
RNF09: O sistema deve ser responsivo.

# 7. Diagrama de Caso de Uso

**7.1 Introdução**

O diagrama de caso de uso é uma ferramenta de modelagem que descreve o comportamento de um sistema a partir da perspectiva do usuário. Ele é usado para capturar os requisitos funcionais de um sistema.

- Especificam a visão externa do sistema.
- Descrevem como o sistema é percebido por seus usuários.
- Descrevem as interações entre os usuários e o sistema.

![Diagrama de Caso de Uso](img/dcu1.png "Diagrama de Caso de Uso")

**Os casos de uso:**
- Descrevem como os **usuários interagem com o sistema** (as funcionalidades do sistema)
- Facilitam a **organização dos requisitos** de um sistema.
- Dão uma **visão externa** do sistema
- O conjunto de casos de uso deve ser capaz de comunicar a **funcionalidade** e o **comportamento** do sistema para o cliente.
- Descrevem **o que** o sistema faz, mas **não** especificam **como** isso deve ser feito.

**7.2 Elementos do diagrama de caso de uso**

7.2.1 **Atores**

- Representam os papéis desempenhados por **elementos externos** ao sistema
  - Ex: humano (usuário), dispositivo de hardware ou outro sistema (cliente)
- Elementos que **interagem** com o sistema

Notação:

![Atores Notação](img/dcu_atores_notacao.png "Atores Notação")

**Exemplo: Loja de CDs**

**Identificando os atores**
- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja.
- A loja possui um **atendente** cuja função é atender os clientes durante a venda dos discos. A loja também possui um **gerente** cuja função é administrar o estoque para que não faltem discos. Além disso é ele quem dá folga ao atendente, ou seja, ele também atende os clientes durante a venda dos discos.

![Identificando os atores](img/dcu_identificando_atores.png "Identificando os atores")

**E o cliente?**
- Não é ator pois ele **não interage** com o sistema!

**7.2.2 Casos de uso**

- Representam **funcionalidades** do sistema (requisitos funcionais).
- São iniciados por **atores** ou por outros casos de uso.

> **Dica**: nomeie os casos de uso com **verbos** no **infinitivo**.

Notação:

![Casos de uso Notação](img/dcu_casos_de_uso_notacao.png "Casos de uso Notação")

**Exemplo: Loja de CDs**

**Identificando os casos de uso**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja. A loja possui um atendente cuja função é atender os clientes durante a **venda dos discos**.
- A loja também possui um gerente cuja função é **administrar o estoque** para que não faltem discos. Além disso é ele quem dá folga ao atendente, ou seja, ele também atende os clientes durante a **venda dos discos**.

![Identificando os casos de uso](img/dcu_identificando_casos_de_uso.png "Identificando os casos de uso")

**7.2.3 Relacionamentos**

**7.2.3.1 Relacionamento de associação**

- Indica que um ator **participa** de um caso de uso, ou seja, o ator **interage** (comunica-se) com o caso de uso.
- É representado por uma **linha sólida**.
- Um ator pode se relacionar com **um ou mais casos de uso**.

> Dicas:
> - Não use setas nas linhas de associação.
> - Associações não representam fluxo de informação.

![Relacionamento de associação](img/dcu_relacionamento_de_associacao.png "Relacionamento de associação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de associação**

- Uma loja de CDs possui discos para venda. Um cliente pode comprar uma quantidade ilimitada de discos para isto ele deve se dirigir à loja. A loja possui um _atendente_ cuja função é atender os clientes durante a **venda dos discos**.
- A loja também possui um _gerente_ cuja função é **administrar o estoque** para que não faltem discos. Além disso é ele quem dá folga ao _atendente_, ou seja, ele também atende os clientes durante a **venda dos discos**.

![Identificando os relacionamentos de associação](img/dcu_identificando_relacionamentos_de_associacao.png "Identificando os relacionamentos de associação")

**7.2.3.2 Relacionamento de generalização/especialização**

**Generalização de atores**

- Quando dois ou mais atores podem se **comunicar com o mesmo conjunto de casos de uso**.
- Indica que um ator **herda** as características de outro ator.
– Um filho (herdeiro) pode se comunicar com todos os casos de uso que seu pai se comunica.

> **Dica:** coloque os herdeiros **embaixo**.

**Notação:**

![Relacionamento de generalização/especialização de atores - notação](img/dcu_relacionamento_de_generalizacao_especializacao_notacao_de_atores.png "Relacionamento de generalização/especialização de atores - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de generalização/especialização de atores**

![Identificando os relacionamentos de generalização/especialização de atores](img/dcu_identificando_relacionamentos_de_generalizacao_especializacao_de_atores.png "Identificando os relacionamentos de generalização/especialização de atores")

**Generalização de casos de uso**

– O caso de uso filho herda o comportamento e o significado do caso de uso pai.
– O caso de uso filho pode incluir ou sobrescrever o comportamento do caso de uso pai.
– O caso de uso filho pode substituir o caso de uso pai em qualquer lugar que ele apareça.

> **Dica:** deve ser aplicada quando uma condição resulta na definição de
diversos fluxos alternativos.

Notação:

![Relacionamento de generalização/especialização de casos de uso - notação](img/dcu_relacionamento_de_generalizacao_especializacao_notacao_de_casos_de_uso.png "Relacionamento de generalização/especialização de casos de uso - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de generalização/especialização de casos de uso**

**Novos requisitos:**

- As vendas podem ser **à vista** ou **a prazo**. Em ambos os casos o estoque é
atualizado e uma nota fiscal, entregue ao consumidor.
- No caso de uma **venda à vista**, clientes cadastrados na loja e que compram mais de 5 CDs de uma só vez ganham um desconto de 1% para cada ano de cadastro.
- No caso de uma **venda a prazo**, ela pode ser parcelada em 2 pagamentos com um
acréscimo de 20%. As vendas a prazo podem ser pagas no **cartão** ou no **boleto**.
  - Para pagamento com **boleto**, são gerados boletos bancários que são entregues ao cliente e armazenados no sistema para lançamento posterior no caixa.
  - Para pagamento com **cartão**, os clientes com mais de 10 anos de cadastro na loja ganham o mesmo desconto das compras à vista.

![Identificando os relacionamentos de generalização/especialização de casos de uso](img/dcu_identificando_relacionamentos_de_generalizacao_especializacao_de_casos_de_uso.png "Identificando os relacionamentos de generalização/especialização de casos de uso")

**Identificando mais relacionamentos de generalização/especialização de casos de uso**

![Identificando mais relacionamentos de generalização/especialização de casos de uso](img/dcu_identificando_mais_relacionamentos_de_generalizacao_especializacao_de_casos_de_uso.png "Identificando mais relacionamentos de generalização/especialização de casos de uso")

**7.2.3.3 Relacionamento de dependência**

**Extensão**

- Representa uma variação/extensão do comportamento do caso de uso base.
- O caso de uso estendido só é executado sob certas circunstâncias.
- Separa partes obrigatórias de partes opcionais.
  - Partes obrigatórias: caso de uso base.
  - Partes opcionais: caso de uso estendido.
- Fatorar comportamentos variantes do sistema (podendo reusar este comportamento
em outros casos de uso).

**Notação:**

![Relacionamento de dependência (extensão) - notação](img/dcu_relacionamento_de_dependencia_extensao_notacao.png "Relacionamento de dependência (extensão) - notação")

**Exemplo: Loja de CDs**

**Identificando os relacionamentos de dependência (extensão)**

**Novos requisitos:**
- No caso de uma venda à vista, clientes cadastrados na loja e que compram mais
de 5 CDs de uma só vez ganham um **desconto** de 1% para cada ano de cadastro.
- No caso de uma venda a prazo...
  - ...Para pagamento com cartão, os clientes com mais de 10 anos de cadastro na loja ganham o mesmo **desconto** das compras à vista.

![Identificando os relacionamentos de dependência (extensão)](img/dcu_identificando_relacionamentos_de_dependencia_extensao.png "Identificando os relacionamentos de dependência (extensão)")

**Inclusão**

- Evita repetição ao fatorar uma atividade
comum a dois ou mais casos de uso.
- Um caso de uso pode incluir vários casos de uso.

**Notação:**

![Relacionamento de dependência (inclusão) - notação](img/dcu_relacionamento_de_dependencia_inclusao_notacao.png "Relacionamento de dependência (inclusão) - notação")

**Exemplo: Loja de CDs**

**Novos requisitos:**
Para efetuar vendas ou administrar estoque, atendentes e gerentes terão que **validar** suas respectivas senhas de
acesso ao sistema.

![Identificando os relacionamentos de dependência (inclusão)](img/dcu_identificando_relacionamentos_de_dependencia_inclusao.png "Identificando os relacionamentos de dependência (inclusão)")

**7.2.4 Fronteira do sistema**

- Elemento opcional (mas essencial para um bom
entendimento).
- Serve para definir a área de atuação do sistema, ou seja, seus limites.

**Identificando a fronteira do sistema**

![Identificando a fronteira do sistema](img/dcu_identificando_a_fronteira_do_sistema.png "Identificando a fronteira do sistema")

---



