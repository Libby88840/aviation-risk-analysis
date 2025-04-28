# aviation-risk-analysis
A project analyzing aviation accident risks using Tableau and Python.
Aviation Risk Analysis for Aircraft Selection
Project Overview
This project analyzes historical aviation accident data to identify aircraft models with the lowest risk, supporting safer and more informed investment decisions for a new company.
The analysis examines accidents, fatalities, injuries, aircraft makes, and other factors to determine which aircraft models present the safest options for acquisition.
Dataset Description
•	Source: Kaggle - Aviation Accident Database & Synopses
•	Files Used:
o	AviationData.csv: Accident reports and details.
o	USState_Codes.csv: U.S. State codes (used for mapping purposes).
•	Key Columns:
o	Event.Id, Accident.Number, Event.Date
o	Location, Country, Latitude, Longitude
o	Airport.Code, Airport.Name
o	Injury.Severity, Aircraft.damage, Aircraft.Category
o	Registration.Number, Make, Model
o	Total.Fatal.Injuries, Total.Serious.Injuries, Total.Minor.Injuries, Total.Uninjured
o	Weather.Condition, Broad.phase.of.flight
o	Purpose.of.flight, Air.carrier

Tools and Technologies
•	Python: Pandas, Matplotlib, Seaborn
•	Tableau: For building an interactive dashboard
•	Jupyter Notebook: For data cleaning, exploration, and visualization

Key Analysis Steps
•	Data Cleaning:
o	Missing values handled appropriately (e.g., replacing missing injury counts with 0).
o	Standardized column names and formats.
•	Exploratory Data Analysis (EDA):
o	Trends in accidents over the years
o	Aircraft makes with the highest and lowest fatality counts
o	Flight phases with the most accidents
o	Weather conditions linked to accident severity
•	Risk Score Calculation:
o	Combining fatalities and accidents to create a risk score per aircraft model.
•	Correlation Analysis:
o	Analyzing relationships between accident characteristics (injuries, aircraft make, flight phase, etc.).

Interactive Dashboard (Tableau)
The dashboard includes:
•	Accidents over time
•	Maps of accident locations
•	Injuries comparison against each make of the aircraft
👉 Dashboard Link: https://public.tableau.com/authoring/LizzOgutu/Dashboard1#4

 Key Findings
•	Accidents have decreased steadily over recent decades.
•	Some aircraft models consistently show fewer accidents and lower fatality rates.
•	Most accidents occur during the Takeoff and Landing phases.
•	Poor weather conditions (IMC - Instrument Meteorological Conditions) contribute significantly to accident severity.

Author
•	Name: Elizabeth Ogutu
•	Role: Student
•	Email: Elizabeth.ogutu@student.moringaschool.com
Notes
•	Missing data was handled conservatively to avoid introducing bias.
•	Some location data was missing and not plotted on maps.
•	Future improvements could involve combining more datasets like maintenance logs or aircraft usage statistics.
