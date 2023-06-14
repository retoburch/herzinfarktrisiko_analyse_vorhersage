# Herzinfarktrisiko Analyse und Vorhersage

Kardiovaskuläre Erkrankungen sind weltweit die häufigste Todesursache. Sie machen mit rund 18 Millionen Sterbefälle 32% aller Todesfälle aus. Mehr als 4 von 5 Sterbefälle sind davon auf Herzinfarkte zurückzuführen ([1]( https://www.who.int/health-topics/cardiovascular-diseases/#tab=tab_1)). Alleine in Deutschland erleiden jährlich über 300.000 Menschen einen Herzinfarkt([2]( https://www.herzstiftung.de/infos-zu-herzerkrankungen/herzinfarkt)).

Gleichzeitig befindet sich das Gesundheitswesen in einer digitalen Transformation. Ärztinnen und Ärzte werden bei der Diagnose, Überwachung oder im OP immer mehr von Algorithmen unterstützt ([3](https://www.iks.fraunhofer.de/de/themen/kuenstliche-intelligenz/kuenstliche-intelligenz-medizin.html)). Insbesondere bei der Diagnose und der Vorhersage von Krankheiten, werden immer öfters ML oder AI eingesetzt. Vorhersagen mit Unterstützung von maschinell ermittelte Algorithmen können bereits das Herzinfarktrisiko genauer voraussagen als Ärzte ([4](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0174944)).

In dieser Analyse soll auf Basis von Patientendaten das Herzinfarktrisiko analysiert und vorhergesagt werden. Die analyseleitenden Fragen sind:
- Mit welcher Genauigkeit kann das Herzinfarktrisiko vorhergesagt werden?
- Welche Faktoren erhöhen oder senken das Risiko?
- Wie verändern die einzelnen Faktoren die Chance eines Herzinfarktes?

Dazu wird ein Datensatz mit Messwerten von 303 Patienten mittels eines ML-Models ausgewertet. Der Datensatz auf Kaggle **[Heart Attack Analysis & Prediction](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset)** basiert dabei auf dem Datensatz der **[UCI](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)**. Im Datenset sind 14 von 76 Attributen enthalten. Die Patientendaten stammen von der V.A. Medical Center, Long Beach and Cleveland Clinic Foundation.
