# Blazing flights
In 3rd semester, we had a semestral project to create a 3tier architecture system. We chose to go with Airline reservation system.

## 3tier system
### Persistance
Written in java. This tier works with database (postgreSQL) and sending datato Middleware through TCP connection
### Middleware
Written in java. This tier is getting data from Persistence and sending data to Client through Webservices.
### Client
Written in C# (Blazor). This tier is seding and getting data through Webservices from/to Middleware.