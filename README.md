# BlockTube[pt_BR/pt_PT]

WebExtensão para Chrome e Firefox.  
Filtre[a] e bloqueie conteúdo indesejado do YouTube ™.

## Extension features[Recursos da extensão]

* Bloqueie[a] videos via: **Video Title[Título do video]** / **Channel Name[Nome do Canal]** / **Channel ID[ID do Canal]** / **Video ID[ID do Video]**
* Bloqueie[a] comentários via **User[Usuário]** / **Comment content[Conteúdo do comentário]**
* Bloqueie[a] vídeos no YouTube usando menus de contexto
* Bloqueie[a] os vídeos não aparecem em nenhum lugar do site
* Bloqueie[a] canais completos[tamente]
* Suporta palavras-chave[Keywords] e Regex bruto[raw Regex]
* Não quebra nem limita nenhum recurso do YouTube, como lista de reprodução ou reprodução automática
* Oculta[e] e bloquea a seção Tendências[Em Alta/Trend Topic]
* Protega[e] as opções de extensão com uma senha
* A filtragem é feita antes de qualquer renderização DOM[DOM Rendering]


## Install[Instalação]

* [**Chrome Webstore**](https://chrome.google.com/webstore/detail/blocktube/bbeaicapbccfllodepmimpkgecanonai?hl=en-US)
* [**Firefox AMO**](https://addons.mozilla.org/en-US/firefox/addon/blocktube/)

## FAQ[Perguntas Mais Frequentes]
* Ainda estou usando o design de layout antigo do YouTube, posso usar esta extensão? 
  Não. Por favor, mude para o novo design [aqui](https://www.youtube.com/new)  
  
* Qual é a diferença entre "Channel ID[ID do Canal]" e "Channel Name[Nome do Canal]"  
  Os nomes dos canais no YouTube não são exclusivos e podem ser duplicados/alterados 
  enquanto o ID do canal é uma cadeia de identificação exclusiva[unique identification string] que nunca muda.  
  Se você deseja bloquear um canal único específico, o método preferido é usar seu ID,  
  Se você deseja bloquear vários canais que compartilham nomes semelhantes, use o nome.

* Como posso obter o ID de um canal[channel's ID]?  
  O ID do canal tem esta aparência: UCXXXXXXXXXXXXXXXX  
  Para obtê-lo, basta acessar uma página do canal e olhar para o URL `/channel/UCXXXXXXXXXXXXXXXXXXXX`  
  Se o URL for `/user/BadChannelExample` use [Esse site](http://johnnythetank.github.io/youtube-channel-name-converter/) para converter o nome de usuário no ID do canal

* Como bloquear comentários de um usuário específico?  
  Os comentários dos canais bloqueados também são removidos; basta adicionar o nome do usuário[Channel Name]/ID do canal[Channel ID]
  para seus filtros

* Qual é o comportamento ao navegar no canal bloqueado?  
  O usuário será redirecionado para a página inicial do YouTube[Youtube homepage].

* Qual é o comportamento ao navegar pelo vídeo bloqueado?  
  Você pode escolher entre duas opções:
  - Bloqueie a página inteira e deixe uma mensagem personalizada
  - Redirecionar automaticamente o usuário para o próximo vídeo

* Como posso garantir que esta extensão não possa ser ignorada[bypassed]?   
  TODO[PARA FAZER]
  
## Future work[Trabalho futuro]

* UI de opções amigáveis[User-friendly options UI]
* Opções de sincronização com políticas de provedor[enterprise policies]/empresa na nuvem[cloud provider]
* ~~Auxiliar de menu de contexto[Context menu helper]~~ Pronto[Done]
* Modo de lista de permissões[Whitelist mode]
* Suporte para jogos[Gaming] do YouTube[YouTube Gaming support]
* Regras dinâmicas (combine várias regras para bloquear um vídeo)[Dynamic rules]

## License[Licensa]

Este projeto está licenciado sob a licença GPLv3 - consulte o arquivo [LICENSA](LICENSA) para obter detalhes

## Acknowledgments[Agradecimentos]

* Ícone de extensão de: http://www.designbolts.com/2013/09/08/40-free-shaded-social-media-icons/
