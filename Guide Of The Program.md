"""
First Programm
This Programm retreives all futher used information including:
    1) Import that is Export
    2) total Import and Export
    3) Greenhouse Gass emmision
    4) Population
It will be stored in
Countries -> Years -> data per country (JSON style)
"""

"""
Data will be used by D3 version x
Needed format change to arrays instead of dict (JSON to Arrays for graphs)
World map:
[country[year [Correct calculated Greenhouse Gass emmision]]]
This way year can be selected and given a new map (per 5 years till 1960)
selecting different years as start position will change a variable year and ask for a update of the world map
where in this variable is used to select the right year.

correct calculated Greenhouse Gass emmision (GGE) --> GGE corrected by defiding to population corrected by export import.

Line Chard:
[country[year [Correct calculated Greenhouse Gass emmision]]] (same as worldmap)
will create a line chard of the last 10 years of the selected countries

Barchard:
[coutry[year [GGE/GDP, GGE/POP, GGE/(POP+Imp+Exp)]]]
Barchard of the 3 ways of GGE representation.
year of barchard might be selected by selecting the year on the linechart.
"""

"""
How it works?
Select a country on world map by clicking on it.
Instandly make line + bar chard.
By selecting another courty up to 5 add the country in the linechard and replace the barchard
Of the selected countries a list is represented by clicking on one of them the lines in the chard are deleted.
"""
