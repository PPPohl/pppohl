---
layout: page
title: Anmeldung
permalink: /anmeldung-lndc/
---

<form>
Anmeldung zur LNDC 


Wenn Sie an der "Langen Nacht des Coding" (#LNDC) teilnehmen möchten, melden Sie sich bitte hier an! <br>
<br>

Anrede: <br> 
    <input type="radio" name="Anrede" value="h" checked id="a1"> <label for="a1">Herr</label> <br>
    <input type="radio" name="Anrede" value="f" checked id="a2"> <label for="a2">Frau</label> <br>
    <input type="radio" name="Anrede" value="d" checked id="a3"> <label for="a3">Divers</label> <br>
<br>

Vorname: <br> 
    <input type="text" name="Vorname" maxlength="15" id="vn"> <br> <br>
Nachname: <br>
    <input type="text" name="Nachname" maxlength="15" id="nn"> <br> <br>

Geburtsdatum: <br>
    <input type="date" id="gb" name="Geburtsdatum" value="" min="1950-01-01" max="2020-12-31"> <br> <br>

Email: <br>
    <input type="email" id="em" name="Email"> <br> <br>

Telefon: <br>
    <input type="text" id="tn" name="Telefonnummer" pattern="[0-9]{13,15}"> <br><br>

Anmeldung als; <br>
    <input type="radio" name="Anzahl" value="ezp" > <label for="an1">Einzelperson</label> <br>
    <input type="radio" name="Anzahl" value="t" > <label for="an2">Team</label> <br> <br>

Steht Ihr Team bereits fest? <br>
    <input type="radio" name="Team-fest" value="ja" > <label for="tf1">Ja, mein Team hat sich bereits zusammengefunden</label> <br>
    <input type="radio" name="Team-fest" value="nein" > <label for="tf2">Nein, aber ich möchte nicht als Einzelperson teilnehmen</label> <br> <br>

Die Anzahl der Teammitglieder beträgt: <br>
    <input type="text" id="tm" name="Teammitglieder" pattern="[0-9]{1,2}"> <br> <br>

Der Names meines Team lautet: <br>
    <input type="text" name="Teamname" maxlength="20" id="Tn"> <br> <br>

Die Namen meiner Teammitglieder lauten: <br>
    <input type="text" name="Teammitglieder" maxlength="100" id="Tm"> <br> <br>

Meine Skills: <br>
    <input type="radio" name="Skills" value="we" > <label for="s1">Web-Entwicklung</label> <br>
    <input type="radio" name="Skills" value="ae" > <label for="s2">App-Entwicklung</label> <br>
    <input type="radio" name="Skills" value="ga" > <label for="s3">Gaming</label> <br>
    <input type="radio" name="Skills" value="de" > <label for="s4">Design</label> <br>
    <input type="radio" name="Skills" value="ig" > <label for="s5">Ideengeber/Kreativkopf</label> <br> <br>
 
Meine IT-Kenntnisse (z.B. Programmiersprachen) <br>
    <input type="text" name="IT-Kenntnisse" maxlength="100" id="ITK"> <br> <br>

Meine T-Shirt Größe: <br>
    <input type="radio" name="Tshirt" value="s" > <label for="g1">S</label> <br>
    <input type="radio" name="Tshirt" value="m" > <label for="g2">M</label> <br>
    <input type="radio" name="Tshirt" value="l" > <label for="g3">L</label> <br>
    <input type="radio" name="Tshirt" value="xl" > <label for="g4">XL</label> <br>
    <input type="radio" name="Tshirt" value="xxl" > <label for="g5">XXL</label> <br> <br>
 
Wie hast Du von dieser Veranstaltung erfahren? <br>
    <input type="text" name="Gesehen" maxlength="50" id="gs"> <br> <br>

Ich habe noch folgende Anmerkung / Frage: <br>
    <input type="text" name="Frage" maxlength="100" id="f"> <br> <br>

Teilnahmebedingungen: <br>
    <input type="checkbox" name="Teilanhmebedingungen" value="y" id="tn"> <label for="tn">Ich habe die Teilnahmebedingungen gelesen und akzeptiere diese</label> <br> <br>

Das sind die <a href="https://pppohl.github.io/Teilnahmebedingungen/">#LNDC Teilnahmebedingungen</a>

Da die Teilnehmeranzahl begrenzt ist, entscheidet ggf. das Los über die endgültige Teilnahme - Wir werden Sie rechtzeitig informieren. <br>
<br>

<input type="submit" value="Bestätigen">
<input type="reset" value="Abbrechen">

</form>