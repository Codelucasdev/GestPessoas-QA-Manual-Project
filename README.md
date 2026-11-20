# GestPessoas | QA Manual

**Antonio Lucas Ribeiro · QA Manual Tester · Braga, Portugal**

Portfólio de testes funcionais manuais de autenticação e gestão de funcionários, desenvolvido em formação.

[LinkedIn](https://www.linkedin.com/in/antonio-lucas-03441b311/) · [GitHub](https://github.com/LucasRibeiroTec)

## O projeto

GestPessoas é o nome utilizado no exercício de formação. A aplicação testada é a demonstração do **OrangeHRM**; este repositório reúne o trabalho de testes, não o desenvolvimento da aplicação.

Os sete relatórios originais descrevem 50 casos de teste, registrados em 31/10 e 01/11/2026. Incluem pré-requisitos, passos, resultados esperados e resultados observados.

## Consulte o trabalho

Comece pelo [catálogo dos 50 casos](docs/catalogo.md) e abra os relatórios abaixo para acompanhar os passos, resultados esperados e observados.

| Módulo | Casos | Relatório |
|---|---:|---|
| Login | 9 | [Consultar](relatorios/01.md) |
| Recuperação de palavra-passe | 4 | [Consultar](relatorios/02.md) |
| Encerramento de sessão | 2 | [Consultar](relatorios/03.md) |
| Lista e pesquisa | 7 | [Consultar](relatorios/04.md) |
| Cadastro de funcionários | 18 | [Consultar](relatorios/05.md) |
| Edição de dados pessoais | 5 | [Consultar](relatorios/06.md) |
| Eliminação de funcionários | 5 | [Consultar](relatorios/07.md) |

As [evidências protegidas](evidencias-protegidas/README.md) incluem o pacote ZIP com as 64 capturas, o manifesto e a documentação correspondente. [Baixar o ZIP](evidencias-protegidas/GestPessoas_Evidencias_Protegidas.zip).

## Funcionalidades testadas

- **Login:** credenciais válidas e inválidas, campos obrigatórios e acesso sem sessão.
- **Recuperação de palavra-passe:** abertura do fluxo, validação e cancelamento.
- **Encerramento de sessão:** logout e comportamento do botão Voltar do navegador.
- **Lista e pesquisa:** busca por nome e ID, filtros, ausência de resultados e paginação.
- **Cadastro:** campos obrigatórios, limites de caracteres, duplicidade, fotografia e dados de acesso.
- **Edição:** alterações de dados pessoais e validações de formulário.
- **Eliminação:** confirmação, cancelamento, seleção múltipla e pesquisa posterior.

## Prática demonstrada

- Organização e execução de casos de teste manuais.
- Exploração de cenários positivos e negativos.
- Comparação entre comportamento esperado e observado.
- Registro de resultados e evidências.
- Identificação de divergências para investigação.

## Contexto e limites

Este é um exercício de formação em QA, com orientação. A aplicação testada pertence a terceiros. Os resultados são registros históricos, não uma nova execução; a contagem de casos não representa cobertura integral nem taxa de aprovação.

Os registros descritos neste projeto são verificações pela interface. Não demonstram execução automatizada, validação por API ou consultas ao banco.

As [notas de revisão](docs/revisao.md) identificam ambiguidades e pontos a confirmar antes de uma nova execução. Os textos históricos foram preservados; divergências documentais não são tratadas automaticamente como defeitos confirmados.

## Sobre mim

Estou direcionando minha trajetória para **QA Manual Tester**, com formação prática em testes de software e base de estudos em HTML, CSS e JavaScript. Também desenvolvo conhecimentos básicos de SQL e prática orientada em testes de API com Swagger Petstore e ServeRest.

Meu foco é documentar o raciocínio de teste com clareza, evidências e atenção ao comportamento da aplicação.

## Outro projeto de formação

[SauceDemo — testes funcionais do checkout](portfolio/saucedemo/README.md). Três casos documentados com pré-condições, ações e resultados observados.
