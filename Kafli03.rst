.. _s.vigrar:

Vigrar
======

Skilgreining
------------
*Vigur* (e. vector) er stærðfræðilegt hugtak fyrir stærð sem hefur bæði lengd og stefnu.
Þeir eru jafnan teiknaðir sem örvar í hnitakerfi og lýst með hnitum.
Hnit vigurs eru venjulegar tölur, líka kallaðar *skalarstærðir* (e. scalar), og lýsa staðsetningu endapunkts miðað við upphafspunkt.
Hvert hnit er tengt einum ás í hnitakerfinu sem notað er og stærð hnitsins (tölunnar) lýsir lengd vigursins í þá átt.

Vigrar eru oftast táknaðir með striki eða ör fyrir ofan bókstafinn, :math:`\bar{a}` , :math:`\vec{a}` , en sumir setja strikið undir, :math:`\underline{a}` .
Í kennslubókum eru vigrar oft ekki yfirstrikaðir heldur aðeins feitletraðir, :math:`\boldsymbol{a}` .

Lengd vigra er táknuð með lóðréttum strikum, algildismerkjum, :math:`|\bar{a}|` , eða einfaldlega bókstafnum án yfirstriksins, :math:`a` .
Þegar vísað er í lengd vigurs eftir einhverjum ás, *þátt* hans (e. component), er það sýnt með því að merkja með heiti ássins í *lágvísi* (e. subscript); :math:`a_x` er lengd vigursins :math:`\bar{a}` í stefnu :math:`x` - áss.
Þættir vigra eru ekki vigrar sjálfir, heldur tölur.


.. figure:: ./myndir/vigrar/vigur.svg
   :width: 60%
   :align: center

Yfirleitt er notað rétthyrnt hnitakerfi (einnig nefnt kartesískt í höfuðið á franska stærðfræðingnum René Descartes).
Vigurinn á myndinni hér að ofan hefur lengd 4 eftir x-ásnum og 3 eftir y-ásnum, svo hnit hans eru :math:`a_x = 4` og :math:`a_y = 3`
og vigurinn :math:`\bar{a}` má þá rita:

.. math::
  \bar{a} = (a_x,a_y) = (4,3) = \begin{pmatrix} 4 \\ 3 \end{pmatrix}

Lengd vigursins sjálfs er reiknuð með jöfnu Pýþagórasar, :math:`|\bar{a}| = a = \sqrt{a_x^2 + a_y^2}` .
Vigurinn á myndinni hér að ofan hefur því lengdina :math:`a = \sqrt{4^2 + 3^2} = 5` .

.. note::
  Stærð og stefna vigurs er óháð því hvar í hnitakerfinu hann er.

Algengt er að láta vigra liggja frá upphafspunkti hnitakerfisins (stöðu- eða staðarvigur) en það er hægt að reikna vigra á milli gefinna upphafs- og endapunkta.
Vigurinn frá punktinum :math:`A=(x_1,y_1)` til punktsins :math:`B=(x_2,y_2)` er

.. math::
  \bar{AB} = (x_2-x_1,y_2-y_1) = \begin{pmatrix} x_2-x_1 \\ y_2-y_1 \end{pmatrix}

.. tip::
  Reiknum vigurinn frá punktinum :math:`A=(-1,7)` til punktsins :math:`B=(5,2)` .

  .. math::
    \begin{aligned}
      \bar{AB} &= \begin{pmatrix} x_2-x_1 \\ y_2-y_1 \end{pmatrix}\\
      &= \begin{pmatrix} 5-(-1) \\ 2-7 \end{pmatrix} \\
      &= \begin{pmatrix} 6 \\ -5 \end{pmatrix}
    \end{aligned}

  .. figure:: ./myndir/vigrar/vigurtveirpkt.svg
    :align: center
    :width: 60%

  Vigurinn :math:`\begin{pmatrix} 6 \\ -5 \end{pmatrix}` er sá sami, hvort sem hann liggur á milli :math:`A` og :math:`B` eða frá upphafspunktinum til punktsins :math:`(6,-5)` .

Stundum er talað um að vigur hafi *hallatölu*  :math:`h=\frac{a_y}{a_x}` , ef :math:`a_x\neq 0` .
Tveir vigrar eru *samsíða* ef þeir hafa sömu hallatölu.

.. tip::
  Finnum vigur sem er samsíða :math:`\bar{a}=(-1,6)` og hefur lengdina 9.

  Hallatala :math:`\bar{a}` er :math:`h_{\bar{a}}=\frac{a_y}{a_x}=\frac{6}{-1}=-6` .
  Þá vitum við að vigurinn sem við leitum að, :math:`\bar{b}` , uppfyllir það sama:

  .. math::
    h_{\bar{b}}=\frac{b_y}{b_x}=-6

  sem er jafngilt því að :math:`b_y=-6b_x` .

  Skilyrðið að :math:`\bar{b}` þurfi að hafa lengdina 9 gefur að:

  .. math::
    |\bar{b}| = \sqrt{b_x^2+b_y^2} =9

  Setjum :math:`b_y=-6b_x` inn og fáum:

  .. math::
    \begin{aligned}
      9 &= \sqrt{b_x^2+b_y^2}\\
      &=\sqrt{b_x^2+(-6b_x)^2} \\
      &= \sqrt{b_x^2+36b_x^2} \\
      &=\sqrt{37b_x^2} \\
      &=b_x\sqrt{37} \\
      b_x&=\frac{9}{\sqrt{37}} \approx 1.480\\
      b_y&= -6b_x = \frac{-54}{\sqrt{37}} \approx -8.878
    \end{aligned}

  Vigur sem er samsíða :math:`\bar{a}=(-1,6)` og hefur lengdina 9 er því

  .. math::
    \bar{b}= \frac{1}{\sqrt{37}} \begin{pmatrix} 9 \\  -54 \end{pmatrix}

Að liða vigra
-------------

Vigra er líka hægt að tákna með pólhnitum, þá eru hnitin lengd og stefnuhorn: :math:`\bar{a} = (a,\theta)` .
Hornið :math:`\theta` er skilgreint frá jákvæðum x-ás og að vigrinum.
Með þessum upplýsingum er hægt að liða vigurinn eftir x- og y-ás með því að nota hornaföll.
`Hér <http://edbook.hi.is/undirbuningur_stae/Kafli07.html>`_ má finna efni um hornaföll.

Þættir vigursins eru föll af stefnuhorninu sem er yfirleitt merkt :math:`\theta` eða :math:`\phi` :

.. math::
  a_x = a\cos(\theta) \\
  a_y = a\sin(\theta)

þar sem :math:`a=|\bar{a}|` er lengd vigursins.

Myndrænt má ímynda sér að ljósi sé lýst á x-ásinn með vasaljósi sem er hornrétt á ásinn.
x-þáttur vigursins er þá eins og skuggi vigursins á x-ásnum.
Þetta er líka kallað ofanvarp vigursins á x-ásinn.

.. tip::
  Hér sjáum við aftur vigurinn frá því í upphafi kaflans:

  .. math::
    \bar{a}= (4,3) = \begin{pmatrix} 4 \\ 3 \end{pmatrix}

  en nú skulum við athuga hvernig við getum lýst honum með lengd og stefnuhorni.

  .. figure:: ./myndir/vigrar/mynd-vigur.svg
     :width: 60%
     :align: center

  Lengd vigursins er eins og áður 5, en stefnuhornið finnum við með því að skoða skammhliðarnar.

  .. math::
    \tan(\theta) = \frac{a_y}{a_x} = \frac{3}{4}\\
    \theta\approx 0.6435

  Vigurinn :math:`(4,3)` má því líka skrifa sem :math:`(a,\theta) = (5,0.6435)`

Öllum vigrum er hægt að lýsa með annað hvort lengdum í :math:`x`- og :math:`y`- stefnu eða með lengd og stefnuhorni.
Eins og við höfum séð er lítið mál að breyta á milli.

Einingarvigrar
--------------
Einingarvigrar eru vigrar sem hafa lengdina 1.
Vigrarnir

.. math::
  \begin{aligned}
  \hat{\imath} &= \begin{pmatrix} 1 \\0 \\0 \end{pmatrix} \\
  \hat{\jmath} &= \begin{pmatrix} 0 \\1 \\0 \end{pmatrix} \\
  \hat{k} &= \begin{pmatrix} 0 \\0 \\1 \end{pmatrix} \\
  \end{aligned}

liggja samsíða :math:`x` - , :math:`y` - og  :math:`z` -  ásunum í rétthyrndu hnitakerfi .
Þeir eru líka táknaðir:

.. math::
  \begin{gather}
  \hat{e}_x, \quad \hat{e}_y, \quad \hat{e}_z
  \end{gather}

.. figure:: ./myndir/vigrar/einingarvigrar.svg
   :width: 60%
   :align: center

Einingarvigrarnir :math:`\hat{e}_x, \hat{e}_y` og :math:`\hat{e}_z` eru *línulega óháðir* (e. linearly independent), sem þýðir að engan þeirra er hægt að mynda úr hinum tveimur með samlagningu þeirra eða margföldun með tölu.
Hvernig sem þú teygir á og raðar saman :math:`\hat{\imath}` og :math:`\hat{\jmath}` færðu aldrei út :math:`\hat{k}` .
Þessi eiginleiki kemur til vegna þess að einingarvigrarnir eru allir hornréttir á hvorn annan.

Alla vigra má skrifa sem skalarstærðir margfaldaðar við einingarvigrana:

.. math::
  \bar{a} = (a_x, \; a_y, \; a_z ) = a_x \hat{\imath} + a_y \hat{\jmath} + a_z \hat{k}

Samlagning vigra
----------------
Þegar vigrar eru lagðir saman eru hnit eftir hverjum ás fyrir sig lögð saman.
Summa tveggja vigra :math:`\bar{a} = (a_x,a_y)` og :math:`\bar{b} = (b_x,b_y)` er:

.. math::
  \bar{c} = \bar{a} + \bar{b} = (a_x + b_x, a_y +b_y) = \begin{pmatrix} a_x+b_x \\ a_y+b_y \end{pmatrix}

.. tip::
  Leggjum saman vigrana :math:`\bar{a}=(4,3)` og :math:`\bar{b}=(1,2)` :

  .. math::
    \bar{a}+\bar{b}=(4,3) + (1,2) = (4+1, 3+2) = (5,5)

Myndrænt má ímynda sér að upphafspunktur seinni vigursins sé settur í endapunkt fyrri vigursins,
og summa þeirra er frá upphafspunkti fyrri vigursins til endapunkts þess seinni.

.. figure:: ./myndir/vigrar/vigrasamlagning.svg
   :width: 60%
   :align: center

.. note::
  Þegar vigrar eru lagðir saman þá leggjast lengdirnar yfirleitt **ekki** saman.
  Þó að :math:`\bar{c} = \bar{a} + \bar{b}` þýðir það **ekki** að :math:`c = a + b`.

  Í dæminu hér á undan er t.d.

  .. math::
    c = |\bar{c}| = \sqrt{5^2+6^2} \approx 7,8 \\
    a + b = \sqrt{4^2+3^2} + \sqrt{1^2+3^2} \approx 8,2

--------------------------------

Um samlagningu vigra gilda eftirfarandi reglur:

.. math::
  \begin{aligned}
    \bar{a} +\bar{b} &= \bar{b} + \bar{a} & \text{Víxlregla}\\
    (\bar{a}+\bar{b})+\bar{c} &= \bar{a} + (\bar{b}+\bar{c}) & \text{Tengiregla}
  \end{aligned}

--------------------------------

.. tip::
  Höfum þrjá punkta:

  .. math::
    \begin{aligned}
    A&=(x_1,y_1)=(1,2) \\
    B&=(x_2,y_2)=(4,5) \\
    C&=(x_3,y_3)=(3,-1)
    \end{aligned}

  Reiknum vigrana :math:`\bar{AB}, \bar{AC} \text{ og } \bar{BC}` :

  .. math::
    \begin{aligned}
      \bar{AB} &= \begin{pmatrix} x_2-x_1 \\ y_2-y_1 \end{pmatrix}\\
      &=\begin{pmatrix} 4-1 \\5-2\end{pmatrix} =\begin{pmatrix} 3 \\3\end{pmatrix} \\
      & \\
      \bar{AC} &= \begin{pmatrix}x_3-x_1\\ y_3-y_1 \end{pmatrix}\\
      &=\begin{pmatrix} 3-1 \\(-1)-2\end{pmatrix} =\begin{pmatrix} 2 \\-3\end{pmatrix} \\
      & \\
      \bar{BC} &= \begin{pmatrix}x_3-x_2\\ y_3-y_2 \end{pmatrix}\\
      &=\begin{pmatrix} 3-4 \\(-1)-5\end{pmatrix} =\begin{pmatrix} -1 \\-6\end{pmatrix} \\
    \end{aligned}

  .. figure:: ./myndir/vigrar/innskots.svg
    :align: center
    :width: 50%

  Hér eru punktarnir teiknaðir inn ásamt vigrunum :math:`\bar{AB}, \bar{AC} \text{ og } \bar{BC}` .

Af þessu dæmi má sjá *innskotsregluna* :

.. math::
  \bar{AC} = \bar{AB} + \bar{BC}


Margföldun vigra
----------------

Þegar vigur :math:`\bar{v}` er margfaldaður með tölu :math:`s` er hver þáttur vigursins margfaldaður með tölunni:

.. math::
    \begin{aligned}
        s \cdot \bar{v} &= s\cdot (v_x, v_y, v_z) \\
        &= (s \cdot v_x, s \cdot v_y, s \cdot v_z)
    \end{aligned}

Margfeldi vigra er tvenns konar, *innfeldi* (punktfeldi, e. dot product, scalar product) og *krossfeldi* (e. cross product, vector product).

Innfeldi
~~~~~~~~

**Innfeldi** tveggja vigra er táknað með punkti og útkoman er *tala*: :math:`c = \bar{a} \cdot \bar{b}` .
Ef þættir vigranna eru þekktir er innfeldið reiknað:

.. math::
  \bar{a} \cdot \bar{b} = a_x b_x + a_y b_y

.. tip::
    Reiknum innfeldi vigranna :math:`\bar{a}=(7,8)` og :math:`\bar{b}=(-1,3)` :

    **Lausn**

    .. math::
      \bar{a} \cdot \bar{b} = a_x b_x + a_y b_y = 7\cdot (-1)+ 8\cdot 3 = -7+24 =17

Ef vigrarnir eru gefnir með lengd og stefnuhorni er innfeldi þeirra:

.. math::
  \bar{a} \cdot \bar{b} = a b \cos{\phi}

þar sem :math:`\phi` er hornið milli :math:`\bar{a}` og :math:`\bar{b}` þegar þeir hafa sama upphafspunkt.

.. note::
  **Tveir vigrar eru hornréttir ef innfeldi þeirra er núll.**

.. tip::
    Reiknum hornið á milli vigranna :math:`\bar{a}=(2,4)` og :math:`\bar{b}=(4,2)` :

    .. figure:: ./myndir/vigrar/innfeldi.svg
      :align: center
      :width: 60%

    **Lausn**

    Við vitum að :math:`\bar{a} \cdot \bar{b} = a b \cos{\phi}` , þar sem :math:`a` og :math:`b` eru lengdir vigranna.
    Lengdirnar eru:

    .. math::
      \begin{aligned}
        a = \sqrt{a_x^2 + a_y^2} = \sqrt{2^2 + 4^2} = \sqrt{20} \\
        b = \sqrt{b_x^2 + b_y^2} = \sqrt{4^2 + 2^2} = \sqrt{20}
      \end{aligned}

    Reiknum innfeldi vigranna:

    .. math::
      \bar{a} \cdot \bar{b} = a_x b_x + a_y b_y = 2\cdot 4+ 4\cdot 2 = 16

    Því er

    .. math::
      \begin{aligned}
        \bar{a} \cdot \bar{b} &= a b \cos{\phi} \\
        \cos{\phi} &= \frac{\bar{a} \cdot \bar{b}}{a b} = \frac{16}{\sqrt{20} \cdot \sqrt{20}} = \frac{16}{20}\\
        \phi &= 36.8 ° = 0.644 \text{Rad}
      \end{aligned}


Krossfeldi
~~~~~~~~~~

**Krossfeldi** (e. cross product) er táknað með krossi og útkoman er *vigur*: :math:`\bar{c} = \bar{a} \times \bar{b}` .
Krossfeldi eru reiknuð með þáttum vigranna, þ.e. vigrum gefnum á forminu :math:`\bar{a} = a_x \hat{\imath} + a_y \hat{\jmath} + a_z \hat{k}` .

.. math::
  \begin{aligned}
    \bar{a} \times \bar{b} &= (a_x \hat{\imath} + a_y \hat{\jmath} + a_z \hat{k}) \times (b_x \hat{\imath} + b_y \hat{\jmath} + b_z \hat{k}) \\
    &= (a_y b_z - a_z b_y)\hat{\imath} + (a_z b_x - a_x b_z)\hat{\jmath} + (a_x b_y - a_y b_x)\hat{k} \\
  \end{aligned}

.. figure:: ./myndir/vigrar/krossfeldi.svg
   :width: 60%
   :align: center

Útkoma krossfeldisins er vigur sem er hornréttur á bæði :math:`\bar{a}` og :math:`\bar{b}`.
Stefna hans ákvarðast af **hægri** handar reglunni:

.. figure:: ./myndir/vigrar/hhr.svg
    :width: 60%
    :align: center

Lengd krossfeldis :math:`\bar{a} \text{ og } \bar{b}` má reikna úr frá lengdum vigranna og horninu á milli þeirra.

.. math::
  |\bar{a} \times \bar{b}| = |\bar{a}| |\bar{b}| \sin(\phi)

.. note::
  Þegar krossfeldi er reiknað skiptir því máli hvor vigurinn er á undan.

  .. math::
    \bar{a} \times \bar{b} = - \bar{b} \times \bar{a}


.. tip::
    Reiknum krossfeldi vigranna :math:`\bar{a}=(1,2,3)` og :math:`\bar{b}=(4,5,6)`.

    **Lausn**

    .. math::
      \begin{aligned}
        \bar{a} \times \bar{b} &= (a_y b_z - a_z b_y)\hat{\imath} + (a_z b_x - a_x b_z)\hat{\jmath} + (a_x b_y - a_y b_x)\hat{k} \\
        &= (2\cdot 6-3\cdot 5)\hat{\imath} + (3\cdot 4 - 1 \cdot 6) \hat{\jmath} + ( 1\cdot 5 - 2\cdot 4) \hat{k}\\
        &= -3 \hat{\imath} +6 \hat{\jmath} - 3\hat{k}\\
        &= (-3,6,-3)
      \end{aligned}
