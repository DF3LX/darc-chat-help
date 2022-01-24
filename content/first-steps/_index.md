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

{{% notice tip %}}
Wir empfehlen die Nutzung des Element Desktopclients, weil so zahlreiche Probleme, die bei dem Nutzen der Verschlüsselung entstehen können, vermieden werden können.
{{% /notice %}}

Downloads für: {{% button href="https://packages.riot.im/desktop/install/win32/x64/Element%20Setup.exe" icon="fas fa-download" %}}Windows{{% /button %}} {{% button href="https://packages.riot.im/desktop/install/macos/Element.dmg" icon="fas fa-download" %}}macOS{{% /button %}} {{% button href="/clients/install_linux" icon="fas fa-download" %}}Linux{{% /button %}}

Nach einer Desktop-Installation ist darauf zu achten, Deinen bestehenden Account mit dem DARC-Login zu nutzen, und keinen neuen Account auf einem anderen Server zu erstellen. Hier am Beispiel von Element:

![Markierter Anmeldebutton im Element Matrixclient](/images/01_Login_de.png)

Dies wird durch Klick auf **Ändern** realisiert. Dann landest du nicht versehentlich auf einem falschen Server...

![Anmeldeseite mit Fokus auf dem Homeserver ändern Button](/images/02_Change-Homeserver_de.png)

Nun kann man manuell die Angabe des Heimservers durchführen: darc.de

![Eingabefeld zum Ändern des Homeservers mit der Eingabe darc.de](/images/03_Set-Homeserver_de.png)

Anschließend ist der einmalige Login mit dem DARC-Login durchzuführen:
"Mit DARC Anmeldung fortfahren" bestätigen. Dann sind folgende Eingaben, auf der sich öffnenden Seite zu tätigen:

**Rufz./Mitgliedsnummer: Rufzeichen/Mitgliedsnummer**  (keine E-Mail-Adresse!)

**Passwort: Passwort das in der Mitgliederverwaltung gesetzt wurde**

Ein alternativer Login, bspw. über die E-Mail-Adresse ist **nicht** möglich.

Es folgt nach dem Erstlogin auch keine E-Mail / Bestätigungsmail.

Um jeden Nutzer die Möglich zu geben, einen eigenen Anzeigenamen zu setzten, wird der technische Nutzername bestehend aus 5 zufälligen Zeichen automatisch festgelegt:

@5ZUFALLSZEICHEN:darc.de (Beispiel: @6472k:darc.de)

![Loginfenster mit Aufforderung DARC Login und Passwort einzugeben](/images/04_Username_de.png)

## Bequemes Nutzen der Ende-zu-Ende-Verschlüsselung (E2EE)

Matrix verschlüsselt nicht nur die Transporte von und zu dem Heimserver (betrieben vom DARC) sondern erlaubt auch dir die Nutzung von Ende-zu-Ende-Verschlüsselung (E2EE). Hierzu müssen kryptografische Schlüssel zwischen allen Geräten ausgetauscht werden, die sich Ende-zu-Ende-verschlüsselt schreiben möchten. Obwohl diese technische Notwendigkeit kompliziert klingt und im Hintergrund auch ist, ist sie inzwischen für dich als Anwender sehr bequem geworden. Die vielen kryptografischen Schlüssel werden vom Client erstellt auf dem jeweiligen Gerät gespeichert. Sollte dies bspw. ein Tab in einem Browser sein, besteht die Gefahr, dass dieser Tab einmal unbeabsichtigt geschlossen wird. Dann sind **alle verschlüsselten Inhalte nicht mehr lesbar**. Damit das nicht bei dir geschieht, wird eine Schlüsselsicherung auf dem Heimserver angeboten, auf der (mit einer Sicherheitsphrase (bzw. daraus errechenbaren Sicherheitsschlüssel) geschützt) alle kryptografischen Schlüssel verschlüsselt abgelegt sind.

{{% notice info %}}
Es wird dringend empfohlen, die Schlüsselsicherung zu nutzen (mit einer sicheren Sicherheitsphrase, welches **nicht** Dein DARC-Passwort ist)!
{{% /notice %}}

![Aufforderung den Sicherheitsschlüssel zu generieren oder eine Sicherheitsphrase einzugeben](/images/11_Setup-Key_de.png)
![Aufforderung eine Passwort für die Schlüsselsicherung einzugeben](/images/12_Enter-Key_de.png)
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

