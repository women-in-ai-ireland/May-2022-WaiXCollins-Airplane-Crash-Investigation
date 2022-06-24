## Original dataset
"Airplane Crashes Since 1908"

dataset source: https://www.kaggle.com/cgurkan/airplane-crash-data-since-1908?select=Airplane_Crashes_and_Fatalities_Since_1908_20190820105639.csv

## Updated dataset
Added one column named "geopyLoc" which contains "geopy.location.Location" object,
extracted by "geopy.geocoders.Nominatim" after some minor data cleaning
