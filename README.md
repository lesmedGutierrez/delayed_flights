# Project


# Installation
## Download the data
- Clone this repository to your computer or download it as a ZIP.
- Use an aplication like Jupyter to open the content of the document.

# Background
The data used on this project has been extracted from the "On-Time Performance" data table of the "On-Time" database from the "TranStats" data library. We extracted only the information from 2017. For more information visit "https://www.transtats.bts.gov/Tables.asp?DB_ID=120".

# RECORD LAYOUT
Below are fields in the order that they appear on the records:

- MONTH = Month.
- DAY OF MONTH = Day of Month.
- FL DATE = Flight Date.
- UNIQUE CARRIER = Code assigned by IATA and commonly used to identify a carrier.
- ORIGIN = Origin airport.
- ORIGIN CITY NAME = Origin Airport, City Name.
- ORIGIN STATE ABR = Origin Airport, State Code.
- ORIGIN STATE NM = Origin Airport, State Name.
- ORIGIN WAC = Origin Airport, World Area Code.
- DEST = Destination Airport.
- DEST CITY NAME = Destination Airport, City Name.
- DEST STATE ABR = Destination Airport, State Code.
- DEST STATE NM = Destination Airport, State Name.
- DEST WAC = Destination Airport, World Area Code.
- DEP TIME = Actual Departure Time (local time: hhmm).
- DEP DELAY = Difference in minutes between scheduled and actual departure time. Early departures show negative numbers.
- DEP DELAY NEW = Difference in minutes between scheduled and actual departure time. Early departures set to 0.
- DEP DEL 15 = Departure Delay Indicator, 15 Minutes or More (1=Yes)
- DEP DELAY GROUP = Departure Delay intervals, every (15 minutes from <-15 to >180).
- DEP TIME BLK = CRS Departure Time Block, Hourly Intervals.
- ARR TIME = Actual Arrival Time (local time: hhmm).
- ARR DELAY = Difference in minutes between scheduled and actual arrival time. Early arrivals show negative numbers.
- ARR DEL 15 =  Arrival Delay Indicator, 15 Minutes or More (1=Yes).
- ARR DELAY GROUP = Arrival Delay intervals, every (15 minutes from <-15 to >180).
- DEP TIME BLK = CRS Arrival Time Block, Hourly Intervals.
- CANCELLED = Cancelled Flight Indicator (1=Yes).
- DIVERTED = Diverted Flight Indicator (1=Yes)
- ACTUAL ELAPSED TIME = Elapsed Time of Flight, in Minutes.
- FLIGHTS = Number of Flights.
- DISTANCE = Distance between airports (miles).
- DISTANCE GROUP = 	Distance Intervals, every 250 Miles, for Flight Segment.
- CARRIER DELAY = Carrier Delay, in Minutes.
- WEATHER DELAY = Weather Delay, in Minutes.
- NAS DELAY = National Air System Delay, in Minutes.
- SECURITY DELAY = Security Delay, in Minutes.
- LATE AIRCRAFT DELAY = Late Aircraft Delay, in Minutes.




- MONTH = Month.
- DAY OF MONTH = Day of month.
- FL DATE = Flight date.
- UNIQUE CARRIER = Código asignado por IATA y comúnmente utilizado para identificar un transportista.
- ORIGIN = Aeropuerto del que proviene el vuelo.
- ORIGIN CITY NAME = Ciudad de la que proviene el vuelo.
- ORIGIN STATE ABR = Abreviación del estado del que proviene el vuelo.
- ORIGIN STATE NM = Nombre completo del estado del que proviene el vuelo.
- ORIGIN WAC = Código de área mundial del aeropuerto.
- DEST = Aeropuerto destino.
- DEST CITY NAME = Nombre de la ciudad donde se ubica el aeropuerto destino.
- DEST STATE ABR = Abreviación del nombre del estado donde se ubica el aeropuerto destino.
- DEST STATE NM = Nombre completo del estado donde se ubica el aeropuerto.
- DEST WAC = Código de área mundial del aeropuerto.
- DEP TIME = Hora real de salida (hora local: hhmm)
- DEP DELAY = Diferencia en minutos entre la hora programada y la hora real de salida. Esta diferencia puede ser negativa si el avión sale antes de la hora programada.
- DEP DELAY NEW = Es un análogo de DEP DELAY pero considera el salir temprano como 0.
- DEP DEL 15 = Es una indicadora. Su valor es 1 si hubo más de 15 minutos de atraso en la hora de salida y 0 si no.
- DEP DELAY GROUP = Intervalos de retardo de salida (cada 15 minutos desde <-15 hasta > 180).
- DEP TIME BLK = Bloque de tiempo de salida, intervalos por hora.
- ARR TIME = Hora real de llegada (hora local: hhmm).
- ARR DELAY = Diferencia en minutos entre la hora programada y al hora de llegada real. Si llega antes entonces se usan números negativos.
- ARR DEL 15 = Es una indicadora. Su valor es 1 si hubo más de 15 minutos de atraso en la hora de llegada y 0 si no.
- ARR DELAY GROUP = Intervalos de retardo de llegada (cada 15 minutos desde <-15 hasta > 180).
- DEP TIME BLK = Bloque de tiempo de llegada, intervalos por hora.
- CANCELLED = Es una indicadora. Su valor es 1 si se canceló el vuelo y 0 si no.
- DIVERTED = Es una indicadora. Su valor es 1 si hubo alguna desviación y 0 si no.
- ACTUAL ELAPSED TIME = Tiempo efectivo del vuelo en minutos.
- FLIGHTS = Número de vuelos.
- DISTANCE = Distancia entre los aeropuertos en (millas).
- DISTANCE GROUP = Distancia en intervalos, cada 250 millas.
- CARRIER DELAY = Atraso del operador, en minutos.
- WEATHER DELAY = Atraso por el clima, en minutos.
- NAS DELAY = Atraso por el sistema de aire nacional, en minutos.
- SECURITY DELAY = Atraso por seguridad, en minutos.
- LATE AIRCRAFT DELAY = Atraso por avión atrasado, en minutos.
