---
title: "Erste Schritte"
date: 2020-08-02T21:26:25+02:00
chapter: true
draft: false
weight: 2
---

# Erste Schritte - Wie kann [chat.darc.de](https://chat.darc.de) genutzt werden?

## Matrix-Login mit DARC-Account

Mitgliedern des DARC wird unter Einhaltung der einschlägigen gesetzlichen und rechtlichen Bestimmungen zum Datenschutz und zur IT-Sicherheit ermöglicht, mittels ihres **DARC-Logins** mit anderen Mitgliedern, Angehörigen und weiteren Matrix-Nutzenden (bspw. andere Funkamateure) per Chat zu kommunizieren.


## Nutzung des Webclients

Der einfachste Weg ist das direkte Öffnen von [chat.darc.de](https://chat.darc.de) in einem modernen Browser (z.B. [Mozilla Firefox](https://www.mozilla.org/de/firefox/)) unter der Adresse: [https://chat.darc.de](https://chat.darc.de).

![Willkommensbildschirm des DARC Element Web Clients](/images/01_Welcome_de.png)

Starten Sie auf [chat.darc.de](https://chat.darc.de).

![Startseite von Element Webclient mit Anmeldebutton](/images/01_Login_de.png)

Hierzu ist keine Registrierung nötig, der Dienst kann sofort durch Klick auf „Anmelden“ auf der Startseite [https://chat.darc.de](https://chat.darc.de) genutzt werden.

![Loginfenster mit Aufforderung Mitgliedsnummer und Passwort einzugeben](/images/02_Login1_de.png)

Durch das Klicken auf den Knopf "Mit DARC Anmeldung fortfahren" gelangt man nun auf die Anmeldeseite.

![Loginseite SSO](/images/01_sso_page_1.png)

Dort sind folgende Eingaben zu tätigen:
**Mitgliedsnr. / Rufzeichen: Mitgliedsnummer oder Rufzeichen**  (keine E-Mail-Adresse!)

![Loginseite SSO mit Nutzernamen](/images/01_sso_page_2.png)

**Passwort: das vergebene Passwort in der Mitgliederverwaltung**

![Loginseite SSO mit Nutzernamen und PW](/images/01_sso_page_3.png)

Danach ist der Klick auf "Anmelden" nötig.

![Loginseite SSO mit Nutzernamen](/images/01_sso_page_4.png)

Ein alternativer Login, bspw. über die E-Mail-Adresse ist **NICHT** möglich.

Es folgt nach dem Erstlogin auch keine E-Mail / Bestätigungsmail.

Nun ist noch die Zustimmung zur Verarbeitung und Weitergabe der Daten erforderlich. Durch das Setzen des Häkchen und klicken auf "Zustimmng erteilen".

![Zustimmung zur Datenverarbeitung und Weitergabe](/images/01_consent_page.png)

Um jeden Nutzer die Möglich zu geben, einen eigenen Anzeigenamen zu setzten, wird der technische Nutzername bestehend aus 5 zufälligen Zeichen automatisch festgelegt:

@5ZUFALLSZEICHEN:darc.de (Beispiel: @6472k:darc.de)

{{% notice warning %}}
Solltest Du statt mit der oben genannten Website [chat.darc.de](https://chat.darc.de) sofort mit einem [Matrix Client]({{< relref "../clients" >}}) starten wollen, ist es wichtig den Heimserver vom zumeist standardmäßig eingestellten matrix.org auf darc.de zu ändern.
{{% /notice %}}

## Browsereinstellungen

### Browserwahl

Empfehlenswert sind die Browser [Firefox](https://www.mozilla.org/de/firefox/new/), [Chromium](https://www.chromium.org/getting-involved/download-chromium), neuere Versionen von MS Edge (basierend auf Chromium). Ältere oder ungeeignete Browser zeigen ggf. nur eine weiße Seite an.

### NoScript

Viele Menschen nutzen u.a. Skript-Blocker, um sich vor [Tracking](https://tu-dresden.de/tu-dresden/newsportal/news/datenschutz-beim-website-tracking) und Schadsoftware im Browser zu schützen, bspw. mit dem Addon [NoScript](https://addons.mozilla.org/de/firefox/addon/noscript/). Hier ist folgende Einstellung durchzuführen:

![Einstellungen des Browserplugins NoScript mit darc.de als vertrauenswürdige Skriptquelle ausgewählt](/images/10_Sicherheit2_de.png)

### Cookies

Erlauben Sie auch Cookies von

- darc.de

## Bequemes Nutzen der Ende-zu-Ende-Verschlüsselung (E2EE)

Matrix verschlüsselt nicht nur die Transporte von und zu dem Heimserver (betrieben vom DARC) sondern erlaubt auch dir die Nutzung von Ende-zu-Ende-Verschlüsselung (E2EE). Hierzu müssen kryptografische Schlüssel zwischen allen Geräten ausgetauscht werden, die sich Ende-zu-Ende-verschlüsselt schreiben möchten. Obwohl diese technische Notwendigkeit kompliziert klingt und im Hintergrund auch ist, ist sie inzwischen für dich als Anwender sehr bequem geworden. Die vielen kryptografischen Schlüssel werden vom Client erstellt auf dem jeweiligen Gerät gespeichert. Sollte dies bspw. ein Tab in einem Browser sein, besteht die Gefahr, dass dieser Tab einmal unbeabsichtigt geschlossen wird. Dann sind **alle verschlüsselten Inhalte nicht mehr lesbar**. Damit das nicht bei dir geschieht, wird eine Schlüsselsicherung auf dem Heimserver angeboten, auf der (mit einer Sicherheitsphrase (bzw. daraus errechenbaren Sicherheitsschlüssel) geschützt) alle kryptografischen Schlüssel verschlüsselt abgelegt sind.

{{% notice info %}}
Es wird dringend empfohlen, die Schlüsselsicherung zu nutzen (mit einer sicheren Sicherheitsphrase, welches **nicht** Dein DARC-Passwort ist)!
{{% /notice %}}

Zunächst den Punkt "Sicherheitsphrase eingeben" anwählen und auf "Fortfahren" klicken:

![Aufforderung den Sicherheitsschlüssel zu generieren oder eine Sicherheitsphrase einzugeben](/images/11_Setup-Key_de.png)

Hier nun das sichere Passwort eintragen und auf "Fortfahren" klicken.

![Aufforderung eine Passwort für die Schlüsselsicherung einzugeben](/images/12_Enter-Key_de.png)

Nun muss zur bestätigung des Passwortes es erneut eingegeben werden, danach ist ein erneuter Klick auf "Fortfahren" nötig.

![Aufforderung eine Passwort für die Schlüsselsicherung erneut einzugeben](/images/12_Enter-Key2_de.png)

Nun gibt es abschließend die Möglichkeit einen Sicherungsschlüssel herunterzuladen oder zu kopieren (z.B. um in einem Passwortmanager gespeichert zu werden)

Alternativ können Sie sich statt der Sicherheitsphrase auch einen Sicherheitsschlüssel generieren lassen, welcher den selben Zweck wie die Sicherheitsphrase erfüllt. Weiterhin wird der Sicherheitsschlüssel immer zusätzlich zur Sicherheitsphrase erstellt und sollte als Notfallschlüssel sicher und wiederauffindbar verwahrt werden (z.B. Abspeichern als .txt-Datei UND Ausdrucken) 
![Anzeige des Sicherheitsschlüssel zum abschreiben oder wegspeichern](/images/13_Present-Key_de.png) 

[Weitere wichtige Einstellungen]({{< relref "settings/_index.md" >}}) können Ihr Matrix-Erlebnis verbessern!


## Aufforderungen zum Einrichten der Schlüsselsicherung

![Screenshot der Aufforderung eine Sicherheitsphrase einzugeben](/images/01_Restore-Session_de.png)

Sollte die Aufforderung zum Einrichten der Schlüsselsicherung übersprungen werden, sähe der nächste Bildschirm so aus:

![Bestätigung des Überspringens der Eingabe einer Sicherheitsphrase](/images/03_Cancel-Restore_de.png)

Die Schlüsselsicherung wird dringend empfohlen, um sorgenfrei Ende-zu-Ende-Verschlüsselung nutzen zu können. Daher wird auch nach einem weiteren Überspringen in einem kleineren Tooltip zur Einrichtung der Verschlüsselung aufgefordert:

![Chatansicht mit der Anzeige eines Tooltips, Verschlüsselung einzurichten. Markierung des bestätigen Feldes](/images/04_Notification_de.png)

Sollten Sie dies auch hier auslassen wird Ihnen eine letzte Warnung bei einem bewussten Abmelden angezeigt. Wenn spätestens hierbei keine Schlüsselsicherung eingerichtet wird, kann später auf ggf. schon stattgefundene verschlüsselte Gespräche nicht mehr zugegriffen werden. Sollte der Tab geschlossen werden, entspricht dies ggf. ebenfalls einem Abmelden.

![Abfrage, ob Nachrichten verschlüsselt werden sollen](/images/05_Logout-Notify_de.png)

Vermeiden Sie diese Situation durch eine eingerichtete Schlüsselsicherung!

## Matrix-Login ohne DARC-Account

Eine Registrierung von Accounts (wie vllt. von anderen Matrix-Servern bekannt) ist hier beim DARC nicht möglich, da den Dienst ausschließlich Personen mit DARC Mitgliedschaft nutzen können. Der DARC ist kein Kommunikationsdiensteanbieter.

## Datenschutzerklärung

Datenschutzerklärung: [Link]({{< relref "privacy/_index.md" >}})

## Impressum

Impressum: [Link]({{< relref "imprint/_index.md" >}})

