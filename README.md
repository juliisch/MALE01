# MALE01
Dieses Repository enthält den Code-Teil der Studienarbeit für das Modul MALE01 Machine Learning.

In diesem Repository werden ausgewählte Methoden zur Behebung von unausgeglichenen Datensätzen sowohl auf Daten- als auch auf Modellebene auf die Machine Learning (ML) Klassifikationsmodelle Random Forest (RF), Logistische Regression (LR) und eXtreme Gradient Boosting (XGBoost) angewendet. Anschließend erfolgt eine Evaluation, bei der die Leistung und die Fairness der Modellvorhersagen miteinander verglichen werden.

In dem Ordner _input_ liegen die in diesem Projekt verwendete Daten. 
(Quelle: Fusion, C., & Cukiersk, W. Give Me Some Credit. Abgerufen am 22.04.2025 von [https//:kaggle.com/competitions/GiveMeSomeCredit](https://kaggle.com/competitions/GiveMeSomeCredit))

Der Ordner _output_ beinhaltet die durch das Notebook generierten Ausgaben, wie der Profilingreport und die Grafiken. 

### Installation

1. **Klonen Sie das Repository und wechseln Sie in das Verzeichnis**

    ```bash
    git clone git@github.com:juliisch/MALE01.git
    ```
    ```bash
    cd MALE01
    ```

2. **Bibliotheken installieren**

    Installieren Sie die benötigten Bibliotheken über die Datei `requirements.txt`.

    ```bash
    pip install -r requirements.txt
    ```

    Nach der Installation der Bibliotheken ist es erforderlich, das Programm neu zu starten, damit diese wirksam werden.

2. **Führen Sie das Notebook aus**

    Führen Sie das Notebook `MALE01_ImbalancedData_JuliaSchmid.ipynb` aus.