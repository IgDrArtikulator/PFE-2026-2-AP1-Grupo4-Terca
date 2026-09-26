
# Documento de Visão

## 1. Introdução

### 1.1 Objetivo do documento

Este Documento de Visão tem como objetivo definir a visão geral, o posicionamento, os principais requisitos e as diretrizes para o desenvolvimento da nova plataforma digital das marcas PKZ (Play Makerz) e One to One.

A solução deverá modernizar a presença digital das marcas, melhorar a experiência dos alunos, responsáveis e gestores e centralizar, em uma única plataforma, informações sobre cadastro, localização e história das empresas, entre outras ferramentas que auxiliam a experiência dos usuários.

O projeto terá como foco inicial o desenvolvimento de uma experiência web desktop-first para o site institucional público. Em uma fase seguinte, será desenvolvida a plataforma logada, com áreas e funcionalidades específicas de acordo com o perfil do usuário.

### 1.2 Público-alvo

A plataforma atenderá principalmente três grupos:

- **Alunos One to One**: adultos, atletas e não atletas, com diferentes objetivos.
- **Atletas PKZ**: crianças e adolescentes, até 17 anos, em formação esportiva.
- **Responsáveis pelos atletas PKZ**: pais ou responsáveis que acompanham a evolução, as avaliações e as informações dos atletas.

Também serão considerados usuários internos, como gestores, professores e profissionais responsáveis pelo acompanhamento dos alunos.

### 1.3 Escopo do sistema

O projeto está dividido em duas fases.

**Fase atual: site institucional público** (é o que o protótipo apresenta):

- Página inicial (Hub), comum às duas marcas, em que o visitante escolhe entre a PKZ e a One to One
- Uma landing page para cada uma das marcas, com:
  - Sobre nós
  - Informações sobre treinos
  - Planos de atendimento
  - Unidades e localização
  - Galeria de fotos e vídeos
  - Contato com as marcas
  - Agendamento de aula experimental
  - Cadastro de alunos e acesso ao login

**Fase seguinte:**

- Plataforma logada: autenticação, áreas por perfil de usuário e acompanhamento de avaliações, treinos e relatórios (RF04 a RF16);
- Link para download ou acesso ao aplicativo (RF22);
- Página de comparação entre os dois programas (o link "Comparar os dois programas" já aparece no Sobre nós);
- Depoimentos de pais e alunos (seções 3.1 e 3.2);
- Unidades Vogue Square e Oasis (seção 4.4).

O desenvolvimento terá como prioridade o front-end web para computadores (desktop-first), com uma versão mobile do site para celulares. Um aplicativo nativo não faz parte deste escopo.

### 1.4 Termos usados neste documento

- **Hub:** página inicial comum às duas marcas.
- **Landing page:** site de cada marca (PKZ ou One to One).
- **Aula experimental:** primeira sessão, gratuita. No site, também aparece como "aula grátis" e "avaliação": os três termos se referem à mesma sessão, que serve de ponto de partida do treino.
- **Cadastro:** registro do aluno ou atleta pelo site. Não é obrigatório para agendar a aula experimental.
- **Fase seguinte:** o que não faz parte do protótipo atual e será desenvolvido depois (seção 1.3).

---

## 2. Posicionamento

### 2.1 Oportunidade

A PKZ e a One to One já possuem uma operação estabelecida e uma base relevante de alunos, porém sua experiência digital atual não representa adequadamente o nível de qualidade e profissionalismo oferecido presencialmente.

Atualmente, a operação utiliza uma solução desenvolvida internamente, além de ferramentas como Drive, Excel e ChatGPT. Embora o sistema atual resolva algumas necessidades operacionais, principalmente relacionadas ao agendamento, ele apresenta limitações de usabilidade, organização e apresentação visual.

Existe, portanto, uma oportunidade de transformar a plataforma digital em uma extensão da experiência premium oferecida pelas marcas.

### 2.2 Problema a ser resolvido

Os principais problemas identificados são:

- Ausência de um site institucional próprio;
- Sistema atual com apresentação visual pouco profissional;
- Navegação considerada confusa;
- Excesso de etapas para acessar testes e relatórios;
- Informações numéricas difíceis de interpretar por pais e responsáveis;
- Baixa familiaridade tecnológica de parte dos gestores;
- Comunicação insuficiente entre a equipe e os responsáveis dos atletas;
- Processos ainda dependentes de ferramentas descentralizadas;
- Necessidade de melhorar a percepção de valor das marcas no ambiente digital.

Além disso, existe o desafio de automatizar processos sem tornar o relacionamento com o aluno impessoal.

### 2.3 Proposta de solução

Desenvolver uma plataforma digital centralizada que una experiência institucional, relacionamento, acompanhamento de desempenho e gestão, proporcionando:

- Interface moderna e visualmente sofisticada;
- Navegação simples e intuitiva;
- Informações apresentadas de forma visual;
- Acesso personalizado por perfil;
- Centralização das informações dos alunos;
- Melhor comunicação entre alunos, responsáveis, professores e gestão;
- Visualização da evolução física e esportiva;
- Redução da fricção nos processos internos;
- Fortalecimento da percepção de marca.

A tecnologia deverá automatizar e facilitar processos sem substituir o contato humano entre equipe e aluno.

---

## 3. Stakeholders e Usuários

### 3.1 Conhecendo os Stakeholders

#### Pais e Responsáveis (Público decisor da PKZ)

Como a PKZ é voltada para o público infantil e jovem, os pais e responsáveis são os tomadores de decisão na contratação do serviço prestado pela PKZ. Eles buscam muito mais do que apenas uma atividade física para os filhos; procuram um ambiente seguro, acolhedor e focado no desenvolvimento esportivo e motor. A plataforma deve transmitir confiança, com transparência sobre os métodos e a segurança do local, e provar, por meio de resultados e depoimentos, que o investimento no futuro e na saúde de suas crianças e adolescentes é a escolha certa.

#### Atletas e Alunos (Público final e decisor da One to One)

Focada no público adulto, a One to One oferece um serviço personalizado e de alta performance para os próprios compradores, sejam eles em busca de alto rendimento ou de saúde, estética e qualidade de vida. Eles chegam à página procurando um ambiente premium, hiperpersonalização de treinos e resultados garantidos. Para esse grupo, o site deve funcionar como um ímã, utilizando recursos visuais de alta qualidade e uma comunicação direta que desperte o desejo imediato de treinar no estúdio e agendar a avaliação física e nutricional oferecida.

#### Crianças e Adolescentes (Público final da PKZ)

Embora não sejam os compradores diretos do plano, eles são os usuários finais atendidos pela PKZ. A página e os materiais visuais também devem despertar a vontade de pertencer a um ambiente esportivo e divertido, pois, se a criança ou o jovem se interessar pela proposta apresentada de forma fácil de entender no site, o processo de conversão e convencimento dos pais se torna muito mais fluido.

#### Proprietários e Gestores (PKZ e One to One)

Para a direção das duas marcas, a plataforma é a principal página de captação de clientes e a maior presença digital para mostrar a essência da PKZ e da One to One. O grande interesse é garantir que a página deixe muito clara a diferença de propósito entre a PKZ e a One to One e aumentar o volume de leads.

#### Professores e Profissionais de Treinamento

Os professores de educação física são a imagem central para transmitir confiança, autoridade e alta performance. A especialização de cada um precisa ser evidenciada: tanto a didática e o cuidado no trato com as crianças e jovens da PKZ quanto a excelência técnica e o foco em resultados para os adultos da One to One.

#### Alunos da Área Tech do Ibmec

Este grupo é formado pelos estudantes dos cursos de graduação da área tech do Ibmec, responsáveis por dar vida ao website. Para eles, o projeto vai muito além de um trabalho acadêmico, pois fará parte de seus portfólios profissionais. Utilizando metodologias ágeis, o foco dessa equipe é garantir a felicidade do cliente, entregando uma solução que gere valor.

### 3.2 Usuários

#### Pais e Responsáveis (Público decisor da PKZ)

**Expectativas:**
1. Sentir segurança e confiança na estrutura física, na qualificação da equipe técnica e na metodologia aplicada ao desenvolvimento dos seus filhos.
2. Compreender os diferenciais da PKZ em relação às escolinhas esportivas tradicionais, enxergando o alto valor de um acompanhamento pautado em dados, saúde e disciplina.

**Necessidades:**
1. Acesso a uma página com explicações visuais, claras e didáticas sobre como funcionam o método de avaliação física inicial e o acompanhamento contínuo.
2. Apresentação de depoimentos em vídeo ou texto de outros pais, transmitindo credibilidade.
3. Canais de comunicação diretos e acolhedores (como o WhatsApp) para tirar dúvidas sobre segurança e horários e para agendar visitas facilmente.

#### Atletas e Alunos (Público final e decisor da One to One)

**Expectativas:**
1. Encontrar um ambiente focado em resultados, que garanta um acompanhamento alinhado aos seus objetivos pessoais (seja alta performance esportiva, estética ou qualidade de vida).
2. Perceber que o serviço oferece um atendimento hiperpersonalizado, que justifica o valor investido.

**Necessidades:**
1. Visualização imersiva no site, com fotos e vídeos mostrando o espaço físico moderno, os equipamentos de ponta e o clima dos treinamentos.
2. Detalhamento claro de como funcionam o personal training da One to One e o ciclo de acompanhamento de treinamento e nutricional.
3. Botões de ação rápidos e estratégicos (Call to Action) espalhados pela página para iniciar um atendimento comercial.

#### Crianças e Adolescentes (Público final da PKZ)

**Expectativas:**
1. Sentir que a PKZ é um lugar ao qual pertencem, e não uma obrigação desinteressante.
2. Desejar fazer parte do time PKZ ao ver outros jovens treinando em um ambiente descontraído, que pode trazer novas oportunidades de jogar no time dos sonhos ou de praticar um esporte divertido.

**Necessidades:**
1. Galeria de fotos e vídeos que destaquem a "vibe" dos treinos e a interação com os professores, para que o próprio jovem peça aos pais para treinar na PKZ.

#### Gestores e Equipe Comercial

**Expectativas:**
1. Utilizar a plataforma digital como um funil de vendas eficiente, que trabalhe para educar o visitante e gerar desejo antes mesmo do primeiro contato direto.
2. Receber contatos mais qualificados, que já entendem a diferença de propósito entre a PKZ e a One to One.

**Necessidades:**
1. Uma página com arquitetura de informação inteligente, que separe os dois mundos (PKZ e One to One).
2. Posicionamento estratégico de links que direcionem o cliente rapidamente para o WhatsApp da equipe comercial.

---

## 4. Visão Geral do Produto

### 4.1 Estrutura Geral

A solução será dividida em duas grandes áreas:

#### Área Pública

Responsável pela apresentação institucional das marcas.

Deverá conter:

- Hub: página inicial comum às duas marcas, com a escolha entre a PKZ (até 17 anos) e a One to One (adultos) e vídeos dos treinos;
- Landing page da PKZ;
- Landing page da One to One.

Cada landing page deverá conter:

- Início;
- Sobre nós, com o link "Comparar os dois programas";
- Treinos e metodologia;
- Planos de atendimento;
- Unidades;
- Galeria;
- Contato, com WhatsApp e Instagram (na PKZ, também e-mail);
- Agendamento de aula experimental;
- Cadastro e login.

#### Área Logada (fase seguinte)

Responsável pelo relacionamento e acompanhamento dos usuários. Será desenvolvida em uma fase seguinte, depois do site público.

A plataforma deverá adaptar sua experiência conforme o perfil:

- Responsável PKZ;
- Atleta PKZ;
- Aluno One to One;
- Gestor/profissional.

### 4.2 PKZ — Play Makerz

A PKZ é um centro de treinamento voltado para atletas crianças e adolescentes, até 17 anos. Sua metodologia envolve um processo contínuo de avaliação e desenvolvimento.

#### Metodologia

O processo deverá ser apresentado de maneira visual e compreensível:

> **Avaliação inicial → Planejamento → Treinamento → Relatório → Reavaliação → Evolução**

A avaliação inicial possui aproximadamente 16 testes físicos, incluindo aspectos como:

- Salto;
- Velocidade;
- Agilidade;
- Tempo de reação;
- Força;
- Outros indicadores físicos relevantes.

Após a avaliação, é desenvolvido um cronograma ou microciclo mensal. Durante o processo, são registrados relatórios dos treinos e, posteriormente, realizadas reavaliações para medir a evolução.

No site público, essa metodologia aparece de forma resumida na página Treinos, em três etapas: avaliação (ponto de partida), programa por idade e modalidade e acompanhamento. Os gráficos de evolução descritos a seguir fazem parte da plataforma logada (fase seguinte).

#### Diferencial da Plataforma

A plataforma deverá transformar esses dados em uma experiência visual.

Em vez de simplesmente apresentar:

- Velocidade: 12,4 segundos;
- Salto: 42 cm;
- Força: 85 kg.

O sistema deverá priorizar elementos como:

- Gráficos;
- Evolução percentual;
- Indicadores;
- Comparações;
- Histórico;
- Tendências;
- Destaques positivos;
- Evolução mensal.

### 4.3 One to One

A One to One é um estúdio de personal training voltado para:

- Adultos;
- Atletas;
- Não atletas;
- Diferentes objetivos.

A experiência deverá ser mais individualizada e direcionada diretamente ao aluno.

Entre os principais objetivos estão:

- Apresentar o conceito do treinamento individualizado;
- Demonstrar a estrutura;
- Apresentar os profissionais;
- Mostrar resultados e treinos;
- Facilitar o contato;
- Permitir o acompanhamento do aluno, na plataforma logada (fase seguinte).

### 4.4 Unidades

A plataforma deverá apresentar as unidades de atendimento:

- Sede principal — Av. Armando Lombardi, 949, Loja G, Barra da Tijuca;
- Vogue Square — unidade em abertura;
- Oasis — unidade/campo voltada também para alunos de intercâmbio e High School.

Nesta fase, o site apresenta apenas a sede principal. As unidades Vogue Square e Oasis serão incluídas na fase seguinte.

A localização deverá ser apresentada de maneira visual e intuitiva, incluindo mapa e informações relevantes sobre cada unidade.

### 4.5 Galeria

O sistema deverá possuir uma área dedicada ao conteúdo visual das marcas.

#### PKZ

- Fotos dos treinamentos;
- Vídeos dos treinamentos;
- Conteúdos relacionados aos atletas.

#### One to One

- Fotos dos treinamentos;
- Vídeos dos treinamentos;
- Conteúdos relacionados aos alunos.

A galeria deverá contribuir para transmitir a identidade, a qualidade e o profissionalismo das marcas.

### 4.6 Contato

O contato deverá ser simples e de fácil acesso.

Principais canais:

- WhatsApp;
- Instagram;
- Informações de contato, como e-mail e horário de atendimento;
- Localização das unidades.

A comunicação deverá respeitar os diferentes públicos:

- **PKZ:** linguagem direcionada principalmente aos responsáveis;
- **One to One:** linguagem mais direta, voltada ao próprio aluno.

### 4.7 Planos de Atendimento

A plataforma deverá apresentar os principais modelos de atendimento.

#### PKZ

- Avaliação física completa;
- Acompanhamento mensal;
- Relatórios de evolução;
- Treinamento direcionado ao desenvolvimento esportivo.

#### One to One

- Personal training individual;
- Atendimento personalizado;
- Diferentes objetivos;
- Atendimento para diferentes perfis de adultos.

No site, os planos são apresentados em três passos, sem tabela de preços:

1. Aula experimental gratuita, agendada pela página de Agendamento ou pelo WhatsApp;
2. Pacote montado a partir da avaliação (frequência, duração e objetivo);
3. Valores passados pela equipe de acordo com o pacote escolhido (na PKZ, pelo WhatsApp).

Os valores não precisam necessariamente ser expostos publicamente, podendo ser direcionados para contato comercial.

---

## 5. Requisitos de Alto Nível

### 5.1 Requisitos funcionais

Os requisitos RF04 a RF16 (plataforma logada) e o RF22 (link do aplicativo) ficam para a fase seguinte. Os demais fazem parte do site público.

| Código | Requisito | Descrição |
|---|---|---|
| RF01 | Site institucional | O sistema deverá disponibilizar um site institucional único para as marcas PKZ e One to One, com uma página inicial (Hub) que direciona o visitante para a landing page de cada marca. |
| RF02 | Diferenciação das marcas | O sistema deverá apresentar as duas marcas de maneira individualizada, mantendo uma identidade visual coesa. |
| RF03 | Cadastro | O usuário deverá poder realizar seu cadastro através do site. Na PKZ, o cadastro é feito pelo responsável (nome do responsável, nome e idade do atleta e WhatsApp); na One to One, pelo próprio aluno (nome completo, e-mail e WhatsApp). O cadastro não é obrigatório para agendar a aula experimental. |
| RF04 | Criação de acesso | Após o cadastro, o sistema deverá permitir a criação ou geração de credenciais de acesso à plataforma. |
| RF05 | Login | O sistema deverá possuir autenticação para acesso à área restrita. |
| RF06 | Controle de perfil | O sistema deverá identificar o perfil do usuário e apresentar as informações e funcionalidades correspondentes. |
| RF07 | Área do aluno | O sistema deverá disponibilizar uma área individual para alunos da One to One. |
| RF08 | Área do responsável | O sistema deverá disponibilizar uma área para responsáveis pelos atletas PKZ. |
| RF09 | Área do atleta | O sistema deverá permitir o acesso às informações relacionadas ao atleta. |
| RF10 | Avaliações físicas | O sistema deverá permitir visualizar os resultados das avaliações físicas. |
| RF11 | Histórico de evolução | O sistema deverá apresentar a evolução do aluno/atleta ao longo do tempo. |
| RF12 | Relatórios | O sistema deverá permitir consultar relatórios relacionados aos treinamentos e avaliações. |
| RF13 | Treinos | O sistema deverá apresentar informações relacionadas aos treinamentos realizados e/ou programados. |
| RF14 | Indicadores visuais | O sistema deverá transformar dados de desempenho em gráficos, indicadores e representações visuais de fácil compreensão. |
| RF15 | Cronograma | Para a PKZ, o sistema deverá apresentar informações relacionadas ao cronograma/microciclo de treinamento. |
| RF16 | Reavaliações | O sistema deverá apresentar o histórico de reavaliações do atleta. |
| RF17 | Galeria | O sistema deverá apresentar fotos e vídeos das marcas. |
| RF18 | Localização | O sistema deverá apresentar as unidades e suas respectivas localizações em mapa. |
| RF19 | Contato | O sistema deverá permitir acesso rápido aos canais de contato. |
| RF20 | WhatsApp | O sistema deverá disponibilizar acesso rápido ao contato via WhatsApp. |
| RF21 | Instagram | O sistema deverá disponibilizar acesso aos perfis das marcas no Instagram. |
| RF22 | Aplicativo | O site deverá disponibilizar link para download/acesso ao aplicativo utilizado pela operação. |
| RF23 | Agendamento de aula experimental | Cada landing page deverá disponibilizar uma chamada para ação (CTA) em destaque, específica da sua marca, que permita ao visitante agendar uma aula experimental: a landing page da PKZ apresentará o CTA da PKZ e a landing page da One to One apresentará o CTA da One to One. Ao acionar o CTA, o visitante deverá escolher o dia e o horário, informar nome, e-mail e telefone e receber uma confirmação da solicitação. O agendamento não exige cadastro prévio. |
| RF24 | Disponibilidade de horários | O sistema deverá mostrar quais horários estão livres e quais estão ocupados, e horários ocupados não poderão ser selecionados. Se o horário escolhido for ocupado por outra pessoa enquanto o visitante preenche os dados, ele deverá ser avisado e poderá escolher outro horário livre, impedindo que o mesmo horário seja agendado duas vezes. |

### 5.2 Requisitos não funcionais

| Código | Requisito | Descrição |
|---|---|---|
| RNF01 | Usabilidade | A interface deverá ser simples e intuitiva, inclusive para usuários com baixa familiaridade tecnológica. |
| RNF02 | Responsividade | O escopo é desktop-first, mas o site também deverá ter uma versão mobile, adaptada para telas de celular. |
| RNF03 | Performance | As páginas deverão apresentar carregamento rápido e navegação fluida. |
| RNF04 | Segurança | Dados pessoais e informações de desempenho deverão ser protegidos de acordo com boas práticas de segurança e privacidade. |
| RNF05 | Privacidade | Informações de atletas, especialmente menores de idade, deverão possuir acesso restrito conforme o perfil autorizado. |
| RNF06 | Escalabilidade | A arquitetura deverá permitir a expansão futura para novas unidades, usuários e funcionalidades. |
| RNF07 | Manutenibilidade | O sistema deverá ser estruturado de forma organizada, permitindo manutenção e evolução futuras. |
| RNF08 | Identidade visual | A interface deverá transmitir uma percepção de qualidade, profissionalismo, tecnologia e alto padrão. |
| RNF09 | Baixa fricção | As principais funcionalidades deverão ser acessíveis com o menor número possível de cliques. |
| RNF10 | Visualização de dados | Dados complexos deverão ser apresentados prioritariamente através de gráficos, indicadores e elementos visuais. |
| RNF11 | Conversão no agendamento | O CTA de aula experimental deverá permanecer visível e facilmente identificável em cada landing page, seguindo a identidade visual da respectiva marca. O fluxo de agendamento deverá ser concluído em poucos passos, solicitando apenas os dados essenciais, com confirmação imediata ao visitante. Os dados coletados deverão ser tratados conforme a LGPD; a forma de coleta do consentimento do visitante será definida no desenvolvimento. |

---

## 6. Restrições e Premissas

### 6.1 Restrições

O projeto possui algumas restrições iniciais:

- O escopo atual é direcionado ao front-end web;
- A prioridade é a experiência desktop-first, com uma versão mobile do site;
- A plataforma logada (RF04 a RF16) e o link do aplicativo (RF22) serão desenvolvidos em uma fase seguinte;
- Um aplicativo nativo para celular não faz parte do desenvolvimento inicial;
- A One to One possui manual de marca, seguido no protótipo. A PKZ não possui, e sua identidade visual (azul-marinho e dourado) foi definida pelo grupo. Por isso os dois sites têm estilos diferentes, dentro da mesma estrutura de páginas;
- Integrações avançadas poderão depender de sistemas externos;
- O WhatsApp será inicialmente utilizado como canal de contato;
- A integração nativa com WhatsApp poderá ser desenvolvida posteriormente;
- Algumas informações poderão depender de dados fornecidos pelos gestores.

### 6.2 Premissas

Considera-se que:

- As marcas possuem conteúdo visual suficiente para construção da galeria;
- Os gestores fornecerão informações sobre alunos, avaliações e treinamentos;
- A metodologia PKZ permanecerá baseada em avaliações periódicas;
- A plataforma será utilizada como complemento, e não substituição, do relacionamento humano;
- O sistema deverá permitir evolução futura para aplicativo mobile;
- A solução poderá posteriormente receber novas funcionalidades.

---

## 7. Riscos e Dependências

### 7.1 Riscos

| Risco | Descrição | Mitigação |
|---|---|---|
| Baixa adesão dos usuários | Pais ou alunos que já são clientes da PKZ ou da One to One podem apresentar resistência à nova plataforma. | Desenvolver uma interface visualmente simples e intuitiva; estabelecer um processo de cadastro; usar gráficos e indicadores em vez de tabelas extensas. |
| Excesso de complexidade | O excesso de informações pode tornar a plataforma complexa. | Priorizar poucos cliques (RNF09) e apresentar os dados de forma visual (RNF10). |
| Dados inconsistentes | Informações hoje armazenadas em diferentes ferramentas podem apresentar inconsistências e gerar conflito de dados. | Centralizar as informações dos alunos em uma única plataforma (seção 2.3). |
| Dependência de processos manuais | Parte da operação ainda depende de processos manuais. | Identificar os processos que possam ser automatizados gradualmente. |
| Perda de personalização | O excesso de automação pode reduzir o contato humano entre a equipe e o aluno ou responsável. | Usar a plataforma como complemento, e não substituição, do relacionamento humano (seção 6.2), mantendo canais diretos como o WhatsApp. |
| Proteção de dados | A plataforma lidará com informações pessoais e dados relacionados ao desempenho e à saúde de atletas. | Implementar controles de acesso e autenticação e seguir boas práticas de proteção de dados, visando à adequação à LGPD. |

### 7.2 Dependências

O desenvolvimento dependerá de:

- Manual de marca da One to One e identidade visual da PKZ;
- Fotos e vídeos;
- Informações das unidades;
- Dados dos alunos;
- Dados das avaliações;
- Informações sobre treinamentos;
- Definição dos perfis de acesso;
- Regras de negócio;
- Infraestrutura tecnológica;
- Sistema atualmente utilizado;
- Definição das integrações futuras.
