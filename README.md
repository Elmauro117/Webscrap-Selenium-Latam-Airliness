# Webscrap-Selenium-Latam-Airliness

# ESP
Full webscrap y webcrawl de LATAM airlines usando Selenium webdriver.

El documento python final consiste de las definiciones AKA formulas con las que se se peude hacer un webscrap y webcrawl. Cabe resalta que solo sirve si tiene 1 escala o ninguna, pero no es dificil la adaptación caso sea 3 o más escalas.

La primera parte consiste en la selección del lugar de origen y destino, luego la cantidad de pasajeros que irán, el tipo de vuelo (premium, normal, economico), si es ida y vuelta y las fechas de IDA y/o VUELTA y funalmente buscar los vuelos disponibles. La segunda en webscrapear la data de los vuelos encontrados, horas, tiempos de vuelo y de escalas.

** Recordar que es una página web cambiante, por lo tanto los XPATHS van a variar en el futuro, es más durante la realziación de este proyecto ocurrio una vez.


# ENG 
Full webscrap and webcrawl of LATAM Airlines webpage using Selenium webdriver

The final python doc consists of all the definitions that we use to webscrap and webcrawl. BTW 1 def only works if the flight has 1 stopover or none, but it is really not hard to tweak the code.

the first part consists on the selection of dates, type of flight, number of passengers, origin and destination, it works with both one way ticket or round-trip flight and the search of flights. the second part is the data webscrap of the flights found by the web-page, data like hours of flight, stopover times, where are the stopovers, etc.

** A little reminder that this webpage changes, hence the XPATHS will change on the future, same happens with the UI design of the webpage. TBH it even happened to me during the development of this project.
