# Checkout aceita números no campo First Name

**Projeto:** SauceDemo · exercício de formação em QA Manual  
**Referência:** TC03, relatório de execução de 18/10/2026  
**Estado:** divergência registada. A classificação como defeito depende da confirmação do requisito.  
**Ambiente registado:** Mozilla Firefox 158.0 (64 bits), Windows 11 Pro 26H2.

## Pré-condições

Sessão iniciada, um artigo no carrinho e primeira página do checkout aberta.

## Passos registados

1. Preencher First Name com um nome que contenha números.
2. Preencher Last Name e Zip/Postal Code.
3. Selecionar Continue.

## Resultado esperado no exercício

O formulário deve permanecer na primeira página e indicar que o nome introduzido é inválido.

## Resultado observado

A aplicação aceitou os dados, avançou para a segunda página e não apresentou mensagem de erro.

## Evidência e impacto

O resultado está documentado no [registo de execução do TC03](README.md), em comparação com o TC01 (dados preenchidos) e o TC02 (código postal em branco). Se a regra do produto proibir números no nome, o comportamento permite prosseguir com dados fora do formato previsto.

**Próxima verificação:** confirmar o critério de aceitação do campo e repetir o caso na versão em avaliação. Esta amostra descreve a execução histórica.
