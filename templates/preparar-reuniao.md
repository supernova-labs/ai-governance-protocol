# Template: preparar a reunião

[Templates](README.md) · [Adaptação](../docs/adaptacao.md) · [Processo](../docs/processo.md)

Use este contrato para construir uma skill local. Preencha e teste a configuração antes do primeiro uso operacional. O agente deve conhecer as fontes e os acordos locais pela skill resultante; perguntas durante a execução tratam das dúvidas concretas do caso.

## Configuração a incorporar

| Campo | Preencher na customização |
|---|---|
| Propósito e acionamento | [time, recorte, resultado da preparação e quando executar] |
| Fontes e consultas | [fontes de critérios, candidatas, catálogo, fricções/fixes e encaminhamentos; formas verificadas de leitura] |
| Identificação | [como reconhecer e relacionar itens entre fontes] |
| Acordos | [critérios vigentes, prioridades conhecidas, workflow, responsáveis e cadência] |
| Mandato | [operações permitidas, condições de consulta e escalonamento] |
| Saída | [formato, destino, público, acesso e passagem para geração da fotografia] |
| Procedência | [release/commit do protocolo, versão deste template, registro de adoção e versão da skill local] |

## Instrução para a skill local

```text
Propósito: preparar a reunião de governança de [time/recorte].

1. Receber [reunião/recorte], consultar [configuração e acordos] e confirmar
   dúvidas sobre o caso com o operador. Aproveitar o contexto já conhecido.
2. Ler [fontes] por [consultas verificadas]. Guardar identificadores, referência
   de origem e data da leitura. Distinguir conteúdo obtido, interpretação e lacuna.
3. Retomar encaminhamentos anteriores, candidatas, problemas repetidos,
   itens sem responsável e dependências. Consultar os critérios vigentes.
4. Relacionar itens quando o vínculo estiver sustentado. Perguntar por conflito,
   ligação incerta ou fonte inacessível na sessão. Tentar resolver a falha e
   pedir ajuda. Seguir com lacuna só por instrução explícita do operador;
   registrar a instrução e o impacto no pacote.
5. Propor pauta e razões de prioridade. Mostrar a origem de cada item,
   requisitos disponíveis e faltantes e quem pode ajudar a julgá-lo.
6. Separar proposta da AI de decisão reconhecida. Nesta referência de base,
   a preparação lê e sintetiza; atualizações exigem função e mandato específicos.
7. Entregar [pacote] por [passagem configurada], com identificação do recorte,
   critérios, referências, pendências, datas e limitações conhecidas.
```

## Saída esperada

O pacote permite localizar os itens nas fontes e entender por que merecem atenção. Inclui pauta proposta, critérios de referência, candidatas e pendências relevantes, fricções/fixes, dependências e encaminhamentos anteriores. Valores desconhecidos aparecem como desconhecidos.

A passagem à geração conserva identificadores, procedência, data, fatos e propostas separados. A prioridade sugerida pela AI não modifica automaticamente o workflow ou a decisão da mesa.

## Extensão experimental optativa

Se o time adotar a [preparação ampliada](../docs/preparacao-ampliada.md), incorporar à configuração o suporte de comentários, prazo local de estudo e revisão, operações de triagem autorizadas e modo de registrar ações já feitas. Ajustar o procedimento para:

```text
Agrupar registros em temas e propostas compreensíveis para públicos distintos.
Triar o que precisa de julgamento conjunto, o que fica no backlog e o que pode
ser resolvido/encaminhado dentro do mandato. Rastrear ação, resultado e pendência.
Circular briefing inicial com fundamento, componentes, decisões críticas e lacunas.
Antes do encontro, ler comentários e progresso nas fontes e revisar o briefing.
Preservar posições distintas; não inferir consenso de silêncio ou concordância parcial.
Entregar a versão revisada à geração da fotografia.
```

Esses encaminhamentos operacionais não substituem destinos de julgamento da mesa. Registrar a adoção experimental e as diferenças locais.

## Ensaio mínimo

Usar candidata com requisito faltante, fricção repetida, item sem encaminhamento e dependência. Conferir origem e racional da pauta. Simular fonte inacessível e confirmar que o agente busca resolver com a pessoa antes de produzir pacote incompleto. Se a extensão estiver adotada, incluir comentários divergentes e uma ação autorizada na triagem; conferir preservação e rastreabilidade.
