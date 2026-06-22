# instagram-cdn

Host **transitorio e publico** de imagens para a Instagram Graph API.

O worker do blog faz push de uma imagem aqui apenas pelos segundos em que o Instagram a baixa ao criar o container de media; depois o Instagram re-hospeda e o worker apaga o arquivo. As imagens vao para o feed publico do Instagram de qualquer forma, entao nada sensivel vaza.
