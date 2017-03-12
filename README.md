# Alexa-Flight-updates-using-Flightaware
SWHacks Hackathon


We have created a Lambda function to call the Flightaware APIs and let the result conveyed through Alexa. Following are the features implemented.

FlightStatus:

Finds out the flights status, whether it has departed from the airport or arrived, delayed and estimated arrival time.

Eg: Alexa, Flight Status flight status for Delta DAL430

FlightDetails:

Finds out the flight

flight details, which country it belongs, Website and phone number

Eg: Alexa, flight details for JBU

InFlightInfo:

Gives the flight Id and current latitude and longitude position of the flight in transit

Eg: Alexa, In flight details for JBU23

AirportOperation:

Gives the details of number of flights in transit, arriving, scheduled for departure and scheduled to arrive.

Eg: Airport Operation details for KJFK

ZipcodeDetails:

Finds the city, state and county pertaining to the given Zipcode

Eg: Find Zipcode details for 85281


Installation:

Create a new Lambda function, copy the code given in alexa.py. Use the intents given in intent_schema file and the following sample utterences


FlightStatus flight status for {Airline} {FlightNumber}
FlightDetails flight details for {FlightNumber}
InFlightInfo In flight details for {FlightNumber}
AirportOperation Airport Operation details for {FlightNumber}
ZipcodeDetails Find Zipcode details for {FlightNumber}

