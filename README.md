Alguns códigos que desenvolví que facilitam o dia a dia

1) O arquivo delete_multiple_photos_instagram.js faz algo que o instagram não nos permite que é selecionarmos várias fotos para a exclusão, o código faz com que através do id da foto(pego através do parâmetro "oe="), role a página a cada 3 segundos, e se encontrado o id da foto na array de valores das classes correspondentes a foto, realize a exclusão.

1.1) Para usar esse script, é necessário emular um ambiente mobile pelo Chrome.
1.2) Após estarmos no ambiente mobile, inspecionar o elemento a ser deletado, procurar pela div correspondente a imagem que desejamos excluir, normalmente é a div com classe KL4Bh.
1.3) Pegue o src da imagem expandindo a classe acima, e procurando pela tag img, no src da img, ao final da url, você deverá ver o parâmetro oe=, é esse que uso para excluir.
