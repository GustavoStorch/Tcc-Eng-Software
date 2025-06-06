# Capa

- **Título do Projeto**: Arquitetura de um Assistente Virtual Inteligente: Aplicação de IA Comportamental no Agendamento e na Automação Administrativa para Profissionais Autônomos na área de saúde e bem-estar.
- **Nome do Estudante**: Gustavo Kauan Storch.
- **Curso**: Engenharia de Software.
- **Data de Entrega**: 01/06/2025 (Última revisão).

# Resumo

  Este projeto tem como objetivo desenvolver uma solução tecnológica para profissionalizar autônomos que enfrentam desafios na gestão de suas atividades administrativas. A proposta é criar um assistente virtual inteligente capaz de automatizar tarefas como agendamento de consultas e cobranças de clientes. Com a implementação desta ferramenta, busca-se aliviar a carga administrativa dos profissionais, lhes permitindo dedicar mais tempo no atendimento aos seus clientes e no aperfeiçoamento de seus serviços.

  Também será desenvolvido um sistema web complementar e por meio deste, o profissional poderá configurar parâmetros de funcionamento para a IA (como horário de atendimento, valores, atividades do profissional) e visualizar relatórios analíticos para acompanhar o número de atendimentos, taxas de confirmação e padrões de agendamentos.

  A solução será projetada para ser simples, eficiente e intuitiva, otimizando o tempo e os recursos dos profissionais autônomos, ao mesmo tempo em que melhora a experiência do cliente.

## 1. Introdução

  O Brasil e o mundo passam a todo o tempo por mudanças e transformações que impactam de forma direta a saúde da população (GADELHA, 2022). Constata-se que a atual sociedade passa por uma crescente demanda na procura por serviços de saúde e bem-estar para minimizar os efeitos do rápido crescimento e evolução das gerações. Segundo Gadelha (2022), é possível notar uma mudança significativa no perfil da população e nas doenças, com menos nascimentos, mais gente idosa e doenças que duram um maior período, transformações no jeito de trabalhar, o aquecimento do planeta e a globalização. 

  Diante disso, práticas como o controle de processos e o monitoramento de indicadores de saúde são vitais para garantir um serviço de melhor qualidade (DA SILVA JÚNIOR et al. 2024). Ao utilizar profissionais para dar assistência aos primeiros atendimentos ao paciente, como recebê-lo na entrada, preencher o formulário e preparar toda a documentação necessária, o profissional permite-se a dedicar seu tempo exclusivamente ao atendimento do paciente. A utilização desses métodos visa não só a melhoria do atendimento ao paciente, mas também o aumento da eficiência organizacional (DA SILVA JÚNIOR et al. 2024).

  Com o passar do tempo, podemos observar que os chatbots têm o potencial e estão transformando o atendimento ao cliente, oferecendo suporte contínuo, 24 horas por dia, além de proporcionar experiências personalizadas que elevam a satisfação dos usuários. Dominar o uso dessas plataformas permite aos profissionais criarem soluções inovadoras, reduzindo custos operacionais e ampliando a capacidade de atendimento das empresas. (SANTOS, 2025). 

  Nesse mesmo contexto, a utilização de chatbots também se destaca como uma poderosa ferramenta no gerenciamento de clínicas e consultórios médicos, padronizando e facilitando o controle das atividades diárias. Eles contribuem diretamente para a organização do setor administrativo, agilizando serviços como agendamento de consultas, retornos, envio de confirmações e lembretes, além de fortalecer o relacionamento entre paciente e clínica. Esses sistemas ainda possibilitam a manutenção de um histórico detalhado de cada paciente, por meio de prontuários eletrônicos, garantindo mais segurança e eficiência no armazenamento das informações. (BRITO, 2018).

  O problema que norteia este trabalho está relacionado ao planejamento e à execução das etapas de implementação de um chatbot em uma clínica, com o propósito de melhorar a comunicação entre paciente e profissional, integrar-se às plataformas de agendamento e ajustar automaticamente os fusos horários. Na prática, espera-se que o chatbot assume tarefas como marcar consultas, esclarecer dúvidas e fornecer informações, permitindo que o profissional foque exclusivamente no atendimento clínico, além de gerar relatórios semanais e mensais sobre consultas e pacientes.
  
  Com esse sistema, qualquer pessoa poderá agendar e obter suporte a qualquer hora, sem depender de um atendente em horário comercial, e o chatbot identificará automaticamente o fuso horário do cliente com base no DDD e no DDI, garantindo agendamentos corretos para consultas online em diferentes regiões do Brasil. Além disso, o chatbot será comportamental: analisará o histórico de cada cliente para sugerir horários de consulta de acordo com padrões anteriores e aplicará políticas de cobrança diferenciadas para quem costuma remarcar ou atrasar pagamentos, incentivando a pontualidade e a assiduidade.


## 2. Descrição do Projeto

  Esse projeto tem como objetivo o desenvolvimento de um assistente virtual inteligente voltado para profissionais autônomos na área de saúde e bem estar com foco atual em psicólogos. A ferramenta proposta visa automatizar tarefas administrativas, como agendamento de consultas e cobrança de clientes, utilizando inteligência artificial para otimizar esses processos. O produto será um assistente virtual simples de usar, que permitirá a integração da automação diretamente no fluxo de trabalho diário dos profissionais. As funcionalidades incluirão envio de lembretes automáticos e inteligentes, controle de agenda e interações personalizadas com os clientes.

  O assistente será utilizado via Telegram, e terá também um site onde os profissionais possam acessar e configurar o assistente conforme necessidade, a combinação dos dois fará com que os profissionais possam gerenciar seus compromissos de qualquer lugar e a qualquer momento.

  Haverá o envio automático e inteligente de lembretes, a ideia principal é usar um agente (IA) responsável por estudar o comportamento de cada cliente. Por exemplo, se o cliente Gustavo costuma agendar suas consultas sempre nas terças-feiras à tarde, entre 15h e 17h, quando ele entrar em contato para um novo agendamento, o assistente virtual sugerirá automaticamente horários semelhantes aos padrões anteriores. Para clientes como João, que frequentemente remarca ou cancela suas consultas, o sistema enviará lembretes antecipados para confirmar a consulta, ajudando a evitar alterações de última hora. 

  Além disso, o sistema irá considerar o fuso horário de cada cliente e do profissional. Ao realizar um agendamento, o paciente poderá informar seu fuso horário, ou o sistema poderá determinar automaticamente o horário com base no local informado. O assistente virtual irá então sugerir horários compatíveis com a disponibilidade do profissional e também dentro do limite de horário do paciente.

  Por exemplo, se o paciente Gustavo mora nos Estados Unidos e deseja agendar uma consulta às 14h (horário local dele), o assistente irá sugerir automaticamente o horário equivalente para a psicóloga em Santa Catarina, ajustando a diferença de fuso horário entre os dois. Isso garante que ambos, paciente e profissional, vejam e entendam o horário correto do agendamento, evitando confusões de horário.

## 2.1. **Problemas a Resolver**

- **Gestão de agenda manual:** Dificuldade dos profissionais autônomos em gerenciar seus compromissos, resultando em conflitos de horários e perda de consultas.
- **Falta de lembretes automáticos:** A ausência de notificações pode levar a atrasos e faltas, prejudicando tanto o profissional quanto o cliente.
- **Carga administrativa excessiva:** Tempo excessivo gasto com tarefas burocráticas reduz a disponibilidade para o atendimento ao cliente.
- **Comunicação ineficiente:** Agendamentos, cancelamentos e mudanças ainda são feitos de forma manual, aumentando a chance de erros e retrabalho.
- **Agendamento entre fusos horários diferentes:** Agendamentos serão possíveis serem feitos sem a falha de comunicação por conta de fusos horários, esses tipos de problemas podem ser mais comuns em consultas online.

## 2.2. **O que será feito**

- **Chatbot via Telegram:** Assistente virtual para comunicação e agendamento.
- **Integração com calendários:** Sincronização com Google Calendar para organização eficiente.
- **Banco de dados (PostgreSQL):** Armazenamento seguro de informações sobre clientes e agendamentos.
- **Notificações automáticas:** Lembretes para pacientes e alertas para os profissionais.
- **Configuração personalizada:** Interface para ajustar horários, valores e métodos de cobrança.
- **Tela de login**
- **Tela para configuração de horários**
- **Tela para configurações de valores**
- **Tela para configurações de mensagens e demais permissões de integrações.**
- **Sugestões inteligentes de horários:** O assistente analisará padrões e comportamentos de agendamento dos clientes para facilitar novas marcações, levando em conta as diferenças de fuso horário entre o cliente e o profissional.
- **Linguagem de programação:** Python (pela versatilidade e suporte a IA) e react para frontend referente às telas de configurações do sistema.
- **Hospedagem:** Solução em nuvem (Heroku ou AWS).

## 2.3. **Limitações**

- **Integração com WhatsApp:** A API do Whatsapp é paga, como o projeto não possui fim lucrativos ainda, não será realizado esta integração.
- **Sistema próprio de pagamentos** (integrações com plataformas existentes podem ser avaliadas posteriormente).
- **Integração com plataformas de pagamento ainda não implementada na fase inicial.**
- **Software de gestão completo (ERP):** O foco é a automação de tarefas específicas.
- **Suporte para grandes empresas ou múltiplos profissionais:** voltado para autônomos e pequenos negócios.
- **Aplicativo móvel nativo:** acesso via Telegram web ou aplicativo Telegram, já a parte de configurações do profissional será por meio do site web.
- **Funcionalidades além do escopo administrativo** (ex.: controle de estoque ou relatórios financeiros detalhados).
- **Escopo focado em saúde e bem estar:** Outras categorias podem ser consideradas no futuro.
- **Sem integração com sistemas complexos de gestão:** Apenas funções básicas de agendamento, controle e lembretes.
- **Sem automação completa de todas as tarefas administrativas:** O foco inicial será em agendamento, lembretes e cobrança.

## 3. Especificação Técnica

Descrição detalhada da proposta, incluindo requisitos de software, protocolos, algoritmos, procedimentos, formatos de dados, etc.

### 3.1. Requisitos de Software
- Apresentar os requisitos do tema proposto.
- **Lista de Requisitos:** Apresentar uma lista contendo os Requisitos Funcionais (RF) e Não-Funcionais (RNF).
- **Representação dos Requisitos:** Representar os RFs por meio de um Diagrama de Casos de Uso (UML).

### 3.2. Considerações de Design

- Discussão sobre as escolhas de design, incluindo alternativas consideradas e justificativas para as decisões tomadas.
- **Visão Inicial da Arquitetura**: Descrição dos componentes principais e suas interconexões.
- **Padrões de Arquitetura**: Indicação de padrões específicos utilizados (ex.: MVC, Microserviços).
- **Modelos C4**: Detalhamento da arquitetura em níveis: Contexto, Contêineres, Componentes, Código.

### 3.3. Stack Tecnológica

- **Linguagens de Programação**: Justificativa para a escolha de linguagens específicas.
- **Frameworks e Bibliotecas**: Frameworks e bibliotecas a serem utilizados.
- **Ferramentas de Desenvolvimento e Gestão de Projeto**: Ferramentas para desenvolvimento e gestão do projeto.
... qualquer outra informação referente a stack tecnológica ...

### 3.4. Considerações de Segurança

Análise de possíveis questões de segurança e como mitigá-las.

## 4. Próximos Passos

Descrição dos passos seguintes após a conclusão do documento, com uma visão geral do cronograma para Portfólio I e II.

## 5. Referências

DA SILVA JÚNIOR, Daniel Melo et al. GESTÃO EM SAÚDE: PRÁTICAS GERENCIAIS PARA A OTIMIZAÇÃO DOS SERVIÇOS. LUMEN ET VIRTUS, v. 15, n. 43, p. 9531-9541, 2024.

GADELHA, Carlos A. Grabois. A Saúde como opção estratégica para o desenvolvimento do Brasil. SAÚDE É DESENVOLVIMENTO, p. 12, 2022.

SANTOS, Isabela. Automação com inteligência artificial: análise de uma empresa provedora de plataforma de chatbot com IA. 2025.

BRITO, Ariadne Elesbão et al. Medclinic: gerenciamento de clínicas médicas. 2018.

## 6. Apêndices (Opcionais)

Informações complementares, dados de suporte ou discussões detalhadas fora do corpo principal.
## 7. Avaliações de Professores

Adicionar três páginas no final do RFC para que os Professores escolhidos possam fazer suas considerações e assinatura:
- Considerações Professor/a:
- Considerações Professor/a:
- Considerações Professor/a:
