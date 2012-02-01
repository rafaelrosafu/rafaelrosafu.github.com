---                                                                                                                        
layout: post
title: "\"Hackeando\" meu HTC Hero"
category : Android
tags : [Android, Hero]
---

Salve!

Depois de muito&nbsp;procrastinar decidi que estava na hora de atualizar o Android do meu <strong>HTC Hero</strong>.

Eu o comprei h&aacute; uns 9 meses, na &eacute;poca paguei um pre&ccedil;o bem salgado (R$ 2.000) e ainda ter me arriscado comprando o bichinho no Mercado Livre (pela <a href="http://gsmtechshop.com" target="_blank">GSMTech</a>). No fim deu tudo certo e&nbsp;n&atilde;o me arrependo, ele &eacute; muito bom sob v&aacute;rios aspectos:

* A bateria dura relativamente bastante - uns 4 dias com uso normal, 1 dia com uso intenso (wi-fi ou 3G navegando o dia todo, como quando estou em eventos)
* Tela com boa resolu&ccedil;&atilde;o, d&aacute; para ler textos numa boa
* Boa sensibilidade ao toque
* Pequeno e leve (mais leve que um iPhone)
* Teclado do Sense &eacute; maravilhoso
* O Sense faz o Android ficar muito mais amig&aacute;vel
* Bot&otilde;es f&iacute;sicos &uacute;teis, especialmente o back e search
* Bluetooth funciona bem com meu headphone
* Boa recep&ccedil;&atilde;o de wi-fi
* Integra&ccedil;&atilde;o total com os aplicativos do Google, especialmente o GMail
* Funciona muito bem como modem 3G conectado ao meu note Ubuntu via USB
* Navega bem em sites com Flash

A &uacute;nica coisa realmente ruim no telefone &eacute; a c&acirc;mera, que apesar de ter 5 Megapixel, &eacute; horr&iacute;vel, as fotos ficam ruins e precisa de muita luz para ficar meia-boca. Tirando isso, nada a reclamar. Como ele &eacute; bem bonitinho e diferente, todos me perguntam que modelo de celular eu estou usando e tal.

## Por que mudar?

Mas porque diabos escolhi fazer isso hoje e n&atilde;o antes? A gota d'&aacute;gua foi a Amazon <a href="http://www.engadget.com/2010/06/28/kindle-for-android-now-available/" target="_blank">anunciar que lan&ccedil;ou o </a><strong><a href="http://www.engadget.com/2010/06/28/kindle-for-android-now-available/">Kindle for Android</a></strong>, antes do prazo inicial que era Julho. Particularmente nunca gostei da id&eacute;ia do Kindle, mas comprar livros pela Amazon &eacute; muito pr&aacute;tico, e ultimamente tenho preferido livros digitais, por quest&otilde;es ecol&oacute;gicas, econ&ocirc;micas e de peso, afinal, &eacute; muito bom poder levar d&uacute;zias de livros no bolso.

Um dos motivos para adiar o update &eacute; que a HTC enrolou muito para lan&ccedil;ar novas vers&otilde;es para o Hero. Quando o comprei, estava usando a vers&atilde;o mais nova, a 1.5, mas depois de 1 m&ecirc;s eles lan&ccedil;aram a 1.6 e logo em seguida a dois 2.0, 2.1 e a 2.2 Froyo j&aacute; est&aacute; rodando em alguns lugares, mas ainda n&atilde;o chegou aos celulares mais velhinhos. Sem querer entrar no m&eacute;rito se o Android est&aacute; se fragmentando ou n&atilde;o (isso vale outro post), a evolu&ccedil;&atilde;o do ambiente tem sido muito r&aacute;pida, e o Kindle s&oacute; &eacute; compat&iacute;vel com a vers&atilde;o 1.6 ou superior, ou seja, era atualizar ou ficar sem o software.

## Cozinhando ROMs

Voltando a vaca fria, s&oacute; agora em Maio a HTC come&ccedil;ou a soltar as atualiza&ccedil;&otilde;es para o 2.1, mas <a href="http://www.engadget.com/2010/06/15/htc-hero-gets-android-2-1-update-across-europe/" target="_blank">apenas em alguns lugares do mundo</a>, e &eacute; a&iacute; que entram os <strong>ROM Cooks</strong>. Cooks s&atilde;o os caras que ficam brincando de fazer novas ROMs, hackeando as oficiais e adicionando coisas novas &agrave; elas. Eles est&atilde;o criando ROMs com as vers&otilde;es mais novas h&aacute; tempos e j&aacute; est&atilde;o trabalhando para liberar as 2.2, esses caras s&atilde;o loucos e eficientes. Voc&ecirc; pode acompanhar o que eles fazem no f&oacute;rum <a href="http://forum.xda-developers.com" target="_blank">xda-developers</a>, na sess&atilde;o de desenvolvimento.

Com uma ajudinha do <strong>Jonas Alves</strong> (que conheci num dos encontros do <a href="http://www.guru-sp.org" target="_blank">Guru-SP</a> e depois reencontrei numa palestra da <a href="http://www.caelum.com.br" target="_blank">Caelum</a>), eu conheci a VillainROM, que &eacute; um das mais profissionais do mercado. A vers&atilde;o 10.3 deles &eacute; feita em cima do release oficial da vers&atilde;o 2.1 da HTC, que inclui o HTC Sense atualizado. Para quem n&atilde;o sabe, o Sense &eacute; uma modifica&ccedil;&atilde;o da interface do Android feita pela HTC para deixar ele com uma carinha mais bonita, e tem um esquema de m&uacute;ltiplas home screens que podem ser customizadas com widgets (se mordam de inveja povo do iPhone).

Ok, decidi que iria atualizar meu Hero, j&aacute; havia escolhido a ROM, mas agora faltava saber como fazer a atualiza&ccedil;&atilde;o. Os cooks tem uma linguagem pr&oacute;pria, e sinceramente n&atilde;o estou no pique de aprender mais uma d&uacute;zia de g&iacute;rias para conseguir fazer uma atualiza&ccedil;&atilde;o de telefone. Sendo assim, corri para o velho e bom <strong>YouTube</strong> e procurei v&iacute;deos sobre rooting de telefones, e <a href="http://www.youtube.com/results?search_query=root+htc+hero&amp;aq=f" target="_blank">o primeiro hit</a> foi o vencedor.

## Tutorial em v&iacute;deo de 10 minutos

Um cara tem um site chamado <strong><a href="http://www.theunlockr.com" target="_blank">The Unlockr</a></strong> que ensina como desbloquear d&uacute;zias de telefones, e ele tem tutoriais e v&iacute;deos para fazer isso com o Hero. Em 10 minutos ele mostrou tudo que eu perdi horas tentando entender em dezenas de posts do f&oacute;rum e tutoriais.

O processo b&aacute;sico tem dois passos:

1. Conseguir acesso root ao seu aparelho
2. Instalar uma nova ROM

Por mais assustador que isso pare&ccedil;a, o processo &eacute; bastante simples, basta seguir os tutorias e pronto. Cada v&iacute;deo abaixo tem um tutorial com as instru&ccedil;&otilde;es, ent&atilde;o n&atilde;o tem muito o que errar. <strong>Mas aten&ccedil;&atilde;o no primeiro v&iacute;deo</strong>, porque as instru&ccedil;&otilde;es do v&iacute;deo mudaram, h&aacute; um aviso vermelho avisando sobre isso, mas &eacute; s&oacute; seguir as instru&ccedil;&otilde;es escritas que fica tudo bem. Seguem os v&iacute;deos e os respectivos tutoriais.


<p><object width="480" height="385">
<param name="movie" value="http://www.youtube.com/v/neE5zA687hE&amp;hl=en_US&amp;fs=1&amp;" />
<param name="allowFullScreen" value="true" />
<param name="allowscriptaccess" value="always" /> <embed src="http://www.youtube.com/v/neE5zA687hE&amp;hl=en_US&amp;fs=1&amp;" type="application/x-shockwave-flash" width="480" height="385"></embed>
</object></p>

<p><a class="small" href="http://theunlockr.com/2009/08/27/how-to-root-your-htc-hero-in-one-click/" target="_blank">Tutorial para fazer root (v&iacute;deo acima)</a></p>

<p><object width="480" height="385">
<param name="movie" value="http://www.youtube.com/v/knWWB9Y9-28&amp;hl=en_US&amp;fs=1&amp;" />
<param name="allowFullScreen" value="true" />
<param name="allowscriptaccess" value="always" /> <embed src="http://www.youtube.com/v/knWWB9Y9-28&amp;hl=en_US&amp;fs=1&amp;" type="application/x-shockwave-flash" width="480" height="385"></embed>
</object></p>

<p><a class="small" href="http://theunlockr.com/2009/08/27/how-to-load-a-custom-rom-on-your-htc-hero/" target="_blank">Tutorial para instalar uma ROM customizada (v&iacute;deo acima)</a></p>

Depois de fazer isso &eacute; s&oacute; configurar a conta do Google, deixar ele sincronizar tudo, e depois configurar o Access Point para utilizar o 3G, &eacute; a &uacute;nica coisa que ele n&atilde;o conseguiu configurar sozinho. Para isso basta entrar em Settings &gt; Wireless &amp; Networks &gt; Mobile Networks &gt; Access Point Names, clicar em Menu e colocar a configura&ccedil;&atilde;o da sua operadora, que basicamente &eacute; o gateway do AP e depois o usu&aacute;rio e senha padr&atilde;o. No caso da Oi, a operadora que escolhi, o gateway &eacute; "gprs.oi.com.br", o username &eacute; "oi" e a senha &eacute; "oi", nada complicado. Se quiser o esquema para outras operadoras, veja esse <a href="http://info.abril.com.br/forum/viewtopic.php?f=152&amp;t=1021" target="_blank">t&oacute;pico no f&oacute;rum da Info</a>.

Outro motivo que me fazia adiar o procedimento era porque alguns tutoriais diziam que era necess&aacute;rio fazer parte do update com o HTC Sync, o software de sincroniza&ccedil;&atilde;o e backup oficial da HTC, que s&oacute; funciona no Windows :( Por&eacute;m, como os v&iacute;deos acima mostram, tudo que voc&ecirc; precisa &eacute; copiar os arquivos para o SD Card do telefone, e isso voc&ecirc; pode fazer com qualquer sistema operacional, no meu caso eu usei o Ubuntu.

Al&eacute;m de conseguir instalar o Kindle e ainda consegui criar duas caixas postais no GMail, uma particular e outra para o trabalho, o que vai facilitar e muito minha vida. Eu tentei fazer alguns dos updates autom&aacute;ticos mas tive alguns probleminhas, ent&atilde;o vou deixar para resolver isso em outro momento. Assim que tiver novidades eu aviso.

__Viva o Android!__

*__Atualiza&ccedil;&atilde;o em 01/07/2010: tudo andando bem, o Kindle for Android &eacute; &oacute;timo, mas o consumo de bateria est&aacute; absurdo :(__*

