# Product Backlog - Plataforma Digital PKZ & One to One

**Projeto:** PFE 2026.2 - AP1 - Grupo 4 (terça)  
**Scrum Master:** Igor Santos  
**Equipe:** Arthur Alves, Caio Abanca, Guilherme Teixeira, Igor Santos, Lucas Cunha, Matheus Borges e Rodrigo Mourão  
**Última atualização:** 28 de setembro de 2026

## 1. Finalidade

Este backlog foi reconstruído retrospectivamente a partir dos artefatos concluídos no repositório. Ele registra o trabalho necessário para produzir as entregas existentes e cria rastreabilidade entre tarefas, Sprints e arquivos. Não representa desenvolvimento de código: o incremento atual é composto por descoberta, documentação, arquitetura de informação, análise de tarefas e prototipação.

## 2. Critérios de priorização

- **Alta:** necessária para compreender o problema, definir o escopo ou validar a solução.
- **Média:** detalha fluxos e transforma os requisitos em uma solução visual.
- **Baixa:** melhoria editorial ou organizacional que não bloqueia as demais entregas.

## 3. Definition of Done

Um item é considerado concluído quando:

1. o artefato correspondente está salvo no repositório;
2. o conteúdo está coerente com a entrevista e com o escopo aprovado;
3. nomes, termos, marcas e navegação estão consistentes;
4. o material pode ser compreendido por outra pessoa da equipe sem explicação adicional;
5. não existem lacunas conhecidas que impeçam o uso do artefato na etapa seguinte.

## 4. Backlog priorizado

| ID | Épico | Item de backlog | Critério de aceitação | Prioridade | Sprint | Status | Evidência |
|---|---|---|---|---|---|---|---|
| PB-01 | Descoberta | Registrar integralmente a reunião com o cliente | A transcrição preserva as falas e as demandas relevantes das duas marcas | Alta | 1 | Concluído | `transcrição-e-requisitos/transcrição.md` |
| PB-02 | Descoberta | Identificar contexto, dores, públicos e objetivos | O levantamento distingue PKZ, One to One, responsáveis, alunos e usuários internos | Alta | 1 | Concluído | `transcrição-e-requisitos/Documento-Requisitos-Cliente.md` |
| PB-03 | Descoberta | Catalogar funcionalidades solicitadas | Site, áreas por perfil, agendamento, avaliações, relatórios, créditos e gestão estão registrados | Alta | 1 | Concluído | `transcrição-e-requisitos/Documento-Requisitos-Cliente.md` |
| PB-04 | Planejamento | Realizar brainstorm presencial | O problema, as ideias, as diretrizes de UX e os primeiros esboços estão registrados | Alta | 1 | Concluído | `Brainstorm/Brainstorm.pdf` |
| PB-05 | Planejamento | Definir método de trabalho e papéis | Scrum Master, equipe, divisão em Sprints e prazo interno estão registrados | Alta | 1 | Concluído | `Brainstorm/Brainstorm.pdf` |
| PB-06 | Produto | Definir visão, problema e proposta de solução | O documento explica oportunidade, problema e valor esperado da plataforma | Alta | 1 | Concluído | `Doc-visão/DOCUMENTO_DE_VISAO.md` |
| PB-07 | Produto | Mapear stakeholders e necessidades | Públicos decisores, usuários finais, gestores e equipe técnica estão descritos | Alta | 1 | Concluído | `Doc-visão/DOCUMENTO_DE_VISAO.md` |
| PB-08 | Produto | Delimitar escopo atual e fase seguinte | Site público, plataforma logada e itens futuros aparecem claramente separados | Alta | 1 | Concluído | `Doc-visão/DOCUMENTO_DE_VISAO.md` |
| PB-09 | Requisitos | Especificar requisitos funcionais e não funcionais | Requisitos possuem identificador, descrição e vínculo com o escopo | Alta | 1/2 | Concluído | `Doc-visão/DOCUMENTO_DE_VISAO.md` |
| PB-10 | Planejamento | Elaborar análise 5W2H | O documento responde What, Why, Who, Where, When, How e How Much | Média | 1 | Concluído | `5w2h/5W2H.md` |
| PB-11 | Arquitetura | Criar mapa mental da solução | Área pública, marcas, páginas e perfis estão organizados visualmente | Média | 1 | Concluído | `Mindmap/mindmap-final.png` |
| PB-12 | Requisitos | Refinar o fluxo de aula experimental | CTA, dados mínimos, confirmação e independência de cadastro estão especificados | Alta | 2 | Concluído | RF23 e RNF11 do Documento de Visão |
| PB-13 | Requisitos | Definir regras de disponibilidade de horários | Horários livres/ocupados e prevenção de dupla reserva estão especificados | Alta | 2 | Concluído | RF24 do Documento de Visão |
| PB-14 | Arquitetura | Definir estrutura do Hub | O Hub permite escolher a marca e comunicar os dois públicos sem misturar posicionamentos | Alta | 2 | Concluído | `AHT/AHT_02_Hub.png` e protótipo do Hub |
| PB-15 | UX | Modelar tarefas gerais e navegação | A visão geral da AHT representa a entrada e os caminhos principais do site | Alta | 2 | Concluído | `AHT/AHT_01_Visao_Geral.png` |
| PB-16 | UX | Modelar tarefas de Home e Sobre nós | Objetivos, subtarefas e sequência de interação estão representados | Média | 2 | Concluído | `AHT/AHT_03_Home.png` e `AHT/AHT_04_Sobre_Nos.png` |
| PB-17 | UX | Modelar tarefas de Treinos, Planos e Unidades | Os três fluxos possuem decomposição hierárquica compreensível | Média | 2 | Concluído | `AHT/AHT_05_Treinos.png` a `AHT/AHT_07_Unidades.png` |
| PB-18 | UX | Modelar tarefas de Galeria, Agendamento, Contato e Cadastro | Os quatro fluxos possuem decomposição hierárquica e correspondem aos requisitos | Alta | 2 | Concluído | `AHT/AHT_08_Galeria.png` a `AHT/AHT_11_Cadastro.png` |
| PB-19 | UI | Criar protótipo desktop do Hub | A tela diferencia PKZ e One to One e direciona para cada landing page | Alta | 2 | Concluído | `protótipo-da-interface/prototipo-HUB/Hub_PKZ_One_to_One.png` |
| PB-20 | UI | Criar protótipo mobile do Hub | A versão móvel preserva escolha de marca, legibilidade e hierarquia | Alta | 2 | Concluído | `protótipo-da-interface/prototipo-HUB/Prototipo-hub-mobile.pdf` |
| PB-21 | UI PKZ | Prototipar Home, Sobre nós e Treinos no desktop | As telas comunicam público jovem, metodologia e proposta da PKZ | Alta | 2 | Concluído | telas 1 a 3 de `pkzDesktop/` |
| PB-22 | UI PKZ | Prototipar Planos, Unidades e Galeria no desktop | As telas apresentam oferta, localização e conteúdo visual da PKZ | Média | 2 | Concluído | telas 4 a 6 de `pkzDesktop/` |
| PB-23 | UI PKZ | Prototipar Contato, Agendamento e Cadastro no desktop | Os fluxos possuem CTAs, dados essenciais e identidade da PKZ | Alta | 2 | Concluído | telas 7 a 9 de `pkzDesktop/` |
| PB-24 | UI One to One | Prototipar Home, Sobre nós e Treinos no desktop | As telas comunicam atendimento premium e personalizado para adultos | Alta | 2 | Concluído | telas 1 a 3 de `OneToOneDesktop/` |
| PB-25 | UI One to One | Prototipar Planos, Unidades e Galeria no desktop | As telas apresentam oferta, localização e conteúdo visual da marca | Média | 2 | Concluído | telas 4 a 6 de `OneToOneDesktop/` |
| PB-26 | UI One to One | Prototipar Contato, Agendamento e Cadastro no desktop | Os fluxos possuem CTAs, dados essenciais e identidade One to One | Alta | 2 | Concluído | telas 7 a 9 de `OneToOneDesktop/` |
| PB-27 | Responsividade | Adaptar toda a landing page PKZ para mobile | Todas as seções e fluxos principais possuem versão móvel legível | Alta | 3 | Concluído | `pkzMobile/Prototipo-pkz-mobile.pdf` |
| PB-28 | Responsividade | Adaptar toda a landing page One to One para mobile | Todas as seções e fluxos principais possuem versão móvel legível | Alta | 3 | Concluído | `OneToOneMobile/Prototipo-onetoone-mobile.pdf` |
| PB-29 | Qualidade | Revisar consistência entre requisitos, AHT e protótipos | Páginas, CTAs, termos e fluxos correspondem entre os três conjuntos de artefatos | Alta | 3 | Concluído | Documento de Visão, AHT e protótipos |
| PB-30 | Qualidade | Atualizar 5W2H com datas e decisões finais | Linha do tempo e estratégia refletem as entregas até 25/09/2026 | Média | 3 | Concluído | `5w2h/5W2H.md` |
| PB-31 | Repositório | Organizar pastas e documentar entregas | O README permite localizar cada entrega e explica a estrutura dos protótipos | Média | 3 | Concluído | `README.md` |
| PB-32 | Scrum | Registrar Sprints e rastreabilidade do backlog | Três relatórios de Sprint referenciam itens do Product Backlog | Média | 3 | Concluído | pasta `Scrum/` |

## 5. Itens identificados para fase futura

Os itens abaixo constam na visão do produto, mas não integram o incremento prototipado nesta AP1:

| ID | Item futuro | Situação |
|---|---|---|
| PF-01 | Implementar autenticação e criação de credenciais | Planejado para fase seguinte |
| PF-02 | Implementar áreas por perfil: responsável, atleta, aluno e gestor | Planejado para fase seguinte |
| PF-03 | Implementar avaliações, evolução, relatórios e cronograma | Planejado para fase seguinte |
| PF-04 | Implementar integração ou link para aplicativo | Planejado para fase seguinte |
| PF-05 | Incluir comparação entre os programas | Planejado para fase seguinte |
| PF-06 | Incluir depoimentos de pais e alunos | Planejado para fase seguinte |
| PF-07 | Incluir unidades Vogue Square e Oasis | Planejado para fase seguinte |
| PF-08 | Desenvolver e integrar o site funcional aos serviços necessários | Não iniciado nesta AP1 |
