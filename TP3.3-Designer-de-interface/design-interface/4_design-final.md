# Design Final da Interface
>O aplicativo TrainerX64 foi desenvolvido com foco em simplicidade, facilidade de navegação e eficiência no uso por personal trainers e alunos. O design segue uma estética moderna, escura (dark theme), predominando tons de preto, cinza e ícones coloridos de fácil identificação. O layout prioriza hierarquia visual, contraste e ergonomia para dispositivos móveis.

-----

## Design final interface: **Personal Trainer**

## Telas Principais
### 1. Tela de Boas-Vindas  

   <img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/8e41d4d5-e06e-442e-b8df-d163ca99639a" />



- Logotipo centralizado.
- Duas opções de acesso:
- Para Personal Trainers.
- Para Alunos.
- Botão principal "Começar".

### 2. Tela de Login  

   <img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/4f5b5e30-fe05-41c1-b1b1-eda0e052d46e" />

- Seleção de usuário.
- E-mail.
- Senha.
- Ações:
-- Entrar.
-- Recuperar senha.
-- Criar nova conta.

### 3. Tela Home do Personal  

   <img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/df618b27-df19-4819-8da1-57dfff2d8711" />

- Estatísticas Rápidas

- Cards com informações principais:

- Alunos Ativos.

- Treinos Pendentes.

- Avaliações Recentes.

- Ações Rápidas

- Criar Treino.

- Cadastrar Aluno.

- Avaliação Física.

- Agenda da Semana.

- Alunos Recentes

- Lista com nome do aluno e status atualizado.


## Estrutura de Navegação

A aplicação utiliza uma barra de navegação inferior fixa, permitindo alternância rápida entre as principais áreas do sistema.

### 1. Menu Inferior  

   <img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/d2a22729-2060-4c93-811f-13baf1047517" />


- Itens do menu:

- Home

- Alunos

- Treinos

- Perfil

O item selecionado é destacado visualmente.


## Telas Internas
### 1. Tela "Meus Alunos"  

   <img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/5a6511b3-6a76-43a0-9635-03b4d92bee26" />

 Exibe:

- Foto.

- Nome.

- Última atualização.

- Status.

- Filtros disponíveis:

- Todos.

- Iniciantes.

- Intermediários.

- Avançados.

### 2. Tela "Detalhes do Aluno"  

   <img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/77e8e558-6dba-45b4-8815-0aa65e535749" />


- Informações apresentadas:

- Foto e nome.

- Peso, altura, idade.

- Nível.

- Última avaliação.

- Último treino.

- Objetivo atual.

- Ações rápidas:

- Criar Treino.

- Enviar Mensagem.

- Avaliação Física.

### 3. Tela "Criar Treino"
<img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/6dea21fc-c9f9-422f-b2f0-bf8d40b12bbb" />


#### Campos:

- Nome do treino.

- Tipo de treino.

- Categoria.

- Descrição (opcional).

#### Ação:

- Adicionar Exercício.

### 4. Tela "Selecionar Exercício"
<img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/c423f4a5-1aaa-47bf-9e15-026229dc39d1" />


- Lista organizada por categorias:

- Peito.

- Costas.

- Pernas.

- Ombros.

- Bíceps.

- Tríceps.

- Abdômen.

#### Filtros superiores:

- Todos.

- Por grupo muscular.

### 5. Tela "Configurar Exercício"
<img width="277" height="569" alt="image" src="https://github.com/user-attachments/assets/3d72d27d-09d8-476a-8ce6-58f814c89ce4" />


#### Elementos:

- Nome do exercício.

- Séries.

- Repetições.

- Carga (opcional).

- Observações.

#### Ações:

- Voltar.

- Adicionar ao Treino.

## 4. Caminhos de Interação
>**Fluxo 1: Criar Treino**
- Home → Criar Treino → Preencher informações → Adicionar Exercícios → Configurar Exercício → Salvar

----

>**Fluxo 2: Ver Detalhes do Aluno**
- Home → Alunos Recentes → Detalhes do Aluno

----

>**Fluxo 3: Navegação Global**
- Home ↔ Alunos ↔ Treinos ↔ Perfil

-----


## Design final interface: **Aluno**

### Telas principais:

#### Tela de login Aluno:      

   <img width="300" height="550" alt="image" src="https://github.com/user-attachments/assets/498368bc-6f4b-4c2d-a38e-6188f68da048" />  
   
#### Tela de início Aluno:   

   <img width="300" height="550" alt="image" src="https://github.com/user-attachments/assets/bacfa38f-2ab9-45f7-8aa2-34b017438cb2" />  
   
#### Tela de Menu:   

   <img width="300" height="550" alt="image" src="https://github.com/user-attachments/assets/63e3665e-080c-4085-bb45-13d91ad2665f" />  
   
#### Tela de configurações Aluno:   

   <img width="300" height="550" alt="image" src="https://github.com/user-attachments/assets/127a10d9-3372-46ef-b00d-dcac018b8b57" />  
   
#### Tela de progrsso Aluno: 

   <img width="300" height="550" alt="image" src="https://github.com/user-attachments/assets/ffda2663-dd37-42c4-acb5-a2a9bee254bb" />


### Estrutura de Navegação
> **Definição:** A arquitetura de informação foi projetada para minimizar o número de toques necessários para alcançar as funções principais.

A navegação do aplicativo se dá através dos seguintes componentes estruturais:

* **Barra de Navegação :**
    * Localizada na parte inferior da tela, fornece acesso rápido às 4 áreas principais do sistema: *Home, Treinos, Progresso e Perfil*.
      
      <img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/e4aa7b71-1b40-4206-817c-1f2eb42d125b" />

* **Cabeçalhos:**
    * Contêm o título da seção atual para contexto e, em telas secundárias, apresentam o botão de "Voltar" (Back Button) no canto superior esquerdo.
 
      <img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/c4954834-cf84-433c-b065-18bbb47df761" />

* **Botões de Ação :**
    * Botões de Ação utilizam a cor primária para indicar o próximo passo lógico.
      
      <img width="588" height="96" alt="image" src="https://github.com/user-attachments/assets/c9146054-f1ed-485f-8feb-9ca5871177b9" />


---


---

## 4.3 Link para o Protótipo Interativo
Para uma avaliação completa da navegabilidade e das microinterações, acesse o protótipo de alta fidelidade:

[🔗 **Acessar Protótipo Navegável (Figma)**](https://www.figma.com/design/QDhrF9N98vg6GZWGxVKpuo/TrainerX64?node-id=111-869&t=4T94EL9FzGKPkZqX-1)

---

**Conclusão da Seção**
O design final apresentado reflete uma interface limpa e consistente. A estrutura de navegação padronizada reduz a curva de aprendizado, enquanto o uso estratégico de botões e barras orienta o usuário através dos fluxos de tarefa sem ambiguidade. [cite_start]As decisões de layout respeitam as diretrizes de usabilidade, garantindo que a interação seja fluida tanto para usuários novatos quanto para os experientes[cite: 7, 76].
