FaceAI to zaawansowany system oparty na sztucznej inteligencji, skoncentrowany na analizie obrazów twarzy w celu wykrywania i diagnozowania różnorodnych stanów i chorób skóry twarzy. Celem jest zapewnienie szybkiej i dokładnej metody diagnostyki, wspomagającej dermatologów i poprawiającej dostępność wysokiej jakości opieki dermatologicznej dla problemów skórnych twarzy.

Język programowania: Python

Biblioteki: TensorFlow, Keras, NumPy, Matplotlib, scikit-learn

Funkcja: Klasyfikacja chorób skóry twarzy za pomocą sieci neuronowej konwolucyjnej (CNN)

Wejście: Zbiór danych obrazów twarzy z etykietami

Wyjście: Ocena dokładności modelu, macierz pomyłek, raport klasyfikacji, wizualizacje dokładności i straty oraz przykładowe obrazy z przewidywaniami

Opis działania skryptu:

Ładowanie modelu: Skrypt zaczyna od wczytania wytrenowanych wag do modelu CNN, które osiągnęły najlepsze wyniki na danych walidacyjnych.

Ocena modelu: Model jest oceniany na zbiorze danych testowych. Wyniki oceny, w tym dokładność i strata, są wyświetlane na konsoli.

Predykcje: Na podstawie modelu wykonane są predykcje dla obrazów w zbiorze testowym. Skrypt przypisuje najbardziej prawdopodobną klasę diagnozy dla każdego obrazu.

Prawdziwe etykiety: Przygotowanie wektora prawdziwych etykiet z użyciem danych z generatora testowego.

Wizualizacja historii treningu: Prezentacja wykresów dokładności i straty dla danych treningowych i walidacyjnych, co pozwala na ocenę postępów uczenia modelu w czasie.

Macierz pomyłek: Generowanie i wyświetlanie macierzy pomyłek, co umożliwia graficzne przedstawienie wyników klasyfikacji i identyfikację klas, które są często mylone przez model.

Raport klasyfikacji: Tworzenie raportu klasyfikacji z precyzją, pełnością (recall) i wynikiem F1 dla każdej z klas diagnoz.

Przykładowe przewidywania: Wyświetlenie przykładów obrazów testowych wraz z ich prawdziwymi i przewidywanymi etykietami, co daje wgląd w skuteczność modelu.