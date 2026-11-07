Sons

Player de música offline, minimalista e personalizável, feito para celular e computador. Funciona como PWA: depois do primeiro acesso, abre e toca sem internet.

Recursos
Biblioteca local: importe arquivos de áudio do aparelho (ou arraste para a janela no computador) e organize por músicas, artistas, álbuns e playlists.
Reprodução completa: play, pause, próxima, anterior, aleatório, repetição (desligada, tudo ou uma música), volume e barra de progresso arrastável.
Fila editável: reordene, remova ou adicione músicas à fila, com “Tocar a seguir” ou “Adicionar à fila”.
Picture-in-Picture: janela flutuante com capa e controles, quando o navegador permite.
Metadados: leitura automática de título, artista, álbum e capa das tags ID3, com edição manual e imagem de capa própria.
Personalização: tema claro, escuro ou personalizado (fundo, texto e destaque), fonte, tamanho do texto, lista ou grade, tamanho dos itens, posição dos controles e animações (podem ser desativadas).
Controle pelo sistema: capa e controles na tela de bloqueio, notificações e teclas de mídia. No computador, Espaço alterna play/pause e Shift + setas trocam de faixa.
Privacidade: nada é enviado a servidores. Músicas, capas, playlists e preferências ficam salvas no próprio aparelho.
Instalação
Hospede os arquivos da pasta sons-pwa em um endereço com HTTPS (GitHub Pages, Netlify, Cloudflare Pages ou similar).
Abra o endereço uma vez com internet.
Instale:
Android (Chrome): menu ⋮ → Instalar app.
iPhone (Safari): Compartilhar → Adicionar à Tela de Início.
Computador (Chrome/Edge): ícone de instalação na barra de endereço.
Atualizar a versão

Ao publicar mudanças, altere sons-v1 para sons-v2 (ou o próximo número) em sw.js. Assim os aparelhos baixam a versão nova.

Estrutura
Arquivo	Função
index.html	App completo (interface, player, biblioteca)
sw.js	Service worker, que permite o uso offline
manifest.webmanifest	Nome, cores e ícones para instalação
icon*.png, icon.svg, apple-touch-icon.png	Ícones do app
LEIA-ME.txt	Instruções rápidas de instalação
Limitações
O PiP de vídeo no celular depende do navegador e do sistema.
A versão publicada no claude.ai não é instalável. Para instalar, hospede os arquivos em um endereço próprio.
Licença

Defina a licença antes de publicar (por exemplo, MIT).
