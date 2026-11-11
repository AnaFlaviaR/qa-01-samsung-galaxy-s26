# Plano de Testes — QA-01

## 1. Objetivo

Realizar testes manuais na página do Samsung Galaxy S26 para verificar a consistência das informações e o funcionamento de elementos disponíveis ao consumidor.

## 2. Identificação da aplicação

- **Aplicação:** Samsung Shop Brasil
- **Página analisada:** https://shop.samsung.com/br/galaxy-s26-512gb/p?skuId=13649
- **Produto:** Samsung Galaxy S26 5G
- **Sistema operacional informado:** Windows 11
- **Navegador informado:** Google Chrome
- **Abordagem:** testes manuais e exploratórios

## 3. Escopo

### Dentro do escopo

- Nome e especificações do produto
- Consistência da informação sobre tamanho da tela
- Seleção de armazenamento (256 GB e 512 GB)
- Seleção de cores
- Galeria de imagens
- Consulta de frete
- Botão “Comprar agora”

### Fora do escopo

- Finalização de compra ou pagamento
- Testes de segurança
- Testes de carga e desempenho
- Testes em outros navegadores, sistemas operacionais ou dispositivos
- Validação de código-fonte e serviços internos

## 4. Critérios de execução

Cada caso deve ser executado conforme seus passos e critérios específicos. O resultado deve ser registrado como aprovado, reprovado ou bloqueado, acompanhado de observações quando necessário.

Cada caso deve avaliar seu próprio objetivo. Um defeito de conteúdo identificado durante a execução de outro cenário deve ser registrado e relacionado ao caso apropriado, evitando reprovações duplicadas quando a funcionalidade principal do cenário foi concluída corretamente.

## 5. Critérios de encerramento

- Executar os oito casos planejados.
- Consolidar os resultados.
- Registrar defeitos observados sem duplicidade.
- Manter o reteste como pendente enquanto não houver confirmação de correção.

## 6. Resultado consolidado

Foram executados 8 casos: 7 aprovados, 1 reprovado e nenhum bloqueado. Foi identificado 1 defeito único, relacionado à divergência da informação sobre o tamanho da tela (BUG-001).
