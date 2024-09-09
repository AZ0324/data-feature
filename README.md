This data feature returns the current temperature of a flight's landing location when a flight number is entered.

APIs USED:

Aviationstack API was used to get data on flights. This API was chosen because it includes the information needed from flights, namely the flight number and arrival location, along with additional data such as timezones, which is helpful when trying to find the temperature.


Weatherbit API was used to get data on the current weather of the arrival locations. This API was chosen because it is relatively straightforward and contains the current temperature of various cities and locations around the world.

INSTRUCTIONS:

Once the code is run, it will prompt the user to enter a flight number. Once the flight number has been entered, the data feature will return the temperature of that flights arrival location.

PREREQUISITES:

To use this data feature, you will need both an Aviationstack API key as well as a Weatherbit API key.