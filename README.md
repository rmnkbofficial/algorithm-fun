# A Node.js algorithm for a hypothetical doctor's appointment service

Sometimes, you just want to put in a date, and within milliseconds, be able to query a database filled with thousands of doctors to see who has an opening for the next 7 days.

Assumptions:

1. Two types of events in the DB - "openings" and "appointments".

2. Openings can be of any length of hours, for example, 9:30am-6:00pm or 9:00am-11:30am. Appointments have to be 30 minute blocks.

3. The number of hours marked available on any given day is not known.

4. The returned data should list openings for a given day, in chronological order, for the next 7 days.

5. The data in the database will consist of "opening" and "appointment" events in a random order of days and hours, but returned data should be sorted in ascending order by days and hours.

6. The query should be optimized for performance and work well on large datasets.

# How to run

`npm install`
`npm test --watchAll`

or just go into src and look at the code idk

Just a little thing I designed for fun. 

