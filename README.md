# Movie Recommender

# Introduzione

L'obiettivo del progetto è quello di consigliare film ad utenti tramite la predizione del rating dei film.

L'obiettivo viene perseguito tramite l'utilizzo di un albero decisionale, sulla base delle caratteristiche del film e della tipologia di utente.

# Directory

dataset: contiene i dati relativi ai film e agli utenti:
 - stopwords: File contenente parole da eliminare nella sinossi dei film, al fine di lasciare le più rilevanti
 - imdb_top_1000: File contenente dati su 1000 film
 - movies2: File contenente dati su 1682 film
 - users: File contenente dati sugli utenti
 - usersmovies: File contenente dati che associano un rating dato dagli utenti ai film

documentazione:
- Report_Progetto_MR: contiene la documentazione del progetto

ml_pipeline: contiene il codice sul progetto opportunamente diviso in sezioni:
- Movie_Recommender_Clustering: codice relativo all'algoritmo di clustering (utile per visualizzare commit e modifiche al codice)
- Movie_Recommender_DecisionTree: codice relativo all'algoritmo di classificazione (utile per visualizzare commit e modifiche al codice)
- Movie_Recommender: elaborato finale
