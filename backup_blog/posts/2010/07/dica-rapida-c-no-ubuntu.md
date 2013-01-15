Rafael Rosa Fu
==============

This is an archived post This is an archived post
-------------------------------------------------

[Previous](../../../posts/2010/07/lutando-contra-uma-bateria.html)
[Index](../../../index.html)
[Next](../../../posts/2010/07/retrospectiva-do-agilebrazil-2010-bluesoft.html)

### Dica rápida - Ç no Ubuntu

July 9 2010, 12:18 PM by Rafael Rosa

Eu adoro o [Ubuntu](http://www.ubuntu.com), é a minha primeira distro e
sempre que tentei usar outras acabei me decepcionando, e ela tem
recebido várias atualizações legais, a cada semestre temos um sistema
melhor. Porém, ele está longe de ser perfeito, e um problema que sempre
tenho quando atualizo é a perda do caractere **ç** no teclado.

Uso um notebook com teclado configurado como USA International e com os
textos em inglês, e normalmente a ç é obtida através da combinação de
teclas **' + c**, que é uma combinação bem confortável para mim, mas
depois de atualizar o Ubuntu essa combinação de teclas gera **ć** o que
me irrita profundamente. Para corrigir isso, é fácil, basta executar

    sudo gedit /usr/lib/gtk-2.0/2.10.0/immodule-files.d/libgtk2.0-0.immodules

e alterar a linha

    "cedilla" "Cedilla" "gtk20" "/usr/share/locale" "az:ca:co:fr:gv:oc:pt:sq:tr:wa" 

para

    "cedilla" "Cedilla" "gtk20" "/usr/share/locale" "en:az:ca:co:fr:gv:oc:pt:sq:tr:wa" 

salve o arquivo e pronto. Note que eu coloquei **en:** no começo da
lista de línguas utilizadas, dessa forma o sistema irá priorizar a
cedilha ao invés do c-com-acento :) Dica boba mas que economiza algum
tempo.

#### Tags

dica, ubuntu

#### 19070 views and 3 responses

-   Jul 9 2010, 12:47 PM
    Prodis a.k.a. Fernando Hamasaki de Amorim responded:
    Tive o mesmo problema.\
    [http://prodis.pro.br/2009/08/14/configurando-teclado-em-ingles-no-ubuntu-e-co...](http://prodis.pro.br/2009/08/14/configurando-teclado-em-ingles-no-ubuntu-e-com-cedilha/)
-   Jul 9 2010, 4:10 PM
    Marcio Toshio Ide responded:
    Eu utilizo alt+, (virgula) - o alt da direita do teclado
-   Jul 11 2010, 3:23 PM
    Nelson Haraguchi responded:
    Também uso ALT + , nem tinha percebido isso mas valeu pela dica

