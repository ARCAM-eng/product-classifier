# Product Classifier

Acest proiect rezolvă sarcina de **clasificare automată a produselor** în categorii pe baza titlului (`Product Title`) și a unor caracteristici numerice simple extrase din text.

## Conținutul proiectului
- `product_classifier.ipynb` – notebook complet, care conține:
  - analiza și curățarea datelor,
  - ingineria caracteristicilor,
  - antrenarea și compararea mai multor modele,
  - alegerea modelului final,
  - salvarea modelului `.pkl`,
  - testare pe exemple predefinite și testare interactivă.
- `product_classifier.pkl` – modelul antrenat și salvat (generat după rularea notebook-ului).
- `IMLP4-TASK_03-products.csv` – setul de date.

## Cum se folosește

1. Asigură-te că fișierul CSV este în același folder cu notebook-ul:
   ```
   IMLP4-TASK_03-products.csv
   product_classifier.ipynb
   ```

2. Deschide și rulează notebook-ul:
   ```
   jupyter notebook product_classifier.ipynb
   ```

3. Modelul va fi salvat ca:
   ```
   product_classifier.pkl
   ```

## Testare
- În notebook există o secțiune unde poți introduce manual titlul unui produs:
  ```
  Introdu titlul produsului (sau 'exit' pentru a ieși): iphone 7 32gb gold
  ```


## Organizare pentru GitHub

product-classifier/
├── product_classifier.ipynb
├── IMLP4-TASK_03-products.csv   # dacă vrei, îl poți exclude
├── product_classifier.pkl
├── README.md

