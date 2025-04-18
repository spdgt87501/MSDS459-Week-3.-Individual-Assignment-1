# MSDS459-Week-3.-Individual-Assignment-1

Part 2 - Week 2 - Knowledge Graphs

For week 2, chapter five of the textbook was assigned. This chapter touches on some key topics in regards to web information extraction or web scraping.  These topics fall primarily into two categories.  Wrappers and the Deep Web.

According to Kejriwal (2021), wrapper generators differ from traditional information extraction techniques such as named entity resolution by using the website tags to define their parameters.  This can often result in a variety of different wrappers being generated for different kinds of webpages.

Wrappers can come in four varieties.  These are manually constructed, supervised, semi-supervised, and unsupervised.  Manually constructed wrappers must be constructed for each webpage or page layout.  Supervised wrappers such as Minerva have various levels of ability to recognize content utilizing procedural programing.  While earlier versions like Minerva are still rules based requiring manual intervention to work exceptions, there are more advanced supervised wrappers such as Rapier.  Rapier utilizes natural language processing and contextual parts of speech to recognize labels for data (Kejriwal, 2021).

Semi-supervised and Unsupervised wrappers decrease the level of required setup and intervention.  While semi-supervised wrappers require less intervention than manually constructed or supervised ones, they still typically require either labeled documents to be trained on or for the user to conduct post-processing activities.  These post processing activities instruct the system on what information to pay attention to.  Unsupervised wrappers do not require any training examples or user intervention.  Some examples of unsupervised wrappers include RoadRunner, EXALG, DeLa, and DEPTA (Kejriwal, 2021).

Kejriwal (2021) describes the deep web as all of the data in the various databases web content is derived from.  He uses the example of an Amazon product search or product page.  The data presented on the page is pulled from a deeper behind the scenes database.  Hence, the deep web.  Most of the data in this behind the scenes database is not accessible to the end user.  However, Kejriwal (2021) also presents other examples where data tables are displayed directly on the webpage such as in the case of government sources.  According to Kejriwal (2021), these tables can be difficult for existing tools to read as the syntax is visual rather than verbal.  Additionally, such visually displayed tables cannot be queried upon directly using traditional methods like SQL.  One solution to this issue is to have the information extraction tool copy the table to a tool for spreadsheets such as Excel.  The secondary tool could interpret the information as a data table rather than text for it to be queried on.  The downside of this methodology is it assumes the web chart is formatted in a manner that could be successfully transformed into a CSV or in a tool such as Excel (Kejriwal, 2021).


References

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. Knowledge graphs: Fundamentals, techniques, and applications. Cambridge, MA: The MIT Press, 2021.
