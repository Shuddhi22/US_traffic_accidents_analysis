# US_traffic_accidents_analysis
Exploratory data analysis and machine learning on the U.S. Accidents (March 2023) dataset. This project examines traffic accident patterns across the U.S., analyzing factors like weather, time, location, and road conditions to identify trends, predict severity, and improve road safety insights.

| Column                     | Description                                              |
| -------------------------- | -------------------------------------------------------- |
| **ID**                     | Unique identifier for each accident record.              |
| **Source**                 | Data provider/source (e.g., MapQuest, Bing, etc.).       |
| **TMC**                    | Traffic Message Channel code indicating the event type.  |
| **Severity**               | Accident severity (1–4 scale, 4 = most severe).          |
| **Start\_Time**            | Date & time when the accident started.                   |
| **End\_Time**              | Date & time when the accident ended.                     |
| **Start\_Lat**             | Starting point latitude of the accident.                 |
| **Start\_Lng**             | Starting point longitude of the accident.                |
| **End\_Lat**               | Ending point latitude (if available).                    |
| **End\_Lng**               | Ending point longitude (if available).                   |
| **Distance(mi)**           | Approximate length of the road segment affected (miles). |
| **Description**            | Natural language description of the accident.            |
| **Number**                 | Street number where the accident occurred.               |
| **Street**                 | Street name.                                             |
| **Side**                   | Side of street (R = right, L = left).                    |
| **City**                   | City where the accident occurred.                        |
| **County**                 | County where the accident occurred.                      |
| **State**                  | U.S. state (abbreviation).                               |
| **Zipcode**                | Postal code.                                             |
| **Country**                | Country code (mostly “US”).                              |
| **Timezone**               | Timezone of the accident location.                       |
| **Airport\_Code**          | Nearest airport code.                                    |
| **Weather\_Timestamp**     | Timestamp of nearest weather observation.                |
| **Temperature(F)**         | Temperature at the time of accident.                     |
| **Wind\_Chill(F)**         | Wind chill value (if available).                         |
| **Humidity(%)**            | Humidity level.                                          |
| **Pressure(in)**           | Atmospheric pressure.                                    |
| **Visibility(mi)**         | Visibility distance in miles.                            |
| **Wind\_Direction**        | Wind direction (e.g., N, S, WNW).                        |
| **Wind\_Speed(mph)**       | Wind speed in mph.                                       |
| **Precipitation(in)**      | Rain/snow precipitation in inches.                       |
| **Weather\_Condition**     | Weather description (e.g., Light Rain, Clear).           |
| **Amenity**                | Whether near amenities (TRUE/FALSE).                     |
| **Bump**                   | Presence of road bump.                                   |
| **Crossing**               | Presence of pedestrian crossing.                         |
| **Give\_Way**              | Presence of “Give Way” sign.                             |
| **Junction**               | Whether near a junction.                                 |
| **No\_Exit**               | Whether it occurred on a no-exit road.                   |
| **Railway**                | Near a railway crossing.                                 |
| **Roundabout**             | Whether near a roundabout.                               |
| **Station**                | Near a station (bus/train).                              |
| **Stop**                   | Near a stop sign.                                        |
| **Traffic\_Calming**       | Traffic calming measures nearby.                         |
| **Traffic\_Signal**        | Near a traffic signal.                                   |
| **Turning\_Loop**          | Whether near a turning loop.                             |
| **Sunrise\_Sunset**        | Day/Night indicator.                                     |
| **Civil\_Twilight**        | Civil twilight (Day/Night).                              |
| **Nautical\_Twilight**     | Nautical twilight (Day/Night).                           |
| **Astronomical\_Twilight** | Astronomical twilight (Day/Night).                       |
