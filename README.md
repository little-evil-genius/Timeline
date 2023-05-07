# Timeline 1.0
Dieses Plugin erweitert das Board um einen Zeitstrahl. Ausgewählte Gruppen können Ereignisse zur Timeline hinzufügen und diese werden in einem Zeitstrahl dargestellt.
Ereignisse vom Team werden automatisch freigeschaltet, doch Ereignisse von Usern müssen erst im Modcp freigeschaltet werden. Es kann eingestellt werden, ob User eigene Ereignisse bearbeiten und/oder löschen können. Das Team hat immer diese Möglichkeit, bei allen Ereignissen.
Auch kann entschieden werden, ob der Zeitstrahl absteigend oder aufsteigend sein soll.
Beim erstellen eines Ereignis kann man ein ganzes Datum (TT.MM.JJJJ) oder nur Monat und das Jahr oder nur eine Jahreszahl angegeben werden.
Die Monate werden innerhalb der Sprachdatei definiert, sollten eure Monate anders heißen, so könnt ihr sie dort ändern. 

# Datenbank-Änderungen
Hinzugefügte Tabellen:
- PRÄFIX_timeline

# Neue Template-Gruppe innerhalb der Design-Templates
- Zeistrahl

# Neue Templates (nicht global!)
- timeline	
- timeline_add	
- timeline_add_date	
- timeline_bit	
- timeline_edit	
- timeline_edit_date	
- timeline_modcp	
- timeline_modcp_bit	
- timeline_modcp_nav

# Template Änderungen - neue Variablen
- header - {$new_timeline_alert}
- modcp_nav_users - {$nav_timeline}

# ACP-Einstellungen - Zeitstrahl
- Erlaubte Gruppen
- Bearbeitung durch User
- Löschung durch User
- Sortierung

# Sonstiges
- Neues Stylesheet "timeline.css" in jedem Theme

# Links
- https://euerforum.de/misc.php?action=timeline
- https://euerforum.de/modcp.php?action=timeline

# Demo
  Zeitstrahl
  <img src="https://stormborn.at/plugins/timeline.png" />
  
  Maske beim Hinzufügen
  <img src="https://stormborn.at/plugins/timeline_add.png" />
  
  Team-Alert auf dem Index
  <img src="https://stormborn.at/plugins/timeline_alert.png" />
  
  Mod-CP
  <img src="https://stormborn.at/plugins/timeline_modcp.png" />
  
  Einstellungen
  <img src="https://stormborn.at/plugins/timeline_setting.png" />

Meine Quelle für das Tutorial rund um ein Timeline Code:
https://www.w3schools.com/howto/howto_css_timeline.asp
