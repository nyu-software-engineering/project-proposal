# Project Proposal

### Project title

TripCanvas

### What and why?

TripCanvas is a web app that lets travelers input their flights, hotels, restaurant reservations, and activities for a trip, and see the entire itinerary laid out visually on a timeline that is easy to share with people you are traveling with. Beyond just displaying the trip visually, TripCanvas actively tracks time-sensitive tasks tied to each booking and sends the user email or notification reminders before they certain actions need to be peformed by the user, such as flight check-in windows opening, visa or entry-requirement deadlines for the destination, and upcoming restaurant or activity reservation times. It also flags scheduling conflicts automatically, like a dinner reservation overlapping other activites

### For whom?

This app is designed for lesiure travelers that may have a difficult time juggling all the reservations and to do tasks they have across many different websites and companies. It makes it an easy and visually appealing place to easily check your trip information that can also be shared with your friends and family so they can visualize the trip rather than trying to make sense of a document.  e can validate the concept early by interviewing classmates or friends about what they've forgotten or missed on past trips, and testing prototypes with them.

### How?

From an end-user's perspective:

- A user creates a new trip and manually enters flight and hotel details (airline, dates/times, confirmation numbers, hotel name/dates, destination)
- The system displays this on a visual timeline, showing flights, hotel stays, restaurant reservations, and activities as blocks across the trip's days
- Based on what's entered, the system automatically identifies relevant time-sensitive tasks: e.g. flight check-in typically opens 24 hours before departure, a destination may require a visa or entry form submitted by a certain date, a restaurant reservation needs a reminder a few hours ahead (this can be auto-generated or created by the user)
- The user receives these reminders via email or in-app notification ahead of the relevant deadline, so nothing is missed
- If a new item overlaps with an existing booking (e.g., a restaurant reservation during a flight), the system flags the conflict visually and via notification
- Users can view the trip as an itinerary list or a visual timeline, and mark tasks (like check-in or visa submission) as completed
- Users can share a read-only link to their trip so friends or family can view the itinerary visually rather than piecing it together from documents or messages

### Scope

This project is scoped to manual data entry rather than live booking APIs (largely unavailable for individual developers) thus making the backend more manageable given our time constraint, though some cloud storage is needed if these trips are to be made shareable via a link. The application is primarily a CRUD app with a strong front-end visualization layer. The features of adding bookings, timeline view, and conflict detection are achievable by a team of 4–6 in a semester, with additional goals of map views, shareable trip links, activity suggestions, drag-and-drop rescheduling, and more that can be added if the team finishes core functionality early or cut if time runs short.