Rafael Rosa Fu
==============

This is an archived post This is an archived post
-------------------------------------------------

[Previous](../../../posts/2010/09/papo-rapido-com-charles-nutter-na-qconsp-2010.html)
[Index](../../../index.html)
[Next](../../../posts/2010/09/novo-episodio-do-grokpodcast-paypal-a-maturid.html)

### Papo rápido com Randy Shoup na \#QConSP 2010

September 26 2010, 5:15 AM by Rafael Rosa

Salve,

Nos dias 11 e 12 de Setembro de 2010 aconteceu a primeira **[QCon São
Paulo](http://www.qconsp.com/)**, organizada pela
[Caelum](http://www.caelum.com.br/), que é a mantenedora do [InfoQ
Brasil](http://www.infoq.com.br). O evento é a versão nacional, e
oficial, do famoso [QCon](http://qcon.infoq.com/), que acontece todos os
anos em San Francisco e em Londres, uma conferência de desenvolvimento e
arquitetura de software, e contou com **mais de 700 de participantes que
assistiram 40 palestras divididas entre 6 tracks**, ainda tivemos vários
Lightining Talks e excelentes happy hours :) Recomendo que vocês leiam o
[resumo da QConSP no blog da
Caelum](http://blog.caelum.com.br/2010/09/17/qconsp-2010-como-foi-o-principal-evento-de-arquitetos-e-desenvolvedores-no-brasil/).

Tivemos vários palestrantes vários internacionais, e tive a oportunidade
de falar com dois deles após suas palestras. O primeiro foi [Randy
Shoup](http://www.linkedin.com/pub/randy-shoup/0/6a0/5a9), Distinguished
Architect do eBay (o que acredito ser algo como o engenheiro-chefe do
lugar). Em sua palestra, ["Best Practices for Large-Scale Web Sites --
Lessons from
eBay"](http://www.slideshare.net/RandyShoup/more-best-practices-for-largescale-websites-lessons-from-ebay),
ele mostrou os números e os desafios absurdos dos sistemas do eBay (veja
o segundo slide para ter uma noção da escala), e explicou as lições que
aprenderam para lidar com esse monstro, uma boa apresentação muito
instrutiva.

![image](../../../image/2010/09/15458423-randy_shoup.jpg)

[Foto do perfil de Randy Shoup site do
QConSP](http://www.qconsp.com/palestrante/randy-shoup)

Porém, ao fim da apresentação, fiquei com algumas dúvidas e consegui
conversar rapidamente com ele. Um dos itens que ele repetiu dezenas de
vezes foi a importância de se desenvolver sistemas resistentes à falhas
e com dezenas de alternativas para evitar problemas que, inevitavelmente
irão acontecer. Muitas pessoas, leia-se,
[PHBs](http://en.wikipedia.org/wiki/Pointy-haired_Boss), acham que esse
tipo de preocupação é um exagero, e classificam investimentos de tempo e
dinheiro nisso como desperdício.

Mas no fim, é um problema estatístico: se você tem 10 mil aplication
servers e mil instâncias de bancos de dados, mais cedo ou mais tarde
você vai ter problemas. Minha primeira pergunta foi: **na prática, esses
problemas acontecem regularmente?** Ele me disse que **sim, é normal
haver problemas**, que vão desde falhas de infra e conexão, até erros em
programas e falhas de deploy. Graças as medidas tomadas, a maior parte
dos problemas são evitados. A resposta só seria melhor se ele tivesse
números para termos uma noção melhor da escala dos problemas :)

Ok, essa resposta era esperada, dado o conteúdo da apresentação. Outra
questão é que, segundo as informações da palestra, os sistemas que hoje
estão em operação começaram a ser desenvolvidos em 2001 (minha memória é
péssima), ou seja, são sistemas relativamente antigos. Naquela época
testes automatizados e as preocupações incessantes com qualidade de
código e boa arquitetura eram muito menos difundidas do que hoje, então
perguntei a ele: **dada a idade do sistema, como é a qualidade do
código?** Ele confirmou minhas suspeitas, disse que **os sistemas mais
antigos não tem os padrões de qualidade que sonhamos hoje em dia**, mas
que eles investem tempo para consertá-los e melhorá-los e também
substituí-los.

O fato deles terem reescrito os sistemas é um atestado de que mesmo
corporações de tecnologia do tamanho deles precisam em algum momento
parar e reavaliar a necessidade de um big rewrite. Concordo que big
rewrites não devem ser comuns, ou mesmo a primeira opção, mas
classificar todos eles como preciosismo técnico ou desnecessários é
burrice.

Ainda sobre a idade do sistema, perguntei sobre a grande quantidade de
sistemas especiais, escritos para fazer coisas como uma real-time search
engine e bancos de dados chave-valor. Hoje em dia temos dezenas de
opções open ou closed source para essas necessidades, e apesar de que
provavelmente nem todas elas serem boas o suficientes para a escala
absurda deles, algumas deveriam diminuir a necessidade de reinventar a
roda. Tendo isso mente perguntei: **vocês usam soluções open source
atuais como os bancos NoSQL (Redis, CouchDB, etc), linguagens além do
Java (Ruby, Python, Erlang, etc) ou search engines como o Lucene ou
coisas similares?** A resposta foi: **sim, eles utilizam algumas dessas
ferramentas**, na época em que desenvolvimento foi feito muitas dessas
ferramentas não estavam disponíveis ou eram muito novas, e eles
preferiram escrever muitos sistemas eles mesmos. Segundo Shoup, **se o
desenvolvimento fosse feito hoje, provavelmente utilizariam algumas
delas**, e estão fazendo testes e experimentos com várias delas apesar
da maioria dos sistemas em produção não utilizá-las.

Foi uma conversa bastante instrutiva, ele foi bem legal. Ouvir histórias
de sucesso sem analisá-las, questioná-las ou colocá-las em contexto
fazem as transformam em passatempo, perguntar faz toda diferença, e nos
mostra que nem nessas empresas monstro os sistemas são perfeitos.

No próximo post vou falar sobre a conversa que tive com [Charles
Nutter](http://twitter.com/headius), lead do [JRuby](http://jruby.org/).

#### 26564 views and 2 responses

-   Sep 26 2010, 8:53 PM

    Thiago Alves responded:

    Conversei com o Randy Shoup também no intervalo de uma das palestras
    e ele foi extremamente receptivo. Conversamos muito sobre a visão
    dele sobre o NoSQL (ele encara o assunto com entusiasmo), softwares
    caseiros x soluções prontas (no eBay eles usam Oracle - que não pode
    ser personalizado, porém pode ser "tunado") e também um pouco sobre
    o eBay (eles possuem milhares de desenvolvedores espalhados pelo
    mundo, especialmente nos Estados Unidos e China).

    Rafael, aguardo ansiosamente seu próximo post!

    Abraço

-   Oct 11 2010, 6:38 AM

    mairon responded:

    massssaaa

    abraco


