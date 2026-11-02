# art-skill-V3

Pacote de prompts e guias para re-renderizar imagens de referência em estilo cartum 2D com iluminação cinematográfica e cel-shading, pensado para edição de imagens no Gemini. O fluxo separa inventário e renderização para preservar personagens, objetos e composição.

## Downloads

- [Baixar pacote ZIP](https://github.com/praimosDEV/art-skill-V3/raw/refs/heads/main/skill%20gera%20arte.zip)
- [Baixar pacote 7z](https://github.com/praimosDEV/art-skill-V3/raw/refs/heads/main/skill%20gera%20arte.7z)

Extraia o arquivo escolhido para acessar o pacote. Para consultar as instruções atuais, use também os arquivos disponíveis neste repositório.

## Como usar

1. Abra um chat novo no Gemini com suporte à edição de imagens.
2. Anexe uma única imagem de referência. Recomenda-se anexar também os guias 02, 03 e 04.
3. Abra [01_PROMPT_MESTRE.txt](01_PROMPT_MESTRE.txt) e cole primeiro a **ETAPA A — Inventário**, sem gerar imagem.
4. Confira a contagem de personagens, poses, objetos, cenário e a paleta proposta. Corrija o inventário e confirme antes de renderizar.
5. Cole a **ETAPA B — Renderização** com os campos de paleta e luz preenchidos; os campos previstos como automáticos podem ficar vazios, conforme o prompt mestre.
6. Se precisar ajustar o resultado, use os prompts do arquivo 04 no mesmo chat.

O objetivo é mudar o estilo visual mantendo identidade, quantidade de elementos, enquadramento e proporção da imagem original. Os resultados dependem do modelo e podem exigir correções.

## Conteúdo do repositório

| Arquivo | Finalidade |
| --- | --- |
| [01_PROMPT_MESTRE.txt](01_PROMPT_MESTRE.txt) | Fluxo completo em duas etapas e versão compacta em inglês. |
| [02_GUIA_DE_ESTILO_VISUAL.txt](02_GUIA_DE_ESTILO_VISUAL.txt) | Guia de estilo visual. |
| [03_PALETAS_E_ILUMINACAO.txt](03_PALETAS_E_ILUMINACAO.txt) | Referências de paleta e iluminação. |
| [04_CONSISTENCIA_E_CORRECOES.txt](04_CONSISTENCIA_E_CORRECOES.txt) | Instruções de consistência e correções. |
| [05_EXEMPLOS_VERSAO_CURTA_E_GEM.txt](05_EXEMPLOS_VERSAO_CURTA_E_GEM.txt) | Exemplos, versão curta e material para Gem. |
| [agent.md](agent.md) | Orientações resumidas para o agente, com inventário e confirmação antes da geração. |

## Diretrizes visuais

- Contornos limpos, cores chapadas e sombras geométricas de borda dura.
- Paleta em HEX com proporção 60/30/10.
- Luz principal direcional e luz de contorno; brilho apenas em elementos emissivos.
- Névoa opcional como acabamento no plano médio e fundo.
- Preservação dos personagens, objetos, cenário e composição da referência.
