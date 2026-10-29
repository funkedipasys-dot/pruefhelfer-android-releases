# GINO Prüfhelfer Android — Downloads

Hier liegt ausschließlich die fertige App als APK. Der Quellcode ist nicht
öffentlich.

**Neueste Version:** [Releases → Latest](https://github.com/funkedipasys-dot/pruefhelfer-android-releases/releases/latest)
— dort die Datei `pruefhelfer.apk` herunterladen.

## Wofür das gedacht ist

Ein Mikrofon-Knopf, der über der GTÜ-FSD-App schwebt. Drücken, Befund
einsprechen, loslassen. Die Aufnahme geht an GINO, die Chrome-Erweiterung
zeigt Transkript und Vorschlag zur Akte. Aufgenommen wird nur, solange der
Knopf gedrückt ist, und was im Prüfbericht steht, entscheidet der Prüfer.

## Diese Fassung braucht einen GINO-Zugang

Die App wird einmalig mit dem GINO-Konto gekoppelt (Büronummer, Prüfernummer
und PIN).
Ohne GINO-Zugang kommt man über die Kopplung nicht hinaus.

## Installieren

1. `pruefhelfer.apk` auf dem Handy herunterladen und antippen.
2. Android fragt, ob der Browser (oder der Dateimanager) Apps installieren
   darf: einmal **erlauben**.
3. Nach dem ersten Start fragt die App nach zwei Berechtigungen:
   **Mikrofon** und **Über anderen Apps einblenden**. Beide werden gebraucht,
   sonst erscheint der Knopf nicht über der FSD-App.

**Update:** neue `pruefhelfer.apk` einfach drüber installieren. Kopplung und
Notizen bleiben erhalten.

**Wichtig:** War vorher eine Testfassung installiert, die nicht von hier
stammt, verweigert Android das Update mit „App nicht installiert". Dann die
alte App einmal deinstallieren und neu koppeln.

## Echtheit prüfen

Jede Version hier ist mit demselben Schlüssel signiert. SHA-256 des
Zertifikats:

```
7A:07:DA:8A:CB:8F:07:87:33:BC:EE:59:88:1A:1F:EA:21:B2:98:51:80:F2:21:F5:AC:64:47:04:D5:8F:E5:17
```

Die Prüfsumme der jeweiligen APK steht in den Notizen zum Release.
