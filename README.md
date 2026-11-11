# QA-01 — Testes Manuais | Samsung Galaxy S26

Projeto independente de portfólio em Quality Assurance (QA), com foco em testes manuais e exploratórios da página de produto do Samsung Galaxy S26 na Samsung Shop Brasil.

## Objetivo

Avaliar informações e funcionalidades da página do produto, executar cenários de teste, registrar resultados e documentar defeitos observados com evidências.

## Aplicação sob teste

- **Produto:** Samsung Galaxy S26 5G
- **Página analisada:** [Samsung Shop Brasil — Galaxy S26 512 GB](https://shop.samsung.com/br/galaxy-s26-512gb/p?skuId=13649)
- **Sistema operacional informado:** Windows 11
- **Navegador informado:** Google Chrome
- **Tipo de teste:** Manual e exploratório

> Este é um projeto de estudo independente. Os resultados representam a execução manual realizada para este portfólio e não constituem auditoria, certificação ou validação oficial da Samsung.

## Escopo

- Conferência do nome e das especificações do produto
- Seleção de armazenamento
- Seleção de cores
- Navegação pela galeria de imagens
- Consulta de frete com CEP válido
- Comportamento do botão “Comprar agora”

## Resultado da execução

| Indicador | Quantidade |
|---|---:|
| Casos planejados | 8 |
| Casos executados | 8 |
| Aprovados | 7 |
| Reprovados | 1 |
| Bloqueados | 0 |
| Defeitos únicos registrados | 1 |

### Resumo dos casos

| ID | Cenário | Resultado |
|---|---|---|
| CT-001 | Validar consistência do tamanho da tela | Reprovado |
| CT-002 | Validar nome do produto | Aprovado |
| CT-003 | Selecionar armazenamento de 256 GB | Aprovado |
| CT-004 | Selecionar armazenamento de 512 GB | Aprovado |
| CT-005 | Validar seleção de cores | Aprovado |
| CT-006 | Validar navegação da galeria | Aprovado |
| CT-007 | Validar consulta de frete | Aprovado |
| CT-008 | Validar botão “Comprar agora” | Aprovado |

## Defeito identificado

**BUG-001 — Divergência na informação do tamanho da tela.**

Durante a execução, foram observadas informações diferentes na página: 6,2 polegadas em uma área e 6,3 polegadas em outra. O problema foi registrado uma única vez, associado ao CT-001.

A seleção de armazenamento de 256 GB foi avaliada separadamente no CT-003. A opção foi selecionada corretamente; a divergência de conteúdo permaneceu documentada no CT-001 e não foi contabilizada como falha adicional do seletor.

- [Consultar documentação do BUG-001](bugs/BUG-001.md)
- [Visualizar evidência do BUG-001](evidencias/BUG-001.png)

## Estrutura do repositório

```text
.
├── README.md
├── planejamento/
│   └── plano-de-testes.md
├── casos-de-teste/
│   └── casos-de-teste.md
├── bugs/
│   └── BUG-001.md
└── evidencias/
    ├── README.md
    └── BUG-001.png
```

## Ferramentas e conhecimentos aplicados

- Testes manuais e exploratórios
- Elaboração e execução de casos de teste
- Análise de resultados esperados e obtidos
- Identificação e documentação de defeitos
- Registro de evidências
- Markdown e GitHub

## Observações

- Os resultados foram registrados a partir da execução manual informada durante o projeto.
- CT-001 é o único caso reprovado e está relacionado ao BUG-001.
- CT-003 verifica a funcionalidade de seleção de armazenamento; a divergência textual da tela foi isolada no CT-001.
- O reteste do BUG-001 permanece pendente, pois não foi confirmada uma correção após a identificação do problema.
- Os casos aprovados não representam cobertura de todas as combinações, dispositivos ou condições possíveis.

---

**Projeto de estudo independente — Portfólio de QA.**
