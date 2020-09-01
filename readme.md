# ARQUIVO CONTENTO MIXINS SASS ÚTEIS PARA DESENVOLVIMENTO FRONTEND

# AUTHOR
    MAT RAMALHO - matheusramalho.dev

# SASS

# Compila
    sass assets/sass/style.scss assets/css/style.css

# Compila comprimido
    sass assets/sass/style.scss assets/css/style.css --style compressed

# Compila sem o arquivo map
    sass assets/sass/style.scss assets/css/style.css --no-source-map

# Compila sem o arquivo map e na versão comprimida
    sass assets/sass/style.scss assets/css/style.css --no-source-map --style compressed

# Monitora um arquivo e envia para o arquivo destino
    sass --watch style.scss style.css
    sass --watch style.scss style.css --no-source-map --style compressed

# Monitora todos os arquivos da pasta e envia para pasta de destino
    - O arquivo sasse o css tem que ter o mesmo nome.
    sass --watch assets/sass:assets/css
    sass --watch assets/sass:assets/css --no-source-map --style compressed