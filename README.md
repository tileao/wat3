# WAC 6800 Unified

Perfis integrados:
- Offshore Helideck — Standard
- Offshore Helideck — EAPS ON

Os demais perfis permanecem reservados para calibração futura.


## Build status

Esta build inclui todos os perfis do suplemento 6800 kg: Offshore, Clear Area / CAT B e Confined Area, nas configurações Standard, EAPS OFF, EAPS ON e IBF Installed.


Ajuste v3: páginas raster do RFM dos perfis Clear Area regeneradas diretamente do PDF-fonte para alinhar a visualização ao referencial geométrico extraído.


## v4
- Figure 4-4 (Confined Area Standard) refeito do zero a partir do PDF-fonte.
- `data/confined-standard-exact.json` regenerado diretamente dos vetores do PDF.
- `docs/page-04.png` rerenderizado do PDF com alinhamento direto às coordenadas da página.
- Overlay do Figure 4-4 agora usa mapeamento direto da página, sem placement manual dedicado.
