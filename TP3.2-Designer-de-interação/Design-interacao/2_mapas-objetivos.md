# Mapa de Objetivos

O **Mapa de Objetivos** é uma etapa fundamental no processo de Design de Interação, pois permite identificar, organizar e representar de forma estruturada o que cada persona deseja alcançar ao utilizar o sistema e como o sistema deve apoiar esses objetivos. Ele transforma necessidades e expectativas em metas claras, que servem de base para toda a modelagem de interação posterior, como HTA e MoLIC.

Para este projeto, o mapa foi desenvolvido considerando três perfis principais:
> - Personal Trainer (PT) – responsável por gerenciar treinos, alunos, avaliações, agenda e comunicação.
> - Aluno (A) – usuário que segue treinos, registra execuções, acompanha desempenho e interage com o personal.
> - Aluno com Acessibilidade (AA) – usuário com baixa visão, que utiliza tecnologias assistivas e possui objetivos equivalentes aos do aluno comum, porém com necessidades específicas de navegação e leitura.

Durante a construção do mapa, foi aplicada a técnica de hierarquização de objetivos, iniciando pelos objetivos macros e detalhando-os em subobjetivos que representam ações ou funcionalidades necessárias.
Além disso, foram feitas ligações diretas entre objetivos semelhantes de A e AA, refletindo que o aluno com acessibilidade herda todas as funcionalidades do aluno padrão, mas com adaptações de acessibilidade, como:

> - leitura por voz
> - alto contraste
> - navegação simplificada
> - textos ampliados
> - descrições alternativas

Para isso, foi criado um objetivo específico para AA — Navegar com Autonomia — responsável por concentrar todos os recursos de acessibilidade utilizados para acessar, compreender e executar qualquer funcionalidade do sistema.
O resultado é um mapa completo, coerente e alinhado às necessidades reais das personas, servindo como guia para garantir que todas as etapas seguintes da modelagem de interação respeitem tanto a funcionalidade técnica, quanto a experiência do usuário, incluindo a acessibilidade de forma sólida e integrada.

----

# Legenda de Papéis

## A — Aluno
Usuário padrão do sistema.  
Segue treinos, acessa vídeos, registra execução e acompanha evolução.

## AA — Aluno com Acessibilidade
Possui **todas as funcionalidades do Aluno (A)**  
+ funcionalidades adicionais de acessibilidade (narração, alto contraste, leitores de tela).

## P — Personal Trainer
Cria treinos, ajusta cargas, visualiza desempenho e orienta o aluno.

### Convenção do Mapa
[A | AA] → Objetivo compartilhado  
AA → Objetivo exclusivo de acessibilidade  
→  Instrumenta diretamente

<img width="2498" height="1365" alt="Diagrama sem nome drawio (3)" src="https://github.com/user-attachments/assets/e0b7af4e-3b3d-4e5c-97f6-0651d091feab" />

### A seguir estão as legendas, cada uma descrevendo claramente o papel e a finalidade daquele grupo dentro do mapa de objetivos.

## 🟩 PT | Gerenciar Alunos

> Conjunto de objetivos relacionados ao gerenciamento completo de alunos pelo personal, incluindo cadastro, busca, atualização de informações e análise de performance.
-----
## 🟩 PT | Criar e Atualizar Treinos

> Abrange todas as ações do personal para montar, ajustar e personalizar treinos. Permite registrar cargas, montar treinos individualizados e visualizar histórico.
-----
## 🟩 PT | Acompanhar Evolução

> Responsável por acompanhar metas, progresso, histórico e comparação entre treinos, auxiliando o personal no monitoramento do desenvolvimento do aluno.
-----
## 🟩 PT | Organizar a Agenda

> Conjunto de ações voltadas para planejamento e organização do dia do aluno, como compromissos, lembretes e preparação do treino.
-----
## 🟩 PT | Controle Financeiro

> Abrange cobranças, mensalidades, pendências e pagamentos. Permite ao personal gerenciar a relação financeira com alunos.
-----
## 🟩 PT | Comunicação Interna

> Ações voltadas para envio de mensagens, receber avisos e organizar trocas de informações com o aluno.
-----
## 🟦 A | Acessar Sistema

> Conjunto que envolve entrada e autenticação no sistema: login, cadastro e acesso às funcionalidades principais.
-----
## 🟦 A | Seguir o Treino do Dia

> Acompanha todas as ações do aluno durante a execução do treino, como ver exercícios, séries, repetições, vídeos e cargas sugeridas.
-----
## 🟦 A | Acessar Vídeos e Instruções

> Conjunto dedicado ao acesso rápido às instruções técnicas, vídeos curtos, dicas e execuções corretas dos exercícios.
-----
## 🟦 A | Registrar Execução

> Conjunto que abrange registrar treino concluído, marcar exercícios como finalizados, adicionar cargas utilizadas e relatar dificuldades.
-----
## 🟦 A | Acompanhar Evolução

> Envolve gráficos, histórico de treinos, performance semanal e progresso geral.
-----
## 🟦 A | Comunicação

> Conjunto que cobre troca de mensagens com o personal e envio/recebimento de feedbacks.
-----
## 🟦 A | Notificações e Consistência

> Ações relacionadas a lembretes, avisos do personal e motivação para manter consistência.
-----
## 🟧 AA | Navegar com Autonomia

> Conjunto exclusivo para alunos com acessibilidade.
Inclui todos os recursos complementares de navegação, como:

- leitura por voz
- alto contraste
- navegação simplificada
- textos ampliados
- descrições alternativas
-----
*(Todos os outros objetivos do AA são herdados automaticamente dos objetivos do Aluno.)*
