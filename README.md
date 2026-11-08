# Trabajo Práctico Integrador - Computación Aplicada - Universidad de Palermo

# Integrantes
- Joel Ezequiel Vegas

# Contenido
 Archivos :
- root.tar.gz
- etc.tar.gz
- opt.tar.gz
- www_dir.tar.gz
- backup_dir.tar.gz
- var.tar.gz.part_aa a part_ad (/var dividido en partes de 20 MB)

# Cómo reconstruir /var
    cat var.tar.gz.part_* > var.tar.gz
    tar -xzf var.tar.gz
