# Casos de Teste — QA-01

**Aplicação:** Samsung Shop Brasil  
**Produto:** Samsung Galaxy S26 5G 512GB  
**Ambiente informado:** Windows 11 / Google Chrome

## CT-001 — Validar tamanho da tela
- **Objetivo:** verificar a consistência da informação sobre o tamanho da tela.
- **Pré-condição:** página do Galaxy S26 acessível.
- **Passos:**
  1. Acessar a página do produto.
  2. Localizar a descrição/características do produto.
  3. Comparar o valor com o apresentado na imagem ou descrição do modelo.
- **Resultado esperado:** informação consistente entre as áreas da página.
- **Resultado obtido:** a descrição apresenta 6,2 polegadas, enquanto outra área apresenta 6,3 polegadas.
- **Status:** **Reprovado**
- **Defeito relacionado:** BUG-001

## CT-002 — Validar nome do produto
- **Objetivo:** verificar se o nome do produto é apresentado corretamente.
- **Pré-condição:** página do Galaxy S26 acessível.
- **Passos:**
  1. Acessar a página do produto.
  2. Conferir o nome apresentado na identificação do produto.
- **Resultado esperado:** nome correspondente ao produto selecionado.
- **Resultado obtido:** nenhum erro ou inconsistência identificado durante a execução.
- **Status:** **Aprovado**

## CT-003 — Selecionar armazenamento de 256 GB
- **Objetivo:** verificar a seleção da opção de armazenamento de 256 GB e observar as informações exibidas.
- **Pré-condição:** página do produto acessível e opção de 256 GB disponível.
- **Passos:**
  1. Acessar a página do Galaxy S26.
  2. Selecionar a opção de armazenamento de 256 GB.
  3. Conferir as informações do tamanho da tela.
- **Resultado esperado:** informações do produto consistentes após a seleção.
- **Resultado obtido:** a divergência entre 6,2 e 6,3 polegadas permaneceu.
- **Status:** **Reprovado**
- **Defeito relacionado:** BUG-001

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

## CT-007 — Validar cálculo de frete
- **Objetivo:** verificar a consulta de frete com um CEP válido.
- **Passos:**
  1. Localizar o campo de consulta de frete.
  2. Informar um CEP válido.
  3. Solicitar a consulta.
- **Resultado esperado:** apresentação do resultado da consulta.
- **Resultado obtido:** consulta considerada correta durante a execução.
- **Status:** **Aprovado**
- **Observação:** o CEP utilizado não foi registrado neste documento.

## CT-008 — Validar botão Comprar agora
- **Objetivo:** verificar o comportamento do botão de compra.
- **Passos:**
  1. Localizar o botão Comprar agora.
  2. Acioná-lo.
  3. Observar o direcionamento apresentado.
- **Resultado esperado:** direcionamento para o fluxo de compra.
- **Resultado obtido:** comportamento considerado correto durante a execução.
- **Status:** **Aprovado**
- **Observação:** nenhuma compra foi finalizada.

## Resumo da execução

| Status | Quantidade |
|---|---:|
| Aprovados | 6 |
| Reprovados | 2 |
| Bloqueados | 0 |
| Total executado | 8 |

Os casos CT-001 e CT-003 reproduziram a mesma inconsistência e estão vinculados ao BUG-001.
