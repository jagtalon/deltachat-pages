---
title: Chatmail für schnelle, interoperable und private Nachrichtenübermittlung
lang: de
---


## Was sind Chatmail-Server?

<img alt="Chatmail logo" src="../assets/logos/chatmail.svg" width="160" style="float:right;" />

Chatmail-Server sind für Delta Chat optimiert, und bieten bequemen, datenschutzfreundlichen und schnellen Nachrichtenaustausch.

Das Delta-Chat-Projekt betreibt den standardmäßig verwendeten, offenen Chatmail-Server [nine.testrun.org](https://nine.testrun.org)
der seit der [Chatmail Ankündigung im Dezember 2023](https://delta.chat/en/2023-12-13-chatmail) stabil ist.

Weitere, von der **Community betriebene Chatmail-Server - zum Verwenden antippen:**

- [mehl.cloud](https://mehl.cloud) ist auf deutschsprachige Nutzer ausgerichtet und ist seit Januar 2024 stabil.

- [mailchat.pl](https://mailchat.pl) ist auf Polnisch sprechende Nutzer ausgerichtet und ist seit Januar 2024 stabil.

- [bcc.chat](https://bcc.chat) wird in den USA betrieben und ist seit Februar 2024 stabil.

Alle Chatmail-Server sind untereinander vollständig und sicher interoperabel und bieten Push-Benachrichtigungen für mobile Nutzer.


## Was sind die Unterschiede zwischen Chatmail- und E-Mail-Servern?

Chatmail-Server sind minimale E-Mail-Server, die auf Geschwindigkeit, Sicherheit und Komfort ausgelegt sind:

- **Komfort:** Sie bekommen ein Profil In wenigen Sekunden automatisch und erhalten Push-Benachrichtigungen

- **Datenschutz:** Keine Fragen, keine Namen, Nummern oder E-Mail-Adressen erforderlich

- **Geschwindigkeit:** Nachrichtenzustellung in deutlich unter einer Sekunde, Ende-zu-Ende

- **Zuverlässigkeit:** Keine lästigen Spam-Prüfungen oder Limits

- **Sicherheit:** Ausgehende Nachrichten müssen Ende-zu-Ende verschlüsselt sein, eingehende Nachrichten werden streng auf ihre Authentizität geprüft.


## Kann ich auch einen regulären E-Mail-Server verwenden?

Ja, viele Benutzer verwenden erfolgreich reguläre E-Mail-Server, vor allem, wenn sie ihre regelmäßige E-Mail-Kommunikation mit Delta Chat abwickeln wollen.
Die [Anbieterdatenbank](https://providers.delta.chat) zeigt Optionen auf.
Beachten Sie, dass Delta Chat mehrere Konten unterstützt:
Es ist also in Ordnung, ein Konto mit Ihrer regulären E-Mail-Adresse zu haben, und ein weiteres Konto zum Chatten.


## Wie vertrauenswürdig sind Chatmail-Server?

Jeder Chatmail-Server bietet zusätzliche Informationen zum Datenschutz auf seiner Webseite.
Normalerweise verarbeitet ein Chatmail-Server nur verschlüsselte Nachrichten und
implementiert eine automatische, bedingungslose Löschung der Nachrichten nach höchstens 40 Tagen.

Delta Chat bietet [garantierte Ende-zu-Ende-Verschlüsselung](https://delta.chat/en/2023-11-23-jumbo-42)
was bedeutet, dass in den meisten Anwendungsfällen die Serverbetreiber Ihre Nachrichten nicht lesen können, selbst wenn sie es versuchen.
Eine Garantie, die durch eine aktuelle [Sicherheitsanalyse der ETH Zürich](https://delta.chat/en/2024-03-25-crypto-analysis-securejoin) bestätigt wird.


## Wie werden Chatmail-Server betrieben?

Alle Chatmail-Server werden automatisch aktualisiert mit dem [öffentlichen Chatmail-Entwicklungs-Repository](https://github.com/deltachat/chatmail).
Chatmail-Server bestehen aus bewährten Standard-E-Mail-Server-Komponenten, [Postfix](https://postfix.org) und [Dovecot](https://dovecot.org), und sind so konfiguriert, dass sie unbeaufsichtigt laufen und sehr wenig Wartungsaufwand erfordern. Chatmail-Server funktionieren auch gut auf Low-End-Hardware wie einem Raspberry Pi.


# Wie werden Chatmail-Server finanziert?

Chatmail-Server sind so konzipiert, dass sie sehr billig zu betreiben sind und sie werden im Allgemeinen von den Betreibern selbst finanziert. Weitere Informationen finden Sie auf der Startseite des jeweiligen Chatmail-Servers.

Um die Chatmail-Entwicklung und den Betrieb des Standard-Onboarding-Servers zu unterstützen, sind Sie herzlich eingeladen, einen Beitrag zu leisten.

[Geld spenden](donate){: .cta-button}