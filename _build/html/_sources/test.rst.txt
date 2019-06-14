Test
====

Hér er ég að reyna að setja inn embedded spurningar, með misjöfnum árangri.

Í extension-inu eqt.py er hægt að setja inn fjölvalsspurningar (og opnar spurningar).
Það er hægt að gera það þannig að sé rangt svar sett inn kemur útskýringar á því hvers vegna valkosturinn er réttur eða rangur
en þá virkni má sjá í fyrra dæminu.

Það er líka hægt að setja inn lausn að dæminu sem britist þegar beðið hefur verið um hana eða rétt svar hefur verið sett inn, en það virkar ekki alveg sem skyldi, enda er lausnin alltaf sýnileg, sjá fyrra dæmi. Í seinna dæminu er smá workaround sem notar toggleblock fyrir lausnina.

Til þess að virkja eqt pakkann þurfti að gera hitt og þetta, m.a. að uppfæra sphinx og uppfæra nokkrar skriptur úr Python2 í Python3, bæta við nokkrum línum í layout.html. Meðal afleiðinga þessa fikts var að toggleblock og geogebra hættu að virka. Ég náði að laga það þannig að nú ert allt næstum því eins og það á að vera, nema að það vantar HÍ-raunvísindadeildar logoið efst til vinstri. Hlýt að geta fundið út úr því á endanum.

.. raw:: HTML

  <hr class="docutils" />
  <div class="reauthoring_embedded_quiz" id="daemi-hradi1"><form class="reauthoring_embedded_quiz_questions"><p><strong>Æfingadæmi 1</strong> Hversu langt kemst maður sem gengur á hraðanum <span class="math notranslate nohighlight">\(v=3 \text{ m/s}\)</span> á einni mínútu?</p>
  <ol class="upperalpha eqt-answer-list simple">
  <li><p><input type="radio" name="question" value="I" />  <img class="result_icon" style="display: none;"       src="_static/Incorrect_20x20.png"></img> 300 metra
  <div class="tip expl admonition" style="display:none;">Þetta er ekki rétt svar, því það eru ekki 100 sekúndur í einni mínútu.</div></p></li>
  <li><p><input type="radio" name="question" value="I" />  <img class="result_icon" style="display: none;"       src="_static/Incorrect_20x20.png"></img> 3 metra
  <div class="tip expl admonition" style="display:none;">Lastu dæmið rétt? Hvað eru margar sekúndur í einni mínútu?</div></p></li>
  <li><p><input type="radio" name="question" value="C" />  <img class="result_icon" style="display: none;"       src="_static/Correct_20x20.png"></img> 180 metra
  <div class="tip expl admonition" style="display:none;">Já! Staðsetning er margfeldi hraða og tíma.</div></p></li>
  <li><p><input type="radio" name="question" value="I" />  <img class="result_icon" style="display: none;"       src="_static/Incorrect_20x20.png"></img> None of the above (engin útskýring)</p></li>
  </ol>
  <div class="tip expl admonition" style="display:none;">
  <p class="admonition-title">Lausn</p>
  <p>Þetta er lausn verkefnisins.
  Hún á ekki að birtast fyrr en beðið hefur verið um hana eða rétt svar hefur verið sett inn,
  en þetta virkar ekki alveg eins og það á að gera.
  Workaround í næsta dæmi.</p>
  <p>Það er hægt að setja inn stærðfræði eins og manni lystir.</p>
  <div class="math notranslate nohighlight">
  \[2+2=4\]</div>
  </div>
  </form><div class="reauthoring_embedded_quiz_buttons"><input class="reauthoring_quiz_button reauthoring-grade"        style="display:none;"        type="button" value="Athuga svar" /><input class="reauthoring_quiz_button reauthoring-again"        style="display:none;"        type="button" value="Reyna aftur" /><input class="reauthoring_quiz_button reauthoring-solution"        style="display:none;"        type="button" value="Sýna svör" />  <img class="correct_icon" style="opacity: 0;"       src="_static/Correct_20x20.png"></img>  <img class="incorrect_icon" style="opacity: 0;"       src="_static/Incorrect_20x20.png"></img><span class="reauthoring-embedded-answer"></span></div></div><hr class="docutils" />



----------------

.. eqt:: daemi-hradi1

   **Æfingadæmi 1** Hversu langt kemst maður sem gengur á hraðanum :math:`v=3 \text{ m/s}` á einni mínútu?

   A) :eqt:`I` 300 metra
      :expl:`Þetta er ekki rétt svar, því það eru ekki 100 sekúndur í einni mínútu.`

   #) :eqt:`I` 3 metra
      :expl:`Lastu dæmið rétt? Hvað eru margar sekúndur í einni mínútu?`

   #) :eqt:`C` 180 metra
      :expl:`Já! Staðsetning er margfeldi hraða og tíma.`

   #) :eqt:`I` None of the above (engin útskýring)

   .. eqt-solution::
      Þetta er lausn verkefnisins.
      Hún á ekki að birtast fyrr en beðið hefur verið um hana eða rétt svar hefur verið sett inn,
      en þetta virkar ekki alveg eins og það á að gera.
      Workaround í næsta dæmi.

      Það er hægt að setja inn stærðfræði eins og manni lystir.

      .. math::

      	2+2=4

----------------

.. eqt:: daemi-hradi2

   **Æfingadæmi 2** Hversu langt kemst maður sem gengur á hraðanum :math:`v=3 \text{ m/s}` á einni mínútu?

   A) :eqt:`I` 300 metra

   #) :eqt:`I` 3 metra

   #) :eqt:`C` 180 metra

   #) :eqt:`I` Ekkert af ofangreindu

---------------

.. begin-toggle::
  :label: Sýna lausn við dæmi 2
  :starthidden: True

Einföld lausn á vandamálinu með sýnilegu lausnina er að nota toggleblock til að fela/sýna lausnina.
Í einni mínútu eru 60 sekúndur. Við margföldum saman hraðann og tímann og fáum:

.. math::
  60\text{ s} \cdot 3 \text{ m/s} = 180 \text{ m}

.. end-toggle::


----------------

.. eqt:: daemi-hradi3

   **Æfingadæmi 3** Er mynd með þessu dæmi?

   .. figure:: ./myndir/einingar/sol.svg
     :align: center
     :alt: texti með mynd

   A) :eqt:`I` nei

   #) :eqt:`I` nei

   #) :eqt:`C` já

   #) :eqt:`I` nei
