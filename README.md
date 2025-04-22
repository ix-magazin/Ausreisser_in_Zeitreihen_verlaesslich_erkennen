# Ausreisser_in_Zeitreihen_verlaesslich_erkennen
Jupyter-Notebook zum [Praxis-Artikel](https://www.heise.de/select/ix/2025/6/2504413533007263934) von Dr. Roland Pleger, erschienen in [iX 06/2025](https://www.heise.de/select/ix/2025/6) und auf [heise online](https://www.heise.de/plus).

# iX-tract
- Ausreißer in Zeitreihen sind besonders gemein, wenn die fehlerhaften Werte im erwartbaren Bereich liegen, aber eben zur falschen Zeit auftauchen.
- Im Graph ist das mit bloßem Auge zu erkennen, Algorithmen zur Fehlersuche tun sich bei der genauen Erkennung jedoch manchmal schwer.
- Gängige Verfahren wie HDBSCAN, Local Outlier Factor (LOF) und Saison-Trend-Zerlegung mit LOESS (STL) erzielen brauchbare Ergebnisse, haben jedoch individuelle Stolperfallen.
- Der unkonventionelle Einsatz von LOF anstelle von Z-Score bei der Analyse des Residuums von STL bringt einen deutlichen Qualitätsgewinn.
