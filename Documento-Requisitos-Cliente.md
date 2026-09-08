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
  2. **Área do Aluno / Atleta**
  3. **Área do Responsável**
  4. **Área do Professor**
  5. **Área de Coordenação / Admin / Recepção**
  6. **Dashboard CEO / Diretoria**
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
 
## 4. Área do Aluno / Atleta
 
- **Agendamento autônomo:** ver horários disponíveis, marcar, desmarcar e remarcar sem precisar mandar mensagem para a recepção.
  - Dor citada: alunos ficam constrangidos de mandar mensagem desmarcando ou trocando horário em cima da hora.
- **Créditos semanais:** exibir saldo (ex.: 5 treinos/semana), com **reset semanal** e **sem acúmulo**.
- **Histórico de treinos e relatórios** do professor.
- **Evolução dos testes físicos** em formato visual/gráfico.
- **Avaliação do treino / do professor** pelo aluno (canal de feedback — necessidade explícita da gestão).
- **Notificações e lembretes**, preferencialmente via WhatsApp:
  - Lembrete do treino agendado (ex.: agendou domingo o treino de terça 18h)
  - Pedido de confirmação de presença
- **Área financeira:**
  - Status da mensalidade (paga / em aberto) e data de vencimento
  - Detalhamento do que está sendo cobrado
  - Troca da forma de pagamento (ex.: débito → crédito)
  - Objetivo: eliminar a cobrança manual feita hoje pela recepcionista
---
 
## 5. Área do Responsável
 
- Acesso próprio, separado do aluno.
- **Visualização simplificada** — o responsável normalmente não tem familiaridade com termos de educação física.
- **Gráficos de evolução** dos testes ao longo do tempo (referência dada pelo cliente: gráfico evolutivo de exames laboratoriais do Sérgio Franco).
- Relatórios **curtos e visuais**. Os relatórios antigos, de 16–17 páginas, não eram lidos pelos pais.
- Canal de comunicação e acompanhamento do desenvolvimento do filho.
---
## 6. Área do Professor
 
- **Agenda do dia**, com filtro por unidade/marca (PKZ, One to One ou todos).
- **Confirmação de presença / check-in** do aluno — o relatório só é liberado após marcar a presença.
- **Formulário de relatório de treino** rápido, com campos:
  - Objetivo da sessão (ex.: hipertrofia, membros inferiores)
  - Intensidade
  - Desempenho (dentro do esperado / abaixo / acima)
  - Dor ou desconforto
  - Conduta para a próxima aula
  - Campo livre de observações relevantes
- **Formulários diferenciados** para PKZ (atleta) e One to One (estúdio).
- **Observações do treino anterior exibidas automaticamente** na agenda / no check-in, sem o professor precisar buscar o aluno e abrir o histórico. *(Solicitação enfatizada na reunião.)*
- **Lista de relatórios de treino pendentes** por professor.
- Preenchimento possível pelo app do professor **ou** pelo terminal da recepção.
- **UX otimizada por tempo:** o professor atende até 3 alunos por horário — o fluxo precisa ser rápido para não fazê-lo perder o timing da aula.
---
 
## 7. Área de Coordenação / Admin / Recepção
 
- **Cadastro completo do aluno** (ficha, dados pessoais, responsáveis).
- **Testes físicos:** lançamento dos ~16 testes, com parametrização por faixa etária/categoria (ex.: atleta de 7 anos avaliado dentro da categoria de 7 anos).
- **Controle de reteste:** alerta automático de quem está com a reavaliação mensal atrasada.
  - Dor atual: controle manual em Excel; retestes atrasavam, gerando problema de relacionamento com os pais.
- **Montagem do cronograma/microciclo mensal** de treinos.
- **Upload e anexo de arquivos externos** ao perfil do aluno (ex.: laudo do fisioterapeuta, exames — documentos não gerados pelo sistema).
- **Gestão de créditos e frequência** por aluno.
- **Agenda geral** com filtro por unidade e visão consolidada.
- **Gestão de cobrança/mensalidades**, retirando essa função do contato pessoal da recepcionista.
---
 
## 8. Dashboard CEO / Diretoria
 
- Visão consolidada com os indicadores já citados como necessários:
  - **Alunos ativos**
  - **Atividades/treinos realizados no mês**
  - **Testes físicos realizados no mês**
  - **Relatórios preenchidos vs. pendentes**
- Recorte por **unidade** (sede, Vogue Square, Oasis) e por **marca** (PKZ / One to One).
- Indicadores financeiros e de inadimplência.
- Frequência e adesão dos alunos.
- Feedbacks dos alunos consolidados.
---
 
## 9. Diretrizes de UX/UI (pedidos explícitos do cliente)
 
- **Priorizar o visual sobre o numérico.** Tabelas com muitos números não são compreendidas pelos pais — traduzir em gráficos e indicadores palpáveis.
- **Reduzir cliques e fricção.** O sistema atual exige navegação confusa para abrir um teste ou relatório.
- **Usuários com baixa familiaridade tecnológica** entre os gestores — interface precisa ser autoexplicativa.
- **"Falta glamour"** foi a expressão usada: o cliente reconhece que o produto atual é funcional mas feio, e considera a apresentação visual crítica para a percepção da marca.
- **Automatizar sem despersonalizar:** preocupação declarada de que a automação afaste a equipe do aluno. A tecnologia deve facilitar processos, não substituir o relacionamento.
---
 
## 10. Fora do escopo imediato (backlog / oportunidades futuras)
 
- **Scout / análise de desempenho esportivo:** hoje 100% manual (assistir a ~10 jogos por atleta, marcando passes, finalizações etc.). Cliente quer rentabilizar o serviço reduzindo o trabalho manual — possível produto futuro.
- Integração nativa com WhatsApp para notificações e confirmações.
- Aplicativo mobile (o foco atual do nosso time é desktop).