# Levantamento de Demandas — PKZ (Playmakers) & One to One
 
> Documento extraído da transcrição da reunião com o cliente.
> Escopo do nosso time: **front-end web (desktop-first)** — site institucional + plataforma logada com áreas por perfil.
 
---
 
## 1. Contexto do Negócio
 
- Grupo com **duas marcas** operando no mesmo espaço físico (galeria dividida em dois lados):
  - **PKZ (Playmakers)** — centro de treinamento para **atletas** (crianças e adolescentes), com avaliação física, periodização e acompanhamento de evolução.
  - **One to One** — **estúdio de personal training**, atende adultos, atletas e não atletas, de todas as idades e objetivos.
- **Unidades:** sede principal, **Vogue Square** (em abertura) e **Oasis** (campo, com alunos de intercâmbio/High School).
- **Volume atual:** ~80 alunos (One to One) + ~60 alunos (PKZ) + ~60 atletas previstos no Oasis.
- **Metodologia PKZ:** avaliação inicial com ~16 testes físicos (salto, velocidade, agilidade, tempo de reação, força) → cronograma/microciclo mensal → relatório a cada treino → reavaliação mensal.
- **Sistema atual:** aplicativo amador feito internamente no Lovable (antes: Drive, Excel e ChatGPT). Resolve agendamento, mas é limitado e visualmente pobre.
### Público-alvo (dois perfis distintos de comunicação)
- **One to One:** contato direto com o próprio aluno (adulto).
- **PKZ:** contato majoritariamente com **responsáveis**. Hoje há déficit de comunicação — quem leva o atleta costuma ser motorista, babá ou segurança, e a equipe muitas vezes não conhece os pais.
---
 
## 2. Escopo do Projeto
 
- Front-end para **desktop/computador**.
- Entregáveis previstos:
  1. **Site institucional público** (não existe hoje)

---
 
## 3. Site Institucional (público)
 
- Cliente **não possui website** atualmente.
- Site único abrigando **as duas marcas**, com seções e comunicação separadas por público:
  - PKZ → público infantojuvenil / atleta em formação
  - One to One → todas as idades, todos os objetivos
- **Portfólio visual:** fotos e vídeos dos treinos das duas marcas.
- **Cadastro do aluno pelo site**, gerando login e senha de acesso à plataforma.
- **Link para o aplicativo** (facilitar download e inscrição).
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
- Integração nativa com WhatsApp para notificações e confirmações.
- Aplicativo mobile (o foco atual do nosso time é desktop).