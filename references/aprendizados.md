# Correções que fizeram a edição evoluir

Estes casos são observações e pedidos do projeto original, não presets obrigatórios. A implementação de uma versão não prova aprovação estética posterior.

## Daniel

- **V1 rejeitada:** placas estáticas e aparência genérica enfraqueciam a comunicação. Preferir tipografia e objetos que evoluem com a tese. Preservar acertos localizados da edição humana, especialmente hook e pausa de autoridade, sem copiar a aparência inteira.
- **V2–V5:** uma linguagem de legenda/motion recebeu aprovação parcial, mas posição, cor, contraste, zoom e áudio precisaram de revisão. Contorno claro no azul foi percebido como infantil; contraste deve ser testado sobre o fundo real. Acelerar legendas encurtou entradas e repousos; preservar cadência natural da voz e conferir a percepção de ritmo no export.
- **Som:** ruído perceptível, cama inaudível e depois pedido de trilha mais animada mostraram que medição sozinha não resolve a mistura. Planejar voz em primeiro plano, música perceptível e SFX associados a momentos de sentido. Quando o pedido era só trilha, preservar imagem, voz e efeitos anteriores.
- **Inserts por significado:** retratos do apresentador em cards e a mesma foto repartida em três não comunicavam problema, prova, solução ou perspectivas. Diagramas e imagens distintas devem corresponder à frase inteira. Uma cadeira ilustrativa inicialmente adotada foi rejeitada no encerramento e depois também no insert anterior; uma correção de princípio exige revisar ocorrências semelhantes, não só o trecho apontado.
- **Resultado e animação:** um maço apenas ampliando não mostrava dinheiro chegando. A revisão usou trajetórias de notas e moedas e acentos nas quedas, sem alegar valores reais. A palavra “transformando” persistia na tela e alterava a leitura; a saída explícita deixou “resultados” sozinho. A passagem de aprendizado para resultado estava seca; linha e objetos passaram a se conectar gradualmente. Verificar saídas e continuidade em movimento, não apenas still final.
- **Cor:** uma comparação localizada entre tratamentos levou a preservar o Rec.709 existente, evitando LUT ou conversão duplicada. Essa decisão não equivale a revisão integral da cor.

## Patrick

- **Primeira direção rejeitada:** acabamento básico e imagens falsas/simples. Antes da primeira versão compartilhada, revisar a peça inteira e corrigir problemas observáveis; quantidade de efeitos ou skills não demonstra qualidade.
- **Foco e zoom:** apagar todo o contexto deixa cena vazia. Um insert humano contextual não prova uma operação de interface. Conferir meio do pan, ação, confirmação e saída; limitar zoom por seus extremos para não cortar rótulos nem caixas.
- **Legenda e gesto:** amostras por cena deixaram passar palavras sobre dedos/mãos. Gerar estados de todos os grupos e verificar alturas máximas; escolher a área de leitura conforme aquela filmagem, sem copiar coordenadas para outro vídeo. Manter layout estável quando a camada de câmera troca e preservar a palavra até o fim canônico.
- **Fronteiras:** arredondamento de SRT gerou um quadro com tamanho/âncora errados. Inspecionar quadro anterior, exato e seguinte com tempo racional. Holds de fala não devem cruzar capítulos; UI preparada pode continuar visível enquanto a próxima animação assenta.
- **Transformações:** fundos que cobrem texto e dissolves entre rótulos falham no meio, mesmo com extremos bons. Progressão de rota deve acompanhar o marcador; cores podem interpolar sem sobrepor dois textos diferentes.
- **Som sincronizado:** remontagem deslocou o efeito de digitação; retimar para o primeiro caractere visível. Comparações sample a sample e ASR ajudam a reconciliar fontes e detectar risco, mas não são escuta.
- **Render:** sintaxe CSS inválida fez uma câmera não acompanhar o objeto; testar no navegador/compositor real. Artefatos de linhas surgiram na camada de vídeo e sumiram ao trocar a implementação; comparar source e render antes de culpar texto/sombra. Falhas de cache e permissão pediram ajustes locais de decodificação e serviço somente leitura, sem congelar imagem ou alterar brutos.
