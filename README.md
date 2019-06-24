# Kreator Ustawień

Skrypt napisany w języku R do wizualizacji przestrzeni 3D głównej aplikacji.

Jako wejście wczytuje plik CSV z danymi przestrzeni po czym tworzy trójwymiarowy i interaktywny wykres.



![](https://i.imgur.com/gnWUQpg.png)

### Wymagania

[Środowisko R](https://cran.r-project.org/bin/windows/base/)

[R Studio](https://www.rstudio.com/products/rstudio/download/)

`RGL - Biblioteka do wizualizacji, R Studio instaluje ją automatycznie`


### Użytkowanie

* Otwórz projekt w R Studio

* Zmień lokalizację pliku wejściowego w kodzie tj.
  ```R
  mydata = read.csv("D:/CA/data.csv")
  ```

* Zaznacz cały skrypt `CTRL + A` po czym go uruchom `CTRL + ENTER`

* Możesz poruszać kamerą, używając myszy tj. LPM, PPM do obracania, ŚPM do przybliżania i oddalania*


## Autor

* **Kamil Łuc** - [GitHub](https://github.com/kamilluc)


## License

This project is licensed under the MIT License