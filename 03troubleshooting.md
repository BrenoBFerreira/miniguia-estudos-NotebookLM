# Ttroubleshooting

Esta parte conta com os principais problemas resolvidos e com os conhecimentos adquiridos no projeto. 

## 1 – Como resolver o erro de “Limite de fontes atingido” ou do carregamento infinito ao inserir muitos links nas fontes de uma vez 
 
Esse erro ocorre provavelmente por ser uma tarefa pesada, no caso, foi com 40 e com 10 links de uma vez. A identifiação é fácil, ao inserir as fontes elas carregam infinitamente ou aparece a mensagem na tela na parte inferior “Limite de fontes atingido” mesmo não ocorrendo.

Divida as fontes em grupos e tente, inserindo cada grupo resultante de cada vez. Se mesmo assim ocorre, divida cada grupo novamente e tente novamente. Faça isso até chegar um número de links que for carregado normalmente.  
Utilize as “Notas” na aba “Estúdio” à direita para que consiga organizar a divisão e copiar e colar. 

## 2 – NotebookLM lerá somente o conteúdo visível e apenas no URL fornecido, não entrará em subpáginas. 

## 3 – O que fazer quando a fonte é um site e suas subpáginas ou quando há necessidade de organizar muitos links para inserção nas fontes 

Uma abordagem mais automatizada é usar uma IA para que acesse e traga os links de cada subpáginas e usar a técnica de engenharia de prompt “especificar estrutura de saída” instruindo para retornar com os links de uma forma que facilite para copiar e inserir no notebook.

Exemplo de uma solução no prompt para formatar a forma de resposta da IA:
```
Formato de saída:
"<link do primeiro>
<link do segundo>
...
<link do último>"
```

## 4 – Quando não sabe se uma fonte está inserida no NotebookLM
 
Basta perguntar no chat da IA no próprio notebook, ela analisará os links e checará se está ou não. 

## 5 – NotebookLM é uma ferramenta que generaliza nas respostas 
 
Caso não queira isso é necessário de prompts que especifiquem, mas caso nada seja feito, a tendência é de a resposta ser geral com tudo. 

---

⬅️ [Anterior: Miniguia de Estudos](02miniguia-de-estudos.md) | 🏠 [Voltar ao Sumário](README.md)
