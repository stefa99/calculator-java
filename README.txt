LOC za kompletan projekat iznosi 235 (188 calculator.java,21 LICENSE,26 Start.java).
Ciklomatska slozenost metoda evaluateExpression i Calculate iznosi 12.
Kognitivna slozenos je izmedju 13 i 14,14 pripada calculate metodi koja je nesto teza za razumevanje 
Staticka analiza fajla Calculator java koristeci Sonarlint:
 fajla Calculator.Java
Pronadjene code smell mogucih izmena koje bi doprinele boljoj operaciji koda 
Ln4,Col14 - Moguce je dodati privatni konstruktor da bi sakrili implicitni javni (public).
Ln18,Col30 - Metoda "ToString" bi se trebala izmeniti u "toString" kako bi izbegli nesporazum(clash)
Ln24,Col26 - isto Treba promenuti metodu "Run" u "run"
Ln 183,Col13-moze da se ukloni 
 fajla Start.java
Ln6,Col10 - "Expression" treba promeniti u "expression"
Ln19,Col5 i Ln8,Col3 oboje sadrze Major code smell gde je potrebno "System.out" zamenuti logger.kako bi se povratak informacija cuvanje i bezbednos bili ispostovani 

