# Revisão da documentação

Os relatórios registram testes realizados em formação. Esta revisão organiza pontos a esclarecer; não representa uma nova execução da aplicação.

| Registro | Ponto a conferir |
|---|---|
| Login TC06 | Explicitar o preenchimento de um usuário inexistente nos passos. |
| Login TC07 | Especificar qual alteração de maiúsculas/minúsculas foi feita e reproduzir a divergência antes de concluir defeito. |
| Login TC08 | O mascaramento está descrito no esperado e no obtido. Separar esse teste de eventual sugestão para exibir a senha. |
| Recuperação TC02 | Explicitar o envio do formulário com Username vazio. |
| Recuperação TC03 | Confrontar texto e captura para confirmar a etapa alcançada. Uma mensagem de envio não comprova recebimento do e-mail. |
| Edição TC04 | 31/12/2026 é uma data válida no calendário, mas futura em relação à execução de 01/11/2026. Confirmar o requisito para data de nascimento. |
| Edição TC05 | Conferir se a evidência demonstra atualização na lista, além do perfil. |
| Eliminação TC03/TC05 | A ausência na interface não comprova eliminação física no banco. Não há consulta SQL registrada. |
| Ambiente | O relatório de login mistura duas versões/edições de Windows. Confirmar o ambiente antes de padronizar. |

## Critério de publicação das evidências

Cada captura deve ficar associada ao relatório e ao caso de origem, com o resultado observado. Não alterar a imagem para simular resultados. Dados pessoais e credenciais devem ser conferidos antes da publicação.

A contagem de casos não equivale à cobertura de requisitos. Métricas de aprovação dependem da conferência dos estados e das evidências.

## Próxima execução proposta

Confirmar requisitos e ambiente, esclarecer os casos acima, repetir os passos necessários e registrar esperado, obtido, estado e evidência. Esta atividade está proposta; não está registrada como executada.

