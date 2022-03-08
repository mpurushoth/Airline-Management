# Airline-Management
Software to manage airlines flights and ticketing written using java for OOP lab project

## Concepts Used
| Java Concepts | Files |
| :-----------: | :---- |
|**Classes:** |<ol><li>[Person](AirlineCore/Person.java)</li><li>[Passenger](AirlineCore/Passenger.java)</li><li>[Flight](AirlineCore/Flight.java)</li><li>[Business Class Ticket](AirlineCore/BusinessClassTicket)</li><li>[Economy Class Ticket](EconomyClassTicket.java)</li></ol>|
|**Interface:**| [Ticket](AirlineCore/Ticket.java) |
|**Collections:** | ArrayList of [Economy Class Ticket](EconomyClassTicket.java) & [Business Class Ticket](AirlineCore/BusinessClassTicket)|
|**Custom Exceptions:** |<ol><li>[Insufficient Tickets Exception](AirlineCore/InsufficientTicketsException.java)</li><li>[Invalid Date Exception](AirlineCore/InvalidDateException.java)</li><li>[No Flights Exception](AirlineCore/NoFlightsException.java)</li></ol>|

## Installation
**Steps For installing java on ubuntu:**
```bash
$sudo apt install default-jdk
$sudo apt install default-jre
```

**Steps For compiling and running source code:**
```bash
$javac AirlineReservation.java
$java ./AirlineReservation.class
```