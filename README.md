
# Background transition

Este é um projeto que demonstra como criar efeitos de transição de background usando CSS. A transição de background é uma maneira eficaz de adicionar um visual atraente e interativo a elementos HTML, como botões, links, seções de página, entre outros.

## Funcionalidades

-   Aplica uma transição suave de background ao fundo da página.
-   Pode ser personalizado para se adequar ao design e às necessidades do seu projeto.

## Pré-requisitos

Certifique-se de ter os seguintes requisitos antes de executar o projeto:

-  Um editor de texto ou ambiente de desenvolvimento para escrever o código CSS.
-   Um navegador web moderno para visualizar o resultado final.

## Como usar

Siga as etapas abaixo para executar o projeto em seu próprio ambiente:

1. Clone este repositório em sua máquina local:
`https://github.com/TelesAlan/BackgroundTransition.git`
2. Navegue até o diretório do projeto:
`cd BackgroundTransition`
3.  Abra o arquivo `index.html` em seu navegador para visualizar o efeito de transição de background.  
4.  No arquivo `assets/css/global.css`, você encontrará os estilos CSS responsáveis pela transição de background. Sinta-se à vontade para modificá-los conforme necessário.

## Personalização


Você pode personalizar o efeito de transição de background para atender às suas necessidades. Aqui estão algumas maneiras de fazer isso:

-   Altere as cores e os gradientes no arquivo `global.css` para criar uma transição personalizada:

	    .animated-background {
			height:  100vh;
			width:  100%;
			background:  linear-gradient(to  right, #d73d6c, #005f89, #fcb045);
			background-size:  400%;
			animation: animate-background 10s  infinite  ease-in-out;
		}

## Suporte
Se você tiver algum problema ou dúvida, sinta-se à vontade para abrir uma **issue** neste repositório.

## Contribuição
Contribuições são bem-vindas! Se você deseja melhorar este projeto, siga estas etapas:

1. Faça um fork deste repositório.
2. Crie uma nova branch: "**git checkout -b minha-branch**".
3. Faça suas modificações e commit: "**git commit -m 'Minhas alterações'**".
4. Envie para o repositório remoto: "**git push origin minha-branch**".
5. Abra uma **pull request** explicando suas alterações.
## Licença
Este projeto está licenciado sob a MIT License. Sinta-se livre para usá-lo da maneira que preferir.