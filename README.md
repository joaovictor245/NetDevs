# NetDevs
Uma copia da netfix 

![image](https://cdn.discordapp.com/attachments/1175249252771958844/1192311231441293332/Netdevs_1.png?ex=65a89d5d&is=6596285d&hm=daa8a0d5dbfca433e70097aeea9caf8ba55c5e194cfe8b5798f143812fb0394a&)

![image](https://cdn.discordapp.com/attachments/1175249252771958844/1192311231831351326/Netdevs_2.png?ex=65a89d5d&is=6596285d&hm=b6fc012a0e6ae662d8329d0fdfc5743e3b5f4cb7150d0518824117951b8aa0b0&)

![image](https://cdn.discordapp.com/attachments/1175249252771958844/1192311231026053151/Netdevs_3.png?ex=65a89d5d&is=6596285d&hm=48775400e0c4d16c830fcb674fcd2dd7c064be3c4b828b92136131f2aeb23eda&)

- HTML (index.html):
Cabeçalho e Metadados:

 Declaração do tipo de documento, idioma e metadados.
Inclusão de folhas de estilo Bootstrap e Bootstrap Icons.
Vinculação de seu próprio arquivo de estilo (netflix.css) e scripts.
Barra de Navegação:

 Barra de navegação fixa no topo com um logotipo, botões de navegação e um menu suspenso.
Ícones de pesquisa, sino e um perfil do usuário à direita.
Vídeo de Destaque:

 Uma seção destacada com um vídeo em plano de fundo e conteúdo sobreposto.
Botões de reprodução e informações sobre o vídeo.
Seções de Conteúdo Trending:

 Três seções para diferentes tipos de conteúdo (Trending Now, Popular na Netdevs, Popular TV).
Cada seção tem um título e um carrossel de cartazes de filmes ou programas de TV.
Rodapé:

 Links e informações sobre áudios, mídia central, privacidade, contato, etc.
Outra seção com links para termos, ajuda, serviços, etc.
Informações legais, termos de uso e direitos autorais.
Scripts JavaScript:

 Ativação do efeito sticky na barra de navegação durante o rolar da página.
Uma função fetchAndDisplayData para buscar e exibir dados de filmes ou programas de TV de uma API e popular as seções de conteúdo.
- CSS (netflix.css):
- Estilos Gerais:

 Definições de fundo, largura máxima da página, etc.
Estilos para a barra de navegação, incluindo a barra fixa no topo quando o usuário rola a página.
- Estilos da Barra de Navegação:

 Estilização específica para a barra de navegação, logotipo, botões e menu suspenso.
Estilos do Vídeo de Destaque:

 Estilos para a seção de vídeo de destaque, sobreposição de conteúdo e botões.
Estilos das Seções de Conteúdo:

 Estilos para as seções de conteúdo Trending Now, Popular na Netdevs, e Popular TV.
Configurações específicas para o carrossel de cartazes.
Estilos do Rodapé:

 Estilos para a seção de rodapé, links, informações e direitos autorais.
Estilos Responsivos:

  Media queries para ajustar o layout em dispositivos de tela menores.
- JavaScript (netflix.js):
Eventos de Rolagem:

 Um manipulador de eventos para tornar a barra de navegação fixa quando o usuário rola a página.
Funções de Busca e Exibição de Dados:

 Uma função fetchAndDisplayData que usa a API do TMDB para buscar dados de filmes ou programas de TV e preencher as seções de conteúdo.
O código é extenso e contém diversas funcionalidades, proporcionando uma experiência interativa e responsiva para os usuários. Certifique-se de fornecer as chaves de API corretas para a integração com a API do The Movie Database (TMDB).
