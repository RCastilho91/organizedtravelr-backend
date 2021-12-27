# OrganizedTravelr

OrganizedTravelr is a trip organizing app that allows for collaborative planning of itineraries.

Groups can collectively add things to do, plan places and dates, and everything the group agrees upon is consolidated into a joint timeline.

Organized travelers can see their activities on a map and add flairs ("Must do", "Food", "Sightseeing", etc) for filtering entries. They can also see what their day or week looks like in terms of activities.


## Main Features
### Map
- Google Maps API
- Maps will have pins based on locations
- Locations can be lodging (e.g. Hotel), activities, and exit way (e.g. Airport, Bus Station)
- Pin color will vary according to the flair assigned to them
- Pins can be filtered based on their dates
- [Future releases] Optimal route can be added to the day's activities based on distance and time of event

### Activities
- Any user can log an activity, which will be sent a pool of "group wants"
- Depending on the settings, an activity can be put in the timeline once everyone, majority, or administrators accept it permanently.
- Activities have title (mandatory), subtitle (recommended), location (strongly recommended), link (strongly recommended), priority (mandatory), and description (recommended).
- Activities can be assigned dates, fixed or recurring.
- Activities can have an estimated time of completion.
- Activities can be marked as done or dismissed.


### Timeline
- Timeline will organize accepted activities in a chronological fashion
- Before an item is added to the timeline, a check runs to make sure the sum of all activities for that day does not exceed 18 hours, and a recommendation is made to that user that it is postponed.
- Timeline activities can be filtered by date, flairs, priority, and done/to do activities


### Administration
- The main administrator will be considered the user that creates the trip
- User can invite any number of participants to the trip
- User can assign "main administrator" powers to any number of users they choose
- Main administrator have powers to assign roles, manage and delete the trip, manage all activities regardless of group vote
- User can assign "moderator" powers to any number of users they choose
- Moderators' votes for activities can be deterministic to whether or not it gets accepted into the timeline. Even if the group is much bigger, there shall be an option allowing an activity to be accepted into the timeline once it reaches consensus or majority of the moderators.