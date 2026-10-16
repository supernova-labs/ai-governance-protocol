# Template: processar reunião e atualizar as fontes

[Templates](README.md) · [Processo](../docs/processo.md) · [Adaptação](../docs/adaptacao.md)

Customize este contrato como skill local de processamento. A pessoa e o agente interpretam o registro e tratam o retorno às fontes numa sessão síncrona. Ações seguem o mandato local; presença do operador não exige autorização a cada etapa.

## Configuração a incorporar

| Campo | Preencher na customização |
|---|---|
| Propósito | [time, recorte e resultado esperado] |
| Entradas | [notas/registro autorizado da reunião e pacote efetivamente apresentado] |
| Fontes de destino | [casa de decisões, critérios, candidatas, catálogo, fricções e fixes] |
| Operações | [como ler versão/estado, atualizar cada destino e verificar o resultado] |
| Identificação | [como reconhecer reunião e item, detectar reprocessamento e evitar duplicação] |
| Mandato | [o que aplicar, o que propor, quando consultar/escalar e quem opera] |
| Recuperação | [como detectar escrita parcial, retomar e conferir conflitos] |
| Saída | [relatório de entendimento e aplicação; onde guardar referências e pendências] |
| Procedência | [protocolo, template, registro de adoção e versão da skill local] |

## Instrução para a skill local

```text
Propósito: transformar a reunião de [time] em continuidade nas fontes.

1. Receber [registro autorizado], [pacote apresentado] e [mapa de itens/fontes].
   Reconhecer reunião, recorte e itens por [mecanismo configurado]. Consultar
   o estado atual dos destinos e as atualizações anteriores desta reunião.
2. Apresentar ao operador o entendimento das decisões e encaminhamentos.
   Perguntar por ambiguidades na sessão. Separar sugestão, decisão e compromisso;
   não inferir aceitação de responsabilidade, data ou consenso.
3. Relacionar o que foi entendido aos itens e trechos do registro. Preservar
   racional, responsáveis, datas, dependências, limites e pendências reconhecidos.
4. Aplicar ou propor cada atualização segundo [workflow/mandato]. A função pode
   operar com autonomia onde autorizada; consultar/escalar nas condições locais.
   Reprocessar a mesma reunião não deve duplicar decisões nem cards. Uma nova
   ocorrência de uso é nova fricção, ligada à anterior quando conhecida.
5. Usar [operações verificadas] sobre [destinos corretos]. Conferir o resultado
   por [leitura/retorno disponível]. Não declarar escrita bem-sucedida sem confirmação.
6. Se a escrita for parcial, mostrar aplicado e faltante e buscar resolver
   com o operador na mesma sessão. Não encerrar silenciosamente nem converter
   o restante automaticamente em pendência assíncrona.
7. Se fonte ficar inacessível, tentar resolver e pedir ajuda. Seguir com lacuna
   exige instrução explícita da pessoa, com impacto registrado. Silêncio ou
   timeout não são autorização. Preservar o resultado já confirmado ao retomar.
8. Entregar [relatório] com decisões, destino de cada mudança, resultado de
   verificação, pendências e limitações. A próxima fotografia será regenerada
   das fontes atualizadas, mantendo visível o que não pôde ser aplicado.
```

## Saída esperada

O relatório permite distinguir o que foi entendido, confirmado, aplicado, proposto e o que falta resolver. Cada atualização tem destino e procedência. Quando o processamento altera critérios, capacidade ou distribuição, o relatório conserva o vínculo com o mandato que permitiu essa ação.

Uma reunião pode terminar com itens devolvidos com data ou descartados. Um fix pode ser concluído sem efeito ainda observado. O processamento preserva essas diferenças sem inventar consenso ou resultado.

## Ensaio mínimo

Processar registro com decisão sobre candidata, fix com responsável/data/dependência e fala ambígua. Confirmar esclarecimento com operador e escrita no item correto. Simular falha após uma atualização confirmada: o agente mostra parcialidade e busca recuperar na sessão. Reprocessar o mesmo registro e conferir ausência de duplicações. Registrar nova recorrência e verificar que ela não é descartada como repetição técnica da reunião. Gerar a próxima fotografia e conferir o estado realmente presente nas fontes.
