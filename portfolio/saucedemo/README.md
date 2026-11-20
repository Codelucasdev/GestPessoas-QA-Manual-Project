# SauceDemo | Testes funcionais do checkout

Projeto de formação em QA Manual de Antonio Lucas Correia Ribeiro. Esta amostra reproduz em texto três casos do relatório de execução de 18 de outubro de 2026. O projeto é independente do GestPessoas.

**Ambiente registado:** Firefox 158.0 (64 bits) em Windows 11 Pro.  
**Pré-condição:** sessão iniciada e um artigo no carrinho. Abrir a primeira página do checkout.

| Caso | Ação | Resultado esperado no exercício | Resultado observado |
|---|---|---|---|
| TC01 · Dados preenchidos | Preencher nome, apelido e código postal e selecionar Continue. | Avançar para a segunda página do checkout. | A aplicação avançou. |
| TC02 · Código postal em branco | Preencher nome e apelido, deixar o código postal vazio e selecionar Continue. | Permanecer na primeira página e receber uma indicação de campo obrigatório. | A aplicação manteve a página e apresentou “Error: Postal Code is required”. |
| TC03 · Nome com números | Introduzir números no nome, preencher apelido e código postal e selecionar Continue. | Segundo o caderno de testes, apresentar um erro e impedir o avanço. | A aplicação aceitou os dados e avançou. |

O TC03 documenta uma divergência face ao esperado no exercício. Para classificar o comportamento como defeito do produto, é necessário confirmar a regra de validação do nome. Os resultados correspondem à execução registada em outubro de 2026.
