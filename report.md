---
title: "Sprint backlog"
titlepage: true
author: [Mateusz Grzonka, Jakub Jabłoński, Krystian Jandy, Błażej Smorawski, Filip Szweda]
date: "2023-11-04"
keywords: [Markdown, Linux]
...
# O projekcie i produkcie

Naszym produktem jest gra programistyczna, w której gracze (głównie uczniowie i nauczyciele szkół podstawowych) sterują agentami w wirtualnym świecie i za ich pomocą rozwiązują różne zadania. Zadania skupiają się wokół różnych interakcji z tym światem, na przykład zbieranie drewna, i rozwijają w użytkowniku umiejętności programistyczne.

# Oszacowanie rozmiaru backlogu produktu
![Estimate](./estimate.png "Oszacowanie backlogu produktu w `story points`")

# Założenia i dobór zakresu sprintu

1. Pojemność zespołu: W skład zespołu wchodzi pięć osób.

2. Rezerwa w pojemności zespołu na pracę inną niż wytwarzanie: Zespołowi zostało przyznane 20% czasu na spotkania, rewidowanie kodu i inne zadania, które nie są bezpośrednio związane z wytwarzaniem produktu.

3. Średnia prędkość zespołu: Zespół pracował już wcześniej nad projektem i osiągnął średnią prędkość 20 punktów backlogu produktu na sprint.

4. Wybrane elementy z backlogu produktu: W ramach tego sprintu zespół wybrał elementy backlogu produktu, które dotyczą stworzenia prototypu gry programistycznej. Elementy te obejmują:

* Stworzenie wirtualnego świata gry, który umożliwi użytkownikowi kontrolowanie agentów
* Dodanie interakcji do gry, takich jak zbieranie drewna
* Stworzenie mechaniki gry, która będzie rozwijała umiejętności programistyczne użytkownika

###Dobór zakresu sprintu:

Biorąc pod uwagę powyższe założenia, zespół zdecydował się na 2-tygodniowy sprint. W ciągu tego czasu planują osiągnąć 20 punktów backlogu produktu, co odpowiada ich średniej prędkości. Wybrali konkretny zakres elementów z backlogu produktu, który będzie realizowany w tym sprincie. Ich celem jest przygotowanie prototypu gry programistycznej, co oznacza, że będą musieli skupić się na stworzeniu wirtualnego świata gry, dodaniu interakcji i stworzeniu mechaniki, która rozwija umiejętności programistyczne użytkownika. Ponieważ zespół pracował już nad projektem, mają już pewne doświadczenie, co pozwala im na osiągnięcie zakładanych celów w ramach tego sprintu.

# Cel sprintu

Celem tego sprintu jest przygotowanie prototypu gry programistycznej, która umożliwi użytkownikom (głównie uczniom i nauczycielom szkół podstawowych) rozwijanie umiejętności programistycznych poprzez sterowanie agentami w wirtualnym świecie i rozwiązywanie różnych zadań. Najważniejszą wartością dla interesariuszy wynikającą z przyrostu po tym sprincie będzie możliwość przetestowania prototypu i uzyskanie informacji zwrotnych od użytkowników, co pozwoli na dalszy rozwój gry i poprawienie jej jakości przed wdrożeniem. Dzięki temu, że prototyp zostanie przygotowany w ciągu jednego sprintu, zespół będzie mógł szybko reagować na uwagi użytkowników i wprowadzać odpowiednie zmiany w kolejnych sprintach, co zwiększy szanse na sukces produktu na rynku.

# Backlog sprintu

![Backlog](./backlog.png "Przygotowany backlog sprintu w programie `Jira`")

# Kryteria Akceptacji

![Prototype](./prototype.png "Przygotowany backlog sprintu w programie `Jira`")
![Complex](./complex.png "Przygotowany backlog sprintu w programie `Jira`")

# Definicja ukończenia

* Testy w formacie Arrange, Act and Assert dla kluczowych funkcji.
* Utworzone Continuous Integration dla wszystkich komponentów.
* Skalowalność mikroserwisów do 1000 różnych użytkowników.
* Wydajność systemu określona w System Efficiency Index.
* Mechanizmy zarządzania, realizacji i współpracy agentów.
* Integracja z systemem płatności do darowizn.
