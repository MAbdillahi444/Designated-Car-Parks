# Requirements

## User Needs

### User stories
TODO: Write brief user stories to explain how various actors would interact with the system to accomplish a goal.
    Express these in the form from agile development:- As a (role) I want (goal) so that (benefit).
    As a student, I would like to find the most affordable car parks nearest to me 
    As a parent, I would want to have step by step directions to the car park
    As a teacher, I would like to find the closest car parks to me

### Actors
Daily Commuters: People who travel on a regular basis and require affordable, convenient parking facilities near employment locations or transit points.
Visitors: Individuals who have traveled to a new location for leisure or errands, seeking where to park as well as rates.
Conference Attendees: Professionals who are attending meetings, seminars, and workshops who need nearby parking as close to venues as possible. 
Shoppers: Customers visiting malls or shopping centers who wish to have good parking access and good rates

### Use Cases
TODO: Describe each use case (at least one per team member).
    Give each use case a unique ID, e.g. UC1, UC2, ...
    Summarise these using the use-case template below.
| : UC1  | TODO: Locate nearest car park | 
| -------------------------------------- | ------------------- |
| Description | :locate nearest car park |
| Actors | : Daily commuter |
| Assumptions | : Browser has by phone.
| Steps | : 1. View car parks in the area  
2. Request user permission to access location.

3.User grants permission for geolocation.

4. Retrieve nearest car parks from the database.

5. Display the nearest car parks to the user.

   | **Variations** | :Possible alternative steps in the process. |
| **Non-functional** | : Performance, security, and usability aspects the system must meet. |
| **Issues** | :List of issues that remain to be resolved |



| : UC2  | : Locate nearest car park | 
| -------------------------------------- | ------------------- |
| **Description** | : Locate nearest car park for Confrence attendee |
| **Actors** | : Conference attendee |
| **Assumptions** | : Browser has location by phone.
| **Steps** | : 1. Display available car parks in the area of the conference attendee
                    2. Request user permission to access location.
                    3. User grants permission for geolocation.
                    4.Retrieve nearest car parks from the data base
                    5. Display the nearest car parks to the user.
| **Variations** | :Possible alternative steps in the process. |
| **Non-functional** | : Performance, security, and usability aspects the system must meet. |
| **Issues** | :List of issues that remain to be resolved |




Variations: Possible alternative steps in the process.


Non-functional Requirements: Performance, security, and usability aspects the system must meet.


Issues: Any unresolved challenges related to this use case.



    






TODO: Your Use-Case diagram should include all use-cases.

![Insert your Use-Case Diagram Here](images/use-case.png)

## Software Requirements Specification
### Functional requirements
1. The system shows available parking spots located in specified geographical coordinates.
2. Parking spots become visible after a click on any available spot.
3. The application can present directions from a user's spot to selected parking areas. 



### Non-Functional Requirements
TODO: Consider one or more [quality attributes](https://en.wikipedia.org/wiki/ISO/IEC_9126) to suggest a small number of non-functional requirements.
Give each non-functional requirement a unique ID. e.g. NFR1, NFR2, ...

NFR1 The system shows available parking spots located in specified geographical coordinates.
NRF2 The application interface provides full support for mobile and desktop browsers.
