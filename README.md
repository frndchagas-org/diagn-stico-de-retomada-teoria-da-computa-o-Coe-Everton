[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zHqjFsRx)
# Diagnóstico de retomada - Teoria da Computação

Esta atividade serve para mapear o que você já domina sobre linguagens formais, autômatos, gramáticas e computabilidade.

Responda individualmente. Use suas palavras. Se usar IA depois da primeira tentativa, registre o uso na seção 7.

## 1. Mapa do que eu lembro

Marque cada tópico como: lembro bem, lembro parcialmente, não lembro, nunca vi ou não tenho certeza.

- alfabeto: lembro parcialmente
- cadeia:lembro parcialmente
- linguagem:lembro parcialmente
- gramática:lembro parcialmente
- autômato finito: nao lembro
- linguagem regular: nao lembro
- linguagem livre de contexto: nao lembro
- linguagem sensível ao contexto: nao lembro
- linguagem irrestrita:nao lembro
- hierarquia de Chomsky:nao lembro
- computabilidade:lembro parcialmente
- máquina de Turing:lembro parcialmente

## 2. Definições com exemplo

Explique, com suas palavras e com um exemplo simples, usando o alfabeto `Sigma = {a, b}`.

1. O que é um alfabeto?
é um conjunto limitado de caracteres sem significado previo
2. O que é uma cadeia?
é a combinação de caracteres de um alfabeto que pode ter um sentindo
3. O que é uma linguagem?
é um dicionario de cadeia que tem sentindo e regras padroes 
4. O que é uma gramática?
é a maneira de como escrever uma liguagem 

## 3. Linguagens

Considere as linguagens:

```text
L1 = { w em {0,1}* | w termina com 01 }
L2 = { a^n b^n | n >= 0 }
L3 = { a^n b^n c^n | n >= 0 }
```

Para cada linguagem:

1. escreva três palavras que pertencem à linguagem;
01, 1101 e 000101
2. escreva duas palavras que não pertencem;
abb, ba
3. diga, se souber, em qual classe ela provavelmente se encaixa;
nao sei
4. explique o motivo em linguagem simples.
nao sei

Não há problema em dizer "não sei". Nesse caso, escreva o que te deixou em dúvida.

## 4. Autômato finito

Considere o autômato abaixo, sobre o alfabeto `{0,1}`:

```text
Estados: q0, q1, q2
Estado inicial: q0
Estado final: q2

Transições:
q0 --0--> q1
q0 --1--> q0
q1 --0--> q1
q1 --1--> q2
q2 --0--> q1
q2 --1--> q0
```

Responda:

1. Qual linguagem esse autômato parece reconhecer?
binaria
2. Execute manualmente as cadeias abaixo e diga se aceita ou rejeita:
   - `01` - sim
   - `101` - sim
   - `100` - nao
   - `1101` - sim
   - `111` - nao
   
3. Monte uma tabela curta mostrando o caminho dos estados para pelo menos duas cadeias.
1 -q0 -> q1 -> q2
2 - q0 -> q0 -> q1 -> q2
## 5. Gramática

Considere a gramática:

```text
S -> aS
S -> b
```

Responda:

1. Gere cinco cadeias produzidas por essa gramática.
aaaab, ab, b, aaab, ab
2. Descreva a linguagem em palavras.
Nao sei
3. Essa gramática parece regular, livre de contexto ou outra classe? Justifique de forma simples.
nao sei

## 6. Ponto de dificuldade
 
Escolha um tópico da lista inicial e escreva:

1. o que você entende dele;
2. onde você se confunde;
3. que tipo de explicação ajudaria: desenho, exemplo, exercício guiado, analogia, prova passo a passo ou lista curta.

## 7. Uso de IA, se houver

Se você usou IA depois da primeira tentativa, registre:

```text
Pergunta feita: 
Resumo da resposta:
Como eu verifiquei:
O que eu alterei na minha resposta:
O que ainda não entendi:
```

## Submissão no Moodle

Depois de finalizar, copie no Moodle:

```text
Repositório:
Commit final:
Autoavaliação: nível atual, maior dificuldade e tópico que precisa ser retomado.
```
