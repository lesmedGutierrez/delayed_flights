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
- UNIQUE CARRIER = Code asigned by IATA and commonly used to identify a carrier 
- ORIGIN = Origin airport of the flight Airport from which the flight originates.
- ORIGIN CITY NAME = Origin city name City from which the flight originates.
- ORIGIN STATE ABR = Abbreviation of the state from which the flight originates.
- ORIGIN STATE NM = Full name of the state from which the flight originates.
- ORIGIN WAC = International airport area code.
- DEST = Destination airport.
- DEST CITY NAME = Name of the city where the destination airport is located.
- DEST STATE ABR = Abbreviation of the name of the state where the destination airport is located.
- DEST STATE NM = Full name of the state where the airport is located.
- DEST WAC = International airport area code.
- DEP TIME = Actual departure time (local time: hhmm)
- DEP DELAY = Difference in minutes between the scheduled time and the actual time of departure. This difference can be negative if the plane leaves before the scheduled time.
- DEP DELAY NEW = It is an analog of DEP DELAY but consider leaving early as 0.
- DEP DEL 15 = It is an indicator. Its value is 1 if there was more than 15 minutes of delay at the time of departure and 0 if not.
- DEP DELAY GROUP = Exit delay intervals (every 15 minutes from <-15 to> 180).
- DEP TIME BLK = Block of exit time, intervals per hour.
- ARR TIME = Actual time of arrival (local time: hhmm).
- ARR DELAY = Difference in minutes between the scheduled time and the actual arrival time. If it arrives before then negative numbers are used.
- ARR DEL 15 = It is an indicator. Its value is 1 if there was more than 15 minutes late in the arrival time and 0 otherwise.
- ARR DELAY GROUP = Arrival delay intervals (every 15 minutes from <-15 to> 180).
- DEP TIME BLK = Block of arrival time, intervals per hour.
- CANCELLED = It is an indicator. Its value is 1 if the flight was canceled and 0 otherwise.
- DIVERTED = It is an indicator. Its value is 1 if there was any deviation and 0 otherwise.
- CURRENT ELAPSED TIME = Effective flight time in minutes.
- FLIGHTS = Number of flights.
- DISTANCE = Distance between airports in (miles).
- DISTANCE GROUP = Distance in intervals, every 250 miles.
- CARRIER DELAY = Delay of the operator, in minutes.
- WEATHER DELAY = Delay due to weather, in minutes.
- NAS DELAY = Delay by the national air system, in minutes.
- SECURITY DELAY = Delay for security, in minutes.
- LATE AIRCRAFT DELAY = Delay due to late flight, in minutes.
