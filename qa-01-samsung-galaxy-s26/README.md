# QA-01 — Testes Manuais | Samsung Galaxy S26 512GB

Projeto de portfólio de QA com foco em testes manuais e exploratórios da página de produto do Samsung Galaxy S26 512GB na Samsung Shop Brasil.

## Objetivo
Avaliar informações e funcionalidades da página, documentar os cenários executados e registrar defeitos observados com evidências.

## Aplicação sob teste
- **Produto:** Samsung Galaxy S26 5G 512GB
- **URL:** https://shop.samsung.com/br/galaxy-s26-512gb/p?skuId=13649
- **Sistema operacional informado:** Windows 11
- **Navegador informado:** Google Chrome
- **Tipo de teste:** Manual / exploratório

> Os resultados deste repositório refletem a execução manual relatada durante o projeto. Não representam certificação, auditoria oficial ou validação interna da Samsung.

## Escopo
- Informações e especificações do produto
- Seleção de armazenamento
- Seleção de cores
- Galeria de imagens
- Consulta de frete
- Fluxo de compra

## Resultado consolidado

| Indicador | Resultado |
|---|---:|
| Casos planejados | 8 |
| Casos executados | 8 |
| Aprovados | 6 |
| Reprovados | 2 |
| Bloqueados | 0 |
| Bugs únicos registrados | 1 |

### Casos de teste

| ID | Cenário | Resultado |
|---|---|---|
| CT-001 | Validar tamanho da tela | Reprovado |
| CT-002 | Validar nome do produto | Aprovado |
| CT-003 | Selecionar armazenamento de 256 GB | Reprovado |
| CT-004 | Selecionar armazenamento de 512 GB | Aprovado |
| CT-005 | Validar seleção de cores | Aprovado |
| CT-006 | Validar navegação da galeria | Aprovado |
| CT-007 | Validar cálculo de frete | Aprovado |
| CT-008 | Validar botão Comprar agora | Aprovado |

## Defeito identificado

**BUG-001 — Divergência na informação do tamanho da tela.**

A execução identificou 6,2 polegadas na descrição do produto e 6,3 polegadas em outra área da página. A divergência também foi observada após selecionar a opção de 256 GB. Os dois casos reprovados estão relacionados ao mesmo defeito, portanto foi criado apenas um registro.

Consulte [`bugs/BUG-001.md`](bugs/BUG-001.md).

## Estrutura do repositório

```text
qa-01-samsung-galaxy-s26/
├── README.md
├── planejamento/
│   └── plano-de-testes.md
├── casos-de-teste/
│   └── casos-de-teste.md
├── bugs/
│   └── BUG-001.md
└── evidencias/
    ├── README.md
    └── testes/
```

## Como reproduzir a análise
1. Acesse a URL da aplicação sob teste.
2. Localize as informações de tamanho da tela.
3. Compare os valores apresentados nas diferentes áreas da página.
4. Selecione a opção de armazenamento de 256 GB.
5. Verifique se a divergência permanece.

## Observações
- Os casos foram executados manualmente e os resultados foram informados pela pessoa responsável pelos testes.
- CT-003 não representa um segundo bug: ele reproduziu a inconsistência já registrada em BUG-001.
- Os testes aprovados não significam que todas as combinações, dispositivos ou condições possíveis foram cobertos.
- O reteste de BUG-001 permanece pendente até que a página seja atualizada ou uma nova execução confirme a correção.

## Ferramentas
- Google Chrome
- Git
- GitHub
- Markdown

---
**Projeto de estudo independente para demonstração de práticas de QA.**
