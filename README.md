# 💰 7 Days of Code — App de Controle Financeiro
Repositório oficial do desafio **7 Days of Code**[span_8](start_span)[span_8](end_span). 
Ao longo de 7 dias, o objetivo é construir, na prática, utilizando Inteligência Artificial e a ferramenta **Lovable**[span_9](start_span)[span_9](end_span), um **App de Controle Financeiro** completo voltado para pequenos negócios e autônomos[span_10](start_span)[span_10](end_span). No final, o projeto estará publicado e pronto para o portfólio[span_11](start_span)[span_11](end_span).
---
## ⚙️ Como funciona
Cada dia do desafio possui uma etapa específica na construção da aplicação:
* **Conceito do dia** — A explicação do que você vai aprender[span_12](start_span)[span_12](end_span).
* **Desafio do dia** — O enunciado e o prompt sugerido para usar no Lovable[span_13](start_span)[span_13](end_span).
* **Saída esperada** — O resultado visual e funcional esperado ao final do dia[span_14](start_span)[span_14](end_span).
* **Exercício opcional** — Um extra para ir além (quando houver)[span_15](start_span)[span_15](end_span).
* **Dica** — Um direcionamento extra para ajudar no desafio[span_16](start_span)[span_16](end_span).
---
## 🗓️ Trilha Completa

| Dia | Tema | Resumo da Etapa |
| :--- | :--- | :--- |
| **[Dia 01](#-dia-017--criando-seu-app-com-ia)** | 🚀 Criando seu app com IA[span_17](start_span)[span_17](end_span) | Configuração inicial do projeto e estruturação da interface com IA no Lovable. |
| **[Dia 02](#-dia-027--registrando-suas-transações)** | 💰 Registrando suas transações[span_18](start_span)[span_18](end_span) | Criação de formulários e lógica para cadastro de receitas e despesas. |
| **[Dia 03](#-dia-037--criando-seu-extrato-e-exportando)** | 📋 Criando seu extrato[span_19](start_span)[span_19](end_span) | Desenvolvimento da tabela ou listagem dinâmica do fluxo financeiro. |
| **[Dia 04](#-dia-047--adicionando-filtros)** | 🔍 Adicionando filtros[span_20](start_span)[span_20](end_span) | Implementação de filtros por período, categoria e tipo de transação. |
| **[Dia 05](#-dia-057--resumo-financeiro-automático)** | 📊 Resumo financeiro automático[span_21](start_span)[span_21](end_span) | Cards de saldo total, receitas e despesas calculados em tempo real. |
| **[Dia 06](#-dia-067--visualizando-o-fluxo-de-caixa)** | 📈 Visualizando o fluxo de caixa[span_22](start_span)[span_22](end_span) | Inclusão de gráficos interativos para análise visual das finanças. |
| **[Dia 07](#-dia-077--finalizando-e-publicando)** | 🏁 Finalizando e publicando[span_23](start_span)[span_23](end_span) | Testes finais, ajustes de layout e publicação do app. |

---
## 🛠️ Pré-requisitos
* Conta gratuita no **Lovable**[span_24](start_span)[span_24](end_span)
* Criatividade[span_25](start_span)[span_25](end_span)
* Vontade de aprender construindo! 🚀[span_26](start_span)[span_26](end_span)
---
## 🚀 Dia 01/7 — Criando seu app com IA
### 💡 Conceito do dia
No Lovable, você não escreve código linha por linha: você **descreve o que quer** em um prompt, e a IA gera a interface para você. Quanto mais claro e específico for o seu prompt (o que a tela deve tener, qual o objetivo, qual o estilo visual), melhor será o resultado gerado.
### 🎯 Desafio do dia
1. Acesse [lovable.dev](https://lovable.dev) e crie uma conta gratuita (se ainda não tiver).
2. Crie um novo projeto.
3. No campo de prompt, descreva a tela inicial do seu app financeiro.
**Exemplo de prompt sugerido:**
> *Crie a tela inicial de um aplicativo de controle financeiro para pequenos negócios e autônomos. A tela deve ter um título chamativo, uma breve descrição do que o app faz, e um botão "Começar agora". Use um design limpo e profissional.*
4. Veja o resultado gerado pela IA e ajuste o prompt até ficar com uma cara que você goste (cores, textos, estilo).
### 👀 Saída esperada
Ao final, você deve ter uma tela inicial visível no preview do Lovable, com título, descrição curta e um botão "Começar agora" funcionando visualmente.
### 🏋️ Exercício opcional
Peça à IA para criar duas versões diferentes de título/descrição para a tela inicial, e escolha a que você achar mais convincente.
### 💡 Dica
Não se preocupe em acertar de primeira. Ajustar o prompt e pedir refinamentos é parte do processo, isso também é aprender a "programar" com IA.
---
## 💰 Dia 02/7 — Registrando suas transações
### 💡 Conceito do dia
Um **formulário** é a porta de entrada dos dados no seu app, é onde a pessoa usuária informa valores, escolhe categorias e registra informações. No Lovable, você descreve os campos que quer, e a IA monta a interface do formulário para você.
### 🎯 Desafio do dia
1. Volte ao seu projeto no Lovable.
2. No campo de prompt, peça a criação de uma tela/formulário de nova transação.
**Exemplo de prompt sugerido:**
> *Crie uma tela de cadastro de transação financeira, com os campos: valor, tipo (receita ou despesa), categoria (ex: vendas, aluguel, fornecedores, marketing) e data. Inclua um botão para salvar a transação.*
3. Teste preencher o formulário com uma transação de exemplo e veja se ele funciona corretamente.
4. Se quiser, peça para a IA ajustar o visual do formulário para combinar com a tela inicial que você já criou.
### 👀 Saída esperada
Você deve conseguir preencher valor, tipo, categoria e data no formulário, clicar em salvar, e ver que a ação é reconhecida pelo app (mesmo que ainda não fique salva permanentemente).
### 🏋️ Exercício opcional
Peça para a IA adicionar uma validação simples, tipo *"o campo valor não pode ficar vazio"*.
---
## 📋 Dia 03/7 — Criando seu extrato e exportando
### 💡 Conceito do dia
Exibir dados em **lista** ou **tabela** é uma das tarefas mais comuns em qualquer aplicativo. Além de mostrar as informações, é possível usar cores e formatação para deixar a leitura mais rápida e intuitiva, como destacar receitas e despesas com cores diferentes.
### 🎯 Desafio do dia
1. Volte ao seu projeto no Lovable.
2. No campo de prompt, peça a criação de uma lista/tabela com as transações cadastradas.
**Exemplo de prompt sugerido:**
> *Crie uma tela de extrato que exiba em formato de lista ou tabela todas as transações cadastradas, mostrando: data, categoria, tipo (receita ou despesa) e valor. Destaque receitas em verde e despesas em vermelho. Crie também um botão no qual será possível exportar em arquivo no formato `.csv` os dados.*
3. Cadastre 3 ou 4 transações de exemplo (algumas receitas, algumas despesas) para ver a listagem funcionando com dados reais.
4. Observe como ficou a organização visual — peça ajustes se algo estiver confuso ou desalinhado.
### 👀 Saída esperada
Ao cadastrar transações de exemplo, elas devem aparecer na tela de extrato, com receitas em verde e despesas em vermelho. E um botão para baixar sua planilha.
### 🏋️ Exercício opcional
Peça para a IA ordenar a lista da transação mais recente para a mais antiga.
### 💡 Dica
Pequenos detalhes visuais, como cores e ordenação, fazem o app parecer um "produto de verdade". Posicione o botão de exportação do Extrato de forma estratégica.
---
## 🔍 Dia 04/7 — Adicionando filtros
### 💡 Conceito do dia
**Filtros** permitem que a pessoa usuária veja apenas o que interessa em um determinado momento, sem precisar rolar a lista inteira. É uma das funcionalidades que mais aumentam a usabilidade de um app com muitos dados.
### 🎯 Desafio do dia
1. Volte ao seu projeto no Lovable.
2. No campo de prompt, peça a criação de filtros para o extrato.
**Exemplo de prompt sugerido:**
> *Adicione filtros na tela de extrato: um filtro por tipo (receita ou despesa) e um filtro por categoria. Os filtros devem atualizar a lista exibida automaticamente, sem precisar recarregar a página.*
3. Teste os filtros: cadastre transações de categorias diferentes (se ainda não tiver) e veja se a lista realmente atualiza quando você filtra.
4. Se algo não funcionar como esperado, descreva o problema para a IA e peça o ajuste.
### 👀 Saída esperada
Ao selecionar um filtro (ex: "despesa" ou uma categoria específica), a lista de transações deve atualizar na hora, mostrando só os itens correspondentes.
### 🏋️ Exercício opcional
Peça também um filtro por período (ex: "últimos 7 dias" ou "este mês").
---
## 📊 Dia 05/7 — Resumo financeiro automático
### 💡 Conceito do dia
Fazer **cálculos automáticos** com base em dados já cadastrados é uma das funcionalidades que mais agregam valor a um app. Aqui, você vai pedir para a IA somar os valores das transações e exibir o resultado em destaque.
### 🎯 Desafio do dia
1. Volte ao seu projeto no Lovable.
2. No campo de prompt, peça a criação de um resumo com os totais calculados automaticamente.
**Exemplo de prompt sugerido:**
> *Crie uma seção de resumo financeiro no topo do app, mostrando três cartões: "Total de Receitas", "Total de Despesas" e "Saldo Final". Os valores devem ser calculados automaticamente com base nas transações cadastradas.*
3. Cadastre algumas transações (se ainda não tiver o suficiente) e confira se os totais estão calculando corretamente.
4. Observe o visual dos cartões — peça ajustes de cor ou destaque se quiser.
### 👀 Saída esperada
Os três cartões devem exibir valores corretos, refletindo a soma das transações cadastradas (ex: Receitas: R$ 1.000 | Despesas: R$ 400 | Saldo: R$ 600).
### 🏋️ Exercício opcional
Peça para a IA deixar o cartão de "Saldo Final" com destaque visual maior que os outros dois, e mudar de cor conforme o saldo for positivo (verde) ou negativo (vermelho).
---
## 📈 Dia 06/7 — Visualizando o fluxo de caixa
### 💡 Conceito do dia
**Gráficos** são uma forma de transformar dados em algo fácil de interpretar visualmente. No Lovable, você pode pedir diferentes tipos de gráfico (barras, linhas, pizza) descrevendo o que quer comparar.
### 🎯 Desafio do dia
1. Volte ao seu projeto no Lovable.
2. No campo de prompt, peça a criação de um gráfico comparando entradas e saídas.
**Exemplo de prompt sugerido:**
> *Crie um gráfico de barras comparando o total de receitas e o total de despesas, com base nas transações cadastradas. Adicione um título ao gráfico e cores diferentes para receitas e despesas.*
3. Veja como o gráfico ficou posicionado na tela — se necessário, peça para reorganizar o layout.
4. Teste cadastrar mais uma ou duas transações e veja se o gráfico atualiza automaticamente.
### 👀 Saída esperada
O gráfico deve exibir duas barras (ou elementos visuais) comparando receitas e despesas, refletindo os valores das transações cadastradas.
### 🏋️ Exercício opcional
Peça um gráfico por categoria, mostrando quanto foi gasto em cada uma.
---
## 🏁 Dia 07/7 — Finalizando e publicando
### 💡 Conceito do dia
**Publicar (deploy)** significa colocar seu projeto no ar, com um link público que qualquer pessoa pode acessar pelo navegador, sem precisar abrir o Lovable. É o que transforma seu projeto de "protótipo" em algo real.
### 🎯 Desafio do dia
1. Volte ao seu projeto no Lovable e faça uma revisão geral: navegue por todas as telas que você criou ao longo da semana.
2. Peça ajustes finais de design. Algumas sugestões de prompt:
> *Deixe o app com uma paleta de cores mais consistente entre todas as telas.*
> 
> *Ajuste o app para ficar responsivo, funcionando bem também em telas de celular.*
3. Publique seu projeto: use a opção de **Publicar**, localizado no canto superior direito da tela do Lovable, para gerar um link público do seu app.
4. Tire um ou dois prints das telas mais bonitas (tela inicial, extrato e gráfico são boas escolhas) para compartilhar o seu trabalho.
### 👀 Saída esperada
Você deve ter um link público funcionando, que abre o app fora do editor do Lovable, além de prints das principais telas.
### 🏋️ Exercício opcional
Escreva uma legenda para postar no LinkedIn contando o que você construiu nos 7 dias.
### 💡 Dica
Sugestão de legenda: *"Nos últimos 7 dias, participei do desafio 7 Days of Code e construí do zero um app de controle financeiro usando IA, com o Lovable. O projeto conta com cadastro de transações, extrato com filtros, resumo automático e gráfico de fluxo de caixa. Foi uma ótima forma de aprender na prática como usar IA para criar produtos digitais! 🚀"*
---
## 📌 Compartilhe sua jornada
Ao concluir os 7 dias, compartilhe seu projeto nas redes sociais e atualize o seu portfólio[span_27](start_span)[span_27](end_span)[span_28](start_span)[span_28](end_span)!
