# QA Testing — Amazon Brasil (Busca e Navegação de Produtos)

Documentação de QA produzida durante a imersão prática de testes de software promovida pela **LumeStack**, mentorada por Henrique Manieri.

## Sobre o projeto

Sistema testado: [Amazon Brasil](https://www.amazon.com.br) — módulo de busca e navegação de produtos.

**Objetivo:** validar o funcionamento da busca de produtos, verificando se os resultados apresentados são coerentes com o termo pesquisado e se os filtros e a ordenação alteram a lista corretamente.

**Escopo testado:**
- Busca por termo existente
- Busca por termo inexistente ou sem resultados
- Aplicação do filtro de faixa de preço
- Ordenação dos resultados (menor preço, maior preço, mais relevantes)
- Comportamento da busca com campo vazio
- Exibição das informações do produto no card de resultado (nome, preço, avaliação)

## Documentos

| Arquivo | Descrição |
|---|---|
| [Test Plan](./Test_Plan_Amazon.pdf) | Plano de teste completo: objetivo, escopo e critérios de validação |
| [Test Cases](./Test_Cases_Amazon.xlsx) | Casos de teste elaborados a partir do plano |
| Bug Report | Em desenvolvimento — em breve |

---
Atividade prática realizada durante a Imersão de QA da LumeStack (agosto de 2026).
