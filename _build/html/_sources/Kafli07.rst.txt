Orka
====
Öll eðlisfræðileg kerfi hafa að geyma orku af einhverju tagi, en hún segir til um hve mikla vinnu þarf til þess að breyta ástandi kerfisins.

Varðveisla orku er eitt af mikilvægustu lögmálum eðlisfræðinnar.

**Orku er ekki hægt að búa til eða eyða.** Hún getur hvorki birst upp úr þurru, né horfið sporlaust. Orka varðveitist í öllum ferlum en getur breytt um form.
Birtingarmyndum orku má skipta í tvo meginflokka, mættisorku og hreyfiorku.

*Mættisorka* (e. potential energy) er geymd á einhvern máta:

- efnaorka (í efnatengjum sameinda)
- kjarnorka (í kjörnum atóma)
- stöðuorka (t.d. vegna þyngdar- og segulsviða)
- spennuorka (t.d. í teygðum og þjöppuðum gormum)

*Hreyfiorka* (e. kinetic energy) er þar sem hlutir eða eindir eru á hreyfingu:

- varmarorka (titrandi atóm)
- hljóð (titrandi efni)
- rafsegulorka (ljós)
- raforka (rafeindir á hreyfingu)

.. tip::
    **Orka breytir um form.**

    Bolti sem fellur til jarðar hefur *stöðuorku* vegna þyngdarsviðs jarðar, en hún breytist í *hreyfiorku* á meðan fallinu stendur. Þegar boltinn lendir á jörðinni þá breytist hreyfiorka boltans sem *hreyfiorka* loftsins í kringum hann í formi hljóðbylgja og mögulega varma auk þess sem jörðin tekur á sig högg.
    Eftir því sem boltinn er hærra yfir yfirborðinu, því meiri stöðuorku hefur hann í upphafi og þar af leiðandi meiri hreyfiorku þegar niður er komið.

    Þegar sprengja springur losnar mikil *hreyfiorka*, *varmaorka* og *rafsegulorka* (ljós) á stuttum tíma, en öll sú orka var í sprengjunni fyrir, bundin í formi *efnaorku*.


Vinna
-----
Kraftur :math:`F` er sagður vinna *vinnu* (e. work) þegar hann flytur hlut um *vegalengd* (e. displacement) :math:`s` .
Vinna er oft táknuð með :math:`W` og er margfeldi kraftsins og færslunnar:

.. math::
  W=F\cdot s

Einingin fyrir vinnu er Joule, táknað :math:`J`.

.. math::
  1 \text{ J} = 1 \text{ N} \cdot 1 \text{ m} = 1 \frac{\text{kg}\text{ m}^2}{\text{s}^2}

.. tip::
  Vinna togkrafts :math:`T=25 \text{ N}` við að flytja hlut vegalengdina :math:`s=10 \text{ m}` er

  .. math::
    W=F\cdot s = 25 \text{ N} \cdot 10 \text{ m} = 250 \text{ J}

Ef vinna er ekki samsíða færslunni þurfum við að skoða vigrana sem krafturinn og færslan eru.
Vinna er þá innfeldi kraftavigursins og færsluvigursins:

.. math::
  \begin{aligned}
    W&=\overline{F}\cdot\overline{s} \\
    W&= Fs\cos(\phi)
  \end{aligned}

þar sem :math:`\phi` er hornið á milli vigranna.

.. figure:: ./myndir/vinna/vinna5.svg
  :align: center
  :width: 70%


.. note::
  Vinna getur verið jákvæð, neikvæð eða núll.

  * Þegar krafturinn er í sömu stefnu og færslan, þ.e. ef hann er að vinna með hreyfingunni, er vinnan jákvæð. Ef :math:`-90°<\phi<90°` þá er :math:`\cos(\phi)>0` .

  .. figure:: ./myndir/vinna/vinna2.svg
    :align: center
    :width: 70%

  * Ef krafturinn er gagnstefna færslunni, þ.e. að vinna gegn hreyfingunni, þá er vinnan neikvæð. Ef :math:`90°<\phi< 270°` þá er :math:`\cos(\phi)<0`.

  .. figure:: ./myndir/vinna/vinna3.svg
    :align: center
    :width: 70%

  * Ef krafturinn er hornréttur á færsluna þá er vinna kraftsins á hlutinn núll. Ef :math:`\phi=90°` eða :math:`\phi=270°` þá er :math:`\cos(\phi)=0`.

  .. figure:: ./myndir/vinna/vinna4.svg
    :align: center
    :width: 70%

Afl
---
Afl er breyting á vinnu á tímabili, eða tímaafleiða vinnu:

.. math::
  P_{meðal} = \frac{\Delta W}{\Delta t}

.. math::
  P=\lim_{\Delta t \to 0} \frac{\Delta W}{\Delta t} = \frac{dW}{dt}

Einingin fyrir afl er Watt, táknað W.

.. math::
  1 W=\frac{1 \text{ J}}{1\text{ s}}

.. note::
  Passið ykkur á því að ruglast ekki á einingunni Watt fyrir afl og tákninu :math:`W` sem er notuð fyrir orku! Það er yfirleitt skýrt af samhenginu hvort er um að ræða.

Hreyfiorka
----------
Hlutur sem hefur massann :math:`m`  og fer á hraðanum :math:`v` hefur hreyfiorku (e. kinetic energy) :math:`K` :

.. math::
  K= \frac{1}{2}mv^2

Hreyfiorka og vinna tengjast með þeim hætti að vinna krafts er jöfn breytingunni sem verður á hreyfiorkunni.

.. math::
  W=\Delta K=K_2-K_1 = \frac{1}{2}mv_2^2-\frac{1}{2}mv_1^2

.. tip::
  Sleði með massann :math:`m=20` kg rennur eftir sléttum, láréttum snjó.
  Þar er lítill núningur, en samt nóg til þess að hægja á sleðanum.
  Hver er vinna núningsins ef upphafshraði sleðans er :math:`v_1 =10` m/s og lokahraðinn er :math:`v_2=5` m/s?

  **Lausn**

  Við vitum að vinnan :math:`W` er jöfn breytingunni á hreyfiorkunni.
  Hreyfiorkan í upphafi er

  .. math::
    K_1= \frac{1}{2} mv_1^2 =  1000 \text{ J}

  Hreyfiorkan í lokin er

  .. math::
    K_2=\frac{1}{2} mv_2^2 = 250 \text{ J}

  Því er vinnan

  .. math::
    \begin{aligned}
      W=K_2-K_1 &= 250 \text{ J}- 1000 \text{ J} \\
      W&= -750 \text{ J}
    \end{aligned}

  Vinnan er neikvæð því krafturinn vinnur gegn hreyfingunni.


Stöðuorka
---------
Þegar hlutir eru í *þyngdarsviði*, þ.e. nálægt yfirborði miklu stærri hlutar (eins og jarðarinnar) hafa þeir *þyngdarstöðuorku* (e. gravitational potential energy) :math:`U` :

.. math::
  U = mgy

þar sem :math:`y` er hæð massans yfir einhverjum tilteknum viðmiðunarpunkti, sem er oft yfirborð jarðarinnar.


Orkuvarðveisla
--------------
Orka er einn eðliseiginleika sem er *varðveittur*, þ.e. hún getur aldrei birst upp úr þurru né horfið sporlaust.
Hún getur aðeins breytt um form, t.d. þá getur stöðuorka orðið að hreyfiorku og öfugt.

Þegar hlutur fellur til jarðar úr einhverri hæð minnkar stöðuorka hans, en á móti kemur að hann fer hraðar, þ.e. hreyfiorka hlutarins eykst. Sé ekki núningur er öll orka kerfisins annað hvort stöðuorka eða hreyfiorka og þá gildir að:

.. math::
  K_1+U_1 = K_2+U_2

.. tip::
  0.5 kg steinn fellur úr kyrrstöðu í 20 metra hæð til jarðar.
  Hver er hraði hans rétt áður en hann skellur á yfirborði jarðarinnar?

  *Lausn*

  Gerum ráð fyrir að loftmótsstaðan hafi engin áhrif, þ.e. að það verði ekki núningur milli steinsins og loftsins sem umlykur hann.

  Í upphafi er hreyfiorka steinsins núll (:math:`K_1=0`), fyrst hann fellur úr kyrrstöðu, en stöðuorka hans er:

  .. math::
    U_1=mgy=0.5 \text{ kg}\cdot  9.8 \text{m/s}^2\cdot 20 \text{ m} = 98 \text{ J}

  Rétt áður en steinninn skellur á yfirborði jarðarinnar í 0 metra hæð er stöðuorkan orðin að núlli (:math:`U_2=0`), en steinninn er á fleygiferð.
  Öll stöðuorka steinsins í upphafi er nú orðin að hreyfiorku.
  Því er:

  .. math::
    \begin{aligned}
    K_1+U_1&=K_2+U_2\\
    0+ U_1&=K_2+0 \\
    U_1 &= \frac{1}{2}mv_2^2 \\
    2 \cdot U_1 / m &= v_2^2 \\
    v&=\sqrt{2\cdot98\text{ J} /20\text{ kg}} = 3.13 \text{m/s}
    \end{aligned}

  .. figure:: ./myndir/vinna/steinn.svg
    :align: center
    :width: 40%




.. fjalla um gorma?
.. spurs með heildaframsetningu vinnu, of snemma?
