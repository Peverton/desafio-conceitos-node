![](https://camo.githubusercontent.com/d25397e9df01fe7882dcc1cbc96bdf052ffd7d0c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67)

# desafio-conceitos-node

![](https://camo.githubusercontent.com/fc8a7de2275ecf116aa018e29a5e90d86972a599/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e504d2d362e31332e342d726564)
![](https://camo.githubusercontent.com/db0037884ec485385bdf9e70f215c3d83dcedad8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a6573742d32352e322e362d79656c6c6f77)
![](https://camo.githubusercontent.com/3938a185f7295e11b304754621f97e80d778cc34/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4e6f64652d31322e31362e302d677265656e)
![](https://camo.githubusercontent.com/66be6b2adf832110bef27fe8a7210d02318d9671/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f457870726573732d342e31372e312d626c7565)

Esse foi o primeiro desafio do bootcamp da Rocketseat 💜

## Como usar

Antes de começar, vamos fazer um clone do repositório no seu computador.

> git clone https://github.com/Peverton/desafio-conceitos-node.git

Entre na pasta do projeto e instale as dependências com o comando

> yarn

Ou

> npm install

Para uma melhor experiência, recomendo instalar o <a href="https://insomnia.rest/download/">Insomnia</a>. Se nunca usou essa ferramenta a rocketseat tem um <a href="https://www.youtube.com/watch?v=3tB0uDliS6Y">vídeo explicando como usar</a>.

## Rotas

Listar todos os repositórios: GET

http://localhost:3333/repositories

Criar um repositório: POST

http://localhost:3333/repositories

Editar um repositório: PUT

http://localhost:3333/repositories/:id

Deletar um repositório: DELETE

http://localhost:3333/repositories/:id

Enviar um like para o repositório: POST

http://localhost:3333/repositories/:id/like
