
---

# Sistema de Recomendação de Imagens por Similaridade

Este projeto implementa um sistema de recomendação de produtos com base em **semelhança visual**. Utilizando um modelo pré-treinado **ResNet50**, o sistema extrai características (embeddings) das imagens e calcula a similaridade entre elas, recomendando produtos similares a partir de uma consulta de imagem.

## Tecnologias

- **Python**
- **TensorFlow/Keras**
- **NumPy**
- **Scikit-learn**
- **PIL/Pillow**

## Como Usar

1. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

2. Organize as imagens no diretório `./images/`.

3. Coloque a imagem a ser consultada no arquivo `query_image.jpg`.

4. Execute o script:

   ```bash
   python script.py
   ```


