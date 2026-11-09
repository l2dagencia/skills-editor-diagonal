---
name: skills-editor-diagonal
description: Aperfeiçoar vídeos falados com montagem rastreável, legendas cinéticas, inserts semânticos, som dirigido, cor e QA do export.
metadata:
  language: pt-BR
  version: 1.0.0
---

# Editor de vídeo orientado por sentido

## 1. Ingestão e referência

Inventarie novamente as mídias antes de concluir que um take falta. Verifique FPS racional, rotação, resolução, timebase, canais, sample rate, faixa de cor e gama quando comprováveis. Preserve brutos e versões anteriores. Assista à edição humana e registre os trechos que funcionam por função narrativa: hook, pausa, virada, demonstração e fecho. Uma versão rejeitada serve para reconhecer regressões, não como padrão aprovado. MP4 não revela keyframes internos com certeza.

## 2. Montagem que se sustenta sozinha

Mapeie promessa, contexto, mecanismo, virada e encerramento presentes na fala. Aproveite seleção humana bem resolvida. Compare takes por sentido, completude, dicção, naturalidade e continuidade; não escolha automaticamente o último. Preserve negações, números, ressalvas, finais de palavras, gestos e pausas expressivas. ASR e correlação de áudio localizam candidatos, mas não comprovam escuta. Use EDL com source in/out, timeline in/out, velocidade, vínculo de áudio e vídeo e motivo. Uma mudança de montagem invalida os tempos afetados de legendas, gráficos e SFX.

## 3. Design semântico durante toda a peça

Divida a peça em beats. Para cada intervenção, anote frase disparadora, função, mudança observável, entrada, repouso, transformação, saída e relação com a legenda e o som. Uma troca visual deve ajudar a entender ou dirigir a atenção. Não conte movimento decorativo, zoom sem motivo ou card parado como progresso. Se o briefing impuser frequência de eventos, audite também as lacunas entre eventos e nas bordas do vídeo; não transforme isso em quota de inserts.

## 4. Legenda fiel e cinética até o fim

Revise texto e tempos a partir da montagem atual. Separe cobertura da fala, ênfase e composição hero. Grupos curtos seguem a sintaxe; palavra de tese recebe hierarquia localizada. Pilhas podem antecipar em cinza, ativar no onset, repousar legíveis e sair antes da próxima unidade. Não antecipe negação ou resposta que precisa surpreender. Não duplique a mesma fala em duas camadas concorrentes. Evite palavra cortada antes de seu fim e grupo que muda de âncora/tamanho no meio da palavra. Confira todos os grupos, inclusive a última fala, em tamanho de celular e nos frames de fronteira.

## 5. Inserts que explicam

Pergunte o que a imagem acrescenta à frase completa. Um retrato repetido, crop diferente ou ilustração bonita não explicam um conceito por si. Para processo, mostre etapas; para comparação, mostre relação; para perspectiva, mostre perspectivas realmente diferentes; para resultado, represente o resultado pretendido sem fabricar métricas. Use material real autorizado, diagrama, metáfora claramente editorial ou somente a fala. Mantenha rosto, mãos, texto e dado livres. Registre origem/licença dos assets e contexto de números e alegações.

## 6. Som e cor por problema encontrado

Faça plano sonoro por beat: voz, ambiente, pausa, música, SFX ou silêncio intencional. Sincronize acentos com a ação visível, não com o início abstrato de uma curva. Evite whoosh/click em toda palavra. Música pode ter energia e ainda abrir espaço à voz; ajuste por escuta e medição. Preserve o stem de voz quando a revisão pede apenas música ou visual. Trate ruído, EQ, compressão e de-esser como correções específicas. Para cor, confirme range/gamut/gamma antes de converter; confira pele, branco, exposição e legibilidade no export. Não aplique LUT pelo nome da câmera nem confunda metadados com avaliação estética.

## 7. Revise o export real

Assista integralmente em 1×, ouça isoladamente, revise imagem sem som e simule a interface mobile quando possível. Inspecione frame anterior, exato e posterior de cada entrada/saída de câmera, legenda e insert; também os estados intermediários das transformações. Compare por função com a referência e procure regressões. Frames isolados comprovam composição naquele instante, não ritmo, transição ou som. Um arquivo decodificado e métricas de áudio não equivalem a aprovação estética ou auditiva. Registre cobertura e pendências com timecode. Entregue MP4, legenda, EDL, mapa de motion, plano de áudio, registro de assets e fontes editáveis que realmente existam.

Leia [aprendizados](references/aprendizados.md) e [QA](references/qa.md) antes de aplicar esta skill.
