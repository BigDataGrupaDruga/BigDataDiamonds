# Diamenty Tiffany'ego :gem:

#### Projekt wykonany jako praca zaliczeniowa na studiach podyplomowych, na Uniwersytecie WSB Merito w Poznaniu na kierunku Big Data i inżynieria danych.
#### Projekt wykonany przez 4 osoby, którego część na Githubie zawiera rozwiązanie 4 przedstawionych zadań oraz proces czyszczenia danych.


# Technologie użyte w projekcie 📁

#### Wiodącą technologią jest język Python 3 a konkretniej biblioteka Pandas, przy użyciu której zostało wykonane czyszczenie danych oraz dwa zadania. Przy pisaniu kodu w Pythonie użyto Jupyter Notebook oraz, oprócz wspomnianego Pandas, innych bibliotek języka Python (jak np. Scikit-learn i matplotlib). 
#### Dane, na których wykonany został projekt przedstawiają dane dotyczące Diamentów Tiffany'ego, plik w formacie .csv został wcześniej "zabrudzony".
#### Wizualizacje danych (dla zadania 1 i 3) zostały wykonane przy użyciu usługi Microsoft Power BI.


# Poszczególne zadania

## Zadanie: Czyszczenie danych:

#### Czyszczenie danych wykonane przy użyciu biblioteki Pandas. Dane zostały wcześniej przekształcone do formatu DateFrame, aby móc na nich łatwiej pracować. Następnie poddane zostały kolejnej fazie czyszczenia.

## Zadanie 1: Analiza wpływu wagi i cech jakościowych na cenę diamentu.

#### Zadanie zostało wykonane przy użyciu technologii Microsoft Power BI. Zaimportowano i przekształcono dane oraz została wykonana wizualizacja dla analizy cech diamentów w stosunku do ceny.

![grafika z analizą ceny diamentów](https://raw.githubusercontent.com/BigDataGrupaDruga/BigDataDiamonds/refs/heads/main/Task%201/Analiza_ceny_Diamenty.png)

## Zadanie 2: Korelacja pomiędzy wymiarami diamentów a ich jakością.

#### W zadaniu drugim najpierw utworzono dodatkową tabelę zawierającą wartości dla określonych kategorii diamentów (zgodnie z wytycznymi np. kolorom zostały przypisane wartości liczbowe wskazujące na ich stopień jakości). Następnie w Pythonie została wykonana korelacja, korzystając z korelacji Pearsona. Na koniec zaimportowano bibliotekę Seaborn dla lepszej jakości graficznego ujęcia problemu.

![grafika z korelacją](https://i.imgur.com/sylNGTc.png)

## Zadanie 3: Segmentacja diamentów na podstawie atrybutów.
#### [W budowie]

## Zadanie 4: Predykcja przy użyciu techniki uczenia maszynowego.

#### W czwartym zadaniu została wybrana technika regresji liniowej. Przeprowadzony został trening na oczyszczonych danych w Pythonie korzystając z biblioteki scikit-learn. Ostateczną predykcję ceny diamentów w stosunku do ilości karatu przedstawiono korzystając z regresji liniowej, tworząc wizualizację przy użyciu biblioteki matplotlib. Dodatkowo została wykonana analiza statystyczna przedstawiająca zakres 95% ufności dla przedziałów przewidywania ceny dla wybranej wagi 2.5 karatów, a także walidacja krzyżowa sprawdzająca wyniki regresji.

![wykres regresji liniowej](https://i.imgur.com/ghoP5K0.png)

