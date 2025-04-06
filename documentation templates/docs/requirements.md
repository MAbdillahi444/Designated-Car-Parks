# Requirements

## User Needs

### User stories


User 1 - As daily commuters, our role is to find a quick and easy designated parking spot to make our commute easier as we are people who travel regularly the benefit of this will be it will direct them straight to an open free parking space.


User 2 - As conference atendees, our role is to  access nearby parking spaces next to venues/buildings we work at attend meetings and seminars as we are proffesionals working the benefit of this will be keeping people satisfied which will spread awarness about our app.


User 3 - As the Bristol City Council, my role is to check all designated parking spaces on the app to gather data the benfit of this will show what needs imporvements and will show our merits.

### Actors
Daily Commuters: People who travel regularly and require affordable, convenient parking facilities near employment locations or transit points.
Conference Attendees: Professionals who are attending meetings, seminars, and workshops who need nearby parking as close to venues as possible. 
Bristol City Council member: who needs access to the app for data.

### Use Cases






|  UC1  |  Locate nearest car park | 
| -------------------------------------- | ------------------- |
| **Description** | :locate nearest car park |
| **Actors** | : Daily commuter |
| **Assumptions** | : Browser has by phone.
| **Steps** |  View car parks in the area is avaiable to park at.
| **Variations** | : Possible alternative steps in the process. |
| **Non-functional** | : Performance, security, and usability aspects the system must meet. |
| **Issues** | :List of issues that remain to be resolved |





| : UC2  | : Locate nearest car park | 
| -------------------------------------- | ------------------- |
| **Description** | : Locate nearest car park for Conference attendee |
| **Actors** | : Conference attendee |
| **Assumptions** | : Browser has location by phone.
| **Steps** |  Display available car parks in the area of the conference attendee
| **Variations** | : Possible alternative steps in the process. |
| **Non-functional** | : Performance, security, and usability aspects the system must meet. |
| **Issues** | :List of issues that remain to be resolved |



| : UC3 |  Locate nearest car park | 
| -------------------------------------- | ------------------- |
| **Description** | :access to the app for data purposes. |
| **Actors** | : Bristol City Council |
| **Assumptions** | : has apps data and reviewes the app.
| **Steps** | Collect data from open data and analayse the data collected.
| **Variations** | Data can be accessed from different sources depending on whether real-time data is available or not.
| **Non-functional** | Standards of data privacy must be followed when collecting the user location data.
| **Issues** | Inaccurate data or old data can lead to incorrect car park recommendation. 






    








## Software Requirements Specification
### Functional requirements
FR1: The system must display clear and easily identifiable indicators for each parking space that has been marked on the map.

FR2: The system must request access to the user's location so it can provide location-based services.

FR3: The system must display live availability information for the visible parking spaces.

FR4: The system must provide details about the cost of parking for each marked spot.



### Non-Functional Requirements
NFR1: The application should be sensitive to user actions to enhance performance and effectiveness.

NFR2: The application should render map markers in a reasonable size conducive to usability and navigation.

NFR3: The application should be fully compatible with Chrome-based internet browsers in order to have it accessible across devices.

NFR4: The application should render a default location in case the user's location is inaccessible to ensure it remains functional without location services.

NFR5: The application should be periodically updated in a way that the parking spaces on the map that are available are functional and available.

NFR6: The system ought to respond to users' requests as quickly as possible, offering performance efficiency.

NFR7: The application ought to be usable on various devices like mobile phones, tablets, and desktops, offering portability.

NFR8: The app must incorporate safety features, such as a straightforward accident reporting mechanism, including location and time, without interfering with user security.

NFR9: The app must be regularly updated to ensure users are informed of available parking spaces, such as real-time availability and status.

