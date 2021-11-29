#### Sam's devlog 3, November 29, 2021

---

#### Updates

* Had fun searching the LAC database for historical maps and images of the Chaudiere Falls. LAC holds many of these and most, if not all, are in the public domain. I downloaded several maps and images and captured key metadata in an Excel spreadsheet. Most items were in .jpeg format but some were PDFs. I found a free online converter that allowed me to convert the PDF files to .jpegs.
* I used some of these maps and images for a PowerPoint presentation for an environmental history seminar with Joanna Dean. The presentation was on the contested nature of the Chaudiere Falls and the changing uses and meanings of the site over time. This helped me think through my ideas for HIST 5706.
* Started working on a web map based on Leaflet. I used the Leaflet tutorial as my guide and modified the code as needed. I now have [the beginnings of an interactive web map](https://samuelmickelson.github.io/HIST5706_Project/Akikodjiwan/) which I am making accessible via GitHub Pages.
* The web map is very bare bones at the moment. I've inputted some more precise longitudinal and latitudinal data into the JavaScript code and used MapWarper to georectify a government map of the falls from 1926. I have added this georectified map as a tile layer in the code and am excited to see it appear on the web map. This is just a start and I am looking forward to seeing my work on the web map progress.

#### Challenges

* I struggled a bit with choosing a title for the map. I initially called it "The Chaudiere Falls across time," but I worried about the politics of this choice. My hope is that this web map is just the beginning of a bigger research project on the history of the Chaudiere Falls that employs digital mapping and historical GIS as key methodologies with settler colonialism and environmental history as my theoretical framework.
* From this vantage point, I wondered if it made more sense to use the Algonquin term for the falls and call the web map "Akikodjiwan across time." I have chosen this title for the time being, but I am concerned about it coming off as disingenuous given my social location as a non-Indigenous newcomer to Ottawa. So the title may change.
* Based on the Leaflet tutorial, I modified the JavaScript code to move the centre and periphery of the map closer to the Chaudiere Falls. However, I don't see the two 'pins' appearing on the map. I will troubleshoot this and ask for help if required.
* All of the historical maps and images of the falls that I found on the LAC database were either created by a government agency or artist of European origin. This is problematic for obvious reasons. It would be good to find some historical maps and images of the Chaudiere Falls created by Indigenous persons, but I realize that this may be outside the scope of this project. That said, I realize that the provenance of these maps--i.e. Library and Archives Canada--has some limitations in terms of methodology. I will add this point to my paradata document.

#### Next steps

* Change the base map to something more interesting and visually attractive.
* Use MapWarper to georectify several more historical maps and images of the Chaudiere Falls. Not sure if one can georectify an image (e.g. a painting or sketch) but I will look into it.
* Figure out how to add icons to the web map and how to design them in interesting ways.
* Figure out how to add accompanying textual information that pops up when someone clicks on an icon.
* Figure out how to add some general information, more detailed historical information, and sources that contextualize and enrich the information represented on the web map. Could I use GitHub Pages to create a static site with a landing page that links to the web map and other supplementary pages?
* Share completed web map on Discord by December 10. I believe that this is the new due date. December 10 or just a bit before would be ideal because it would give me a bit more time to do the kinds of things that I envision with this web map.
* NB: I don't expect the web map that I share at the end of this course to be a finished product. I expect it to be interesting--and hopefully informative--but I expect that I will be iterating and tinkering with the web map for some time after.
