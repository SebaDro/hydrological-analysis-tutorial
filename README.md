# GI-Projekt KI SoSe 2021 - Hydrological Analysis Tutorial

Ziel dieser Tutorial ist es, eine Data Science Umgebung in Python einzurichten und Grundlagen in der Anwendung bekannter
Data Science Bibliotheken zu erlernen. Hierzu erfolgen einige einfache Auswertungen hydrologischer Messwerte.

## Beschreibung

Das Projekt enthält ein Jupyter Notebook, das durch die Auswertung hydrologischer Zeitreihen führt. Die Teilnehmer sollen
so einen Einstieg in grundlegende Data Science Bibliotheken wie [Matplotlib](https://matplotlib.org/) und [pandas](https://pandas.pydata.org/)
finden. Für die Auswertung stellt das Projekt die Abfluss- und Niederschlagszeitreihen einiger ausgewählter Einzugsgebiete
aus dem [CAMELS-Dataset](./data/README.md) bereit. Zunächst erfolgt die Einrichtung einer Data Science Umgebung mit dem
Python Paketmanager [conda](https://docs.conda.io/). Mit eingerichteter Umgebung kann das Jupyter Notebook über die
interaktive Web-IDE [Juypter Lab](https://jupyterlab.readthedocs.io/) bearbeitet werden. Nach der schrittweisen und angeleiteten Auswertung und Visualisierung
der Datensätze, sind abschlißend einige Aufgaben zur Auswertung der Zeitreihen zu bearbeiten.

## Vorgehensweise

**1. Paketmanager conda installieren**  
Installieren Sie die den Paketmanager _conda_. Dieser kann in einer minimalen Konsolen-basierten Version als [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
installiert werden. Mit [Anaconda](https://docs.continuum.io/anaconda/install/) gibt es auch eine UI-basierte Version,
die standardmäßig bereits einige weit verbreitete Pakete beinhaltet und somit um einiges größer ist als Miniconda. Für 
den Kontext dieser LV ist Miniconda ausreichend und wird daher empfohlen.  

**2. "Getting started with conda"**  
Machen Sie sich mit der Funktionsweise und den wesentlichen conda Befehlen vertraut. Einen praktischen Einstieg, der die 
wesentlichen Funktionen von conda abdeckt, finden Sie im [Conda User Guide](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html).  

**3. GitLab Projekt herunterladen**  
Checken Sie dieses GitLab Projekt über Git aus oder laden Sie es über die Web-Oberfläche als Archiv herunter und entpacken
Sie es in einen lokalen Ordner.

**4. Conda Environment erstellen**  
Das Projekt enthält ein [environment.yml file](./environment.yml), das bereits alle benötigten Python Pakete definiert,
die für dieses Tutorial benötigt werden. Zum Erstellen der Umgebung führen Sie folgenden Befehl in der Anaconda 
Kommandozeile aus `conda env create -f environment.yml`. Die Umgebung kann anschließend mit `conda activate gi-projekt-ki`
aktiviert werden.  

**5. Jupyter Lab starten**  
Mit der Installation der conda Umgebung, haben Sie auch bereits die interaktive Web-IDE Jupyter Lab instlliert. Diese
können Sie mit der Ausführung des Befehls `jupyter lab` in der conda Kommandoziele starten. In ihrem Browser sollte sich
automatisch Jupyter Lab öffnen. Sollte dies nicht der Fall sein, zeigt Ihnen die conda Kommandozeile eine lokale URL
an, die sie in Ihren Browser kopieren können

**6. "Get started with Jupyter Notebooks"**  
Machen Sie sie mit den wesentlichen Funktionen von Jupyter Notebooks vertraut. Verwenden Sie hierfür die
[Dokumentation für Jupyter Notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html). Eine umfangreiche
[Dokumentation für Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/) gibt es auch, die Bedienung von Jupyter Lab
sollte jedoch ausreichend intuitiv sein.  

**7. Hydrological Analysis Tutorial**  
Bearbeiten Sie interaktiv das Tutorial für hydrologischen Analysen, in dem Sie das bereitgestellte [analysis-tutorial.ipynb](./analysis-tutorial.ipynb)
in Jupyter Lab öffnen. Experimentieren Sie ein wenig mit den Code-Blöcken  

**8. Eigene Analysen**  
Bearbeiten Sie abschließend die im Notebook aufgeführten Aufgaben. Hierzu ist es ggf. nützlich auch einen Blick in die 
Dokumentationen zu [pandas](https://pandas.pydata.org/docs/user_guide) und [matplotlib](https://matplotlib.org/stable/tutorials/index.html)
zu werfen.



