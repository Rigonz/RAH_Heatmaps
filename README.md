# RAH_Heatmaps
## Geo-diacronic Heatmaps with data from RAH's Historia Hispanica

### Intro
The Spanish Royal Academy of History (*Real Academia de la Historia*) has a series of short biographies published online, including [Historia Hispánica](https://historia-hispanica.rah.es).
It is very notable that the biographies are georeferenced, that is: on the one hand, an interactive map has been built that shows important localities in the life of the group of the biographed persons, and, on the other, from each biography one can also access a map (not the general one).

In the words of the institution, it is *the most extensive information on Hispanic History gathered to date*, and *the first time that a virtual space of these characteristics has been developed*.
The website of the *Historia Hispánica* is very interesting and the amount of work behind it must have been large indeed.
I think there are not *more than 50,000 characters*, but just over 40,000 (the difference coming from repeated records),
that the georeferencing is very incomplete (most biographies only have their *α* and *ω*, nothing in between despite many biographies includind additional geodata),
and that there is a surprising number of small errors in the data organization,
but, all in all, the work is highly praiseworthy.

It is difficult, however, to dinamically visualize some trends, and that is why I have prepared a series of heatmaps with the data from the biographies showing the geodiachronic evolution of some simple variables: places of birth, places of death, and life itineraries.

The three attached maps show the evolution from the year -100 to 2000.
The dates that appear on the mobile ruler at the bottom of each map correspond to the center of the time interval, which extends for 100 years.
I have grouped the locations in a square grid with 0.1º increments (this makes comparisons between very different latitudes difficult, but it is the best simple solution).
The maps are zoomable, and the passage of time can be stopped, but I note that the maximum value associated with the color scale is not constant, it can vary between periods.
(When the exact location of an event is unknown the country is usually associated, which is why there are so many points in the centre of Spain or France at certain times.
The animation has just the right speed on my computer, but when converting it to HTML and uploading to the web this control is lost - apologies.
There is no major problem in tracing the geovital itinerary of each biography - except that there are too many to generate the map online in real time; it remains to be reviewed.)

### Direct Links
**Main page in Spanish**: [https://rigonz.github.io/RAH_Heatmaps/](main page)
**Map of births**: [https://htmlpreview.github.io/?https://github.com/Rigonz/RAH_Heatmaps/blob/main/docs/200%20rah_heatmap%20R0%20BI.html](births)
**Map of deaths**: [https://htmlpreview.github.io/?https://github.com/Rigonz/RAH_Heatmaps/blob/main/docs/200%20rah_heatmap%20R0%20DE.html(deaths)
**Map of itineraries**: [https://htmlpreview.github.io/?https://github.com/Rigonz/RAH_Heatmaps/blob/main/docs/200%20rah_heatmap%20R0%20IT.html](itineraries)
