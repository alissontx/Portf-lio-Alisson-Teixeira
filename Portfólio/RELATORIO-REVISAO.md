# Relatório de revisão — Portfólio Alisson

## Correções aplicadas
- Removido o texto literal `\\n` que aparecia acima do cabeçalho.
- Preservados a composição visual de humanidade e tecnologia, as fotografias pessoais e os contactos.
- Removidas regras antigas de contactos que já não eram necessárias.
- Verificados os ficheiros principais, recursos locais, âncoras internas e IDs.
- Verificado o equilíbrio das chavetas CSS e a estrutura HTML com um parser.

## Resultado da verificação estática
- Arquivo ZIP íntegro.
- Nenhuma referência local a ficheiros inexistentes.
- Nenhum ID duplicado.
- Nenhuma âncora interna sem destino.
- HTML analisado sem erro de parsing.
- CSS com chavetas equilibradas.
- E-mail e ligação WhatsApp presentes.
- Imagem `humanidade-tecnologia.png` presente e associada à secção correspondente.
- O breakpoint de 760px aparece em dois blocos separados porque um trata a estrutura geral e o outro a secção visual de humanidade e tecnologia; não é, por si só, um erro.

## Atenção / melhoria futura
- A imagem `humanidade-tecnologia.png` tem cerca de 2,5 MB. Recomenda-se gerar uma versão WebP otimizada para reduzir o tempo de carregamento, mantendo o PNG como original.
- A auditoria foi estática. Ainda é necessário testar visualmente em navegadores e dispositivos reais e executar Lighthouse para medir performance, acessibilidade e SEO.
