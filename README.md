# Econometric Analysis in Python

## Opis projektu
Projekt dotyczy analizy ekonometrycznej wpływu różnych parametrów społecznych, ekonomicznych i demograficznych na poziom przestępczości w Polsce w latach 2013–2023. Celem jest zbudowanie modelu, który pomoże zrozumieć zależności między zmiennymi takimi jak urbanizacja, bezrobocie i liczba ludności a poziomem przestępczości w różnych regionach Polski.

Analiza opiera się na danych pochodzących z Banku Danych Lokalnych oraz Eurostat. Dane te zawierają informacje o liczbie ludności, wskaźniku urbanizacji, stopie bezrobocia oraz liczbie przestępstw w różnych kategoriach.

## Parametry modelu
Zmienne objaśniające, na których opiera się analiza, pochodzą z oficjalnych źródeł:
- **Średnia ludność na 1 km²**
- **Średnia liczba ludności w tysiącach**
- **Średnia liczba ludności w tysiącach mężczyzn**
- **Średnia liczba ludności w tysiącach kobiet**
- **Średni wskaźnik urbanizacji (%)**
- **Średnia liczba bezrobotnych osób**
- **Średnia liczba bezrobotnych mężczyzn**
- **Średnia liczba bezrobotnych kobiet**
- **Średni dochód budżetu powiatów na mieszkańca**
- **Średnie dochody budżetów powiatów**

## Główne hipotezy badawcze
- **Wpływ poziomu urbanizacji na przestępczość**: Wysoki poziom urbanizacji ma istotny wpływ na poziom przestępczości. Hipoteza zakłada, że im wyższy poziom urbanizacji, tym wyższy poziom przestępczości.
- **Wpływ średniej liczby ludności na przestępczość**: Im wyższa średnia liczba ludności, tym większe ryzyko przestępczości, związane z większą anonimowością i trudnościami w monitorowaniu działań społecznych.
- **Wpływ bezrobocia na przestępczość**: Wyższy poziom bezrobocia prowadzi do wzrostu przestępczości, jako że osoby bez pracy mogą poszukiwać nielegalnych źródeł dochodu lub wyładowywać frustrację poprzez działania przestępcze.

## Dane wejściowe
Dane pochodzą z oficjalnych źródeł statystycznych, takich jak Bank Danych Lokalnych i Eurostat. Analiza bazuje na statystykach przestępstw w Polsce w latach 2013–2023, z podziałem na kategorie. Wszystkie dane zostały uśrednione dla każdego roku.

**Kategorie przestępstw:**
- Średnia liczba przestępstw ogółem
- Średnia liczba przestępstw o charakterze kryminalnym
- Średnia liczba przestępstw o charakterze gospodarczym
- Średnia liczba przestępstw przeciwko bezpieczeństwu powszechnemu i komunikacji (drogowe)
- Średnia liczba przestępstw przeciwko życiu i zdrowiu
- Średnia liczba przestępstw przeciwko mieniu
- Średnia liczba przestępstw przeciwko wolności, wolności sumienia, wolności seksualnej i obyczajności
- Średnia liczba przestępstw przeciwko rodzinie i opiece
- Średnia liczba przestępstw przeciwko bezpieczeństwu powszechnemu i komunikacji

## Jak uruchomić projekt?
1. **Zainstaluj wymagane biblioteki**:  
   Użyj poniższego polecenia, aby zainstalować zależności:
   ```bash
   pip install -r requirements.txt

