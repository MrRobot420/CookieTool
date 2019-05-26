# CookieTool
# Readme-Datei für "<Cookle>:"
# Readme-File for "<Cookle>:" 
---------------------------

##########################################################################################
############################### 	W I C H T I G  ! ! !	 #################################
##########################################################################################
############################	I M P O R T A N T  ! ! !	##################################
##########################################################################################


[D:] Um das Programm problemlos ausführen zu können, muss zunächst ein Pfad im Programmcode angepasst werden.

[E:] To run the program without problems, one has to first adjust a path in the Code.



[D:] In der Datei: "backend.py"
     In Zeile 16: ROOT_DIR = "/YOUR-PATH/..."
     
[E:] In the file: "backend.py"
     In Line 16: ROOT_DIR = "/YOUR-PATH/..."

##########################################################################################


[D:] Um das Programm ausführen zu können, müssen die folgenden Module installiert sein:

  * Python Version 3.6.6 	(oder höher)
  * tkinter		(wird automatisch mit python 3.6.6 installiert)
  * matplotlib
  * pandas
  * numpy			(wird automatisch mit pandas installiert)
  
  
[E:] To run the program, the following modules have to be installed:

  * Python version 3.6.6 (or higher)
  * tkinter   (installs automatically with python 3.6.6)
  * matplotlib
  * pandas
  * numpy     (installs automatically with pandas)


##########################################################################################


[D:] Das Programm kann anschließend aus der Konsole heraus gestartet werden, indem 
     "python3 start_gui.py" eingegeben und ausgeführt wird. 

  Der Nutzer muss sich dafür sich im entsprechenden Ordner befinden.

  Der Pfad zu dem richtigen Ordner ist der folgende:

      /tracking/cookies
     
     
[E:] The program can be started form the console afterwards by typing and running: "python3 start_gui.py" 

  Therefore the user has to be in the correct folder.
  
  The path to the right folder is the following:
  
      /tracking/cookies
      

##########################################################################################

[D:] Im Ordner befinden sich 8 Skripte, die das Analyse-Tool ergeben:

      + start_gui.py		     # Startet das Programm.

      + backend.py 		          # Das Backend (Zuständig für Dateizugriffe und -änderungen).

      + ui_menu.py		          # GUI des Hauptmenüs.
      + ui_menu_setting.py	     # GUI des Einstellungsmenüs.	(Pfad zur Datei einstellen)
      + ui_menu_info.py		     # GUI des 1. Untermenüs.	(Generelle Informationen erhalten)
      + ui_menu_data.py		     # GUI des 2. Untermenüs.	(Datentranformation und -visual.)
      + ui_menu_delete.py	     # GUI des 3. Untermenüs.	(- Nicht implementiert -)

      + ui_group.py		          # Ermöglicht gruppierte Suche nach ID, VALUE und NAME 

      + ui_save.py		          # Ermöglicht das Transformieren von SQLITE-Dateien in das CSV-Format.
      + ui_report.py		     # Ermöglicht die Erstellung von "Reports" im CSV-Format.
      + ui_visual.py		     # Schnittstelle für die Visualisierung.
      + visualization.py	          # Ermöglicht die Erstellung der Diagramme.

      + ui_existing.py		     # Listet existierende Dateien auf. (Available Files & Available Reports)

      + (ui_compare.py)            # (- Hat keine Funktionalität -) -> Wurde verworfen.
      
      
[E:] In the folder are 8 scripts that add to the analysis-tool:

      + start_gui.py		     # Starts the program.

      + backend.py 		          # The backend (for data-access and -changes).

      + ui_menu.py		          # GUI of the main-menu.
      + ui_menu_setting.py	     # GUI of the settings-menu.	(set the path to a file)
      + ui_menu_info.py		     # GUI of the 1. sub-menu.	(get general informations)
      + ui_menu_data.py		     # GUI of the 2. sub-menu.	(datatranformation and -visual.)
      + ui_menu_delete.py	     # GUI of the 3. sub-menu.	(- not implemented -)

      + ui_group.py		          # Enables grouped search for ID, VALUE and NAME 

      + ui_save.py		          # Enables the transformation of SQLITE-files into CSV-format.
      + ui_report.py		     # Enables the creation of "reports" in CSV-format.
      + ui_visual.py		     # Interface for visualisation.
      + visualization.py	          # Enables the creation of diagrams.

      + ui_existing.py		     # Lists existing files. (Available Files & Available Reports)

      + (ui_compare.py)            # (- has no functionality -) -> was discarded.
