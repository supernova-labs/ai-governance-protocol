# Evolução, releases e adoção seletiva

Uma release oferece mudanças para avaliação. Ela não altera acordos, mandatos, skills ou configurações de quem usa o protocolo, inclusive da própria Supernova.

## Três versões com trabalhos diferentes

| Versão | O que identifica | Onde consultar |
|---|---|---|
| Protocolo | Edição da referência de processo, seus princípios e contratos | Tag `vX.Y.Z`, GitHub Release e `release.json` naquela tag |
| Template | Edição de cada instrução para produzir uma skill local | Mapa `templates` em `release.json` naquela tag |
| Implementação local | Skill adaptada, plugin, configuração, integração ou código efetivamente usado | Repositório ou sistema escolhido pelo time; registrado na adoção local |

Atualizar um template não instala uma skill. Atualizar um plugin não prova que o time adotou todas as práticas de uma edição do protocolo. Uma implementação pode combinar práticas de releases diferentes; o registro local precisa explicar essa composição.

`main` contém o trabalho mais recente e pode ter mudanças ainda sem release. Para uma base reproduzível, use uma tag publicada e anote também o commit quando disponível. O identificador em `release.json` indica a edição preparada; a publicação é confirmada pela tag e pela GitHub Release correspondentes.

## Convenção de versões

Usamos `MAJOR.MINOR.PATCH` como convenção editorial:

- PATCH corrige redação, exemplos ou erros sem mudar o sentido do processo ou contrato.
- MINOR acrescenta práticas, orientações ou contratos compatíveis com o que já estava documentado.
- MAJOR muda ou remove princípios ou contratos de modo que exige reavaliar a adaptação.

As edições `0.x` são referências iniciais. Mudanças que exigem reavaliação podem ocorrer entre versões MINOR e devem ser destacadas no changelog. O número orienta a comparação; a nota de impacto explica o trabalho necessário.

Cada template tem versão própria. Uma correção só na documentação do protocolo pode manter as versões de todos os templates. Uma alteração nas entradas, saídas ou limites de uma função deve incrementar o template afetado e explicar a compatibilidade. Implementações locais escolhem sua própria convenção.

## Da aprendizagem à publicação

1. Receber uma proposta ou aprendizagem com problema, contexto compartilhável, evidência e limites. Uma discussão pública não autoriza transportar dados privados para cá.
2. A Supernova examina o que é princípio do método, arranjo de referência ou particularidade local. Mudanças conceituais passam pela manutenção da fonte canônica interna antes de integrar o corpo de referência público. Propostas ainda em exame ficam identificadas como tal.
3. Preparar um pull request com documentação afetada, templates e impacto nas adaptações. Explicitar o que a evidência sustenta e o que continua hipótese.
4. Revisar a coerência metodológica, a clareza para humanos e agentes, links e confidencialidade. Conferir que a documentação não promete um software executável ou uma eficácia ainda não observada.
5. Atualizar `release.json` e `CHANGELOG.md`, identificando versões de templates alteradas. Registrar a correspondência com a base canônica no controle interno de manutenção, sem publicar suas informações restritas.
6. Após a revisão da Supernova, criar uma tag `vX.Y.Z` no commit aprovado e uma GitHub Release com as mesmas notas. Conferir que a tag, os arquivos e a release correspondem. Preservar as edições anteriores; correções geram outra release, sem mover tags publicadas.

As notas de cada release devem dizer o que mudou, por quê, que evidências ou raciocínios sustentam a mudança, seus limites, quais práticas/templates foram afetados e o que um time precisa comparar. A publicação de uma experiência como exemplo não a torna resultado universal.

## Como avaliar uma release no seu time

Comparar as notas e os arquivos da release com o [registro de adoção](../templates/registro-de-adocao.md) e com as skills realmente instaladas. Identificar mudanças pertinentes ao propósito e às condições locais. Para cada prática relevante, decidir dentro dos mandatos vigentes se será adotada, adaptada, adiada ou deixada fora do recorte, com razão e responsável quando houver trabalho.

Se a mudança pede outra fonte, acesso ou autonomia, revisar o acordo correspondente antes da execução dependente. Testar uma amostra proporcional ao risco e registrar a versão local resultante. Preservar a base anterior e a possibilidade de recuperá-la conforme as condições locais.

Práticas incorporadas depois da adoção inicial ganham linhas com sua release de origem e a decisão local. Atualizar apenas o campo de versão apagaria a diferença entre adoção completa e parcial. Nenhum agente deve inferir consentimento para mudar o time a partir da existência de uma release mais recente.

Para acompanhar mudanças, consultar as Releases do repositório ou usar as notificações de releases do GitHub. A cadência de avaliação pertence ao time; receber uma notificação não inicia uma migração.
