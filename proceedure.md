1. EDA
 - Fehlende Werte: sind ok --> extra Gruppe "Unknown"
 - Unique Werte verstehen
 - Ausreißer ?

2. Bias im Datensatz vorhanden? auf sex, race, age, workclass, native countrys bezogen? 
Umgang damit: 
    -Datenbereinigen: Oversampling (SMOTE)
    -Reweighting:
        Bias - Metriken berechnen (?)
            Equalized Odds
            Disparate Impact
        Bias - Reduktionsmetriken
        Fainess - Checks
Dafür auch die Spalte "fnlwgt": Gruppen die unterrepresäntiert werden sollen damit stäker gewichtet werden
    -hilft aber nur bedingt bei der Ausgleichung, wird oft ignoriert, das es keinen Zusammenhang zum Income gibt