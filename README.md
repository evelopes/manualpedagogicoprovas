# 📝 Gerador de Provas — Manual Pedagógico

Uma ferramenta do **Manual Pedagógico** para facilitar a criação de diferentes versões de uma mesma avaliação.

📚 **Instagram:** @manualpedagogico

O Gerador de Provas permite cadastrar questões e respostas, gerar automaticamente diferentes versões da prova, embaralhar questões e alternativas e criar os respectivos gabaritos para facilitar a correção pelo professor.

## ✨ Funcionalidades

- Cadastro dos dados da avaliação;
- Inserção de várias questões de uma só vez;
- Cadastro de questões individualmente;
- Importação de questões por arquivo `.txt`;
- Download de arquivo de exemplo;
- Validação automática das questões;
- Identificação de questões sem resposta correta;
- Embaralhamento da ordem das questões;
- Embaralhamento das alternativas;
- Geração de múltiplas versões da mesma prova;
- Prevenção de versões idênticas;
- Distribuição das respostas corretas entre as alternativas;
- Identificação de cada versão como **Prova 01, Prova 02, Prova 03...**;
- Gabarito rápido separado por versões;
- Gabarito detalhado para o professor;
- Impressão tradicional;
- Modo econômico de impressão em duas colunas;
- Salvamento das provas em PDF pelo navegador;
- Exportação para Word;
- Layout desenvolvido com a identidade visual do **Manual Pedagógico**.

## 📚 Como cadastrar várias questões

As questões podem ser inseridas utilizando um formato simples.

A primeira linha corresponde à **pergunta**.

Nas linhas seguintes, coloque **uma alternativa por linha**.

Adicione um asterisco `*` antes da alternativa correta.

Deixe uma linha em branco antes de iniciar a próxima questão.

### Exemplo

```text id="f8sm1y"
Qual é a capital do Brasil?
São Paulo
*Brasília
Salvador
Rio de Janeiro

Quanto é 5 + 5?
8
9
*10
11

Qual planeta é conhecido como Planeta Vermelho?
Vênus
Júpiter
*Marte
Saturno
```

> **Importante:** cada questão deve possuir exatamente uma alternativa marcada com `*`.

O asterisco é utilizado apenas para identificar a resposta correta e **não aparece na prova do aluno**.

## ⚙️ Como funciona

Depois que as questões são cadastradas, a ferramenta organiza e valida os dados.

Ao gerar diferentes versões da avaliação, o sistema pode:

1. alterar a ordem das questões;
2. alterar a ordem das alternativas;
3. manter o vínculo com a resposta correta;
4. impedir a geração de versões idênticas;
5. gerar automaticamente o gabarito correspondente a cada versão.

Assim, uma mesma questão pode aparecer como **Questão 2 na Prova 01** e como **Questão 8 na Prova 02**, por exemplo.

A alternativa correta também pode mudar de letra devido ao embaralhamento.

O gabarito é recalculado automaticamente.

## 🚨 Validação

Antes de gerar as provas, o sistema verifica se as questões foram cadastradas corretamente.

Caso uma questão não possua resposta correta, será exibido um alerta solicitando que seja colocado um `*` antes da alternativa correta.

Também são identificadas questões com mais de uma alternativa marcada como correta.

As provas só devem ser geradas depois que os problemas forem corrigidos.

## 🖨️ Impressão econômica

Além do formato tradicional, o Gerador de Provas possui uma opção de impressão em **duas colunas**.

Nesse modo:

- o cabeçalho permanece na parte superior;
- as questões são distribuídas em duas colunas;
- existe espaçamento entre as colunas;
- o sistema procura manter cada questão inteira dentro da mesma coluna.

O objetivo é reduzir a quantidade de folhas utilizadas sem comprometer a organização e a legibilidade da avaliação.

## ✅ Gabaritos

Ao final das provas, o sistema gera um material exclusivo para o professor.

### Gabarito rápido

Apresenta as letras corretas de cada versão, facilitando a correção das avaliações.

Para melhorar a visualização, as versões são organizadas em grupos.

### Gabarito detalhado

Além da letra correta, permite relacionar a questão apresentada na prova com sua questão original e respectiva resposta.

## 🔒 Privacidade

O Gerador de Provas foi desenvolvido para funcionar diretamente no navegador.

As questões inseridas pelo professor são processadas localmente pela aplicação e não precisam ser enviadas para um servidor externo para que o embaralhamento e a geração das provas funcionem.

## 💻 Tecnologias

O projeto utiliza:

- HTML
- CSS
- JavaScript

A aplicação pode funcionar como um site estático, sem necessidade de banco de dados para suas funcionalidades principais.

## 🎨 Identidade visual

A interface segue a identidade do **Manual Pedagógico**, inspirada em:

- post-its;
- materiais escolares;
- papéis e recortes;
- scrapbook;
- colagem editorial;
- anotações e elementos manuscritos.

A área destinada à impressão das avaliações permanece mais limpa para preservar a legibilidade e reduzir o consumo de tinta.

## 🚀 Executando o projeto

Faça o download ou clone o repositório.

Depois, abra:

```text id="vd4m0g"
index.html
```

em um navegador moderno.

Por ser uma aplicação web estática, não é necessário instalar dependências para utilizar a versão atual.

## 📌 Objetivo do projeto

O projeto foi criado para tornar mais simples a preparação de avaliações escolares, especialmente quando o professor deseja aplicar **diferentes versões da mesma prova**.

A ferramenta busca reduzir o trabalho manual de reorganizar questões, alternativas e gabaritos, permitindo que o professor concentre seu tempo no planejamento e na prática pedagógica.

---

## 📚 Manual Pedagógico

Conteúdos e ferramentas para apoiar professores no planejamento e na prática pedagógica.

**Instagram: @manualpedagogico**

**Gerador de Provas — uma ferramenta do Manual Pedagógico.**
