# food-menu-image-dataset
Dataset de Imagens de Menu de Comidas em Português
(Food Menu Image Dataset - PT-BR)

Dataset utilizado para a construção do Autopictograma, descrito e apresentado na dissertação de Mestrado Profissional em Engenharia de Software - CESAR School do aluno Afonso Henrique Anastácio Calábria.

# Imagens /images
A base de dados é composta por 44 imagens de cardápios extraídos da web na Língua Portuguesa. O critério de escolha das imagens foram: imagens com qualidade suficiente para leitura humana e tamanhos e cores variadas. Com o objetivo de obter uma experiência próxima da realidade, as imagens presentes na base possuem dimensões entre 450x338 e 3108x1654 pixels. As cores também variam de acordo com cada cardápio, além das disposições das informações e fontes de texto.

# Extrações /extracting
Os arquivos foram extraídos em 3 tipos:

- <image-filename>.txt => extração com Tesseract (Python)
- <image-filename>.txt2 => extração manual
- <image-filename>.txt => extração manual das Entidades/pratos dos cardápio