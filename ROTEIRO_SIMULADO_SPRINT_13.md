# 🚀 Roteiro Didático - Sprint 13: O Desafio do Gerente (Simulado Integrado)

**Disciplina:** Informática Empresarial (1ADM)  
**Tempo Disponível:** 50 minutos cravados  
**Alvo:** Alunos Leigos e "Preguiçosos" (Alta Pressão, Zero Ociosidade)

> [!CAUTION]
> **A Regra de Ouro da Aula:** "Na vida real, o chefe não pergunta se você sabe usar o Excel. Ele pergunta onde está o relatório que era pra ontem." Hoje não há espaço para "não sei fazer".

---

## 🛠️ O Chão de Fábrica (Metáfora Física Simplificada)

Para introduzir a aula, escreva este diagrama na lousa antes de eles abrirem os computadores:

```text
[ MATERIAL DE DEMOLIÇÃO ] ----------> [ ENGENHARIA CIVIL ] ----------> [ PRÉDIO PRONTO ]
A Planilha Bomba (Lixo)               Limpeza e Estruturação           Dashboard Lindo
(Cores berrantes, erros, espaços)     (Largura, Moeda, `=SOMA()`)      (Gráficos e IF/SE)
      ^                                      ^                                ^
(Minuto 0 a 10)                        (Minuto 10 a 30)                (Minuto 30 a 50)
```

**A Analogia:** Ninguém constrói um prédio em cima de entulho. Se você tentar fazer a conta `=SOMA()` em uma coluna de "Lixo" (textos misturados com números), o prédio cai (retorna `#VALOR!`). Primeiro limpamos o terreno, depois construímos.

---

## 👨‍🏫 Feedback da "Banca de Especialistas"

Sempre que um aluno travar ou reclamar, responda adotando uma destas três perspectivas (encarne o personagem):

* **🏛️ Arquitetura (O Diretor Rigoroso):** *"Esse vermelho fluorescente machuca o olho do cliente. Ninguém vai investir na nossa empresa com uma tabela de circo. Formatação não é 'frescura', é credibilidade."*
* **⚙️ Baixo Nível/Performance (O Robô do Excel):** *"Pessoal, para o computador, a letra 'O' e o número '0' são coisas diferentes. 'R$ 50' escrito à mão é um TEXTO. O Excel não sabe multiplicar texto. Vocês precisam digitar o número limpo e deixar a máquina pintar o R$ usando a ferramenta 'Moeda'."*
* **🤝 Acolhimento Didático (O Gerente Compreensivo):** *"Calma. Eu sei que parece desesperador ver essa tabela feia. Todo estagiário passa por isso. Respirem. Selecionem tudo, tirem o fundo vermelho e coloquem fonte preta. Pronto, 50% do pânico já foi embora. Um passo de cada vez."*

---

## ⚔️ Comparação Direta: A Diferença de Postura

Mostre no projetor como os dois tipos de profissionais reagem ao abrirem a "Planilha Bomba":

### ❌ Jeito Amador (O Estagiário Desesperado)
- Tenta fazer a fórmula de SOMA direto na bagunça.
- O resultado dá "Erro de Valor". Ele apaga tudo e tenta usar a calculadora do celular para fazer na mão.
- Pinta a tabela linha por linha em vez de usar as ferramentas corretas.
- **Veredito:** *Demissão por baixa produtividade e falta de lógica de sistema.*

### ✅ Jeito Engenheiro de Negócios (O Futuro Gerente)
- Remove as formatações poluídas em 3 segundos.
- Higieniza os dados (converte textos em valores numéricos).
- Automatiza as operações matemáticas em 10 segundos.
- Cria os gráficos e vai tomar café enquanto o resto da empresa sua frio.

---

## ⏱️ ROTEIRO DO SIMULADO (A Dinâmica dos 50 Minutos)

### 🔴 00-10 min: O Choque de Realidade (O Briefing)
1. **Atitude do Professor:** Entre na sala rápido. Sem conversinhas.
2. **O Anúncio:** *"Turma, o gerente da Lanchonete anterior foi demitido. Ele deixou o arquivo `PLANILHA_BOMBA_SPRINT13.xlsx` na pasta do drive e bloqueou o celular. A diretoria chega em 40 minutos para ver se damos lucro. Abram o arquivo."*
3. **A Reação:** Eles vão abrir e ver cores terríveis (Fundo vermelho neon, letras azuis gigantes, nomes como " joão   "). Deixe que eles sofram por 2 minutos.

### 🟡 10-25 min: A Limpeza do Terreno (Higienização de Dados)
**Meta:** Deixar a planilha com cara de empresa profissional.
1. Remover toda a cor de fundo horrorosa (Preenchimento > Sem preenchimento). Isso apagará a grade padrão do Excel!
2. **As Bordas Perdidas:** Imediatamente após tirar a cor, aplique "Todas as Bordas" na tabela para ela não virar uma mancha branca flutuante.
3. Ajustar as fontes (Tamanho 11, cor Automática/Preta) e a Largura das Colunas.
4. **A Coluna Fantasma (Datas):** A primeira coluna de Datas está misturada (`03/ago`, `02/08/26`). Selecionar tudo e aplicar o formato "Data Curta" para padronizar.
5. **Higienização Vital:** 
   - Nomes: Tirar espaços e padronizar as letras (ex: 'João', 'Maria'), explicando que relatório com 'joão' em minúsculo vai pro lixo na diretoria. *(Aviso ao Professor: Valide a frustração deles. Diga: "Sei que dá raiva fazer na mão. Na próxima Sprint ensinarei as fórmulas `=PRI.MAIUSCULA()` e `=ARRUMAR()` que fazem isso em 1 segundo", justificando o trabalho braçal de hoje).*
   - A Armadilha do Ponto: O valor `50.00` não converte para moeda no Excel em PT-BR, ele vira texto. Ensine-os a alterar o ponto para vírgula manualmente se der erro. Apagar os textos como "R$ 50,00" e "cinquenta", digitar o número puro (`50`) e só então clicar em **Moeda**.

> [!TIP]
> **Dica do Especialista (Robô):** Se o número estiver alinhado à esquerda na célula, o Excel acha que é texto. Se for número mesmo, ele alinha automaticamente para a direita.

### 🟢 25-35 min: Automação Matemática (O Coração da Planilha)
**Meta:** Usar o computador como máquina de calcular, não como folha de papel.
1. **O Total:** Multiplicar a Quantidade pelo Valor. `=C2*D2` e arrastar para baixo.
2. **O Mapa do Tesouro (Totais Finais):** Para evitar planilhas visualmente destruídas, dê as coordenadas exatas: "Escrevam 'Total Geral' na célula `C12` e façam `=SOMA()` na `D12`. Em C13 'Venda Máxima' e C14 'Venda Média'."
3. **O Ápice Cognitivo (A Decisão):** Adicionar uma coluna "Bônus".
   - **O Chefe diz:** "Se o vendedor vendeu mais de 10 unidades na linha, escreva 'Bônus'. Se não, escreva 'Nada'."
   - **Fórmula:** `=SE(C2>10; "Bônus"; "Nada")`. Arrastar para baixo. 
   *(Atenção Professor: Se algum aluno usar o Google Sheets em inglês, a fórmula quebra. Avise que nesses casos a fórmula muda para `=IF(C2>10, "Bônus", "Nada")` com vírgula em vez de ponto-e-vírgula).*

### 🔵 35-45 min: A Tomada de Decisão (DataViz)
**Meta:** Desenhar para a diretoria ver rápido.
1. **A Magia do CTRL (Aviso Fatal):** Não deixe o aluno arrastar o mouse por tudo, ou sairá um gráfico mutante. Ensine a regra de ouro do DataViz: "Selecione a coluna Vendedor (ex: da linha 1 à 11). Segure a tecla `CTRL`. Selecione a coluna Total na mesma proporção (linha 1 à 11). **NÃO inclua a linha do Total Geral**, senão a barra gigante da soma vai esmagar todas as outras barras do gráfico."
2. Inserir Gráfico de Colunas.
3. Formatar o gráfico (Título claro: "Faturamento por Vendedor").
4. Remover bordas desnecessárias do gráfico (Design Limpo).

### 🏆 45-50 min: O "Relatório Tá na Mesa" (Fechamento)
1. Os alunos precisam subir a planilha limpa, formatada e com os gráficos no Google Drive deles e compartilhar o link para o e-mail do professor (Simulando entrega para a Chefia).
2. O Professor abre a planilha do primeiro que entregou no projetor e elogia publicamente: *"Eis aqui um profissional que a empresa não demitiria."*
