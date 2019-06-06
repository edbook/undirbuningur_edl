Kraftar
=======

*Kraftur* (e. force) er orð sem við notum um samspil hluta sem veldur breytingu á hreyfingu þeirra, þ.e. valda því að hlutirnir fá hröðun. Kraftar eru :ref:`vigrar <s.vigrar>`, sem þýðir að þeir hafa  *bæði stærð og stefnu*.
SI- einingin fyrir krafta er *Newton*, táknað :math:`\text{N}`. Eitt Newton er sá kraftur sem þarf til þess að gefa :math:`1 \text{ kg}` massa hröðunina :math:`1 \frac{\text{m}}{\text{s}^2}` .
Kraftar eru margfeldi massa og hröðunar og því má skrifa eininguna Newton sem :math:`1\text{ N} = 1 \text{ kg}\cdot \frac{\text{m}}{\text{s}^2}` .

.. note::
  Athugið að í eðlisfræði er *massi* (e. mass) ekki það sama og þyngd, þó að í daglegu tali sé þyngd oft notað fyrir bæði.

  *Massi* (e. mass) hlutar lýsir því hve mikið efni er í honum og er eins sama hvar í alheiminum hann er. SI-eining massa er kílógramm.

  *Þyngd* (e. weight) hlutar er stærð þyngdarkraftsins sem á hann verkar, þ.e. margfeldi massans við þyngdarhröðunina :math:`g`. SI-eining þyngdar er Newton.

Kraftar eru oftast táknaðir með :math:`F` eða :math:`f`, frá enska heitinu *force*. :math:`F` er þá táknið fyrir þyngdarkraft og aðra krafta sem beitt er á hluti en :math:`f` táknar viðbragðskrafta eins og t.d. núning.

.. tip::
  Skoðum samlagningu kraftvigra.
  Inga og Gunna eru í reipitogi. Inga togar í reipið beint til vinstri með kraftinum :math:`F_I=1000 \text{N}` en Gunna beint til hægri með kraftinum :math:`F_G = 1200 \text{N}`. Í hvaða átt hreyfist reipið?

  **Lausn**
  Þar sem krafar Ingu og Gunnu eru vigrar notum við vigursamlagningu til þess að skoða hver heildarkrafturinn er á reipið.

  .. figure:: ./myndir/kraftar/reipitog.svg
    :align: center
    :width: 80%

  Kraftvigur Ingu bendir til vinstri, þ.a. :math:`x` hnit hans er neikvætt.

  .. math::
    \overline{F}_I = \begin{pmatrix} -1000 \\ 0 \end{pmatrix}

  Kraftvigur Gunnu bendir til hægri, þ.a. :math:`x` hnit hans er jákvætt.

  .. math::
    \overline{F}_G = \begin{pmatrix} 1200 \\ 0 \end{pmatrix}

  Leggjum nú saman vigrana:

  .. math::
    \begin{aligned}
    \overline{F_{net}} &= \overline{F}_I + \overline{F}_G \\
    &= \begin{pmatrix} -1000 \\ 0 \end{pmatrix} + \begin{pmatrix} 1200 \\ 0 \end{pmatrix} \\
    &= \begin{pmatrix} 200 \\ 0 \end{pmatrix}
    \end{aligned}

  Samanlagður krafturinn sem verkar á reipið er því :math:`F_{net}=\begin{pmatrix} 200 \\ 0 \end{pmatrix}`. Reipið mun því hreyfast til hægri og Gunna vinnur reipitogið. Þetta kemur okkur ekkert á óvart, enda togar hún fastar í reipið.

Lögmál Newtons
--------------
Enski eðlisfræðingurinn `Isaac Newton <https://is.wikipedia.org/wiki/Isaac_Newton>`_ setti fram þrjú lögmál um krafta á 17. öld, en þau mynda grunn þess hluta eðlisfræðinnar sem er kölluð aflfræði (e. classical mechanics).

Fyrsta lögmál Newtons
~~~~~~~~~~~~~~~~~~~~~
"Hlutur sem enginn kraftur verkar á helst kyrr eða ferðast áfram á jöfnum hraða."

Þetta lögmál er oft nefnt **tregðulögmálið** og segir m.a. að bolti muni liggja kyrr á jörðinni þangað til einhver sparkar í hann og að boltinn muni halda áfram að rúlla endalaust, nema núningur hans við grasflötina hægi á honum.

Kraftar valda hröðun svo að tregðulögmálið gildir þegar enginn kraftur er til staðar eða þegar allir kraftarnir sem eru ýta hver á móti öðrum.
Hröðun er afleiða hraðans, svo ef hröðunin er núll er hraðinn :math:`\overline{v}` er fasti, svo hluturinn er annað hvort kyrr eða ferðast á jöfnum hraða.

.. _s.lnII:

Annað lögmál Newtons
~~~~~~~~~~~~~~~~~~~~
"Kraftur sem verkar á hlut er margfeldi massa hlutarins og hröðunar sem hann verður fyrir."

.. math::
   \overline{F} = m \overline{a}

Kraftur og hröðun eru vigrar sem hafa sömu stefnu og massi er einskonar hlutfallsstuðull milli krafts og hröðunar.
Þannig má túlka massa sem *tregðustuðul*, þ.e. fyrir mikinn massa fæst lítil hröðun fyrir gefinn kraft. Massi hlutar segir okkur hve erfitt það er að breyta hraða hlutar.

Þriðja lögmál Newtons
~~~~~~~~~~~~~~~~~~~~~
"Sérhvert átak á sér gagnátak."

.. math::
   \overline{F}_{AB} = -\overline{F}_{BA}

:math:`F_{AB}` er kraftur sem hlutur A veldur á B og :math:`F_{BA}` er verkun B á A.
Kraftarnir eru jafnstórir en stefna gegn hvorum öðrum.

Normalkraftur
-------------
Hlutur sem liggur kyrrstæður á borði hlýtur að vera í kraftajafnvægi (fyrst hann er ekki á hreyfingu getur ekki verið nein hröðun) og samkvæmt fyrsta lögmálinu mun hann vera kyrrstæður áfram meðan svo er.
Þó að hluturinn se kyrrstæður þýðir það samt ekki að engir kraftar verki á hann.
Þyngdarkrafturinn togar hann niður að borðinu og samkvæmt þriðja lögmálinu er jafnstór kraftur frá borðinu sem ýtir hlutnum upp.
Sá kraftur er kallaður normalkraftur, oft táknaður :math:`f_{n}` .

.. figure:: ./myndir/kraftar/normal.svg
  :align: center
  :width: 60%

Normalkraftar eru hornréttir á yfirborðið sem þeir koma frá.

Núningskraftur
--------------
Núningskraftar eru kraftar sem verða á milli yfirborða og vinna gegn hreyfingu þeirra miðað við hvort annað.
Núningur finnst í nær öllum kerfum, hann er ástæða þess við getum farið um á hjóli; það er kraftur milli dekkjanna og malbiksins sem ýtir hjólinu áfram þegar dekkin snúast. Annars myndi hjólið spóla og standa í stað, eins og gerist þegar það er mikil hálka.
Skautasvell er einmitt dæmi um kerfi þar sem er nær enginn núningur og hefur afar lítil áhrif á útreikninga dæmisins. Ef núningurinn er mjög lítill getum við leyft okkur að hunsa hann.

.. tip::
  **(a)** Ásta ætlar að toga þungan kassa eftir steypugólfi og beitir til þess krafti :math:`F_{tog}` á kassann.
  Kassinn hreyfist ekki. Af hverju ekki?

  **(b)** Ásta togar fastar og kassinn fær hröðun í átt til hennar. Hvaða kraftar verka á kassann og Ástu?

  **Lausn**

  **(a)** Fyrst kassinn hreyfist ekki er hraði hans fasti (í núlli) og því hlýtur heildarkrafturinn sem verkar á hann að vera núll.
  Skoðum kraftana betur:

  Kassinn verður fyrir þyngdarkrafti :math:`F_g` og gólfið ýtir á móti með jafnstórum en gagnstefna normalkrafti :math:`f_n`.
  Kraftarnir tveir stytta hvorn annan út og það helst óbreytt þó Ásta togi í kassann.

  Fyrst kassinn hreyfist ekki þýðir það að summa kraftanna sem verka á hann er núll.
  Því hlýtur að vera núningskraftur sem er að toga á móti þegar Ásta togar í kassann.
  Á meðan kassinn hreyfist ekki er núningskrafturinn jafnstór togkraftinum sem Ásta beitir.

  .. figure:: ./myndir/kraftar/asta.svg
    :align: center
    :width: 60%

  **(b)** Þar sem kassinn fær hröðun er heildarkrafturinn á hann ekki lengur núll.
  Togkraftur Ástu er núna meiri en núningskrafturinn.
  Þetta eru þó ekki allir kraftarnir sem verka í þessum aðstæðum. Samkvæmt 3. lögmáli Newtons koma kraftar í pörum jafnsstórra og andstæðra krafta.
  Þegar Ásta togar í kassann verður því líka til kraftur jafnstór togkraftinum sem verkar á hana.
  Ef hún stæði á sleipu gólfi myndi hún fá hröðun í átt að kassanum (og sennilega detta á hausinn), því núningskraftur hennar við gólfið yrði ekki nægur til að vega á móti togkraftinum.

  Því eru fjórir kraftar sem verka á Ásta og kassann: togkraftapar á milli þeirra og núningskraftur undir þeim báðum.
  Auk þess, auðvitað, verða bæði Ásta og kassinn fyrir þyngdarkrafti og normalkrafti frá gólfinu.

  .. figure:: ./myndir/kraftar/asta2.svg
    :align: center
    :width: 60%

.. tip::
  Hokkípökkur með massa :math:`m = 0.15` kg rennur á svelli með hraðanum :math:`\overline{v}_0 = 5 \text{m/s}`  .
  Núningskrafturinn milli hokkípökksins og svellsins er :math:`\overline{f}_{nún} = 0.3 \text{N}` og verkar á þann hátt að hann hægir á pökknum.

  Hvaða kraftar verka á pökkinn?
  Hversu langt rennur pökkurinn áður en hann stöðvast?

  **Lausn**

  Byrjum á að teikna kraftamynd.

  .. figure:: ./myndir/kraftar/hockey.svg
    :width: 70%
    :align: center

  Pökkurinn verður fyrir þyndarkrafti :math:`f_g` og normalkrafti :math:`f_n` vegna hans, auk núningskraftsins :math:`f_{nún}`.

  Upphafshraðinn :math:`v_0` er merktur inn rauður.

  Þyngdarkrafturinn og normalkrafturinn eru jafnstórir og gagnstefna og stytta því hvorn annan út.
  Það er því engin hreyfing í :math:`y` stefnu og við megum gera ráð fyrir að það muni vera þannig áfram.

  Það er því bara hreyfing í eina stefnu, eftir x-ásnum, svo við getum sleppt hinum víddum kraftanna.
  Þá þarf ekki að pæla í stefnu vigranna, þeir sem benda í eina átt fá jákvætt gildi, en þeir sem benda í hina fá neikvætt gildi.
  Höfum því hraðann jákvæðan og núningskrafturinn neikvæðan.

  Látum pökkinn byrja í miðju hnitakerfisins, svo :math:`x_0 = 0` .
  Notum annað lögmál Newtons til að finna hröðunina sem núningskrafturinn gefur pökknum, þ.e. hve mikið hann hægir á honum.

  .. math::
    f_{nún} = m a \Rightarrow a = \frac{f_{nún}}{m} = \frac{-0.3 \text{N}}{0.15 \text{kg}} = -2 \text{m/s}^2

  Takið eftir að hröðunin er neikvæð eins og krafturinn.
  Notum nú eina af :ref:`hreyfijöfnunum <s.hreyfijofnur>` til að finna lokastaðsetninguna:

  .. math::
    v^2 - v_0^2 &= 2 a (x - x_0) \\
    (0 \text{m/s})^2 - (5 \text{m/s})^2 &= 2(-2\text{m/s}^2)(x-0\text{m}) \\
    \Rightarrow x &= \frac{25 \text{m}^2\text{/s}^2}{4\text{m/s}^2}   = 6.25 \text{m}

  Pökkurinn rennur því  :math:`6.25` m á svellinu áður en hann stöðvast vegna núningskraftsins.


.. tip::
  5 kg kassi liggur kyrrstæður á skáplani með hallann :math:`\theta = 30°` .
  Hver er núningskrafturinn á milli kassans og skáplansins :math:`f_{nún}`?

  **Lausn**

  Byrjum á að teikna kraftamynd.

  .. figure:: ./myndir/kraftar/skaplan.svg
    :width: 70%
    :align: center

  Þar sem kassinn er kyrrstæður er heildarkrafturinn núll.
  Núningskrafturinn :math:`f_{nún}` liggur samsíða skáplaninu upp eftir því.
  Á kassann verkar þyngdarkraftur :math:`f_g` beint niður.
  Normalkrafturinn :math:`f_n` ýtir á kassann, hornrétt af yfirborði skáplansins.

  Skilgreinum hnitakerfið þannig að x-ásinn sé samsíða skáplaninu og y-ásinn hornrétt á hann.

  .. figure:: ./myndir/kraftar/skaplanhnit.svg
    :width: 70%
    :align: center

  Liðum þyngdarkraftinn í þann hluta sem er samsíða skáplaninu, :math:`f_{g,x}` og þann sem er hornrétt á það, :math:`f_{g,y}`

  .. figure:: ./myndir/kraftar/lidunkrafta2.svg
    :width: 30%
    :align: center

  Til þess að kassinn haldist kyrr þurfa samanlagðir kraftar í hvora stefnu, :math:`x` - og :math:`y`, að vera núll.
  Því þarf normalkrafturinn að vera jafnstór :math:`y` - þætti þyngdarkraftsins og núningskrafturinn að vera jafnstór :math:`x` þættinum.

  Þyngdarkrafturinn er

  .. math::
    F_g = m \cdot g = 5 \text{kg} \cdot 9.8 \text{m/s} = 49 \text{N}

  Þá er þáttur hans samsíða skáplaninu

  .. math::
    F_{g,x} = F_g \sin{\theta} = 49 \text{N} \cdot \sin{30°} = 24.5 \text{N}

  Þar með hlýtur núningskrafturinn að vera :math:`f_{nún} = F_{g,x}= 24.5 \text{N}` .

Vægi
----

*Vægi* (e. torque) er margfeldi vogararms og krafts hornrétt á arminn. Það er oft táknað með :math:`M` eða gríska stafnum :math:`\tau` (tá) og einingarnar eru Newton metrar :math:`1\text{N m}=1 \frac{\text{N m}^2}{\text{s}^2}`.

.. math::

	M=F\cdot r \qquad  \qquad  M_{tot} = \sum_i M_i= \sum_i F_i\cdot r_i

Þar sem :math:`r` er fjarlægð kraftsins :math:`F` frá punktinum sem reikna á vægið um.
Vægi er skilgreint sem jákvætt ef það veldur hreyfingu rangsælis.

.. figure:: ./myndir/kraftar/vaegiskilgr.svg
  :align: center
  :width: 60%

Hér má sjá tvo jafnstóra krafta, :math:`F_1` og :math:`F_2` verka á sitt hvorn endann á stöng sem hvílir á veltipunkti (grái þríhyrningurinn).
Báðir kraftarnir gefa jákvætt vægi á stönguna um veltipunktinn, en vægið frá :math:`F_2` er meira vegna þess að armurinn er lengri, :math:`r_2>r_1`. Heildarvægið um veltipunktinn er þá summan:

.. math::

	M_{tot} = \sum_i M_i = M_1 + M_2 = F_1r_1+F_2r_2

.. tip::
  Kassi er fastur á enda 6 metra langrar stangar og verkar þar með kraftinum :math:`F_k=500\text{ N}`. Stöngin getur velt um punkt, :math:`A`, einum metra frá kassanum. Hve stór þarf krafturinn :math:`F` að vera til halda kassanum kyrrum?

  .. figure:: ./myndir/kraftar/vog.svg
    :align: center
    :width: 60%

  **Lausn**

  Krafturinn :math:`F_k` veldur jákvæðu vægi um punktinn A, en :math:`F` veldur neikvæðu vægi. Kassinn mun hreyfast upp ef vægið frá :math:`F` er jafn stórt og vægið frá :math:`F_k`, þ.e. að heildarvægið um punktinn :math:`A` þarf að vera núll.

  Reiknum nú heildarvægið um punktinn :math:`A` :

  .. math::
    \sum M_A = F_k \cdot 1 \text{ m} + (-F)\cdot 5 \text m = 500 \text{N m}-F\cdot 5\text{ m}

  Heildarvægið er núll ef :math:`500 \text{N m}=F \cdot 5\text{ m}` þ.e.

  .. math::
    F=\frac{500 \text{N m}}{5\text{m}} = 100 \text{N}
