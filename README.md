# Questões Resolvidas · Lógica de Programação

Site com exercícios de lógica de programação resolvidos e transformados em programas interativos.

**Site:** https://viniciusframos0.github.io/questoes-resolvidas-programacao/

## Como o site funciona
- **Página inicial (`index.html`):** lista as questões por número e título. Ao clicar, o aluno vê o enunciado, os conceitos trabalhados e o botão **Abrir solução**. Tem busca e, quando houver mais de um tema, filtros por tema.
- **Cada solução (`questoes/NN-nome/index.html`):** um programa funcional com Entrada → Processamento → Saída e o algoritmo em Portugol Studio, Python e JavaScript.

## Estrutura
```
index.html                     ← lista de questões
questoes.js                    ← dados da lista (título, enunciado, tema…)
assets/og-image.jpg            ← imagem de compartilhamento do site
questoes/
  01-idade-em-tempo/
    index.html                 ← solução interativa
    og-image.jpg               ← imagem de compartilhamento da questão
```

## Como adicionar uma questão
1. Crie a pasta `questoes/02-nome-da-questao/` com o `index.html` da solução.
   Uma forma fácil é copiar a pasta da questão 01 e adaptar.
2. Em `questoes.js`, acrescente um bloco no final da lista:
   ```js
   {
     numero: "02",
     titulo: "Título curto da questão",
     tema: "Estrutura sequencial",
     enunciado: "Texto do enunciado, como foi passado em aula.",
     conceitos: ["Variáveis", "Operadores aritméticos"],
     pasta: "questoes/02-nome-da-questao/"
   },
   ```
3. Envie para o GitHub. O site se atualiza sozinho em cerca de um minuto.

## Questões
| Nº | Título | Tema |
|---|---|---|
| 01 | Idade em meses, dias, horas e minutos | Estrutura sequencial |
