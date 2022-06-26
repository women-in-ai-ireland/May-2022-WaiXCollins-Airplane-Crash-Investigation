## Original dataset
"Airplane Crashes Since 1908"

dataset source: https://www.kaggle.com/cgurkan/airplane-crash-data-since-1908?select=Airplane_Crashes_and_Fatalities_Since_1908_20190820105639.csv

## Updated dataset
Added one column named "geopyLoc" which contains "geopy.location.Location" object,
Added another column named "geopyRoute" which contains a list of at least two "geopy.location.Location" objects,

extracted by "geopy.geocoders.Nominatim" after some minor data cleaning

saved as pkl to preserve object types

simply load it to pandas dataframe:

df=pd.read_pickle("https://github.com/women-in-ai-ireland/May-2022-WaiXCollins-Airplane-Crash-Investigation/raw/main/dataset/Airplane_Crashes_and_Fatalities_Since_1908_20190820105639.pkl")
