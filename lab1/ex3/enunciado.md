# Exercício 3 (variação) — Media Queries por faixas de dispositivo e orientação

## Enunciado
Implemente um layout **mobile-first** para uma lista de conteúdos que se adapte a diferentes larguras de tela e também à **orientação** do dispositivo.  

### Regras de responsividade (largura)
- **≤ 360px (mini-phone):** 1 coluna, fontes compactas, espaçamento reduzido.  
- **361–599px (phone):** 1 coluna, fontes padrão.  
- **600–899px (tablet em pé):** 2 colunas, aumenta levemente a tipografia.  
- **900–1199px (tablet deitado / small desktop):** 3 colunas, largura máxima de 1100px centralizada.  
- **≥ 1200px (desktop amplo):** 4 colunas, aumenta novamente a tipografia.  

### Regras adicionais
- Em **orientação landscape**, reduzir a altura máxima dos cards para melhor aproveitamento do espaço horizontal.  
- Utilizar apenas **HTML e CSS** (sem JavaScript).  
- Seguir a abordagem **mobile-first** (usar `min-width`).  
