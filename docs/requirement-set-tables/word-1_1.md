| Classe | Campos | Descrição |
|:---|:---|:---|
|[Body](/javascript/api/word/word.body)|[clear()](/javascript/api/word/word.body#clear--)|Limpa o conteúdo do objeto Body.|
||[getHtml()](/javascript/api/word/word.body#gethtml--)|Obtém uma representação HTML do objeto Body.|
||[getOoxml()](/javascript/api/word/word.body#getooxml--)|Obtém a representação OOXML (Office Open XML) do objeto Body.|
||[ignorePunct](/javascript/api/word/word.body#ignorepunct)||
||[ignoreSpace](/javascript/api/word/word.body#ignorespace)||
||[insertBreak (breaktype: Word. Breaktype, insertLocation: Word. InsertLocation)](/javascript/api/word/word.body#insertbreak-breaktype--insertlocation-)|Insere uma quebra no local especificado no documento principal.|
||[insertContentControl()](/javascript/api/word/word.body#insertcontentcontrol--)|Quebra o objeto Body com um controle de conteúdo de rich text.|
||[insertFileFromBase64 (base64file: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.body#insertfilefrombase64-base64file--insertlocation-)|Insere um documento no corpo, no local especificado.|
||[Métodoinserthtml (HTML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.body#inserthtml-html--insertlocation-)|Insere HTML no local especificado.|
||[Métodoinsertooxml (OOXML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.body#insertooxml-ooxml--insertlocation-)|Insere um formato OOXML no local especificado.|
||[insertParagraph (paragraphText: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.body#insertparagraph-paragraphtext--insertlocation-)|Insere um parágrafo no local especificado.|
||[insertText (Text: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.body#inserttext-text--insertlocation-)|Insere texto no corpo, no local especificado.|
||[matchCase](/javascript/api/word/word.body#matchcase)||
||[matchPrefix](/javascript/api/word/word.body#matchprefix)||
||[matchSuffix](/javascript/api/word/word.body#matchsuffix)||
||[matchWholeWord](/javascript/api/word/word.body#matchwholeword)||
||[matchWildcards](/javascript/api/word/word.body#matchwildcards)||
||[contentControls](/javascript/api/word/word.body#contentcontrols)|Obtém a coleção de objetos de controle de conteúdo de Rich Text no corpo.|
||[font](/javascript/api/word/word.body#font)|Obtém o formato de texto do corpo.|
||[inlinePictures](/javascript/api/word/word.body#inlinepictures)|Obtém a coleção de objetos InlinePicture no corpo.|
||[paragraphs](/javascript/api/word/word.body#paragraphs)|Obtém a coleção de objetos Paragraph no corpo.|
||[parentContentControl](/javascript/api/word/word.body#parentcontentcontrol)|Obtém o controle de conteúdo que inclui o corpo.|
||[text](/javascript/api/word/word.body#text)|Obtém o texto do corpo.|
||[Search (ProcurarTexto: cadeia de caracteres, searchoptions?: Word. Searchoptions \| {ignorePunct?: Boolean ignorespace?: Boolean MatchCase?: Boolean matchPrefix?: Boolean matchSuffix?: Boolean matchWholeWord?](/javascript/api/word/word.body#search-searchtext--searchoptions--ignorepunct--ignorespace--matchcase--matchprefix--matchsuffix--matchwholeword--matchwildcards-)|Realiza uma pesquisa com o Searchoptions especificado no escopo do objeto Body.|
||[selecionar (selectionMode?: Word. SelectionMode)](/javascript/api/word/word.body#select-selectionmode-)|Seleciona o corpo e navega na interface do usuário do Word até ele.|
||[style](/javascript/api/word/word.body#style)|Obtém ou define o nome do estilo para o corpo.|
|[ContentControl](/javascript/api/word/word.contentcontrol)|[apresentação](/javascript/api/word/word.contentcontrol#appearance)|Obtém ou define a aparência do controle de conteúdo.|
||[cannotDelete](/javascript/api/word/word.contentcontrol#cannotdelete)|Obtém ou define um valor que indica se o usuário pode excluir o controle de conteúdo.|
||[cannotEdit](/javascript/api/word/word.contentcontrol#cannotedit)|Obtém ou define um valor que indica se o usuário pode editar o conteúdo do controle de conteúdo.|
||[clear()](/javascript/api/word/word.contentcontrol#clear--)|Limpa o conteúdo do controle de conteúdo.|
||[color](/javascript/api/word/word.contentcontrol#color)|Obtém ou define a cor do controle de conteúdo.|
||[excluir (keepContent: Boolean)](/javascript/api/word/word.contentcontrol#delete-keepcontent-)|Exclui o controle de conteúdo e o respectivo conteúdo.|
||[getHtml()](/javascript/api/word/word.contentcontrol#gethtml--)|Obtém uma representação HTML do objeto de controle de conteúdo.|
||[getOoxml()](/javascript/api/word/word.contentcontrol#getooxml--)|Obtém a representação OOXML (Office Open XML) do objeto do controle de conteúdo.|
||[ignorePunct](/javascript/api/word/word.contentcontrol#ignorepunct)||
||[ignoreSpace](/javascript/api/word/word.contentcontrol#ignorespace)||
||[insertBreak (breaktype: Word. Breaktype, insertLocation: Word. InsertLocation)](/javascript/api/word/word.contentcontrol#insertbreak-breaktype--insertlocation-)|Insere uma quebra no local especificado no documento principal.|
||[insertFileFromBase64 (base64file: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.contentcontrol#insertfilefrombase64-base64file--insertlocation-)|Insere um documento no controle de conteúdo no local especificado.|
||[Métodoinserthtml (HTML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.contentcontrol#inserthtml-html--insertlocation-)|Insere HTML no local especificado dentro do controle de conteúdo.|
||[Métodoinsertooxml (OOXML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.contentcontrol#insertooxml-ooxml--insertlocation-)|Insere OOXML no controle de conteúdo no local especificado.|
||[insertParagraph (paragraphText: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.contentcontrol#insertparagraph-paragraphtext--insertlocation-)|Insere um parágrafo no local especificado.|
||[insertText (Text: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.contentcontrol#inserttext-text--insertlocation-)|Insere texto no local especificado dentro do controle de conteúdo.|
||[matchCase](/javascript/api/word/word.contentcontrol#matchcase)||
||[matchPrefix](/javascript/api/word/word.contentcontrol#matchprefix)||
||[matchSuffix](/javascript/api/word/word.contentcontrol#matchsuffix)||
||[matchWholeWord](/javascript/api/word/word.contentcontrol#matchwholeword)||
||[matchWildcards](/javascript/api/word/word.contentcontrol#matchwildcards)||
||[placeholderText](/javascript/api/word/word.contentcontrol#placeholdertext)|Obtém ou define o texto do espaço reservado do controle de conteúdo.|
||[contentControls](/javascript/api/word/word.contentcontrol#contentcontrols)|Obtém a coleção de objetos de controle de conteúdo no controle de conteúdo.|
||[font](/javascript/api/word/word.contentcontrol#font)|Obtém o formato de texto do controle de conteúdo.|
||[id](/javascript/api/word/word.contentcontrol#id)|Obtém um número inteiro que representa o identificador do controle de conteúdo.|
||[inlinePictures](/javascript/api/word/word.contentcontrol#inlinepictures)|Obtém a coleção de objetos inlinePicture no controle de conteúdo.|
||[paragraphs](/javascript/api/word/word.contentcontrol#paragraphs)|Obtém a coleção de objetos Paragraph no controle de conteúdo.|
||[parentContentControl](/javascript/api/word/word.contentcontrol#parentcontentcontrol)|Obtém o controle de conteúdo que inclui o controle de conteúdo.|
||[text](/javascript/api/word/word.contentcontrol#text)|Obtém o texto do controle de conteúdo.|
||[type](/javascript/api/word/word.contentcontrol#type)|Obtém o tipo de controle de conteúdo.|
||[removeWhenEdited](/javascript/api/word/word.contentcontrol#removewhenedited)|Obtém ou define um valor que determina quando o controle de conteúdo é removido após a edição.|
||[Search (ProcurarTexto: cadeia de caracteres, searchoptions?: Word. Searchoptions \| {ignorePunct?: Boolean ignorespace?: Boolean MatchCase?: Boolean matchPrefix?: Boolean matchSuffix?: Boolean matchWholeWord?](/javascript/api/word/word.contentcontrol#search-searchtext--searchoptions--ignorepunct--ignorespace--matchcase--matchprefix--matchsuffix--matchwholeword--matchwildcards-)|Realiza uma pesquisa com o Searchoptions especificado no escopo do objeto de controle de conteúdo.|
||[selecionar (selectionMode?: Word. SelectionMode)](/javascript/api/word/word.contentcontrol#select-selectionmode-)|Seleciona o controle de conteúdo.|
||[style](/javascript/api/word/word.contentcontrol#style)|Obtém ou define o nome do estilo do controle de conteúdo.|
||[identificador](/javascript/api/word/word.contentcontrol#tag)|Obtém ou define uma marca para identificar um controle de conteúdo.|
||[title](/javascript/api/word/word.contentcontrol#title)|Obtém ou define o título do controle de conteúdo.|
|[ContentControlCollection](/javascript/api/word/word.contentcontrolcollection)|[getById(id: number)](/javascript/api/word/word.contentcontrolcollection#getbyid-id-)|Obtém um controle de conteúdo pelo respectivo identificador.|
||[getByTag(tag: string)](/javascript/api/word/word.contentcontrolcollection#getbytag-tag-)|Obtém os controles de conteúdo com a marca especificada.|
||[getByTitle(title: string)](/javascript/api/word/word.contentcontrolcollection#getbytitle-title-)|Obtém os controles de conteúdo com o título especificado.|
||[getItem(index: number)](/javascript/api/word/word.contentcontrolcollection#getitem-index-)|Obtém um controle de conteúdo por seu índice na coleção.|
||[items](/javascript/api/word/word.contentcontrolcollection#items)|Obtém os itens filhos carregados nesta coleção.|
|[Document](/javascript/api/word/word.document)|[GetSelection ()](/javascript/api/word/word.document#getselection--)|Obtém a seleção atual do documento.|
||[body](/javascript/api/word/word.document#body)|Obtém o objeto Body do documento.|
||[contentControls](/javascript/api/word/word.document#contentcontrols)|Obtém a coleção de objetos de controle de conteúdo no documento.|
||[salvo](/javascript/api/word/word.document#saved)|Indica se as alterações do documento foram salvas.|
||[sections](/javascript/api/word/word.document#sections)|Obtém a coleção de objetos section no documento.|
||[save()](/javascript/api/word/word.document#save--)|Salva o documento.|
|[Font](/javascript/api/word/word.font)|[bold](/javascript/api/word/word.font#bold)|Obtém ou define um valor que indica se a fonte está em negrito.|
||[color](/javascript/api/word/word.font#color)|Obtém ou define a cor da fonte especificada.|
||[doubleStrikeThrough](/javascript/api/word/word.font#doublestrikethrough)|Obtém ou define um valor que indica se a fonte tem um tachado duplo.|
||[highlightColor](/javascript/api/word/word.font#highlightcolor)|Obtém ou define a cor de realce.|
||[italic](/javascript/api/word/word.font#italic)|Obtém ou define um valor que indica se a fonte está em itálico.|
||[name](/javascript/api/word/word.font#name)|Obtém ou define um valor que representa o nome da fonte.|
||[size](/javascript/api/word/word.font#size)|Obtém ou define um valor que representa o tamanho da fonte em pontos.|
||[Tachado](/javascript/api/word/word.font#strikethrough)|Obtém ou define um valor que indica se a fonte tem um tachado.|
||[subscript](/javascript/api/word/word.font#subscript)|Obtém ou define um valor que indica se a fonte é um subscrito.|
||[superscript](/javascript/api/word/word.font#superscript)|Obtém ou define um valor que indica se a fonte é um sobrescrito.|
||[underline](/javascript/api/word/word.font#underline)|Obtém ou define um valor que indica o tipo de sublinhado da fonte.|
|[InlinePicture](/javascript/api/word/word.inlinepicture)|[altTextDescription](/javascript/api/word/word.inlinepicture#alttextdescription)|Obtém ou define uma cadeia de caracteres que representa o texto alternativo associado à imagem embutida.|
||[altTextTitle](/javascript/api/word/word.inlinepicture#alttexttitle)|Obtém ou define uma cadeia de caracteres que inclui o título da imagem embutida.|
||[getBase64ImageSrc()](/javascript/api/word/word.inlinepicture#getbase64imagesrc--)|Obtém a representação de cadeia de caracteres codificada em base64 da imagem embutida.|
||[height](/javascript/api/word/word.inlinepicture#height)|Obtém ou define um número que descreve a altura da imagem embutida.|
||[hiperlink](/javascript/api/word/word.inlinepicture#hyperlink)|Obtém ou define um hiperlink na imagem.|
||[insertContentControl()](/javascript/api/word/word.inlinepicture#insertcontentcontrol--)|Quebra a imagem embutida com um controle de conteúdo de rich text.|
||[lockAspectRatio](/javascript/api/word/word.inlinepicture#lockaspectratio)|Obtém ou define um valor que indica se a imagem embutida mantém as respectivas proporções originais quando você a redimensiona.|
||[parentContentControl](/javascript/api/word/word.inlinepicture#parentcontentcontrol)|Obtém o controle de conteúdo que inclui a imagem embutida.|
||[width](/javascript/api/word/word.inlinepicture#width)|Obtém ou define um número que descreve a largura da imagem embutida.|
|[InlinePictureCollection](/javascript/api/word/word.inlinepicturecollection)|[items](/javascript/api/word/word.inlinepicturecollection#items)|Obtém os itens filhos carregados nesta coleção.|
|[Paragraph](/javascript/api/word/word.paragraph)|[Alignment](/javascript/api/word/word.paragraph#alignment)|Obtém ou define o alinhamento de um parágrafo.|
||[clear()](/javascript/api/word/word.paragraph#clear--)|Limpa o conteúdo do objeto Paragraph.|
||[delete()](/javascript/api/word/word.paragraph#delete--)|Exclui o parágrafo e o respectivo conteúdo do documento.|
||[firstLineIndent](/javascript/api/word/word.paragraph#firstlineindent)|Retorna ou define o valor, em pontos, para um recuo deslocado ou da primeira linha.|
||[getHtml()](/javascript/api/word/word.paragraph#gethtml--)|Obtém uma representação HTML do objeto Paragraph.|
||[getOoxml()](/javascript/api/word/word.paragraph#getooxml--)|Obtém a representação OOXML (Office Open XML) do objeto Paragraph.|
||[ignorePunct](/javascript/api/word/word.paragraph#ignorepunct)||
||[ignoreSpace](/javascript/api/word/word.paragraph#ignorespace)||
||[insertBreak (breaktype: Word. Breaktype, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#insertbreak-breaktype--insertlocation-)|Insere uma quebra no local especificado no documento principal.|
||[insertContentControl()](/javascript/api/word/word.paragraph#insertcontentcontrol--)|Quebra o objeto Paragraph com um controle de conteúdo de rich text.|
||[insertFileFromBase64 (base64file: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#insertfilefrombase64-base64file--insertlocation-)|Insere um documento no parágrafo no local especificado.|
||[Métodoinserthtml (HTML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#inserthtml-html--insertlocation-)|Insere HTML no local especificado dentro do parágrafo.|
||[insertInlinePictureFromBase64 (base64EncodedImage: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#insertinlinepicturefrombase64-base64encodedimage--insertlocation-)|Insere uma imagem no local especificado dentro do parágrafo.|
||[Métodoinsertooxml (OOXML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#insertooxml-ooxml--insertlocation-)|Insere OOXML no parágrafo no local especificado.|
||[insertParagraph (paragraphText: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#insertparagraph-paragraphtext--insertlocation-)|Insere um parágrafo no local especificado.|
||[insertText (Text: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.paragraph#inserttext-text--insertlocation-)|Insere texto no local especificado dentro do parágrafo.|
||[leftIndent](/javascript/api/word/word.paragraph#leftindent)|Obtém ou define o valor de recuo à esquerda, em pontos, para o parágrafo.|
||[lineSpacing](/javascript/api/word/word.paragraph#linespacing)|Obtém ou define o espaçamento entre linhas, em pontos, para o parágrafo especificado.|
||[lineUnitAfter](/javascript/api/word/word.paragraph#lineunitafter)|Obtém ou define a quantidade de espaçamento, em linhas de grade, após o parágrafo.|
||[lineUnitBefore](/javascript/api/word/word.paragraph#lineunitbefore)|Obtém ou define a quantidade de espaçamento, em linhas de grade, antes do parágrafo.|
||[matchCase](/javascript/api/word/word.paragraph#matchcase)||
||[matchPrefix](/javascript/api/word/word.paragraph#matchprefix)||
||[matchSuffix](/javascript/api/word/word.paragraph#matchsuffix)||
||[matchWholeWord](/javascript/api/word/word.paragraph#matchwholeword)||
||[matchWildcards](/javascript/api/word/word.paragraph#matchwildcards)||
||[outlineLevel](/javascript/api/word/word.paragraph#outlinelevel)|Obtém ou define o nível de estrutura de tópicos para o parágrafo.|
||[contentControls](/javascript/api/word/word.paragraph#contentcontrols)|Obtém a coleção de objetos de controle de conteúdo no parágrafo.|
||[font](/javascript/api/word/word.paragraph#font)|Obtém o formato de texto do parágrafo.|
||[inlinePictures](/javascript/api/word/word.paragraph#inlinepictures)|Obtém a coleção de objetos InlinePicture no parágrafo.|
||[parentContentControl](/javascript/api/word/word.paragraph#parentcontentcontrol)|Obtém o controle de conteúdo que inclui o parágrafo.|
||[text](/javascript/api/word/word.paragraph#text)|Obtém o texto do parágrafo.|
||[rightIndent](/javascript/api/word/word.paragraph#rightindent)|Obtém ou define o valor de recuo à direita, em pontos, para o parágrafo.|
||[Search (ProcurarTexto: cadeia de caracteres, searchoptions?: Word. Searchoptions \| {ignorePunct?: Boolean ignorespace?: Boolean MatchCase?: Boolean matchPrefix?: Boolean matchSuffix?: Boolean matchWholeWord?](/javascript/api/word/word.paragraph#search-searchtext--searchoptions--ignorepunct--ignorespace--matchcase--matchprefix--matchsuffix--matchwholeword--matchwildcards-)|Realiza uma pesquisa com o Searchoptions especificado no escopo do objeto Paragraph.|
||[selecionar (selectionMode?: Word. SelectionMode)](/javascript/api/word/word.paragraph#select-selectionmode-)|Seleciona e navega na interface do usuário do Word até o parágrafo.|
||[spaceAfter](/javascript/api/word/word.paragraph#spaceafter)|Obtém ou define o espaçamento, em pontos, após o parágrafo.|
||[spaceBefore](/javascript/api/word/word.paragraph#spacebefore)|Obtém ou define o espaçamento, em pontos, antes o parágrafo.|
||[style](/javascript/api/word/word.paragraph#style)|Obtém ou define o nome do estilo para o parágrafo.|
|[ParagraphCollection](/javascript/api/word/word.paragraphcollection)|[items](/javascript/api/word/word.paragraphcollection#items)|Obtém os itens filhos carregados nesta coleção.|
|[Range](/javascript/api/word/word.range)|[clear()](/javascript/api/word/word.range#clear--)|Limpa o conteúdo do objeto Range.|
||[delete()](/javascript/api/word/word.range#delete--)|Exclui o intervalo e o respectivo conteúdo do documento.|
||[getHtml()](/javascript/api/word/word.range#gethtml--)|Obtém uma representação HTML do objeto Range.|
||[getOoxml()](/javascript/api/word/word.range#getooxml--)|Obtém a representação OOXML do objeto Range.|
||[ignorePunct](/javascript/api/word/word.range#ignorepunct)||
||[ignoreSpace](/javascript/api/word/word.range#ignorespace)||
||[insertBreak (breaktype: Word. Breaktype, insertLocation: Word. InsertLocation)](/javascript/api/word/word.range#insertbreak-breaktype--insertlocation-)|Insere uma quebra no local especificado no documento principal.|
||[insertContentControl()](/javascript/api/word/word.range#insertcontentcontrol--)|Quebra o objeto Range com um controle de conteúdo de rich text.|
||[insertFileFromBase64 (base64file: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.range#insertfilefrombase64-base64file--insertlocation-)|Insere um documento no local especificado.|
||[Métodoinserthtml (HTML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.range#inserthtml-html--insertlocation-)|Insere HTML no local especificado.|
||[Métodoinsertooxml (OOXML: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.range#insertooxml-ooxml--insertlocation-)|Insere um formato OOXML no local especificado.|
||[insertParagraph (paragraphText: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.range#insertparagraph-paragraphtext--insertlocation-)|Insere um parágrafo no local especificado.|
||[insertText (Text: String, insertLocation: Word. InsertLocation)](/javascript/api/word/word.range#inserttext-text--insertlocation-)|Insere um texto no local especificado.|
||[matchCase](/javascript/api/word/word.range#matchcase)||
||[matchPrefix](/javascript/api/word/word.range#matchprefix)||
||[matchSuffix](/javascript/api/word/word.range#matchsuffix)||
||[matchWholeWord](/javascript/api/word/word.range#matchwholeword)||
||[matchWildcards](/javascript/api/word/word.range#matchwildcards)||
||[contentControls](/javascript/api/word/word.range#contentcontrols)|Obtém a coleção de objetos de controle de conteúdo no intervalo.|
||[font](/javascript/api/word/word.range#font)|Obtém o formato de texto do intervalo.|
||[paragraphs](/javascript/api/word/word.range#paragraphs)|Obtém a coleção de objetos Paragraph no intervalo.|
||[parentContentControl](/javascript/api/word/word.range#parentcontentcontrol)|Obtém o controle de conteúdo que inclui o intervalo.|
||[text](/javascript/api/word/word.range#text)|Obtém o texto do intervalo.|
||[Search (ProcurarTexto: cadeia de caracteres, searchoptions?: Word. Searchoptions \| {ignorePunct?: Boolean ignorespace?: Boolean MatchCase?: Boolean matchPrefix?: Boolean matchSuffix?: Boolean matchWholeWord?](/javascript/api/word/word.range#search-searchtext--searchoptions--ignorepunct--ignorespace--matchcase--matchprefix--matchsuffix--matchwholeword--matchwildcards-)|Realiza uma pesquisa com o Searchoptions especificado no escopo do objeto Range.|
||[selecionar (selectionMode?: Word. SelectionMode)](/javascript/api/word/word.range#select-selectionmode-)|Seleciona e navega na interface do usuário do Word até o intervalo.|
||[style](/javascript/api/word/word.range#style)|Obtém ou define o nome do estilo para o intervalo.|
|[RangeCollection](/javascript/api/word/word.rangecollection)|[items](/javascript/api/word/word.rangecollection#items)|Obtém os itens filhos carregados nesta coleção.|
|[SearchOptions](/javascript/api/word/word.searchoptions)|[ignorePunct](/javascript/api/word/word.searchoptions#ignorepunct)|Obtém ou define um valor que determina quando ignorar todos os caracteres de pontuação entre as palavras.|
||[ignoreSpace](/javascript/api/word/word.searchoptions#ignorespace)|Obtém ou define um valor que indica se deve ignorar todos os espaços em branco entre as palavras.|
||[matchCase](/javascript/api/word/word.searchoptions#matchcase)|Obtém ou define um valor que determina quando realizar uma pesquisa que diferencia maiúsculas de minúsculas.|
||[matchPrefix](/javascript/api/word/word.searchoptions#matchprefix)|Obtém ou define um valor que determina quando fazer correspondência com as palavras que começam com a cadeia de caracteres da pesquisa.|
||[matchSuffix](/javascript/api/word/word.searchoptions#matchsuffix)|Obtém ou define um valor que determina quando fazer correspondência com as palavras que terminam com a cadeia de caracteres da pesquisa.|
||[matchWholeWord](/javascript/api/word/word.searchoptions#matchwholeword)|Obtém ou define um valor que determina quando a operação Localizar encontra apenas palavras inteiras, e não o texto que faz parte de uma palavra maior.|
||[matchWildcards](/javascript/api/word/word.searchoptions#matchwildcards)|Obtém ou define um valor que indica se a pesquisa será realizada com operadores de pesquisa especiais.|
|[Section](/javascript/api/word/word.section)|[getrodapé (tipo: Word. HeaderFooterType)](/javascript/api/word/word.section#getfooter-type-)|Obtém um dos rodapés da seção.|
||[GetHeader (tipo: Word. HeaderFooterType)](/javascript/api/word/word.section#getheader-type-)|Obtém um dos cabeçalhos da seção.|
||[body](/javascript/api/word/word.section#body)|Obtém o objeto Body da seção.|
|[SectionCollection](/javascript/api/word/word.sectioncollection)|[items](/javascript/api/word/word.sectioncollection#items)|Obtém os itens filhos carregados nesta coleção.|
