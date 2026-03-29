# Análise de Usabilidade, UX e Acessibilidade

O desenvolvimento da interface não se limitou à estética; cada decisão foi fundamentada em princípios sólidos de Interação Humano-Computador (IHC). Nesta seção, detalhamos como o design atende às Heurísticas de Usabilidade de Nielsen, garante a comunicabilidade através de signos metalinguísticos claros e promove uma experiência inclusiva, respeitando as necessidades da persona de acessibilidade definida no início do projeto.

## Aplicação das Heurísticas de Nielsen
> **As 10 Heurísticas de Usabilidade de Nielsen são um conjunto de diretrizes de design amplamente aceitas que representam princípios gerais para a avaliação e melhoria da usabilidade de interfaces de usuário. Estas heurísticas focam em garantir que o sistema seja intuitivo, eficiente e fácil de usar ao cobrir aspectos como a visibilidade do status do sistema (manter o usuário informado), a correspondência com o mundo real (uso de linguagem familiar), o controle e a liberdade do usuário (saídas de emergência como Undo), a consistência e padronização (uso uniforme de elementos), a prevenção de erros, o reconhecimento em vez de recordação (minimizar a carga de memória), a flexibilidade e eficiência (atalhos para usuários avançados), o design estético e minimalista (evitar distrações), o diagnóstico e recuperação de erros (mensagens claras) e a ajuda e documentação (informações de apoio).**

> **Objetivo:** Demonstrar a conformidade do sistema com os princípios gerais de design de interface para garantir facilidade de uso e aprendizado.

A tabela abaixo descreve onde e como as heurísticas selecionadas se manifestam nas telas do aplicativo:

| Heurística de Nielsen | Tela / Contexto | Como se manifesta no Design? |
| :--- | :--- | :--- |
| **1.Ajuda e Documentação 2.Correspondência entre o Sistema e o Mundo Real <br> 3. Controle e Liberdade do Usuário**| <img width="394" height="891" alt="TrainerX64 (1)" src="https://github.com/user-attachments/assets/60605f7c-261b-4d49-8465-b7e9ffb84921" /> | *1: A frase "Não tem uma conta? Crie uma agora" sugere um link ou modal de ajuda para novos usuários. <br> 2: Utiliza campos familiares de login/perfil (Email, Senha, Opção de "Esqueci a senha") que correspondem à convenção de acesso de qualquer serviço digital. <br> 3: O ícone de seta (voltar) no canto superior esquerdo.* |
| **1. Estética e Design Minimalista <br> 2. Reconhecimento em Vez de Recordação** | <img width="394" height="884" alt="TrainerX64 (2)" src="https://github.com/user-attachments/assets/75441a05-2b2b-4398-a868-c6feec6b0e5a" /> | *1: A tela de boas-vindas tem um design limpo, priorizando o resumo das métricas principais e o acesso rápido aos módulos. <br> 2: Os ícones são combinados com textos claros ("Alunos", "Treinos", "Agenda", "Avaliação Física"), facilitando o reconhecimento rápido das funcionalidades.* |
| **1. Correspondência entre o Sistema e o Mundo Real <br> 2. Consistência e Padronização** | <img width="405" height="905" alt="TrainerX64 (3)" src="https://github.com/user-attachments/assets/2c7b6bbd-e30f-4a06-9d78-2c9a94609801" /> | *1: O uso de termos familiares do universo do fitness ("Supino Reto", "Puxada Frontal") e a separação por categorias (Membros e Corpo) ajudam a corresponder o sistema à lógica de um treino real. <br> 2: O padrão de seleção de exercícios através de um pop-up (modal) é consistente; a estrutura de filtros e busca se mantém padronizada.* |
| **1. Reconhecimento em Vez de Recordação <br> 2. Controle e Liberdade do Usuário <br> 3. Ajuda para Reconhecer, Diagnosticar e Recuperar-se de Erros** |<img width="397" height="892" alt="criar treinos" src="https://github.com/user-attachments/assets/269b9053-d68d-407b-9067-c4263689abae" /> | *1: Textos de exemplo nos campos ("Ex: Peito e Tríceps, Full Body A") e descrições claras dos campos. <br> 2: O ícone de seta (voltar) no canto superior esquerdo. <br> 3: O ponto de interrogação (?) no canto superior direito.* |
| **1. Consistência e Padronização <br> 2. Flexibilidade e Eficiência de Uso <br> 3. Visibilidade do Status do Sistema** | <img width="397" height="874" alt="Login Screen for Training System" src="https://github.com/user-attachments/assets/0a5149cb-9b2d-40a1-a1ea-73aecb9d1c41" /> | *1: O padrão de lista (foto/emoji, nome, status, seta de acesso) é idêntico para todos os 10 alunos. <br> 2: O campo de "Pesquisar aluno..." e os filtros "Todos", "Treino Atualizado", "Personalizados". <br> 3: Informações como "Último treino há X dias" e "Avaliação pendente" (em verde/vermelho/destaque).* |
| **1. Consistência e Padronização <br> 2. Flexibilidade e Eficiência de Uso <br> 3. Estética e Design Minimalista <br> 4. Reconhecimento em Vez de Recordação** | <img width="394" height="891" alt="TrainerX64 (6)" src="https://github.com/user-attachments/assets/f8c1f429-767f-4f62-8232-af12ab93ab2f" /> | *1:O padrão de card (cartão) para representar cada treino ativo (Treino A, Treino B, Treino C) é idêntico na estrutura. <br> 2:O botão de ação principal "Iniciar Treino Agora" em destaque. <br> 3: O design foca nas informações essenciais do treino (nome, foco muscular, duração) e a ação principal ("Iniciar"), minimizando elementos de distração. <br> 4: Os ícones de navegação na parte inferior (Home, Treinos, Progresso, Perfil) combinados com o texto.* |
| **1.. Reconhecimento em Vez de Recordação <br> 2. Flexibilidade e Eficiência de Uso <br> 3. Estética e Design Minimalista <br> 4. Ajuda e Documentação** | <img width="394" height="891" alt="TrainerX64 (7)" src="https://github.com/user-attachments/assets/959b771e-3796-4bb6-ae2b-c3405496891e" /> | *1:O gráfico permite que o aluno reconheça sua tendência de peso ao longo do tempo (visualização de dados), ao invés de ter que lembrar todos os números. <br> 2:A capacidade de alternar o período de visualização (7, 30 ou 90 dias) com um único toque. <br> 3: A tela foca no gráfico e nas métricas principais, usando a cor verde para destacar o progresso positivo. <br> 4: O ícone de informação (i) no canto superior direito ao lado do título "Meu Progresso".* |
| **1. Visibilidade do Status do Sistema <br> 2. Controle e Liberdade do Usuário <br> 3.Flexibilidade e Eficiência de Uso** | <img width="394" height="891" alt="TrainerX64 (8)" src="https://github.com/user-attachments/assets/a53c676c-2577-4037-b668-f48dfddd18e3" /> | *1: O header mostra "Full Body A" e "1/5 exercícios", e a barra de progresso verde indica o tempo do treino ("45 min"). <br> 2: O ícone de seta (voltar) no canto superior esquerdo. <br> 3: O grande botão "Descanso" com o tempo decrescente.* |
| **1. Consistência e Padronização <br> 2. Visibilidade do Status do Sistema <br> 3. Reconhecimento em Vez de Recordação** | <img width="394" height="891" alt="TrainerX64 (9)" src="https://github.com/user-attachments/assets/37e7b076-a4b5-4187-baec-c1f039158aa6" /> | *1: O uso de ícones (cadeado, pessoa, sino, etc.) ao lado de cada link de configuração. Além disso, o uso de toggles (botões liga/desliga) para as opções de notificação. <br> 2: O nome e a foto do aluno ("João Silva") no topo e o ID de acesso (#2847). <br> 3: Os títulos dos itens de configuração são descritivos ("Lembretes de treino", "Alertas de progresso").* |
| **1. Controle e Liberdade do Usuário <br> 2.Consistência e Padronização <br> 3. Reconhecimento em Vez de Recordação <br> 4. Estética e Design Minimalista** |<img width="320" height="875" alt="Container" src="https://github.com/user-attachments/assets/22aa42fb-d446-4699-b626-9f4a2db2f2d3" /> | *1:O ícone "X" (fechar) no canto superior direito. <br> 2: O uso de ícones uniformes ao lado de cada item de menu (Configurações, Meu Perfil, Histórico, Calendário). <br> 3:Os rótulos são claros e diretos ("Meu Perfil", "Minhas Metas", "Histórico", "Calendário"), dispensando a necessidade de o aluno memorizar a função de um ícone abstrato. <br> 4: O menu é limpo e vertical, usando o contraste do fundo escuro com textos claros.* |

---

## Acessibilidade e Inclusão
> **Foco:** Decisões de design que promovem uma experiência acessível, especialmente para a persona de acessibilidade do TP1.

Para garantir que o produto seja utilizável pelo maior número de pessoas, implementamos as seguintes diretrizes:

---

* [ ] **Contraste de Cores:** Todas as combinações de texto e fundo foram testadas e possuem taxa de contraste superior a **4.5:1** (Padrão WCAG AA), garantindo legibilidade para usuários com baixa visão.
<img width="350" height="700" alt="iPhone 16 Pro - 59" src="https://github.com/user-attachments/assets/4078fe85-7a3b-406b-9858-1db293f1d17e" />

---

* [ ] **Área de Toque:** Elementos interativos (botões e ícones) possuem área mínima de **44x44dp**, facilitando o uso por pessoas com dificuldades motoras.
<img width="350" height="700" alt="iPhone 16 Pro - 61" src="https://github.com/user-attachments/assets/8a89eae2-8f85-408e-bc05-5e43795b7057" />

---

* [ ] **Hierarquia Tipográfica:** Diferenciação clara entre títulos e corpo de texto para facilitar a leitura e o escaneamento visual da página.
<img width="350" height="700" alt="iPhone 16 Pro - 60" src="https://github.com/user-attachments/assets/a3406ba8-b04a-4618-b54d-0b269df010cb" />

---

## Comunicabilidade e Signos Metalinguísticos
> **Objetivo:** Explicar como a interface "conversa" com o usuário através de símbolos e códigos visuais.

Incorporamos signos comunicativos para reforçar mensagens e intenções sem depender exclusivamente de texto:

---

* **Feedback Visual de Estado:** Cores semânticas universais foram aplicadas (Verde = Sucesso/Segurança; Vermelho = Erro/Perigo; Amarelo = Atenção).
<img width="350" height="700" alt="Login Screen for Training System" src="https://github.com/user-attachments/assets/b194eef9-c23c-4471-929a-982892a4d76b" />


---

* **Iconografia de Apoio:** Os ícones não são apenas decorativos; eles funcionam como rótulos visuais que antecipam a função do botão antes mesmo da leitura do texto.
<img width="350" height="700" alt="TrainerX64 (9)" src="https://github.com/user-attachments/assets/085daad3-c0f4-481f-8e5c-8f0330a67cfe" />

---

* **Microinterações:** Animações sutis (como um botão que muda de cor ao ser clicado) servem como feedback tátil-visual, confirmando que a ação física do usuário foi registrada pelo sistema.
<img width="350" height="700" alt="iPhone 16 Pro - 27" src="https://github.com/user-attachments/assets/c6b1c124-ff97-4521-861e-6c6526301a0f" />
<img width="350" height="700" alt="iPhone 16 Pro - 31" src="https://github.com/user-attachments/assets/5bb63d75-3f40-4e18-85ea-509a3cca3d41" /> 


---

## **Conclusão da Seção**
A análise acima evidencia que o design proposto vai além da aparência. Ao integrar as Heurísticas de Nielsen, priorizar a acessibilidade e utilizar uma linguagem visual clara, criamos uma interface que é robusta, tolerante a erros e intuitiva. Essas qualidades asseguram que o usuário final, independentemente de suas limitações ou nível de experiência técnica, consiga atingir seus objetivos com eficácia e satisfação.
