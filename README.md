# vacappt
A script to schedule COVID-19 vaccinations through HEB's website.

# Instructions for Use
 1. Download this script
 2. Open command prompt and navigate to directory that contains this file (ie, __cd C:\Users\you__)
 3. Run the following in command line: __python vacappt.py "[city]"__ 
where __[city]__ is the city/cities you would like to restrict the search to. For example, if you are looking for appointments in the Austin area, you would enter:
        __python vacappt.py "austin"__
 4. If no city is input, every HEB statewide that has open time slots will be opened. This is not advised. Once activated, this script will ping HEB's vaccination registration website repeatedly until open appointments are found. 
 5. Once you find an open time at your preferred location, select the vaccine from the options offered, and select an appointment time.
