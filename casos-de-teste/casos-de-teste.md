# Casos de Teste — QA-01

**Aplicação:** Samsung Shop Brasil  
**Produto:** Samsung Galaxy S26 5G  
**Ambiente informado:** Windows 11 / Google Chrome

## CT-001 — Validar consistência do tamanho da tela

- **Objetivo:** verificar se a informação sobre o tamanho da tela é consistente entre as áreas da página.
- **Pré-condição:** página do produto acessível.
- **Passos:**
  1. Acessar a página do Galaxy S26.
  2. Localizar a informação do tamanho da tela na descrição/características.
  3. Comparar com o valor apresentado em outra área da página.
- **Resultado esperado:** informação consistente entre as áreas consultadas.
- **Resultado obtido:** foram observados os valores de 6,2 polegadas em uma área e 6,3 polegadas em outra.
- **Status:** **Reprovado**
- **Defeito relacionado:** [BUG-001](../bugs/BUG-001.md)

## CT-002 — Validar nome do produto

- **Objetivo:** verificar se o nome apresentado corresponde ao produto selecionado.
- **Pré-condição:** página do produto acessível.
- **Passos:**
  1. Acessar a página do produto.
  2. Conferir o nome apresentado na identificação do produto.
- **Resultado esperado:** nome correspondente ao produto selecionado.
- **Resultado obtido:** nenhum erro ou inconsistência identificado durante a execução.
- **Status:** **Aprovado**

## CT-003 — Selecionar armazenamento de 256 GB

- **Objetivo:** verificar se a opção de armazenamento de 256 GB pode ser selecionada corretamente.
- **Pré-condição:** página do produto acessível e opção de 256 GB disponível.
- **Passos:**
  1. Acessar a página do Galaxy S26.
  2. Selecionar a opção de armazenamento de 256 GB.
  3. Conferir se a opção selecionada é indicada corretamente na página.
- **Resultado esperado:** opção de 256 GB selecionada e identificada corretamente.
- **Resultado obtido:** seleção realizada; a divergência de informação sobre o tamanho da tela observada na página foi registrada separadamente no CT-001.
- **Status:** **Aprovado**
- **Observação:** a inconsistência de conteúdo não foi contabilizada como falha do seletor de armazenamento.

## CT-004 — Selecionar armazenamento de 512 GB

- **Objetivo:** verificar a seleção da opção de armazenamento de 512 GB.
- **Passos:**
  1. Acessar a página do produto.
  2. Selecionar a opção de 512 GB.
- **Resultado esperado:** opção selecionada corretamente.
- **Resultado obtido:** comportamento considerado correto durante a execução.
- **Status:** **Aprovado**

## CT-005 — Validar seleção de cores

- **Objetivo:** verificar a seleção das cores disponíveis.
- **Passos:**
  1. Acessar as opções de cores.
  2. Selecionar as opções disponíveis.
  3. Observar a apresentação correspondente.
- **Resultado esperado:** seleção realizada corretamente.
- **Resultado obtido:** comportamento considerado correto durante a execução.
- **Status:** **Aprovado**

## CT-006 — Validar navegação da galeria

- **Objetivo:** verificar a navegação entre as imagens do produto.
- **Passos:**
  1. Acessar a galeria de imagens.
  2. Navegar pelas imagens disponíveis.
- **Resultado esperado:** imagens exibidas durante a navegação.
- **Resultado obtido:** comportamento considerado correto durante a execução.
- **Status:** **Aprovado**

## CT-007 — Validar consulta de frete

- **Objetivo:** verificar a consulta de frete com um CEP válido.
- **Passos:**
  1. Localizar o campo de consulta de frete.
  2. Informar um CEP válido.
  3. Solicitar a consulta.
- **Resultado esperado:** apresentação do resultado da consulta.
- **Resultado obtido:** consulta considerada correta durante a execução.
- **Status:** **Aprovado**
- **Observação:** o CEP utilizado não foi registrado neste documento.

## CT-008 — Validar botão “Comprar agora”

- **Objetivo:** verificar o comportamento do botão de compra.
- **Passos:**
  1. Localizar o botão “Comprar agora”.
  2. Acioná-lo.
  3. Observar o direcionamento apresentado.
- **Resultado esperado:** direcionamento para o fluxo de compra.
- **Resultado obtido:** comportamento considerado correto durante a execução.
- **Status:** **Aprovado**
- **Observação:** nenhuma compra foi finalizada.

## Resumo da execução

| Status | Quantidade |
|---|---:|
| Aprovados | 7 |
| Reprovados | 1 |
| Bloqueados | 0 |
| Total executado | 8 |

**Defeito único registrado:** BUG-001, relacionado ao CT-001.
