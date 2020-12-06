# Algorytmy-i-eksploracja-danych
Na UTP

# Labolatorium 1

Zadanie zostało ukończone w Jupyter Notebook.
Każda funkcja skryptu odpowiada za ukończenie jednego zadania.
* load_wine() - zwraca zbiór Wine (https://archive.ics.uci.edu/ml/datasets/wine) w postaci Pandas DataFrame,
* train_test_split_method(dataset) - dzieli zbiór na treningowy i testowy i zapisuje je do postaci pliku csv, nie zwraca żadnej wartości,
* dataset_analysis(dataset) - analizuje zbiór wg poniższych kryteriów:\
  • ilość wartości\
  • ilość wartości unikatowych\
  • wartość średnia w zbiorze (jeśli są wartości null – nie uwzględniaj ich)\
  • ilość wartości null\
  • wartość maksymalna\
  • wartość minimalna\
  • wartość najczęściej występująca w zbiorze\
  Przykładowy wynik wywołania:
  ![grafika](https://github.com/Kuchtek/Algorytmy-i-eksploracja-danych/blob/main/%5BAED%5DLab1/analysis_dataset.png)


# Laboratorium 2

Zadanie zostało ukończone w Jupyter Notebook.
Każda komórka odpowiada za całe zadanie lub jego podzadanie, oznaczone stosownym komentarzem.
Całość zadania znajduje się w folderze [AED]Lab2
• Zadanie 1 - pobrać i zapisać zbiór danych http://archive.ics.uci.edu/ml/machine-learning-databases/00396/Sales_Transactions_Dataset_Weekly.csv w pamięci
• Zadanie 2 - przeprowadzić analizę skupień poprzez KMeans, wygenerować etykiety, dodać do zbioru i zapisać w pliku CSV.
• Zadanie 3 - przeprowadzić analizę skupień poprzez AgglomerativeClustering i DBSCAN. Dla pierwszego zbudować dendrogram oraz heatmap (dla dowolnego zakresu), dla drugiego wykres przedstawiający przewagę algorytmu nad KMeans (lepsze dopasowanie próbek),
• Zadanie 4 - przeprowadzić analizę optymalnej ilości skupień dla wymienionych wyżej algorytmów. Dla DBSCAN nie przeprowadza się takiej analizy, bo algorytm sam znajduje optymalną liczbę zbiorów.

Przykładowe obrazki analizy:
• KMEANS
![grafika](https://github.com/Kuchtek/Algorytmy-i-eksploracja-danych/blob/main/%5BAED%5DLab2/kmeans.png)
![grafika](https://github.com/Kuchtek/Algorytmy-i-eksploracja-danych/blob/main/%5BAED%5DLab2/clusters_analysis_kmeans.png)
• Agglomerative Clustering
![grafika](https://github.com/Kuchtek/Algorytmy-i-eksploracja-danych/blob/main/%5BAED%5DLab2/dendrogram.png)
• DBSCAN
![grafika](https://github.com/Kuchtek/Algorytmy-i-eksploracja-danych/blob/main/%5BAED%5DLab2/dbscan.png)

