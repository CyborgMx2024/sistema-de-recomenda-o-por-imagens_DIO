🖼️ Image Similarity Product Recommender

Image Similarity Product Recommender é um sistema poderoso que identifica e recomenda produtos semelhantes a partir de imagens, utilizando a arquitetura de Deep Learning VGG16. Este projeto permite buscar imagens visualmente parecidas diretamente da web, sem a necessidade de APIs externas. É ideal para e-commerce e plataformas que desejam oferecer recomendações baseadas em características visuais dos produtos, como cor, formato e textura.
🚀 Funcionalidades

    Busca de Imagens na Web: Faz scraping de imagens relacionadas usando Google Imagens.
    Comparação de Similaridade: Utiliza redes neurais para extrair embeddings de imagens e calcula a similaridade com base em suas características visuais.
    Exibição de Resultados: Assemelha produtos a partir de uma imagem de consulta e exibe os itens mais parecidos.
    100% API-Free: Totalmente funcional sem a necessidade de APIs pagas ou chaves de autenticação.

🛠️ Tecnologias Utilizadas

    TensorFlow & Keras: Para a construção e utilização do modelo VGG16 pré-treinado.
    Web Scraping: Com BeautifulSoup para a busca de imagens na web.
    Cosine Similarity: Para calcular a proximidade visual entre as imagens.
    Matplotlib: Para visualização das imagens recomendadas.

🎯 Como Funciona

    Processamento de Imagens: O sistema processa a imagem de consulta utilizando o modelo VGG16, que extrai as principais características visuais (embeddings).
    Busca de Produtos Semelhantes: O sistema então busca por imagens semelhantes na web com base em um termo de pesquisa definido.
    Cálculo de Similaridade: Compara a imagem de consulta com as imagens retornadas e exibe as mais parecidas.

🌟 Exemplos de Uso

Busque e recomende produtos como:

    Relógios
    Roupas
    Acessórios
    Calçados
    E muito mais!

📸 Visualização

Abaixo está um exemplo de visualização de recomendações:

📦 Como Executar
1- Clone o repositório:
git clone https://github.com/seu-usuario/seu-repositorio.git

2- Instale as dependências:
pip install -r requirements.txt

3- Execute o script principal:
python image_similarity_recommender.py

💻 Requisitos

    Python 3.x
    TensorFlow
    Keras
    BeautifulSoup
    Requests
    
🤝 Contribuição

Sinta-se à vontade para contribuir com o projeto! Envie suas sugestões, melhorias ou correções por meio de Pull Requests.
