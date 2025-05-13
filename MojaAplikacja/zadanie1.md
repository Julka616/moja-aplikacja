
# Aplikacja Pogodowa w Node.js z użyciem Dockera

## 1. Opis aplikacji

Aplikacja pogodowa została stworzona w technologii **Node.js** z użyciem frameworka **Express**. Umożliwia użytkownikowi wybór kraju i miasta w celu wyświetlenia aktualnej pogody na podstawie danych pobieranych z API.
Aplikacja wykorzystuje metodę POST do przesyłania danych z formularza i dynamicznie wyświetla wynik w przeglądarce użytkownika.
Użytkownik może wybrać jeden z trzech krajów: Polska, Niemcy lub Francja, a następnie miasto dostępne w wybranym kraju.


## 2. Uruchamianie aplikacji

1. Zbuduj obraz:

   docker build -t moja-aplikacja .
   
2. Uruchom kontener:
   
   docker run -p 3000:3000 --name moja-aplikacja moja-aplikacja

3. Sprawdzanie lagów:
  
   docker logs moja-aplikacja

4. Rozmiar obrazu: 

   docker images

 Aplikacja będzie dostępna pod adresem `http://localhost:3000`.

## 3. Linki

**GitHub (repozytorium z kodem źródłowym)**: https://github.com/Julka616/moja-aplikacja

**DockerHub (obraz aplikacji)**: https://hub.docker.com/r/jlasota123/moja-aplikacja

