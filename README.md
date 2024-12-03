# Projekttitel: Kundensegmentierung im Elektronikhandel mithilfe der RFM-Analyse

## Projektübersicht
Dieses Projekt untersucht die Kundensegmentierung eines Elektronikhandels anhand von Datenanalysen und maschinellen Lernmethoden. Ziel ist es, Kundensegmente zu identifizieren, um personalisierte Marketingmaßnahmen zu entwickeln und die Kundenbindung zu stärken. Der Datensatz wurde synthetisch erstellt, um reale Szenarien zu simulieren.

---

## Motivation
Eine effektive Kundensegmentierung hilft:
- **Marketingressourcen gezielter einzusetzen** und Streuverluste zu minimieren.
- **Kundenbindung zu stärken**, indem Maßnahmen individuell angepasst werden.
- **Umsätze nachhaltig zu steigern**, durch datenbasierte Entscheidungen.
- **Markenloyalität zu fördern**, indem Kundensegmente besser verstanden werden.

---

## Verwendete Analysemethoden
1. **RFM-Analyse:**
   - **R (Recency):** Zeit seit dem letzten Kauf.
   - **F (Frequency):** Anzahl der Käufe pro Kunde.
   - **M (Monetary Value):** Gesamtausgaben pro Kunde.

2. **KMeans-Clustering:**
   - Bestimmung der optimalen Cluster-Anzahl mit der **Elbow-Methode** und dem **Silhouette-Score**.
   - Bildung von vier Clustern basierend auf RFM-Werten.

3. **Zusätzliche Segmentierung:**
   - Innerhalb der Cluster wurden die Kunden nach **Kanalpräferenzen** und **Rabattnutzung** weiter segmentiert.

4. **Ausreißer-Analyse:**
   - Identifikation und Behandlung von Ausreißern im Bereich Frequency und Monetary Value mit der IQR-Methode.

---

## Ergebnisse
### Kundensegmente
1. **Cluster 1 (hoher Monetary Value, niedrige Frequency):**
   - Ziel: Erhöhung des Kundenwerts durch Zubehörangebote und Premium-Services.
   - Marketingstrategie: Cross-Selling und Erweiterung des Serviceangebots.

2. **Cluster 2 (hoher Monetary Value, hohe Frequency):**
   - Ziel: Förderung von Käufen weiterer langlebiger Güter.
   - Marketingstrategie: Rabattaktionen, Treueprogramme und Bundles.

3. **Cluster 0 + 3 (kombiniert):**
   - Ziel: Aktivierung durch Einstiegskampagnen.
   - Marketingstrategie: Promotions für kleinere Produkte und Cross-Selling.

4. **Monetary Value-Ausreißer:**
   - Ziel: Sicherung langfristiger Loyalität.
   - Marketingstrategie: Exklusive Vorteile, Premium-Loyalitätsprogramme und personalisierte Kommunikation.

---

## Technologien
- **Programmiersprache:** Python
- **Analyseumgebung:** Jupyter Lab
- **Bibliotheken:** 
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## Inhalte des Repositories
1. **/data:** Der synthetische Datensatz (CSV-Format).
2. **/notebooks:** Python-Notebooks für die RFM-Analyse, Clustering und Visualisierungen.
3. **/results:** PowerPoint-Präsentation mit den Ergebnissen.

---

## Weiterführende Analysen
Zur Generierung weiterer Erkenntnisse könnten folgende Analysen durchgeführt werden:
- **Customer Lifetime Value (CLV):** Analyse der langfristigen Kundenprofitabilität.
- **Sentiment-Analyse:** Identifikation emotionaler Bindung durch Kundenfeedback.
- **Kundenabwanderungsanalyse (Churn Prediction):** Proaktive Maßnahmen zur Kundenbindung.

---

## Fazit
„Unser Ziel ist ein erstklassiges Kundenerlebnis, das durch datenbasierte Entscheidungen und individuelle Maßnahmen die Kundenbindung stärkt und die Loyalität fördert.“

---

### Kontakt
- [oezdemir.emrah@gmx.de]
- [https://github.com/emrah-oe]
