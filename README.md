# Microstructure of Financial Markets

A comprehensive quantitative analysis of the microstructure of financial markets using high-frequency (tick-by-tick) trading data for two selected companies (Spółka A and Spółka E). The project implements advanced econometric models to analyze transaction durations, intraday seasonality, and realized volatility.

**Authors:** Sebastian Szklarski, Wiktor Suchoński-Romaniuk, Wiktoria Wróbel, Maciej Więcek

## Projects Overview

* **Part 1: Intraday Data Analysis & Seasonality** (`MRF_1.Rmd` / `MRF_1.html`)  
  Exploratory analysis of tick-by-tick data aggregated to 1-second and 5-minute intervals. The study confirms the lack of normality in returns and identifies a strong U-shaped intraday seasonality pattern. Advanced methods, including the Flexible Fourier Form and the Engle-Sokalska multiplicative model (supported by ARMA-GARCH), were used to filter out this diurnal deterministic component.

* **Part 2: Trade and Price Durations (ACD Models)** (`MRF_2.rmd` / `MRF_2.html`)  
  Modeling the time between consecutive transactions and price changes of a specific magnitude. The project implements Autoregressive Conditional Duration (ACD and LACD) models. Various innovation distributions were tested, with the Generalized Gamma distribution yielding the best fit. The estimated hazard functions revealed a decreasing probability of immediate price changes over time.

* **Part 3: Realized Volatility & Price Jumps** (`MRF_3.Rmd` / `MRF_3.html`)  
  An in-depth study of market volatility using Realized Volatility (RV) and Bipower Variation (BV) estimators. The analysis includes adjustments for overnight effects and employs Barndorff-Nielsen and Shephard (BNS) statistical tests (difference-based, log-difference, and ratio tests) to identify and quantify the frequency of significant price jumps during continuous trading.

## Technologies & Methodologies
* **Language:** R
* **Reporting:** R Markdown
* **Key Methods:** High-Frequency Data Analysis, ACD/LACD Models, Fourier Transforms, RV/BV Volatility Estimators, BNS Jump Tests.

---

# Mikrostruktura Rynków Finansowych

Kompleksowa analiza ilościowa mikrostruktury rynków finansowych z wykorzystaniem danych wysokiej częstotliwości (tick-by-tick) dla dwóch wybranych spółek (Spółka A i Spółka E). Projekt wdraża zaawansowane modele ekonometryczne do analizy czasów trwania, sezonowości śróddziennej oraz zmienności zrealizowanej.

**Autorzy:** Sebastian Szklarski, Wiktor Suchoński-Romaniuk, Wiktoria Wróbel, Maciej Więcek

## Opis projektów

* **Część 1: Analiza danych śróddziennych i sezonowości** (`MRF_1.Rmd` / `MRF_1.html`)  
  Eksploracyjna analiza danych transakcyjnych zagregowanych do 1 sekundy i 5 minut. Badanie potwierdza brak normalności stóp zwrotu i identyfikuje silny, U-kształtny wzorzec sezonowości śróddziennej. Do odfiltrowania tego komponentu wykorzystano zaawansowane metody: Elastyczną Formę Fouriera oraz model multiplikatywny Engle i Sokalskiej (wsparty estymacją ARMA-GARCH).

* **Część 2: Transakcyjne i cenowe czasy trwania (Modele ACD)** (`MRF_2.rmd` / `MRF_2.html`)  
  Modelowanie czasu pomiędzy kolejnymi transakcjami oraz zmianami cen o ustalony próg. Wdrożono modele z rodziny ACD i LACD. Przetestowano różne rozkłady innowacji, z których najlepsze dopasowanie zapewnił uogólniony rozkład Gamma. Wyznaczone funkcje hazardu wykazały malejące prawdopodobieństwo natychmiastowej zmiany ceny w czasie.

* **Część 3: Zmienność zrealizowana i skoki cenowe** (`MRF_3.Rmd` / `MRF_3.html`)  
  Pogłębione badanie zmienności przy użyciu estymatorów zmienności zrealizowanej (RV) oraz wariacji dwupotęgowej (BV). Analiza uwzględnia korekty o efekt overnight i wykorzystuje testy statystyczne BNS (oparty na różnicach, różnicach logarytmów i ilorazowy) do identyfikacji oraz oceny intensywności występowania skoków cenowych w trakcie notowań ciągłych.

## Technologie i Metodologia
* **Język:** R
* **Raportowanie:** R Markdown
* **Kluczowe metody:** Analiza danych High-Frequency, Modele ACD/LACD, Transformata Fouriera, Estymatory zmienności RV/BV, Testy skoków BNS.
