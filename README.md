# Quizbot

Dieses Projekt nutzt Natural Language Processing (NLP), um automatisch Quizfragen aus Lerntexten zu generieren. Die Anwendung richtet sich an Lehrkräfte, Studierende oder Entwickler im Bildungsbereich, die eine einfache Möglichkeit zur Quizgenerierung aus Textdokumenten benötigen.

## Projektstatus

⚠️ **Hinweis**: Dieses Projekt befindet sich noch in der Entwicklung und ist daher noch experimentell. Die derzeitige Version dient als Prototyp und ist ideal für die Nutzung in Jupyter Notebooks geeignet. Es sind Erweiterungen geplant, darunter die Verbesserung der Genauigkeit und der Schwierigkeitsklassifikation der generierten Fragen.

## Funktionsübersicht

1. **Einlesen von Lerntexten**: Die Anwendung erlaubt das Einlesen von Textinhalten, entweder direkt oder durch das Hochladen einer `.txt`-Datei.
2. **Textsegmentierung**: Der eingegebene Text wird in Abschnitte unterteilt, um spezifische Fragen zu jedem Abschnitt zu generieren.
3. **Automatische Fragegenerierung**: Ein vortrainiertes NLP-Modell erzeugt Fragen zu den einzelnen Textabschnitten.
4. **Schwierigkeitsschätzung (in Entwicklung)**: Eine zukünftige Version wird Fragen in Schwierigkeitsgrade einteilen, basierend auf Satzstruktur und Wortwahl.

## Installationsanweisungen

### Voraussetzungen

- Python 3.8 oder höher
- Jupyter Notebook
- Die folgenden Python-Bibliotheken:
  - `transformers` (für das NLP-Modell)
  - `nltk` (für die Textsegmentierung)

### Installation

1. Installieren Sie die erforderlichen Bibliotheken:
   ```bash
   pip install transformers nltk
