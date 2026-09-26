# Levantamento de Demandas — PKZ (Play Makerz) & One to One

> Documento extraído da transcrição da reunião com o cliente.
> Escopo do nosso time: **front-end web (desktop-first, com versão mobile)**. Nesta fase, o site institucional público; na fase seguinte, a plataforma logada com áreas por perfil.

---

## 1. Contexto do Negócio

- Grupo com **duas marcas** operando no mesmo espaço físico (galeria dividida em dois lados):
  - **PKZ (Play Makerz)** — centro de treinamento para **atletas** (crianças e adolescentes), com avaliação física, periodização e acompanhamento de evolução.
  - **One to One** — **estúdio de personal training**; segundo o cliente, atende adultos, atletas e não atletas, de todas as idades e objetivos.
- **Unidades:** sede principal, **Vogue Square** (em abertura) e **Oasis** (campo, com alunos de intercâmbio/High School).
- **Volume atual:** ~80 alunos (One to One) + ~60 alunos (PKZ) + ~60 atletas previstos no Oasis.
- **Metodologia PKZ:** avaliação inicial com ~16 testes físicos (salto, velocidade, agilidade, tempo de reação, força) → cronograma/microciclo mensal → relatório a cada treino → reavaliação mensal.
- **Sistema atual:** aplicativo amador feito internamente no Lovable (antes: Drive, Excel e ChatGPT). Resolve agendamento, mas é limitado e visualmente pobre.

### Público-alvo (dois perfis distintos de comunicação)

- **One to One:** contato direto com o próprio aluno (adulto).
- **PKZ:** contato majoritariamente com **responsáveis**. Hoje há déficit de comunicação — quem leva o atleta costuma ser motorista, babá ou segurança, e a equipe muitas vezes não conhece os pais.

> **Decisão do grupo:** no site, a One to One foi direcionada ao público adulto, e crianças e adolescentes (até 17 anos) são direcionados à PKZ, para deixar clara a diferença entre as duas marcas.

---

## 2. Escopo do Projeto

- Front-end web **desktop-first**, com versão mobile do site.
- Entregáveis previstos:
  1. **Site institucional público** (não existe hoje): página inicial comum às duas marcas (Hub) e uma landing page para cada marca.
  2. **Plataforma logada** com áreas por perfil (fase seguinte).

---

## 3. Site Institucional (público)

- Cliente **não possui website** atualmente.
- Site único abrigando **as duas marcas**, com uma página inicial (Hub) e seções e comunicação separadas por público:
  - PKZ → público infantojuvenil / atleta em formação
  - One to One → segundo o cliente, todas as idades e todos os objetivos (no site, público adulto; ver decisão na seção 1)
- **Portfólio visual:** fotos e vídeos dos treinos das duas marcas.
- **Cadastro do aluno pelo site**, gerando login e senha de acesso à plataforma (o acesso à plataforma logada fica para a fase seguinte).
- **Link para o aplicativo** (facilitar download e inscrição), previsto para a fase seguinte.
- **Contato via WhatsApp**.
- Identidade visual forte e coesa — é o primeiro contato do público com a marca.

---

## 4. Diretrizes de UX/UI (pedidos explícitos do cliente)

- **Priorizar o visual sobre o numérico.** Tabelas com muitos números não são compreendidas pelos pais — traduzir em gráficos e indicadores palpáveis.
- **Reduzir cliques e fricção.** O sistema atual exige navegação confusa para abrir um teste ou relatório.
- **Usuários com baixa familiaridade tecnológica** entre os gestores — interface precisa ser autoexplicativa.
- **"Falta glamour"** foi a expressão usada: o cliente reconhece que o produto atual é funcional mas feio, e considera a apresentação visual crítica para a percepção da marca.
- **Automatizar sem despersonalizar:** preocupação declarada de que a automação afaste a equipe do aluno. A tecnologia deve facilitar processos, não substituir o relacionamento.

---

## 5. Fora do escopo imediato (backlog / oportunidades futuras)

- **Scout / análise de desempenho esportivo:** hoje 100% manual (assistir a ~10 jogos por atleta, marcando passes, finalizações etc.). Cliente quer rentabilizar o serviço reduzindo o trabalho manual — possível produto futuro.
- Integração nativa com WhatsApp para notificações, lembretes e confirmações de agendamento.
- **Cobrança:** área para o aluno ver se a mensalidade está paga, a data de vencimento e trocar a forma de pagamento. Hoje a recepcionista cobra por mensagem.
- **Observações do treino anterior:** mostrar automaticamente, na agenda do dia, as observações do último relatório de treino do aluno, sem o professor precisar abrir o relatório.
- Aplicativo nativo (o time faz o site desktop-first, com versão mobile).
