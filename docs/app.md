# Podcast Manager 

# Descrição

um app estilo netflix para ter videos de podcast

# Dominio 

podcast feito em video

### Features 

- Listar os eps, podcasts em sessoes de categorias 
    - [saude, fitness, mentalidade, humor]
- Filtrar eps por nome do podcast

## Como 

### Feature:
    Listar os eps dos podcasts em sessoes de categorias 

### Como vou implementar:
    Vou retornar em uma api rest o nome do poscast, episodio, imagem de capa, link, categoria 

    ```js
    [
        {
            podcastName: "flow",
            episode: "CBUM - Flow #319",
            cover: "https://i.ytimg.com/vi/pQSuQmUfS30/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGBACGAY4AUAB&rs=AOn4CLCeNGQeHGq3EN9VBoh7CCsKQU0L4Q",
            link: "https://www.youtube.com/live/pQSuQmUfS30?si=Pt9AzlpOdNI9HBg3",
            categories: ["saude", "bodybuilder"]
        },
        {
            podcastName: "flow",
            episode: "CLÓVIS DE BARROS - Flow #477",
            cover: "https://i.ytimg.com/vi/sVfBJY-YWAM/hq720.jpg?sqp=-oaymwEnCNAFEJQDSFryq4qpAxkIARUAAIhCGAHYAQHiAQoIGBACGAY4AUAB&rs=AOn4CLCdyjaKLLRH8HBlPThfDiMUjgBxcw",
            link: "https://www.youtube.com/live/sVfBJY-YWAM?si=UeDkAn6gTs_o2duo",
            categories: ["saude", "politica"]
        }
    ]
    ```