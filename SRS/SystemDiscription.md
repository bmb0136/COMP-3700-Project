## Mentor Profiles
Mentor Profiles allows the mentors to store personal information on their account such as  preferred name, profile picture, expertise in subjects approved by CSSE and expected graduation date. Mentors can edit their profile using the Edit Profile use Case. If mentors change the profiles preferred name or profile picture then using Request Special Profile Edit an Admin gets notified about the preferred name or profile picture change then after approval or denial of the change by the admin will the change go in effect or not.
Admins can freely edit mentor profiles using Override Profile which is an Admin variant of Edit Profile. Admins can also Summarise Mentor Activity which shows what all the mentors are doing and information about the Mentor’s statistics. Another action that Admins can do is Query Mentor Profiles to look in more detail about what the mentor has done or retrieves information regarding Mentors Occurrences or Score.

## Penalty Score Management
Penalty Score Management controls the tracking of Penalty Scores for Mentors and at what points in Occurences do Actions occur. A use case for the Admin is the Configure Action Thresholds Which allows the Admin freely determine at what point values that certain actions occur, ie. at -10 Points a mentor might get a warning notification sent and or a notification to an Admin. Update Mentor Point Total lets the Admin add or modify the point total for a mentor that is then logged in the Penalty Score invoice for clean tracking. Admins can also Configure Tardy Intervals which change how late or absent a Mentor needs to be to have Penalties Occur. The capability to change what points are assigned to a Tardy Occurrence is applied by Admin with Configure Default Point Values.

## Occurrences
Occurrences are events that happened in the system that cause other actions to occur, and all of the types of Occurrences are configurable by Admin with Configure Occurrence Types use case. One such Occurrence that a mentor can call is Report Occurrence which gives the mentor a framework to report an event that happened during a mentoring session which is independent of whether it's a good or bad event.. Admins are heavily involved with Occurrences where they can Review Occurrences and choose to Close the Occurrence during such a Review, or Admins can directly Edit any Occurrence. Another thing Admins can do is Configure the Default Actions for any Occurrences in the system.

## Sessions
Sessionsi is where the Mentor mentors Mentees. In here Mentors can Start the Session and depending on the time of start the system will auto Mark Mentor as Tardy.  A Report Tardy Occurrence happens If the Mentor does not ever start the session then the Absence Timer will Mark Mentor as Absent which reports an Absence Occurrence.
Admins can also Assign Sessions to Mentorts which will Notify the Mentor of the session that they have been assigned to..

## Notifications
Notifications are Handled by the system, and Notification settings for a Mentor for example where to send the notification, and what are configurable, can be changed with Configure Notifications Preferences.

## Admin Summary Screen
The Admin Summary Screen encompass most of the previous sections and gives the admin a framework that lets the Admin manage most if not all events from one screen such as, acknowledge attendance and behavior occurrences,displays a list of occurrences, pending or closed, and a list of Mentors, All these fields can be filtered and from this filtered list the Admin can Review a specific Occurrence. And can manage as well as see Mentor profile information.v

