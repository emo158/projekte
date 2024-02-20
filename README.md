Readme-Anleitung für Countdown HTML-Seite

Diese Anleitung bietet eine Übersicht über die Verwendung der Countdown-HTML-Seite sowie die Anpassung der Countdown-Zeiten.

1. Verwendung:

Die Countdown-HTML-Seite bietet eine interaktive Countdown-Funktionalität. Sie zeigt einen Countdown bis zu einem bestimmten Datum und startet eine Konfetti-Animation, wenn dieser Zeitpunkt erreicht ist.

2. Anpassung des Countdowns:

Um den Countdown anzupassen, folgen Sie diesen Schritten:

Öffnen Sie die HTML-Datei in einem Texteditor Ihrer Wahl.
Suchen Sie nach der Zeile 116 im <script>-Abschnitt:

const targetDate = new Date("2024-02-21T21:54:39").getTime();

Ändern Sie das Datum und die Uhrzeit auf ein zukünftiges Datum und eine zukünftige Uhrzeit Ihrer Wahl. Verwenden Sie das Format "YYYY-MM-DDTHH:MM:SS", wobei YYYY für das Jahr, MM für den Monat, DD für den Tag, HH für die Stunde, MM für die Minuten und SS für die Sekunden steht. Stellen Sie sicher, dass das Datum in der Zukunft liegt.
3. Anpassung nach dem Countdown:

Um die Aktion nach dem Countdown abzustimmen, bearbeiten Sie erneut die Zeile 116 im <script>-Abschnitt:

const targetDate = new Date("2024-02-21T21:54:39").getTime();

Diesmal ändern Sie das Datum und die Uhrzeit auf ein vergangenes Datum und eine vergangene Uhrzeit Ihrer Wahl. Stellen Sie sicher, dass das Datum in der Vergangenheit liegt.

4. Speichern und Öffnen:

Speichern Sie die Änderungen in der HTML-Datei und öffnen Sie sie in einem Webbrowser Ihrer Wahl, um den aktualisierten Countdown und die Konfetti-Animation zu sehen.

Das ist alles! Sie haben nun erfolgreich den Countdown und die Konfetti-Animation auf dieser HTML-Seite angepasst und können sie nach Ihren Vorstellungen verwenden. Bei Fragen oder Problemen können Sie sich gerne an den Entwickler wenden. Viel Spaß beim Nutzen der Countdown-HTML-Seite!
