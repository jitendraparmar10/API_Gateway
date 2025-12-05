# FRONTED - MIDDLE-END - BACKEND

- We need an intermediate layer between the client side and the microservices
- Using this middle end , when client sends request we will be able to make decision that which microservice should actually respond to this request
- we can do message validation , response transformation , rate limiting
- we try to prepare an API Gateway that acts as this middle end.

Links to other Microservices Repo:

- Flight and Search Service: https://github.com/jitendraparmar10/FlightsAndSearchService
- Booking Service: https://github.com/jitendraparmar10/AirTicketBookingService
- Auth Service: https://github.com/jitendraparmar10/Auth_Service
- Reminder Service: https://github.com/jitendraparmar10/ReminderService
