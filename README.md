# ML-NN-Weather-Forecast

Ten projekt miał na celu przewidywanie warunków pogodowych za pomocą historycznych danych pogodowych pobranych z Kaggle. Zbiór danych obejmiał informacje pogodowe dla kilku miast, głównie w Stanch Zjednoczonych.

### Cel
Głównym celem było opracowanie rozwiązania opartego na sieciach neuronowych, które wykorzystywało historyczne dane do prognozowania warunków pogodowych na kolejny dzień oraz trzy kolejne dni. Konkretnie, model miał przewidywać średnią temperaturę dzienną i prędkość wiatru na podstawie danych z trzech poprzednich dni, prognozując na kolejny dzień (+1D) oraz trzy kolejne dni (łącznie cztery prognozy).

### Podejście
Zbudowano różne architektury sieci neuronowych, w tym perceptron wielowarstwowy (MLP), aby porównać ich wydajność. Porównanie oparto na miarach takich jak Błąd Średniokwadratowy (MSE), Średni Błąd Bezwzględny (MAE), kwadratowa korelacja Pearsona (R^2), Indeks Porozumienia (IA) i inne.
![image](https://github.com/Kacpez/ML-NN-Weather-Forecast/assets/84182940/a046f83b-fff9-4646-bce4-08a9ba402597)

### Zbiór danych
Zbiór danych zawierał:
* Historyczne godzinowe dane pogodowe dla wielu miast.
* Cechy obejmujące temperaturę, prędkość wiatru, wilgotność itp.
###  Miary oceny
Modele oceniano za pomocą następujących miar:
* Błąd Średniokwadratowy (MSE)
* Średni Błąd Bezwzględny (MAE)
* Kwadratowa korelacja Pearsona (R^2)
* Indeks Porozumienia (IA)

### Implementacja
Stworzono kilka modeli sztucznych sieci neuronowych wykorzystujących różne podejście uczenia. Mamy do czynienia z rekurencyjnymi, konwolucyjnymi czy zwykłymi MLP sieciami neuronowymi. W implementacji wykorzystano Tensorflow wraz z innymi bibliotekami Pythona.
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,tensorflow," />
  </a>
</p>

### Wyniki Vancouver
![image](https://github.com/Kacpez/ML-NN-Weather-Forecast/assets/84182940/4f0a6f80-69a2-45b3-94e9-82aa05db8b71)

