# Catálogo de casos de teste

Índice dos 50 casos descritos nos sete relatórios de formação. A numeração TC é a dos documentos originais e reinicia em cada relatório. Esta contagem não representa taxa de aprovação ou cobertura integral.

## 01 — Login

| Caso | Cenário |
|---|---|
| TC01 | Credenciais válidas |
| TC02 | Username vazio |
| TC03 | Password vazia |
| TC04 | Ambos os campos vazios |
| TC05 | Password incorreta |
| TC06 | Usuário inexistente |
| TC07 | Password case-sensitive |
| TC08 | Caracteres da password ocultos |
| TC09 | Acesso direto sem sessão |

## 02 — Recuperar palavra-passe

| Caso | Cenário |
|---|---|
| TC01 | Abrir recuperação |
| TC02 | Username vazio |
| TC03 | Username válido |
| TC04 | Cancelar recuperação |

## 03 — Terminar sessão

| Caso | Cenário |
|---|---|
| TC01 | Logout pelo menu |
| TC02 | Voltar no navegador após logout |

## 04 — Lista e pesquisa

| Caso | Cenário |
|---|---|
| TC01 | Funcionários atuais |
| TC02 | Pesquisa por nome |
| TC03 | Pesquisa por ID |
| TC04 | Nome inexistente |
| TC05 | Limpar filtros |
| TC06 | Combinar filtros |
| TC07 | Paginação |

## 05 — Adicionar funcionário

| Caso | Cenário |
|---|---|
| TC01 | Cadastro válido |
| TC02 | Primeiro nome vazio |
| TC03 | Apelido vazio |
| TC04 | Middle name opcional |
| TC05 | Nome acima de 30 caracteres |
| TC06 | Editar ID automático |
| TC07 | ID duplicado |
| TC08 | ID acima de 10 caracteres |
| TC09 | Fotografia válida |
| TC10 | Formato de arquivo não permitido |
| TC11 | Fotografia acima de 1 MB |
| TC12 | Ativar Create Login Details |
| TC13 | Username abaixo de 5 caracteres |
| TC14 | Username duplicado |
| TC15 | Password abaixo de 7 caracteres |
| TC16 | Confirmação de password diferente |
| TC17 | Login com funcionário criado |
| TC18 | Cancelar cadastro |

## 06 — Editar dados pessoais

| Caso | Cenário |
|---|---|
| TC01 | Alterar apelido |
| TC02 | Remover nome obrigatório |
| TC03 | Guardar nacionalidade, estado civil e género |
| TC04 | Validar data de nascimento |
| TC05 | Verificar nome atualizado na lista |

## 07 — Eliminar funcionário

| Caso | Cenário |
|---|---|
| TC01 | Exibir confirmação |
| TC02 | Cancelar eliminação individual |
| TC03 | Confirmar eliminação individual |
| TC04 | Eliminar múltiplos funcionários |
| TC05 | Pesquisar funcionário eliminado |

## Rastreabilidade

Fontes: relatórios GestPessoas de 31/10/2026 e 01/11/2026, de Antonio Lucas C Ribeiro. Índice elaborado a partir dos textos dos relatórios; a planilha e as capturas ainda aguardam publicação. Consulte as [notas de revisão](revisao.md) antes de interpretar divergências como defeitos confirmados.

