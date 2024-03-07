  # Honolulu Climate Analysis and Flask App

## Introduction
Welcome to Honolulu, Hawaii! If you're planning a vacation to this beautiful destination, you'll want to know about the local climate. This README provides guidance on analyzing climate data and designing a Flask API to access the results.

## Part 1: Analyze and Explore the Climate Data

### Steps
1. Use Python and SQLAlchemy to connect to the SQLite database provided (hawaii.sqlite).
2. Reflect the database tables into classes using SQLAlchemy's automap_base().
3. Perform a precipitation analysis to find the most recent date and get the previous 12 months of precipitation data.
4. Perform a station analysis to calculate the total number of stations and find the most-active station.
5. Design queries to calculate the lowest, highest, and average temperatures for the most-active station.
6. Plot the results of precipitation and temperature analysis.
7. Close the SQLAlchemy session.

## Part 2: Design Your Climate App

### Routes
1. **Home (/)**: Displays the homepage with a list of available routes.
2. **Precipitation (/api/v1.0/precipitation)**: Returns JSON data of precipitation for the last 12 months.
3. **Stations (/api/v1.0/stations)**: Returns JSON list of stations.
4. **Temperature Observations (/api/v1.0/tobs)**: Returns JSON list of temperature observations for the most-active station in the previous year.
5. **Temperature Stats (/api/v1.0/<start> and /api/v1.0/<start>/<end>)**: Returns JSON list of minimum, average, and maximum temperatures for a specified start or start-end range.

### Hints
- Utilize Flask to create the routes and jsonify function to return JSON responses.
- For temperature stats, consider joining the station and measurement tables.

## Conclusion
By following the steps outlined in this README, you'll be able to conduct a climate analysis of Honolulu, Hawaii, and design a Flask API to access the results, helping you plan your vacation effectively.




