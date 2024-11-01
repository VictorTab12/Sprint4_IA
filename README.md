# Sprint4_IA
InovaX
Integrantes:
Lucas dos Santos Lopes RM:550790
Murilo Machado RM:550718
Victor Taborda Rodrigues RM:97900
Gustavo Marques Catelan RM:551823
Gabriel Bacelar Valentim RM97901

DESCRIÇÃO DO PROJETO
A InovaX é uma plataforma inovadora desenvolvida para comparar produtos e serviços essenciais, como planos de saúde e assinaturas, além de itens convencionais. Nosso objetivo é oferecer uma experiência completa de comparação, facilitando a tomada de decisões com base nas melhores opções disponíveis em diversas plataformas.
Funcionalidades Principais
Pesquisa Avançada de Produtos: Utilizando a linguagem Kotlin e a SerpAPI para integração com o Google Shopping, é possível buscar produtos e visualizar uma lista de opções com preços e fornecedores variados, permitindo ao usuário encontrar a melhor opção.
Gestão de Carrinho de Compras: O usuário pode adicionar produtos ao carrinho com as melhores ofertas que encontrou, visualizar o valor total dos itens selecionados e remover produtos conforme sua preferência.
Comparação de Ofertas: Cada produto pesquisado exibe diferentes preços e sites, facilitando a escolha da oferta ideal.

CRUD Completo nas Telas
Create (Adicionar Produto): A funcionalidade de adicionar produtos ao carrinho está implementada. O método addToCart na classe Pesquisa permite ao usuário incluir um produto no carrinho e salva esses dados localmente via SharedPreferences (usando CartUtils).
Read (Ler Produtos): Os produtos são exibidos na tela de pesquisa com a opção de visualizar os detalhes do produto. Essa leitura é feita a partir da pesquisa via API (Google Shopping usando SerpAPI), e os resultados são mostrados no ResultAdapter. O carrinho também exibe os produtos armazenados.
Update (Atualizar o Total do Preço no Carrinho de Compras): O total do carrinho é atualizado automaticamente conforme produtos são adicionados ou removidos, refletindo o valor atual dos itens.
Delete (Remover Produto): A remoção de produtos do carrinho está implementada. O método removeFromCart na classe Carrinho permite ao usuário excluir itens do carrinho e atualiza o armazenamento local.Pesquisa via API: A integração com a API (Google Shopping via SerpAPI) está presente no método searchProducts da classe Pesquisa. Essa função faz uma chamada para obter dados de produtos, que são exibidos ao usuário.
Tecnologias Utilizadas
Linguagem: Kotlin
API de Pesquisa: SerpAPI (Google Shopping)


Link do video:
https://youtu.be/xF-zvT1buic
