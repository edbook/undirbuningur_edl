Skriðþungi
==========

Hugsum okkur hlut sem hefur fastan massa :math:`m`. Nú verður þessi hlutur fyrir einhverjum kröftum, en skv. fyrsta lögmáli Newtons getum við skrifað:

.. math::
  \sum \overline{F} = m\overline{a}

þar sem :math:`\overline{a}` er hröðunin sem hluturinn fær vegna kraftanna. Þar sem hröðun er tímaafleiða hraða, :math:`\overline{a} = \frac{d\overline{v}}{dt}`, þá getum við skrifað:

.. math::
  \sum \overline{F} = m \frac{d\overline{v}}{dt}

Við skilgreinum *skriðþunga* (e. momentum) hlutar á hreyfingu sem margfeldi massans og hraðans sem hann er á.

.. math::
  \overline{p}=m\overline{v}

Massamikill hlutur á miklum hraða hefur því mikinn skriðþunga á meðan massalitlir hlutir á hægri hreyfingu mjög lítinn.

Því gildir að summa kraftanna sem verka á hlut er jöfn breytingunni sem verður á skriðþunga hlutarins.

.. math::
  \sum \overline{F} = \frac{d\overline{p}}{dt}

Þetta þýðir því að það ef koma á massamiklum hlut á mikla hreyfingu úr kyrrstöðu þarf mikinn kraft.
Hugsaðu þér að þú sért að versla í innkaupakerru. Í upphafi ferðarinnar er kerran tóm og hún lætur auðveldlega að stjórn. Eftir því sem vörurnar safnast í hana, þyngist hún og það verður sífellt erfiðara (krefst meiri krafts) að koma henni af stað. Að sama skapi er erfitt að stoppa hana sé hún komin á skrið.

.. tip::
  :math:`m=1600` kg bíll keyrir áfram á :math:`v=5` m/s.
  Skriðþungi hans er :math:`P=mv= 1600\text{ kg}\cdot 5 \text{m} /\text{s} = 8000 \text{ kg } \text{m} /\text{s}`.
  Hér er massamikill hlutur á hægri hreyfingu. Væri bíllinn að fara tvöfalt hraðar myndi skriðþunginn tvöfaldast líka.

  Byssukúla hefur hraðann :math:`v=965` m/s og hefur massann :math:`4.2` g :math:`=0.0042` kg.
  Skriðþungi hennar er þá  :math:`P=mv =0.0042\text{kg} \cdot 965\text{m} /\text{s} = 40.5  \text{ kg } \text{m} /\text{s}`. Hér er massalítill hlutur á miklum hraða, meira en tvöföldum hljóðhraða.


Atlag
-----
Hugsum okkur hlut sem verður fyrir kröftum (sem hafa summuna :math:`\sum \overline{F}`) frá tímanum :math:`t_1` til tímans :math:`t_2`. Þá er *atlag* (e. impulse) kraftsins margfeldi kraftanna við lengd tímabilsins:

.. math::
  \overline{J} = \sum \overline{F}(t_2-t_1) = \sum \overline{F} \Delta t

Ef hluturinn verður fyrir sama kraftinum allt tímabilið þá er atlagið jafnt breytingunni á skriðþungnanum:

.. math::
  \overline{J} = \overline{p_2} - \overline{p_1} = \Delta \overline{p}

.. tip::
  Hvað þarf að beita miklum (jöfnum) krafti til þess að stöðva 50 kg innkaupakerru sem fer á 6 m/s, ef það þarf að takast á 3 sekúndum?

  .. figure:: ./myndir/skrth/kerra.svg
    :align: center
    :width: 60%

  Skriðþunginn í upphafi er :math:`p_1 = mv_1 = 50 \text{ kg} \cdot 6 \text{m/s} = 300 \text{kg m/s}` . Skriðþunginn í lokin er :math:`p_2 = 0` því :math:`v_2=0`. Við gerum ráð fyrir að aðeins einn kraftur verki, :math:`\overline{F}`, svo :math:`\sum \overline{F} = \overline{F}` . Þar sem krafturinn verkar bara í einni vídd þá dugar að hugsa bara um stærð vigursins, :math:`F`. Hér er :math:`\Delta t = 3 \text{ s}`

  .. math::
    \begin{aligned}
    J=F\Delta t &= \Delta p  = p_2-p_1\\
    F &= \frac{p_2-p_1}{\Delta t} \\
     &= \frac{0-300 \text{kg m/s}}{3 \text{ s}} \\
     &= -100 \text{ N}
    \end{aligned}

  Krafturinn fær neikvætt gildi því hann bendir á móti hreyfingunni.



Varðveisla
----------
Ef summa allra kraftanna sem verka á kerfi er núll, þá er breyting heildarskriðþunga kerfis með tilliti til tíma líka jafnt núll. Það merkir að heildarskriðþungi kerfis breytist ekki, en skriðþungar hlutanna innan kerfisins geta breyst, en summa þeirra er alltaf sú sama.

.. note::
  Skriðþungi er varðveittur ef engir kraftar koma utan frá.

Hugsum okkur tvær kúlur á núningslausu borði (það að borðið sé núningslaust gefur okkur vísbendingu um að engir utanaðkomandi kraftar, eins og núningur, eru að verki). Þær hafa ekki endilega sama massann en önnur þeirra (2) er kyrr á meðan hin (1) hefur hraðann :math:`v_0`. Þá er heildarskriðþungi kerfisins :math:`m_1v_0`. Hvað gerist þegar þær rekast saman?

.. figure:: ./myndir/skrth/skrth1.svg
  :align: center
  :width: 60%

Fullkomlega fjaðrandi árekstur
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Áður en kúlurnar skella saman þá er heildarskriðþungi kerfisins margfeldi :math:`v_0` við massa kúlu 1. Við áreksturinn varðveitist skriðþunginn, svo við vitum að skriðþunginn eftir áreksturinn er sá sami og fyrir. Þegar seinni kúlan tekur við öllum skriðþunganum og fær hraðann :math:`v_2` á meðan hin stöðvast þá er talað um *fullkomlega fjaðrandi árekstur*.

.. note::
  Í fjaðrandi árekstrum er bæði skriðþungi og hreyfiorka kerfisins varðveitt.

.. figure:: ./myndir/skrth/skrth2.svg
  :align: center
  :width: 60%

Fyrst skriðþunginn er varðveittur þá er:

.. math::
  m_1 v_0 = m_2 v_2

þ.a. hraði seinni kúlunnar eftir áreksturinn er:

.. math::
  v_2 = \frac{m_1 v_0}{m_2}

Ef kúlurnar tvær hafa sama massann :math:`m_1=m_2` þá mun seinni kúlan fara áfram með hraðanum :math:`v_2=v_0`

Fullkomlega ófjaðrandi árekstur
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

En hvað ef kúlurnar eru þannig gerðar að þær klístrist saman við áreksturinn? Þá er talað um *fullkomlega ófjaðrandi árekstur* og kúlurnar myndu ferðast áfram, klesstar saman, en með annan hraða en fyrir árekstur.

.. note::
  Í ófjaðrandi árekstrum er skriðþungi kerfisins varðveittur, en hreyfiorkan *ekki*.

.. figure:: ./myndir/skrth/skrth3.svg
  :align: center
  :width: 60%

Hér er skriðþunginn líka varðveittur, svo:

.. math::
  m_1v_0 = m_1v_1+m_2v_2 = (m_1+m_2)v_1

því þær fara á sama hraða eftir áreksturinn :math:`v_1=v_2`. Því er hraðinn sem þær fara á:

.. math::
  v_1=v_2 = \frac{m_1v_0}{m_1+m_2}

Ef kúlurnar hafa sama massann :math:`m_1=m_2` þá er hraðinn sem kúlurnar ferðast saman á hálfur upprunalegi hraðinn: :math:`v_1=v_2=\frac12 v_0`.

Önnur tilvik
~~~~~~~~~~~~

Til er millistig af þessu tvennu: ófjaðrandi árekstur þar sem hreyfiorkan er ekki varðveitt og hlutirnir ferðast ekki á sama hraða eftir árekstur.

.. figure:: ./myndir/skrth/skrth5.svg
  :align: center
  :width: 45%

Það getur gerst að fyrri kúlan ýti seinni af stað en haldi sjálf áfram. Þá þarf að gilda að samanlagður skriðþungi kúlnanna eftir áreksturinn sé jafn skriðþunganum fyrir áreksturinn:

.. math::
  m_1v_0 = m_1v_1+m_2v_2

Þetta er jafna með tvær óþekktar stærðir, :math:`v_1` og :math:`v_2`. Því eru til *óendanlega margar* lausnir á þessu verkefni og við myndum þurfa meiri upplýsingar, t.d. að önnur kúlan endi á að fara þrefalt hraðar en hin (:math:`v_2 = 3v_1`) . Í raunveruleikanum myndi þetta ráðast af eiginleikum efnanna.

Það eru líka til lausnir þar sem fyrri kúlan fær hraða í gagnstæða átt og skoppar til baka. Þá er :math:`v_1<0`


.. figure:: ./myndir/skrth/skrth4.svg
  :align: center
  :width: 60%

----------------------

.. math::
  \begin{array}{| c | c |}
   \hline
  \text{Fullkomlega fjaðrandi árekstur} & \text{Hreyfiorkan er varðveitt} \\ \hline
  \text{Fullkomlega ófjaðrandi árekstur} & \text{Hlutirnir klessast saman og} \\
  &                           \text{ferðast áfram með sama hraða}   \\ \hline
  \text{Ófjaðrandi árekstur} & \text{Hreyfiorkan er ekki varðveitt} \\ \hline
  \end{array}
