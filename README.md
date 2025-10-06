# UK_City_Livability_Analysis
-> The author collected the data and visualize different parameters to find best and worst cities to live in United Kingdom.

-> It compare total 76 places officialy stated as cities by the crown by their popularity which are:

'Aberdeen', 'Armagh', 'Bangor(NI)', 'Bangor(W)', 'Bath', 'Belfast', 'Birmingham', 'Bradford', 'Brighton and Hove', 'Bristol', 'Cambridge', 'Canterbury', 'Cardiff', 'Carlisle', 'Chelmsford', 'Chester', 'Chichester', 'City of London', 'City of Westminster', 'Colchester', 'Coventry', 'Derby', 'Derry', 'Doncaster', 'Dundee', 'Dunfermline', 'Durham', 'Edinburgh', 'Ely', 'Exeter', 'Glasgow', 'Gloucester', 'Hereford', 'Inverness', 'Kingston upon Hull', 'Lancaster', 'Leeds', 'Leicester', 'Lichfield', 'Lincoln', 'Lisburn', 'Liverpool', 'Manchester', 'Milton Keynes', 'Newcastle', 'Newport', 'Newry', 'Norwich', 'Nottingham', 'Oxford', 'Perth', 'Peterborough', 'Plymouth', 'Portsmouth', 'Preston', 'Ripon', 'Salford', 'Salisbury', 'Sheffield', 'Southampton', 'Southend-on-Sea', 'St Albans', 'St Asaph', 'St Davids', 'Stirling', 'Stoke-on-Trent', 'Sunderland', 'Swansea', 'Truro', 'Wakefield', 'Wells', 'Winchester', 'Wolverhampton', 'Worcester', 'Wrexham', 'York'.

-> The parameters on which cities are compared are:

'Population' : 'Population', 'Population Density', Scores: Bell Shaped(Gaussian) function around ideal population density.

'Rent': '1_BedRoom', '2_BedRoom','3_BedRoom','4+_BedRoom', Scores: Inverse Normalization and adding weights for each parameter according to importance.

'Air_Quality': 'AQI', Scores: Inverse Normalization and adding weights for each parameter according to importance.

'Universities': 'Number_of_uni', 'Top_100', 'Top_500', 'Top_2000': Scores: Normalization and adding weights for each parameter according to importance.

'Safety': 'Crimes_per_km2_yearly', 'mild', 'moderate', 'dangerous', Scores: Inverse Normalization and adding weights for each parameter according to importance.

'Healthcare': 'Major_Hospital_Density', 'Major_Pharmacy_density', Scores: Normalization and adding weights for each parameter according to importance.

-> Analysis can be viewed in 

