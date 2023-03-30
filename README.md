# Programação Orientada a Objetos em C#
Este repositório contém exemplos de código em C# para ilustrar os conceitos apresentados na wiki de Programação Orientada a Objetos.

## Pré-requisitos
Para executar os exemplos neste repositório, você precisará ter o Docker instalado em sua máquina. Se você ainda não tem o Docker instalado, siga as instruções de instalação apropriadas para o seu sistema operacional aqui.

## Executando a aplicação com Docker
Para executar a aplicação em um ambiente Docker, siga os seguintes passos:

1. Clone este repositório em sua máquina:
git clone https://github.com/seu-username/seu-repositorio.git>`

2. Navegue para o diretório raiz do repositório clonado:
`cd seu-repositorio`

3. Construa a imagem Docker para a aplicação:
`docker build -t exemplo-poo-csharp .`

4. Execute a imagem Docker em um contêiner
`docker run -p 8080:80 -it exemplo-poo-csharp`

5. Abra um navegador e acesse a aplicação em http://localhost:8080.

## Contribuindo
Se você encontrar um problema ou tiver uma sugestão para melhorar este repositório, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este repositório é licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.
