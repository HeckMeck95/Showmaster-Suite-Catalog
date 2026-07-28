<!--
Showmaster Suite – Launcher-Changelog-Format:
Jeder Absatz beginnt mit "## JJJJ-MM-TT" (ein Eintrag pro Update-Häppchen), neueste zuerst.
Darunter je eine Zeile pro Änderung, mit einem der drei Präfixe:
  - version: <spielId> <alte Version> -> <neue Version>   (zwei Pillen: alt rot, neu grün)
  - status:  <spielId> <neuer Status>                       (planning|work|ready, eine farbige Pille)
  - note:    <freier Text>                                  (keine Pille, einfache Zeile)

<spielId> muss zu einer Id aus games.json passen (für den Anzeigenamen) - sonst wird die Id
roh angezeigt statt eines lokalisierten Titels. Farben/Stil sind fest im App-Code hinterlegt
(dieselben wie die Status-Farben der Spielkarten), hier nicht einstellbar.

Status-Werte: planning (blau), work (gelb), ready (grün).
-->

## 2026-07-28
- version: buzzerraum 0.1.0 -> 0.2.0
- version: quizpoker 0.1.0 -> 0.2.0
- version: rankraiders 0.1.0 -> 0.2.0
- note: Remote-Gamescatalog + Added Changelog-Display in Launcher.
- note: App will now check the Remote-Gamescatalog for games, version and status.
