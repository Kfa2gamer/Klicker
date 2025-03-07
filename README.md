Clicker Farm Game

Ein einfaches Browser-Clicker-Spiel, bei dem du Ressourcen sammelst, Gebäude und Upgrades kaufst und so deine Farm und Produktion immer weiter ausbaust. Dieses Projekt zeigt exemplarisch, wie man HTML, CSS und JavaScript kombiniert, um ein unterhaltsames Clicker-Spiel zu erstellen.

Features

Mehrere Ressourcentypen: Mais, Holz, Stein, Wasser, Weizen, Brot, Gold und Planken.
Klick-Mechanik: Klicke auf Blöcke (z. B. Maiskolben, Baum, Stein) und erhalte Ressourcen.
Automatisierungen:
Farmen produzieren passiv Mais, Holz und Stein.
Arbeiter können Ressourcen sammeln, verbrauchen dafür jedoch Brot.
Ein Brunnen produziert automatisch Wasser, sobald er gebaut ist.
Forschungen: Erforsche Upgrades, die z. B. das Nachwachsen von Ressourcen beschleunigen oder die Erntemenge erhöhen.
Shops und Handel: Tausche Ressourcen gegen Gold, kaufe neue Gebäude und Werkzeuge.
Offline-Progess: Bei erneutem Laden des Spiels werden die gesammelten Ressourcen in der Zwischenzeit anhand der verstrichenen Zeit hochgerechnet.
Autosave: Alle paar Sekunden wird automatisch im localStorage gespeichert. Ein manueller Reset ist ebenfalls möglich.
Voraussetzungen

Ein moderner Browser (Chrome, Firefox, Safari, Edge).
Keine Installation von Datenbanken oder Servern notwendig – das Spiel läuft komplett clientseitig.
Installation

Repository klonen oder herunterladen
Lade das ZIP herunter oder führe git clone <repository-url> aus.
Datei öffnen
Öffne die index.html (bzw. den Dateinamen, den du gewählt hast) im Browser.
Losklicken
Das Spiel startet sofort, und du kannst deine ersten Ressourcen sammeln.
Aufbau

index.html
Enthält den kompletten HTML-Aufbau, inkl. der <div>-Container für jede Ressourcenseite (Mais, Holz, Stein, Wasser, Weizen, Brot, Farm, Arbeiter).
Außerdem sind im <script>-Abschnitt sämtliche JavaScript-Funktionen untergebracht (Ressourcenverwaltung, Klick-Handler, automatische Produktion, Forschung usw.).
CSS (im <style>-Tag)
Definiert das grundlegende Layout, z. B. das Menü, die Container sowie die Hintergründe (Maisfeld, Wald, Steinbruch usw.).
JavaScript
Verwaltung der Ressourcen und Upgrades.
Event-Listener für Buttons (z. B. „Mais tauschen“, „Brunnen bauen“, „Forschung starten“).
localStorage-Speicherung und Laden des Spielstands.
Nutzung

Seiten-Navigation:
Klicke im oberen Menü (Mais, Holz, Stein, Wasser, etc.), um zwischen den Bereichen zu wechseln.
In jedem Bereich gibt es weitere Unterseiten (Feld, Shop, Forschung …).
Ressourcen sammeln:
Klicke auf das entsprechende Symbol (🌽, 🌳, 🪨, 💧, …), um Ressourcen zu bekommen.
Beachte: Manche Ressourcen (z. B. Holz, Stein) erfordern zuerst den Kauf eines Werkzeugs (Axt bzw. Pickel).
Upgrades und Forschung:
Investiere Gold, Holz, Stein und weitere Ressourcen in Upgrades, die deine Klick- oder Produktionsraten erhöhen.
Erforsche z. B. schnelleres Nachwachsen oder höhere Erträge.
Farm und Arbeiter:
Baue Farmen, die passiv Ressourcen produzieren.
Stelle Arbeiter ein, um die Produktion zu steigern. Diese verbrauchen jedoch Brot, also solltest du gleichzeitig deine Brotproduktion ausbauen.
Speichern und Laden:
Das Spiel speichert sich automatisch im Browser-localStorage.
Mit „Spiel zurücksetzen“ kannst du den Spielstand löschen und neu anfangen.
Anpassungen

Du kannst leicht neue Gebäude, Forschungen oder Ressourcen hinzufügen, indem du weitere Funktionen und HTML-Elemente einfügst.
Das Balancing (z. B. Kosten, Produktionsraten) lässt sich durch Anpassen der JavaScript-Variablen steuern.
Bekannte Probleme / To-Do

Noch kein responsives Layout für sehr kleine Bildschirme.
Balancing kann bei großen Zahlen ungenau werden.
Eventuell könnten weitere Komfortfunktionen (Tooltipps, Fortschrittsbalken etc.) ergänzt werden.
Lizenz

Dieses Projekt dient als Beispiel und Lernressource. Du kannst es frei nutzen, verändern und weitergeben (MIT-Lizenz oder ähnlich). Bitte beachte jedoch, dass externe Assets (Bilder, Placeholder-Links) abweichen oder lizenzierte Inhalte enthalten können.

Viel Spaß beim Ausprobieren und Weiterentwickeln!
