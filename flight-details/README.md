# Flight details

Details for flights departing between 2022-06-09 and 2022-06-16, departing or arriving to French airports.

## flights.csv.gz

The list of flights.

- __flight_id:__ unique identifier of the flight
- __callsign:__ aircraft's registration number
- __airline:__ ICAO code of the operating airline
- __aircraft:__ ICAO code of the aircraft
- __origin:__ ICAO code of the departure airport
- __destination:__ ICAO code of the destination airport
- __scheduled_time_of_departure:__ timestamp of of the scheduled time of departure in seconds
- __scheduled_time_of_arrival:__ timestamp of of the scheduled time of arrrival in seconds
- __actual_time_of_departure:__ timestamp of of the actual time of departure in seconds
- __actual_time_of_arrival:__ timestamp of of the actual time of arrrival in seconds

## flight_details.csv.gz

The position, speed and heading of the aircraft trough time.

- __flight_id:__ unique identifier of the flight
- __time:__ timestamp of the record is seconds
- __latitude:__ latitude of the aircraft in degrees
- __longitude:__ longitude of the aircraft in degrees
- __altitude:__ altitude of the aircraft in feet
- __speed:__ speed of the aircraft in knot
- __heading:__ heading of the aircraft in degree
