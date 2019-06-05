Hreyfing í tveimur víddum
=========================
Hingað til hefur verið fjallað um einvíða hreyfingu, þar sem staðsetning, hraði og hröðun eru öll eftir sömu beinu línunni.
Í eðlisfræði er hins vegar nauðsynlegt að geta lýst hreyfingu í tveimur og jafnvel þremur víddum.

.. tip::
  Flugvél setur stefnuna beint norður á við og flýgur á hraðanum :math:`v_f= 20 \text{ m/s}`. Það er hvöss vestanátt, :math:`v_v =15\text{ m/s}`, sem vélin berst með. Hver er hraði flugvélarinnar og stefna hraðans miðað við jörðu?

  .. figure:: ./myndir/2d/flugvel.svg
    :align: center
    :width: 40%

  Hér notum við vigursamlagningu. Hreyflar vélarinnar gefa henni hraða :math:`v_f` í stefnu norður (stefnu :math:`y` - áss). Þá er:

  .. math::

  	\overline{v}_f = \begin{pmatrix} 0 \\ 20 \end{pmatrix}

  Vindurinn blæs frá vestri til austurs, til hægri (í stefnu :math:`x` - áss). Því er:

  .. math::

  	\overline{v}_v = \begin{pmatrix} 15 \\ 0 \end{pmatrix}

  Leggjum nú saman vigrana :math:`\overline{v}_f` og :math:`\overline{v}_v`:

  .. math::
    \begin{aligned}
  	\overline{v} &= \overline{v}_f + \overline{v}_v \\
    &= \begin{pmatrix} 0 \\ 20 \end{pmatrix} + \begin{pmatrix} 15 \\ 0 \end{pmatrix} \\
    &= \begin{pmatrix} 15 \\ 20 \end{pmatrix}
    \end{aligned}

  Hraði flugvélarinnar miðað við jörðina er því lengdin á :math:`\overline{v}`:

  .. math::
    \begin{aligned}
  	|\overline{v}| &= \sqrt{15^2+20^2} \\
    &=\sqrt{625} \\
    &= 25
    \end{aligned}

  Vélin er því að fara á :math:`25` m/s, en stefna hraðans er í norðaustur.

Hlutur á hreyfingu hefur breytilega staðsetningu sem táknuð má með ferli í hnitakerfi.
Ferillinn er bein lína ef hraði hlutarins hefur fasta stefnu, þ.e. hluturinn hefur enga hröðun eða ef hröðunin er samsíða hreyfingunni. Ef hröðunin er ekki samsíða hreyfingunni þá veldur hún breytingu á stefnu hraðans og þá beygir ferillinn.

Hraði hlutarins er snertill við feril hlutarins og
hröðun hans bendir alltaf inn í kúpta hluta ferilsins.

Hröðunarvigurinn hefur stefnu óháð staðsetningu og hraða hlutar, en segir til um hvernig hraðinn og stefna hans eru að breytast.

.. image:: ./myndir/2d/hrodun.svg
    :align: center
    :width: 40%

*Kasthreyfingar* og *hringhreyfingar* eru algengar tvívíðar hreyfingar.

Kasthreyfing
------------
Kasthreyfing (e. projectile motion) er þegar hlutur er á hreyfingu í þyngdarsviði og verður ekki fyrir neinni hröðun nema þyngdarhröðun.
Í okkar einfölduðu kerfum er gerum við ráð fyrir að loftmótstaða sé engin,
svo allir *kastferlar* (e. trajectories) verða hluti af fleygboga.

.. tip::
    Tveir eins boltar eru látnir falla til jarðar úr sömu hæð, bolta 1 er sleppt úr kyrrstöðu en bolta 2 er kastað lárétt áfram.
    Gerum ráð fyrir engri loftmótstöðu.
    Hvor boltanna lendir á undan?

    **Lausn**

    Á báða boltana verkar sama þyngdarafl, svo þeir fá sömu hröðun niður sem nemur þyngdarhröðuninni og fá báðir sívaxandi hraða niður á við.

    Bolti 1 mun því hreyfast lóðrétt niður á við.
    Bolti 2 mun halda áfram að hreyfast lárétt því hann verður ekki fyrir neinni hröðun í lárétta stefnu (fyrsta lögmál Newtons).
    Hröðunin sem bolti 2 verður fyrir lóðrétt hefur engin áhrif á lárétta hreyfingu hans (og lárétta hreyfingin hefur engin áhrif á lóðrétta hröðun).

    Boltarnir tveir byrjuðu báðir með sama lóðrétta hraðann (engan) og verða fyrir sömu lóðréttu hröðuninni.
    Þeir ferðast því samtímis niður á við og lenda því *á sama tíma*.

    .. image:: ./myndir/2d/tveirboltar.svg
        :align: center
        :width: 40%

    Ferill bolta 1 er lóðrétt strik en ferill bolta 2 er fleygbogi, því hann hefur hreyfingu í tvær stefnur.

Við lausn dæma um kasthreyfingar eru :ref:`hraðajöfnurnar<s.hreyfijofnur>` notaðar.
Það borgar sig að teikna mynd til að átta sig á dæminu.
Þá þarf að ákveða hnitakerfi, en venjan er að hafa x-ás láréttan og y- (eða z-) ás lóðréttan upp þannig á þyngdarhröðun bendi niður.
Upphafspunkt hreyfingarinnar er þægilegast að setja í miðju hnitakerfisins, enda geta hnitin :math:`(x_0,y_0)=(0,0)` einfaldað reikning töluvert.
Hafið svo í huga að þar sem þyngdarhröðunin er einungis í :math:`y`-stefnuna eru jöfnurnar fyrir staðsetningu sem fall af tíma eftirfarandi:

.. math::
    \begin{aligned}
        x &= x_0 + v_{0,x} \cdot t \\
        y &= y_0 + v_{0,y} \cdot t + \frac{1}{2} g \cdot t^2
    \end{aligned}

.. tip::
    Sagan segir að landið Gambía á vesturströnd Afríku hafi orðið til þegar breski flotinn sigldi upp Gambíuána, skaut úr fallbyssum sínum á báða borða og eignuðu sér landið innan færis fallbyssanna.
    Ef upphafshraði fallbyssukúlu er :math:`\overline{v} = (v_x, v_y) = (50,42)` m/s, hversu breið yrði Gambía?

    **Lausn**

    Byrjum á að teikna mynd.
    Stillum hnitakerfinu upp þannig að fallbyssan sé í :math:`(x_0,y_0) = (0,0)`, x-ásinn liggi út frá ánni í skotstefnuna og y-ásinn er upp.
    Gerum ráð fyrir að hæð lendingarstaðarins sé jöfn hæð fallbyssunnar, þ.e. :math:`y_1=0` .
    Takið eftir að :math:`y`-ásinn er skilgreindur upp en þá er  þannig að þyngdarhröðunin er neikvæð (:math:`g=-9.8` m/s).

    .. image:: ./myndir/2d/gambia.svg
        :align: center
        :width: 60%

    Við vitum að kúlan muni lenda á jörðinni, þannig að lokahnit kúlunnar eru :math:`(x_1,y_1) = (x_1,0)`.
    Rifjum upp hreyfijöfnurnar og notum þá sem gefur staðsetningu sem fall af tíma.
    Viljum finna tímann :math:`t_1` þegar :math:`y_1=0` .

    .. math::
        \begin{aligned}
            y_1 &= y_0 + v_{0,y} \cdot t + \frac{1}{2} a \cdot t^2 \\
            0 &= 0 + v_{0,y} \cdot t + \frac{1}{2} g \cdot t^2
        \end{aligned}

    Þetta er annars stigs margliða með óþekkta stærð :math:`t` sem við leysum:

    .. math::
        \begin{aligned}
            & a \cdot t^2 + b \cdot t + c = 0 \\
            & a= \frac{1}{2} \text{g} \\
            & b= v_{0,y} = 42 m/s \\
            & c=0 \\
        \end{aligned}

        \begin{aligned}
            \Rightarrow t &= \frac{-b \pm \sqrt{b^2-4\text{a}c}}{2\text{a}} \\
            &= \frac{-v_{0,y} \pm \sqrt{v_{0,y}^2-4 \cdot \frac{1}{2} g}}{2 \cdot \frac{1}{2} g} \\
            &= \frac{-42 \pm \sqrt{42^2-2 \cdot (-9.8)}}{-9.8} \\
            &= \begin{cases} 0 \text{ s} = t_0\\
                             8.58 \text{ s} = t_1
                \end{cases}
        \end{aligned}

    Það eru tvær lausnir á jöfnunni því :math:`y`-hnitið er 0 bæði í upphafi og enda ferils kúlunnar.
    Nú getum við notað sömu hreyfijöfnu, í þetta skipti fyrir :math:`x`-hnitin, til að finna hversu langt fallbyssan drífur.
    Athugið að þyngdarhröðunin er lóðrétt svo hún hefur ekki áhrif á lárétta :math:`x`-þátt hraðans.

    .. math::
        \begin{aligned}
            x_1 &= x_0 + v_0 \cdot t_1\\
            &= 0 + 50 \cdot 8.58  \\
            &= 429 \text{ m}
        \end{aligned}

    Fallbyssukúlan lendir því 429 metrum frá ánni og breidd Gambíu er tvöföld sú lengd: 858 m.


Finnum nú jöfnu fyrir ferlinum sem hlutur ferðast eftir í loftinu og sannfærum okkur um að hann sé fleygbogi.
Skoðum hlut sem hefur upphafshraða :math:`v_0` í stefnu hornsins :math:`\alpha_0` og upphafsstaðsetningu :math:`(0,0)` .

Byrjum á því að liða :math:`v_0` í :math:`x` - og :math:`y` - stefnu.

.. math::
  \begin{aligned}
    v_{0x} &= v_0\cos(\alpha_0) \\
    v_{0y} &= v_0\sin(\alpha_0)
  \end{aligned}

.. figure:: ./myndir/2d/v0split.svg
  :align: center
  :width: 50%

Því næst notum við :ref:`hreyfijöfnurnar <s.hreyfijofnur>`.
Hröðunin í :math:`x` - stefnu er núll svo staðsetningin í :math:`x` - stefnu er

.. math::
  x=v_{0x} t = v_0\cos(\alpha_0)t

Hröðunin í :math:`y` - stefnu er :math:`g` og bendir niður á við (:math:`g<0`) svo staðsetningin í :math:`y-` stefnu er:

.. math::
  y=v_{0y} t + \frac{1}{2}gt^2 = v_0\sin(\alpha_0) t+ \frac{1}{2}gt^2

Einangrum :math:`t` út frá jöfnunni fyrir :math:`x`, :math:`t=x/(v_0\cos(\alpha_0))` og setjum inn í jöfnuna fyrir :math:`y` . Þá fæst

.. math::
  \begin{aligned}
    y& =v_0\sin(\alpha_0)t + \frac{1}{2}gt^2 \\
    y&= v_0\sin(\alpha_0) \cdot \frac{x}{v_0\cos(\alpha_0)} + \frac{1}{2}g  \left(\frac{x}{v_0\cos(\alpha_0)}\right)^2\\
    y&= \frac{\sin(\alpha_0)}{\cos(\alpha_0)} x + \frac{1}{2}g \frac{x^2}{v_0^2\cos^2(\alpha)} \\
    y&=\tan(\alpha_0) x + \frac{g}{2v_0\cos^2(\alpha_0)}x^2
  \end{aligned}

Ferill hlutar í kasthreyfingu hefur því lögun fleygboga :math:`y=ax^2+bx+c` þar sem

.. math::
  \begin{aligned}
    a&=\frac{g}{2v_0\cos^2(\alpha_0)}\\
    b&=\tan(\alpha_0) \\
    c&=0
  \end{aligned}

.. figure:: ./myndir/2d/kasthr.svg
  :align: center
  :width: 80%

------------------------

Út frá jöfnunni er meðal annars hægt að sjá hvar hluturinn lendir.
Þá finnum við fyrir hvaða :math:`x` hæð boltans :math:`y` er núll, sem er þegar :math:`x=0` (upphaf) og þegar

.. math::
  \begin{aligned}
    x&=\frac{-2\tan(\alpha_0)v_0^2\cos^2(\alpha_0)}{g}\\
    &=\frac{-2\sin(\alpha_0)\cos(\alpha_0)v_0^2}{g} \\
    &= \frac{-\sin(2\alpha_0)v_0^2}{g} \\
  \end{aligned}

því :math:`\sin(2\alpha)=2\sin(\alpha)\cos(\alpha)` .

------------------------

Það er líka hægt að finna hámarkshæð hlutar í kasthreyfingu með því að finna hágildi þessarrar jöfnu.
Þá finnum við hvar afleiða fallsins með tilliti til :math:`x` er núll.

Afleiðan er

.. math::
  y'=\tan(\alpha_0)+\frac{g}{v_0^2\cos^2(\alpha_0)}x

Hápunktur fleygbogans er því þegar :math:`y'=0` eða:

.. math::
  \begin{aligned}
    x&=\frac{-\tan(\alpha_0)v_0^2\cos^2(\alpha_0)}{g} \\
    &= \frac{-\sin(\alpha_0)\cos(\alpha_0) v_0^2}{g}\\
    &= \frac{sin(2\alpha_0)v_0^2}{2g}
  \end{aligned}

.. math::
  x&=\frac{-\tan(\alpha_0)v_0^2\cos^2(\alpha_0)}{g} = \frac{-\sin(\alpha_0)\cos(\alpha_0) v_0^2}{g}

.. ggb:: mkyudgwh

------------------------

Munið að eðlisfræði gengur ekki út á að muna jöfnur, heldur að kunna hvernig og hvenær á að nota þær.
Til dæmis er ástæðulaust að leggja mikla vinnu í að muna þessar formúlur, þegar það er lítið mál að leiða þær út frá hreyfijöfnunum eða að fletta þeim upp.

------------------------


Hringhreyfing
-------------

Hröðunarvigurinn hefur stefnu óháða stefnu hraðavigursins, en segir til um hvernig hraðavigurinn er að breytast.
Þægilegt er að vinna með vigurinn í tveimur hlutum, annars vegar þáttinn samsíða hraðavigrinum :math:`a_\parallel`
og hins vegar hornrétta þáttinn :math:`a_\perp` en þættir hröðunarvigursins hafa mismunandi áhrif á hraðavigurinn.
.. Þessir þættir eru líka táknaðir með :math:`a_{tan}` (tangential: eins og snertill) og :math:`a_{rad}` (radial: eins og radíus).

.. figure:: ./myndir/2d/tvividd.svg
    :width: 60%
    :align: center

:math:`a_\parallel` hefur meiri áhrif á lengd hraðavigursins, sem oft er kölluð *ferð* hlutarins (e. speed).

:math:`a_\perp` hefur meiri áhrif á stefnu hraðavigursins, þ.e. segir til um hvernig hluturinn er að beygja.

Ef hlutur hefur bara hröðun sem er hornrétt á hraðavigurinn (:math:`a_\paralell =0`) þá beygir hluturinn endalaust í sömu áttina en lengd hraðavigursins er föst, þ.e. *ferð* hlutarins er fasti.

.. note::
  Í kaflanum um hreyfingar í einni vídd kom fram að þegar hröðun hlutar væri núll þá væri hraði hlutarins fasti, en það kemur til vegna þess að þá er

.. tip::
    Hringekja snýst með jöfnum hraða.
    Barn á hringekjunni hefur hraðavigur sem er snertill við hringinn í staðsetningu barnsins.
    Þar sem snúningshraðinn er jafn er ferð barnsins fasti, en hraðavigurinn er samt sem áður stöðugt að breytast.
    Stefnan er það eina sem breytist svo barnið hlýtur að hafa hröðun sem er hornrétt á hraðann, þ.e. beint inn að miðjunni.

    .. figure:: ./myndir/2d/hringekja.svg
        :align: center
        :width: 60%

    Þessi hröðun kallast *miðsóknarhröðun* (e.centripetal acceleration).

Eins og áður segir vísar hröðunarvigur alltaf inn í kúpta hluta ferilsins.
Þegar hröðunin er bara hornrétt á hraðann er talað um *jafna hringhreyfingu* (e.uniform circular motion).
Þá gilda eftirfarandi jöfnur:

.. math::
    \begin{aligned}
        v &= \frac{2 \pi R}{T} \\
        |\vec{a}|= a_\perp &= \frac{v^2}{R}\\
        &= \frac{4 \pi^2 R}{T^2}
    \end{aligned}

Þar sem :math:`R` er radíus hringferilsins og :math:`T` er umferðartíminn (tíminn sem það tekur að fara einn hring).

------------------------

Þegar hlutur í hringhreyfingu hefur ekki fasta ferð er talað um *ójafna hringhreyfingu* (e.nonuniform circular motion).
Þá er hröðunarvigurinn ekki hornréttur á hraðann og lengd hraðavigursins breytileg með tíma.

Takið eftir að stærðirnar :math:`\frac{d |\overline{v}|}{dt}` og :math:`\Bigl|\frac{d \overline{v}}{dt}\Bigr|` eru ekki endilega jafnar.
Sú fyrri, afleiða ferðarinnar :math:`|\overline{v}|`, er sá þáttur hröðunarinnar sem er samsíða hraðanum, :math:`a_{\parallel}`.
Hún er núll í jafnri hringhreyfingu þar sem ferðin er fasti.
Sú seinni er stærð afleiðu hraðans sem er stærð hröðunarvigursins.
Hún er aðeins núll þegar hraðavigurinn er fasti, þ.e. þegar engin hröðun er. Þá ferðast hluturinn í beina línu með föstum hraða.

.. tip::
    Lykkja á rússíbana er dæmi um ójafna hringhreyfingu.
    Ferð rússíbanavagnsins er ekki fasti á meðan hann ferðast eftir lykkjunni, heldur er mest neðst og minnst efst.
    Takið eftir hvernig hröðunavigurinn breytist og reynið að sjá fyrir ykkur þætti hans á mismunandi stöðum í lykkjunni.

    .. figure:: ./myndir/vinna/nonuniform.svg
        :width: 40%
        :align: center
