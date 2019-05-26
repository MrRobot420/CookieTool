Readme-Datei für "<Cookle>:" 
---------------------------

##########################################################################################
############################	W I C H T I G  ! ! !	##################################
##########################################################################################


Um das Programm problemlos ausführen zu können, muss zunächst ein Pfad im Programmcode angepasst werden.


In der Datei: "backend.py"
In Zeile 16: ROOT_DIR = "/YOUR-PATH/..."


##########################################################################################


Um das Programm ausführen zu können, müssen die folgenden Module installiert sein:

* Python Version 3.6.6 	(oder höher)
* tkinter		(wird automatisch mit python 3.6.6 installiert)
* matplotlib
* pandas
* numpy			(wird automatisch mit pandas installiert)


##########################################################################################


Das Programm kann anschließend aus der Konsole heraus gestartet werden, indem 
"python3 start_gui.py" eingegeben und ausgeführt wird. 

Der Nutzer muss sich dafür sich im entsprechenden Ordner befinden.

Der Pfad zu dem richtigen Ordner ist der folgende:

/tracking/cookies

##########################################################################################

Im Ordner befinden sich 8 Skripte, die das Analyse-Tool ergeben:

start_gui.py		# Startet das Programm.

backend.py 		# Das Backend (Zuständig für Dateizugriffe und -änderungen).

ui_menu.py		# GUI des Hauptmenüs.
ui_menu_setting.py	# GUI des Einstellungsmenüs.	(Pfad zur Datei einstellen)
ui_menu_info.py		# GUI des 1. Untermenüs.	(Generelle Informationen erhalten)
ui_menu_data.py		# GUI des 2. Untermenüs.	(Datentranformation und -visual.)
ui_menu_delete.py	# GUI des 3. Untermenüs.	(- Nicht implementiert -)

ui_group.py		# Ermöglicht gruppierte Suche nach ID, VALUE und NAME 

ui_save.py		# Ermöglicht das Transformieren von SQLITE-Dateien in das CSV-Format.
ui_report.py		# Ermöglicht die Erstellung von "Reports" im CSV-Format.
ui_visual.py		# Schnittstelle für die Visualisierung.
visualization.py	# Ermöglicht die Erstellung der Diagramme.

ui_existing.py		# Listet existierende Dateien auf. (Available Files & Available Reports)

(ui_compare.py)		# (- Hat keine Funktionalität -) -> Wurde verworfen.
