# Análise Hierárquica de Tarefas (AHT)

Este documento apresenta a legenda visual, o padrão de leitura e o índice das Análises Hierárquicas de Tarefas da plataforma digital PKZ & One to One.

## 1. Como ler os diagramas

Cada AHT parte de um objetivo principal e o divide em tarefas numeradas. A numeração indica a hierarquia: por exemplo, `6.4.1` é uma subtarefa de `6.4`, que pertence à tarefa principal `6`.

As linhas representam relações hierárquicas entre objetivos, tarefas e subtarefas. A ordem de execução e as condições especiais aparecem no bloco **Plano**, localizado na parte inferior de cada diagrama.

## 2. Legenda de cores e estilos

| Aparência do retângulo | Significado | Exemplo |
|---|---|---|
| **Azul-marinho escuro, texto branco** | Objetivo ou tarefa principal da AHT | `6. Agendar a aula experimental` |
| **Branco, contorno azul-acinzentado** | Tarefa intermediária, agrupamento ou etapa geral | `6.4 Preencher os dados` |
| **Verde-claro, contorno verde** | Ação do usuário ou conteúdo disponível na interface | Escolher um horário ou ler um conteúdo |
| **Azul-claro, contorno azul** | Variação ou comportamento específico da versão mobile | Paginação da galeria no celular |
| **Laranja-claro, contorno laranja tracejado** | Transição para outra tela, saída do fluxo, confirmação fora da tela ou funcionalidade futura | Abrir WhatsApp ou acessar área futura |
| **Cinza, contorno preto** | Plano de execução, sequência, condição ou observação do fluxo | `Plano 6: 6.1 → 6.2 → 6.3...` |

### Elementos complementares

- **Linha azul-acinzentada:** relação entre uma tarefa e suas subtarefas.
- **Seta no texto (`→`):** destino ou continuação do fluxo.
- **`[PKZ]`:** conteúdo ou comportamento específico da PKZ.
- **`[OTO]`:** conteúdo ou comportamento específico da One to One.
- **`[DESKTOP]`:** elemento exclusivo ou adaptado para computador.
- **`[MOBILE]`:** elemento exclusivo ou adaptado para celular.
- **Fim de ramo:** ponto em que a navegação sai da AHT atual, termina ou depende de uma etapa futura.

## 3. Regras de padronização

1. O azul-marinho deve aparecer somente no objetivo principal de cada AHT.
2. O verde deve identificar ações e conteúdos efetivamente disponíveis na interface.
3. O azul-claro deve ser reservado às diferenças da experiência mobile.
4. O laranja tracejado deve identificar transições, saídas do fluxo, confirmações externas ou itens ainda não representados por uma tela.
5. O cinza deve ser usado apenas no plano de execução.
6. As siglas PKZ, OTO, DESKTOP e MOBILE devem aparecer entre colchetes e em letras maiúsculas.
7. As tarefas devem manter numeração hierárquica e corresponder ao número do objetivo principal.
8. Cada diagrama deve possuir um plano, exceto quando a própria imagem funcionar apenas como visão geral do conjunto.

## 4. Índice das AHTs

| Código | Página ou fluxo | Objetivo principal | Arquivo |
|---|---|---|---|
| AHT-01 | Visão geral | Agendar a aula experimental gratuita | [AHT_01_Visao_Geral.png](AHT_01_Visao_Geral.png) |
| AHT-02 | Hub | Escolher a marca no Hub | [AHT_02_Hub.png](AHT_02_Hub.png) |
| AHT-03 | Home | Confirmar que é o programa certo | [AHT_03_Home.png](AHT_03_Home.png) |
| AHT-04 | Sobre nós | Confirmar que é o programa certo | [AHT_04_Sobre_Nos.png](AHT_04_Sobre_Nos.png) |
| AHT-05 | Treinos | Entender como funciona o treino | [AHT_05_Treinos.png](AHT_05_Treinos.png) |
| AHT-06 | Planos | Ver os planos | [AHT_06_Planos.png](AHT_06_Planos.png) |
| AHT-07 | Unidades | Checar a unidade | [AHT_07_Unidades.png](AHT_07_Unidades.png) |
| AHT-08 | Galeria | Checar a galeria | [AHT_08_Galeria.png](AHT_08_Galeria.png) |
| AHT-09 | Agendamento | Agendar a aula experimental | [AHT_09_Agendamento.png](AHT_09_Agendamento.png) |
| AHT-10 | Contato | Falar com a equipe | [AHT_10_Contato.png](AHT_10_Contato.png) |
| AHT-11 | Cadastro | Fazer o cadastro ou entrar | [AHT_11_Cadastro.png](AHT_11_Cadastro.png) |

## 5. Verificação de consistência

| AHT | Correspondência verificada | Observação |
|---|---|---|
| AHT-01 | Hub, Home, Sobre nós, Treinos, Planos, Unidades, Galeria, Agendamento, Contato e Cadastro | Visão condensada; não utiliza todas as cores porque resume o percurso completo. |
| AHT-02 | Hub desktop e mobile | Diferencia PKZ e One to One antes da entrada nas landing pages. |
| AHT-03 | Home das duas marcas | CTAs direcionam o visitante para o fluxo de agendamento. |
| AHT-04 | Sobre nós | Registra a comparação entre programas como transição cujo destino ainda não possui tela. |
| AHT-05 | Treinos | Representa avaliação, programa e acompanhamento, com variações de conteúdo por marca. |
| AHT-06 | Planos | Representa comparação de opções e direcionamento para aula experimental ou contato. |
| AHT-07 | Unidades | Corresponde à apresentação da sede principal e do mapa. |
| AHT-08 | Galeria | Registra a paginação específica da experiência mobile. |
| AHT-09 | Agendamento | Cobre acesso, escolha de dia e horário, dados, conflito de reserva e confirmação. |
| AHT-10 | Contato | Cobre canais por marca e saída do fluxo para o WhatsApp. |
| AHT-11 | Cadastro | Diferencia os campos da PKZ e da One to One e identifica a área do aluno como fase futura. |

## 6. Observações de legibilidade

- As AHTs 01 e 09 são diagramas horizontais extensos e devem ser exibidas ocupando a largura completa da página ou da tela.
- Para apresentação, recomenda-se ampliar as AHTs 01 e 09 ou dividi-las visualmente por etapas durante a explicação.
- As demais imagens possuem menos ramificações e podem ser apresentadas integralmente.
- As imagens devem ser visualizadas em tamanho original para evitar perda de legibilidade nos textos menores.
- Novas AHTs devem seguir a legenda desta documentação para manter a consistência do conjunto.
