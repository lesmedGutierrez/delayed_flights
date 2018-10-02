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
