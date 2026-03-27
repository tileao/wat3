# WAC 6800 Unified

Perfis integrados:
- Offshore Helideck — Standard
- Offshore Helideck — EAPS ON

Os demais perfis permanecem reservados para calibração futura.


## Build status

Esta build inclui todos os perfis do suplemento 6800 kg: Offshore, Clear Area / CAT B e Confined Area, nas configurações Standard, EAPS OFF, EAPS ON e IBF Installed.


Ajuste v3: páginas raster do RFM dos perfis Clear Area regeneradas diretamente do PDF-fonte para alinhar a visualização ao referencial geométrico extraído.

## Build note
This v4-fixed rebuild refactors Figure 4-4 (Confined Area Standard) from the PDF source while preserving the stable v3 app structure.

## Build note
This v5 build fixes the confined IBF interpolation edge case near 0 ft and reanchors Figure 4-6 (Confined Area EAPS ON) to the calibrated page placement used by the PDF-derived chart frame.



## v6 - início da integração Confined 6400

- Adicionadas as cartas do Supplement 12 para Confined: Standard, EAPS OFF, EAPS ON e IBF.
- Os perfis Confined agora usam seleção automática entre a família 6400 e a família 6800.
- Nesta primeira etapa, a família 6400 entra como fonte preferencial até 6400 kg e como fallback para fechar buracos quando a família 6800 falha.

## v7 - costura geométrica em 6400 (Confined Standard)

- O perfil Confined Standard agora usa uma curva unificada entre Supplement 12 e Supplement 50.
- A costura é feita em 6400 kg: a carta baixa alimenta o trecho até 6400 e a carta alta continua acima desse ponto.
- A seleção da página exibida continua simples: até 6400 mostra o Supplement 12; acima de 6400 mostra o Supplement 50.
