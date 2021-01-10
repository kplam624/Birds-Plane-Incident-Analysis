# Bird/Plane Incidents

## Birds and Planes

Group 8 (Combat Wombats)

### Team Members

* Rongjun "Tom" Ding

* Joe Lubrano

* Kevin Lam

* Rafael Rodriguez

* Ramyata Umpaka

## Resources

---

The database that we worked with is database.csv. This database was found on www.kaggle.com with the link listed below.

[link to the database](https://www.kaggle.com/faa/wildlife-strikes)

Cleaned_data.csv- the final database after cleaning.

Brainstorming.txt

### Software

---

* Python 3

* Matplotlib

* Pandas

## Goal: Create awareness of the issue of birds striking airplanes and identify important factors related to this occurrence

Our team looked for trends and risks associated with bird strikes over a 15 year period (1990-2015) in the U.S. (states and territories) and Canada.

## Roles

---

* Data Cleaning - All team members

* Plane Damage Analysis - Ramyata Upmaka

* Statistical Analysis - Rafael Rodriguez

* Region Analysis - Joe Lubrano

* Bird Analysis - Kevin Lam

* Weather and Precipitation Analysis - Rongjun "Tom" Ding

## Cleaning Process

---

In our analysis we had decided to look at the territories within the United States. Cleaning was required as animals would appear that are not birds(e.g. deer, alligators, turtles, etc.). Further cleaning was needed to remove unknown and private planes. NAN records were changed to 0 as the database counted 0 as false. When appropiate the zeroes were removed from the database(e.g. Names). The result is the final database Cleaned_data.csv.

More indepth explanation of cleaning in "Cleaned_Database_Code.ipynb".

## Results / Findings

---

Upon finishing the analysis there are interesting findings.

### Strikes by Season

---

![Bird Strikes By Season](Output_data/BSbySeason.png)

![Bird Strikes By Month](Output_data/BSbyMonth.png)

![Bird Rate of Injury](Output_data/bird_rate_data.png)

When it comes to the frequency of bird strikes, a majority of them occur during the Summer by a large margin. When it came to the months the highest frequency of bird hits occur during September. August, September, and October have the three highest incident rate of bird hits. An even more interesting event is the rate of injury and death from the incidents. With January leading the way with the highest percentage of injury.

### Plane Damage

---

![Plane Damage](Output_data/PlaneParts.png)

![Plane With Fatalities](Output_data/PlanePartsFatalities.png)

![Plane With Injuries](Output_data/PlanePartsInjuries.png)

With the plots above, we examine incidents involving the plane's parts. From the first plot the most hit is the windshield followed by the nose of the plane. While these parts are the most hit, the part that is damaged more frequently is the Wing or Rotor of the plane.

### Weather Conditions

---

![visibility](Output_data/Visibility_vs_bird_strikes.png)

When looking at the conditions, based on the data a majority of the incidents are during the day.

### Bird hits by Area

---

![birdsbyregion](Output_data/SBSinFAA.png)

The  top three states that have the most incidences are Texas, California, and Florida.

![airportmap](Output_data/Screenshot(200).png)

This map is represents the top 100 airports with the most incidences in the United States. Based on this heat map the east coast has a large cluster of airports.

### Types of Birds

---

![bird by flock](output/known_inc_bar.png)

The above chart shows the frequency of hits and the size of their flock.

![bird](output/birds_bar.png)

Based on the plot above the most common bird involved is the gull followed by the mourning dove.

![Incidences by known](output/inc_by_quant.png)

With the above charts, we find that the birds that strike planes are individuals. The chart above represents a further breakdown on the top ten bird and their flock size.

### Statistical Analysis

---

![chi-square](Output_data/bird_correlation.png)

The chi square above shows that the time of day does have a relationship to the amount of bird hits.

### Conclusion

---

Based on our analysis, the most common bird in the bird strikes are the gulls. Bird strikes mainly occur on the coast. With the help of the heatmap, it shows that the airports are located on the east coast as well. The summer time has the highest amount of bird hits of the seasons.

### Other words

---

* See our powerpoint presentation for interesting analysis: "Project-1_CombatWombats.pptx"

* All of the images, plots and charts are saved in the "Output" and "Output_data" files

* Methodology for cleaning the database at the beginning of the projects is in "Cleaned_Database_Code.ipynb" and the data is saved as a .csv file in the "Resources" folder (Cleaned_data.csv)

* Individual analysis questions are examined in other jupyter notebooks
