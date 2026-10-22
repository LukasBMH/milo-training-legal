# Datenschutzerklärung — Milo Training

**Stand: 22. Oktober 2026**

## Kurzfassung

Milo Training speichert alle Daten ausschließlich auf deinem Gerät. Die App
sendet keine Daten an einen Server — weder an uns noch an Dritte. Es gibt kein
Nutzerkonto, keine Registrierung, keine Analyse- oder Tracking-Dienste und keine
Werbung. Wer die App deinstalliert, löscht damit sämtliche Daten.

Der Rest dieses Dokuments erklärt das im Einzelnen, weil die
Datenschutz-Grundverordnung (DSGVO) es verlangt.

## 1. Verantwortlicher

Verantwortlich im Sinne von Art. 4 Nr. 7 DSGVO:

> **Lukas Ben Mangel-Hoffmann** — Milo Training
> Randstraße 1
> 22525 Hamburg
> Deutschland
>
> E-Mail: hello@milo-training.net

Ein Datenschutzbeauftragter ist nicht bestellt; die Voraussetzungen des
Art. 37 DSGVO bzw. § 38 BDSG liegen nicht vor.

## 2. Grundprinzip: Verarbeitung nur auf deinem Gerät

Milo Training ist eine reine Offline-Anwendung. Sämtliche Eingaben werden in
einer lokalen Datenbank (SQLite) im privaten, durch das Betriebssystem
geschützten Speicherbereich der App abgelegt. Diese Datenbank verlässt das
Gerät nicht.

Wir als Anbieter haben zu keinem Zeitpunkt Zugriff auf diese Daten. Wir
erfahren nicht, ob, wann und wie du die App benutzt.

## 3. Welche Daten die App auf dem Gerät speichert

Die App speichert nur, was du selbst eingibst, sowie das, was sich unmittelbar
daraus ergibt:

**Profil**
- eine zufällig erzeugte, geräteinterne Kennung (UUID) zur internen
  Datenzuordnung — sie wird auf dem Gerät erzeugt, nirgendwohin übertragen und
  lässt keinen Rückschluss auf deine Person zu
- Maßeinheiten-Einstellung (metrisch/imperial)
- Körpergewicht, sofern du es angibst
- Standard-Pausenzeit
- welche Module der App du aktiviert hast

**Training**
- selbst angelegte oder als Favorit markierte Übungen
- Trainingspläne mit Tagen, Übungs-Slots, Satz- und Wiederholungsvorgaben
  sowie deinen Notizen
- Trainingseinheiten mit Datum, Uhrzeit, Zeitzonen-Versatz, Dauer, subjektiver
  Anstrengung (RPE), Notizen und dem Körpergewicht zum Zeitpunkt der Einheit
- einzelne Sätze mit Gewicht, Wiederholungen, Distanz, Dauer und optional
  „Reps in Reserve"

**Systemeinstellungen**
- die geplanten lokalen Benachrichtigungen des Pausen-Timers

**Fehlerberichte**
- Stürzt die App ab, hält sie den technischen Fehler fest: Zeitpunkt,
  Fehlermeldung, Aufrufliste (Stack), App-Version und Betriebssystem-Version.
  Diese Berichte liegen in einer eigenen Datei auf dem Gerät, sind unter
  Einstellungen → Diagnose vollständig einsehbar und werden **nicht**
  automatisch übertragen. Es gibt keinen Absturzberichts-Dienst und keinen
  Empfänger. Du kannst einen Bericht über die Teilen-Funktion deines Geräts
  selbst weitergeben — dann entscheidest du, an wen, und siehst vorher den
  vollständigen Inhalt. Aufbewahrt werden die letzten 50 Berichte; du kannst
  sie jederzeit löschen.

Nicht erhoben werden: Name, E-Mail-Adresse, Telefonnummer, Geburtsdatum,
Adresse, Standort, Kontakte, Fotos, Kamera, Mikrofon, Werbe-ID, Geräte-ID des
Betriebssystems, IP-Adresse.

## 4. Gesundheitsbezogene Daten

Körpergewicht, Trainingsleistungen und die subjektive Anstrengung können als
Gesundheitsdaten im Sinne von Art. 4 Nr. 15 DSGVO gelten und unterliegen damit
dem besonderen Schutz des Art. 9 DSGVO.

Genau deshalb ist die App so gebaut, wie sie gebaut ist: Diese Daten werden
ausschließlich lokal auf deinem Gerät verarbeitet, allein zu dem Zweck, den du
selbst verfolgst — dein Training zu dokumentieren. Sie werden nicht übermittelt,
nicht ausgewertet, nicht zusammengeführt und nicht an Dritte weitergegeben. Wir
erhalten sie nicht.

## 5. Keine Übermittlung, keine Empfänger, keine Drittländer

Es findet keine Übermittlung personenbezogener Daten statt — weder an uns, noch
an Auftragsverarbeiter, noch an sonstige Dritte, noch in Drittländer außerhalb
der EU/des EWR. Eine automatisierte Entscheidungsfindung oder ein Profiling im
Sinne von Art. 22 DSGVO findet nicht statt.

Die Auswertungen, die die App anzeigt (etwa Fortschrittsverläufe oder
Wochenvolumen), werden vollständig auf dem Gerät berechnet.

### Sicherung und CSV-Export

Du kannst deine Daten jederzeit selbst aus der App herausgeben: als
Sicherungsdatei (JSON) oder als Tabelle (CSV). Beides erzeugt die App lokal
und übergibt die Datei nur an das Ziel, das du im Teilen-Dialog deines
Geräts auswählst — etwa deinen Cloud-Speicher, eine Mail oder ein anderes
Gerät. Wir erhalten dabei nichts. Dasselbe gilt für Fehlerberichte aus dem
Bereich „Diagnose", die du nur auf ausdrücklichen Wunsch teilst.

## 6. Berechtigungen

- **Benachrichtigungen** — nur für den Pausen-Timer während einer
  Trainingseinheit. Die Benachrichtigung wird lokal auf dem Gerät geplant und
  ausgelöst; es wird kein Push-Token erzeugt und keine Verbindung zu einem
  Push-Dienst von Apple, Google oder Expo aufgebaut. Du kannst die Berechtigung
  verweigern; die App funktioniert dann ohne akustischen Pausenhinweis
  weiter.
- **Vibration** — für die haptische Rückmeldung beim Abhaken eines Satzes.
- **Internetzugriff** — die App deklariert die Android-Berechtigung `INTERNET`,
  weil das technische Grundgerüst (React Native) sie im Standard mitbringt. Die
  App stellt damit keine Verbindungen her und überträgt keine Daten.

## 7. Speicherung auf dem Endgerät (§ 25 TDDDG)

Die App speichert Informationen in deinem Endgerät und liest sie dort aus. Das
geschieht ausschließlich, um den von dir ausdrücklich gewünschten Dienst
bereitzustellen — ohne diese Speicherung könnte die App ihren einzigen Zweck,
dein Training festzuhalten, nicht erfüllen. Die Speicherung ist damit nach
§ 25 Abs. 2 Nr. 2 TDDDG einwilligungsfrei zulässig. Zu Analyse-, Marketing- oder
Werbezwecken wird nichts gespeichert.

## 8. Speicherdauer und Löschung

Deine Daten bleiben so lange auf dem Gerät, wie du sie behältst. Eine
automatische Löschfrist gibt es nicht — bei einem Trainingstagebuch wäre sie
sinnwidrig.

Du löschst deine Daten, indem du
- einzelne Einträge, Pläne oder Einheiten in der App entfernst, oder
- die App deinstallierst. Damit wird der gesamte App-Datenbereich einschließlich
  der Datenbank vom Betriebssystem gelöscht.

Wenn du eine Geräte-Sicherung (iCloud-Backup, Google-Backup) aktiviert hast,
kann die App-Datenbank Teil dieser Sicherung sein. Für diese Sicherung sind
Apple bzw. Google verantwortlich; die Einstellung dazu triffst du in deinem
Betriebssystem, nicht in dieser App.

## 9. Rechtsgrundlage

Soweit die Verarbeitung ausschließlich lokal auf deinem Gerät und unter deiner
alleinigen Kontrolle stattfindet, verarbeiten wir keine personenbezogenen Daten
und sind insoweit auch nicht Verantwortlicher im Sinne der DSGVO.

Für den Fall, dass du uns per E-Mail kontaktierst, verarbeiten wir die von dir
mitgeteilten Angaben zur Bearbeitung deiner Anfrage. Rechtsgrundlage ist
Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an der Beantwortung von
Anfragen). Diese Nachrichten löschen wir, sobald die Anfrage erledigt ist und
keine gesetzlichen Aufbewahrungspflichten entgegenstehen.

## 10. App Stores

Der Bezug der App erfolgt über den Apple App Store bzw. Google Play. Beim
Herunterladen, Aktualisieren und Verwalten der App verarbeiten Apple und Google
personenbezogene Daten (etwa deine Store-Kennung, den Zeitpunkt des Downloads
und Geräteinformationen) in eigener Verantwortung. Darauf haben wir keinen
Einfluss. Es gelten:

- Apple: <https://www.apple.com/legal/privacy/de-ww/>
- Google: <https://policies.google.com/privacy>

Wenn du in den Systemeinstellungen deines Geräts zugestimmt hast, Absturz- und
Nutzungsdaten mit Entwicklern zu teilen, erhalten wir von Apple bzw. Google
aggregierte, nicht auf dich zurückführbare Statistiken. Du kannst das in den
Einstellungen deines Betriebssystems jederzeit abschalten.

## 11. Deine Rechte

Dir stehen gegenüber dem Verantwortlichen die folgenden Rechte zu: Auskunft
(Art. 15 DSGVO), Berichtigung (Art. 16), Löschung (Art. 17), Einschränkung der
Verarbeitung (Art. 18), Datenübertragbarkeit (Art. 20) und Widerspruch
(Art. 21).

In der Praxis übst du diese Rechte unmittelbar selbst aus: Da sämtliche Daten
nur auf deinem Gerät liegen, kannst du sie jederzeit in der App einsehen,
ändern und löschen. Eine Auskunft unsererseits müsste ergeben, dass wir keine
Daten über dich gespeichert haben.

Unabhängig davon hast du nach Art. 77 DSGVO das Recht, dich bei einer
Datenschutz-Aufsichtsbehörde zu beschweren. Zuständig ist die Behörde deines
Wohnsitzes oder unseres Sitzes:

> **Der Hamburgische Beauftragte für Datenschutz und Informationsfreiheit (HmbBfDI)**
> Ludwig-Erhard-Straße 22, 7. OG
> 20459 Hamburg
>
> E-Mail: mailbox@datenschutz.hamburg.de
> <https://datenschutz-hamburg.de>

## 12. Kinder

Die App richtet sich nicht gezielt an Kinder. Da keine Daten erhoben oder
übertragen werden, entstehen für jüngere Nutzerinnen und Nutzer keine
zusätzlichen datenschutzrechtlichen Risiken.

## 13. Änderungen dieser Erklärung

Diese Erklärung beschreibt den Stand der App zum oben genannten Datum. Sollten
künftige Versionen Funktionen enthalten, die Daten übertragen — etwa eine
Cloud-Synchronisation, ein Nutzerkonto, eine Absturzberichterstattung oder eine
Anbindung an Health Connect bzw. Apple Health —, wird diese Erklärung vorher
angepasst und die Änderung in der App kenntlich gemacht.
