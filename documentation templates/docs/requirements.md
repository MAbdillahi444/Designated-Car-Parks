# Requirements

## User Needs

### User stories
TODO: Write brief user stories to explain how various actors would interact with the system to accomplish a goal.
    Express these in the form from agile development:-

As daily commuters, our role is to find a quick and easy designated parking spot to make our commute easier as we are people who travel regularly the benefit of this will be it will direct them straight to an open free parking space.


As conference atendees, our role is to  access nearby parking spaces next to venues/buildings we work at attend meetings and seminars as we are proffesionals working the benefit of this will be keeping people satisfied which will spread awarness about our app.


As the Bristol City Council, my role is to check all designated parking spaces on the app to gather data the benfit of this will show what needs imporvements and will show our merits.

### Actors
Daily Commuters: People who travel regularly and require affordable, convenient parking facilities near employment locations or transit points.
Conference Attendees: Professionals who are attending meetings, seminars, and workshops who need nearby parking as close to venues as possible. 
Bristol City Council member: who needs access to the app for data.

### Use Cases

| : UC1  |  Locate nearest car park | 
| -------------------------------------- | ------------------- |
| Description | :locate nearest car park |
| Actors | : Daily commuter |
| Assumptions | : Browser has by phone.
| Steps | : 1. View car parks in the area  
2. Request user permission to access location.

3.User grants permission for geolocation.

4. Retrieve nearest car parks from the database.

5. Display the nearest car parks to the user.

   | **Variations** | : Possible alternative steps in the process. |
| **Non-functional** | : Performance, security, and usability aspects the system must meet. |
| **Issues** | :List of issues that remain to be resolved |



| : UC2  | : Locate nearest car park | 
| -------------------------------------- | ------------------- |
| **Description** | : Locate nearest car park for Conference attendee |
| **Actors** | : Conference attendee |
| **Assumptions** | : Browser has location by phone.
| **Steps** | : 1. Display available car parks in the area of the conference attendee
                    2. Request user permission to access the location.
                    3. User grants permission for geolocation.
                    4.Retrieve the nearest car parks from the database
                    5. Display the nearest car parks to the user.
| **Variations** | : Possible alternative steps in the process. |
| **Non-functional** | : Performance, security, and usability aspects the system must meet. |
| **Issues** | :List of issues that remain to be resolved |



Variations: Possible alternative steps in the process.


Non-functional Requirements: Performance, security, and usability aspects the system must meet.


Issues: Any unresolved challenges related to this use case.



    








## Software Requirements Specification
### Functional requirements
RF1 The system shows available parking spots located in specified geographical coordinates.
RF2 Parking spots become visible after a click on any available spot.
RF3 The application can present directions from a user's spot to selected parking areas. 



### Non-Functional Requirements

NFR1 The system shows available parking spots located in specified geographical coordinates.
NRF2 The application interface provides full support for mobile and desktop browsers.
