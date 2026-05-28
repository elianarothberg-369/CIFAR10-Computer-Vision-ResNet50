# CIFAR10-Computer-Vision-ResNet50

# Computer-Vision-Projekt zur Bildklassifikation mit CIFAR-10 unter Verwendung von Transfer Learning und ResNet50.

⸻

## Projektübersicht

Dieses Projekt untersucht den Einsatz moderner Deep-Learning-Methoden zur Bildklassifikation mit dem CIFAR-10-Datensatz.

Der Fokus lag auf der Entwicklung eines vollständigen Computer-Vision-Workflows – von der Datenvorbereitung über das Modelltraining bis hin zur Evaluation und Interpretation der Ergebnisse.

Als Basisarchitektur wurde das vortrainierte ResNet50-Modell verwendet, um Transfer Learning im Bereich Computer Vision praktisch umzusetzen.

⸻

### Projektziel

Ziel des Projekts war die Entwicklung eines Deep-Learning-Modells zur automatischen Klassifikation von Bildern aus dem CIFAR-10-Datensatz in zehn verschiedene Klassen.

Zusätzlich sollte untersucht werden:

•⁠  ⁠wie effektiv Transfer Learning mit ResNet50 funktioniert

•⁠  ⁠welche Herausforderungen kleine Bilddatensätze mit sich bringen

•⁠  ⁠wie Accuracy, Loss und Fehlklassifikationen interpretiert werden können

⸻
### Colab Notebook

🔗 Colab Notebook öffnen:

https://colab.research.google.com/drive/18wl2qTXyyZxRoiCTch9uLMzLy9M31k8H?usp=sharing

⸻
### Präsentation (PPT)

🔗 Präsentation öffnen

https://1drv.ms/p/c/90db5a923eed8ffe/IQCoBUkjohmwS6RuEMmjgZloAe1VLN9MYgOAvMAZHqMRo9o

⸻
### Executive Summary

🔗 Executive Summary PDF öffnen

https://drive.google.com/file/d/13YBIqn4b_w2VCj1Ht5Nceiu8CHwSwiBX/view?usp=sharing

⸻

### Verwendeter Datensatz

Der CIFAR-10-Datensatz enthält:

•⁠  ⁠60.000 RGB-Bilder

•⁠  ⁠10 verschiedene Klassen

•⁠  ⁠Bildauflösung: 32 × 32 Pixel

Klassen:

•⁠  ⁠Airplane

•⁠  ⁠Automobile

•⁠  ⁠Bird

•⁠  ⁠Cat

•⁠  ⁠Deer

•⁠  ⁠Dog

•⁠  ⁠Frog

•⁠  ⁠Horse

•⁠  ⁠Ship

•⁠  ⁠Truck

⸻

### Verwendete Technologien

•⁠  ⁠Python

•⁠  ⁠TensorFlow / Keras

•⁠  ⁠NumPy

•⁠  ⁠Matplotlib

•⁠  ⁠Scikit-learn

•⁠  ⁠Google Colab

•⁠  ⁠GitHub

⸻

### Projektworkflow

Der Workflow des Projekts umfasste:

•⁠  ⁠Laden und Vorverarbeitung der Bilddaten

•⁠  ⁠Datenexploration und Visualisierung

•⁠  ⁠Transfer Learning mit ResNet50

•⁠  ⁠Data Augmentation

•⁠  ⁠Modelltraining und Validierung

•⁠  ⁠Vorhersageanalyse

•⁠  ⁠Confusion Matrix

•⁠  ⁠Classification Report

•⁠  ⁠Accuracy- und Loss-Analyse

•⁠  ⁠Ergebnisinterpretation

⸻

### Modellentwicklung

Für die Bildklassifikation wurde ResNet50 als vortrainiertes Convolutional Neural Network verwendet.

Die ursprüngliche Klassifikationsschicht wurde entfernt und durch eigene Dense-Layer ersetzt, um die zehn CIFAR-10-Klassen vorherzusagen.

Zusätzlich wurden Data-Augmentation-Techniken eingesetzt, darunter:

•⁠  ⁠horizontales Spiegeln

•⁠  ⁠Rotation

•⁠  ⁠Zoom

•⁠  ⁠Bildskalierung

Dadurch sollte die Generalisierungsfähigkeit des Modells verbessert werden.

⸻

### Ergebnisse

Das Modell erreichte:

•⁠  ⁠Trainingsgenauigkeit: ca. 98–99 %

•⁠  ⁠Validierungsgenauigkeit: ca. 60 %

Die Ergebnisse zeigen typische Overfitting-Effekte:

Das Modell lernte die Trainingsdaten sehr gut, konnte dieses Wissen jedoch nur eingeschränkt auf unbekannte Testdaten übertragen.

Besonders gut erkannt wurden Klassen wie:

•⁠  ⁠Ship

•⁠  ⁠Truck

•⁠  ⁠Airplane

Schwierigkeiten traten insbesondere bei visuell ähnlichen Tierklassen auf.

⸻

### Evaluation

Zur Bewertung der Modellleistung wurden folgende Methoden verwendet:

•⁠  ⁠Accuracy- und Loss-Plots

•⁠  ⁠Confusion Matrix

•⁠  ⁠Classification Report

•⁠  ⁠Beispielvorhersagen

Die Visualisierungen halfen dabei, Fehlklassifikationen und Overfitting sichtbar zu machen.

⸻

### Herausforderungen

Eine der größten Herausforderungen war die geringe Bildauflösung des CIFAR-10-Datensatzes.

Durch die kleinen 32×32-Pixel-Bilder gehen wichtige visuelle Details verloren, wodurch ähnliche Klassen schwerer zu unterscheiden sind.

Zusätzlich stellte Overfitting eine zentrale Herausforderung während des Trainingsprozesses dar.

⸻

### Fazit

Das Projekt demonstriert erfolgreich einen vollständigen Computer-Vision-Workflow mit TensorFlow, Keras und ResNet50.

Neben der technischen Umsetzung vermittelte das Projekt wertvolle praktische Erfahrungen in den Bereichen:

•⁠  ⁠Computer Vision

•⁠  ⁠Transfer Learning

•⁠  ⁠Modelltraining

•⁠  ⁠Evaluationsmetriken
•⁠  ⁠Ergebnisinterpretation

Das Projekt bildet eine solide Grundlage für zukünftige Verbesserungen wie Fine-Tuning, stärkere Regularisierung oder größere Datensätze.
