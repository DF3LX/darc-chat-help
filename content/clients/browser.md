---
title: "Element Web (Browser)"
date: 2020-07-15T16:46:07+02:00
draft: false
chapter: true
weight: 10
---

## Nutzung des Webclients

Starten Sie auf [chat.darc.de](https://chat.darc.de).

![Startseite von Element Webclient mit Anmeldebutton](/images/01_Welcome_de.png)

Hierzu ist keine Registrierung nötig, der Dienst kann sofort durch Klick auf „Anmelden“ auf der Startseite [https://chat.darc.de](https://chat.darc.de) genutzt werden.

![Loginfenster mit Aufforderung Mitgliedsnummer und Passwort einzugeben](/images/02_Login1_de.png)

Durch das Klicken auf den Knopf "Mit DARC Anmeldung fortfahren" gelangt man nun auf die Anmeldeseite. Dort sind folgende Eingaben zu tätigen:
**Mitgliedsnr. / Rufzeichen: Mitgliedsnummer oder Rufzeichen**  (keine E-Mail-Adresse!)

**Passwort: das vergebene Passwort in der Mitgliederverwaltung**

Ein alternativer Login, bspw. über die E-Mail-Adresse ist **NICHT** möglich.

Es folgt nach dem Erstlogin auch keine E-Mail / Bestätigungsmail.

Um jeden Nutzer die Möglich zu geben, einen eigenen Anzeigenamen zu setzten, wird der technische Nutzername bestehend aus 5 zufälligen Zeichen automatisch festgelegt:

@5ZUFALLSZEICHEN:darc.de (Beispiel: @6472k:darc.de)

{{% notice warning %}}
Solltest Du statt mit der oben genannten Website (Element Web-App des DARC) sofort mit einem [Matrix Client]({{< relref "../clients" >}}) starten wollen, ist es wichtig den Heimserver vom zumeist standardmäßig eingestellten matrix.org auf https://darc.de zu ändern (dargestellt in den folgenden drei Bildschirmfotos):
{{% /notice %}}

![Anmeldeseite mit Fokus auf dem Homeserver ändern Button](/images/02_Login2_de.png)

1. Klick auf Ändern

![Eingabefeld zum Ändern des Homeserers mit der Eingabe darc.de](/images/02_Login3_de.png)

2. Markieren der voreingestellten Heimserver-Adresse und entfernen dieser.

![](/images/02_Login4_de.png)

3. Eintragung der Matrix-Heimserver-Adresse des DARC


Der einfachste Weg ist das direkte Öffnen der Element Web Anwendung in einem modernen Browser (z.B. [Mozilla Firefox](https://www.mozilla.org/de/firefox/)) unter der Adresse: [https://chat.darc.de](https://chat.darc.de).

![Willkommensbildschirm des DARC Element Web Clients](/images/01_Welcome_de.png)

## Browsereinstellungen

### Browserwahl

Empfehlenswert sind die Browser [Firefox](https://www.mozilla.org/de/firefox/new/), [Chromium](https://www.chromium.org/getting-involved/download-chromium), neuere Versionen von MS Edge (basierend auf Chromium). Ältere oder ungeeignete Browser zeigen ggf. nur eine weiße Seite an.

### NoScript

Viele Menschen nutzen u.a. Skript-Blocker, um sich vor [Tracking](https://tu-dresden.de/tu-dresden/newsportal/news/datenschutz-beim-website-tracking) und Schadsoftware im Browser zu schützen, bspw. mit dem Addon [NoScript](https://addons.mozilla.org/de/firefox/addon/noscript/). Hier sind folgende Einstellungen durchzuführen (für den Integrationsmanager, z.B. Jitsi/Etherpad)

![Einstellungen des Browserplugins NoScript mit darc.de und vector.im als vertrauenswürdige Skriptquellen ausgewählt](/images/10_Sicherheit2_de.png)

### Cookies

Erlauben Sie auch Cookies von

- darc.de
- (vector.im (für den Integrationsmanager))
