# Unidades


## Unidades Fixas/Absolutas: px, cm, mm;


    - cm e mm: o CSS tem suporte, porém quase não são usadas ou aproveitadas para web-design;
    - px: É uma unidade fixa "normalizada", ela se adapta a densidade de pixels no dispositivo que está sendo usado(DPI);


## Unidade de viewport: vw, vh, vmin, vmax;

    -vw: porcentagem da largura da tela
    -vh: porcentagem da largura da tela;
    -vmin: é a porcentagem do menor lado da tela;
    -vmax: é a porcentagem do maior lado da tela;

## Unidade de fonte: rem, em;

    -rem: trabalhará com uma fonte relativa ao elemento html raíz (body);
    -em: trabalhará com uma fonte relativa ao elemento pai (div, ou qualquer elemento que esteja englobando o filho em questão);

## Caso especial: % (porcentagem);

    - % : é bem semelhante às unidades de viewport(vw,vh...), porém não considera como relativo o elemento pai mais próximo, ao invés do tamanho da tela;