ISSUE SUMMERY
This problem started on the 7th of August, 2022 at 2:30am WAT and we were finally able to contain it on the 12th of August, 2022 at 3:00pm WAT after a grueling night and day effort put in by staffs.

IMPACT
I don't believe we can totally summise everything that went wrong during that period. Our server was down so there was no way to store information. Consequently, our users lost all the data they inputed at the time of the system fault. A good 75% lost thier planned schedule for the day and the remaining 25% never made of the app on that day.

CAUSE
The root cause was basically a surge of users on the app beyond the site's capacity.

TIMELINE
Unfortunately, the issue was detected after the crash on the 7th of August, 2022 at 3:00am WAT after the engineers conducted a survey to discover the cause of the failure. The server was immediately examined and was solved by enlarging capacity.

ROOT CAUSE AND RESOLUTION
The problem turned out to be caused by improper data storing technique for the massive data recieved. To fix this, we implemented a simple change to our database management system.

Corrective and preventative measures
To ensure that this never happens again, we must be prepared to have large influx of data. We need to add some sort of monitoring on the server memory to keep[ track of the amount of data being stored there. 
