# MSDS459-Week-3.-Individual-Assignment-1

Part 1 - Week 1 - Knowledge Graphs

Readings for week 1 from the Knowledge Graphs textbook included the first two chapters of the book.  The first chapter gave an overview of Euler Paths and Circuits, introduced Knowledge Graphs, and explained the relationship between the two.

According to Gupta (2024), the concept of a knowledge graph can be understood in five simple points.  First, a knowledge graph organizes data by defining entities in data by their relationships to other data.  Second, this is a unique approach as the data is now stored in a method where the structure itself defines the relationships between entities.  Third, this is different from a traditional database as it removes the need to store the different entities and relationships on disparate tables forcing the need to manually join them together.  Fourth, in a knowledge graph each entity is a node and the relationships could be drawn as lines connecting them.  Finally, this allows systems like AI to answer complex questions in a simpler way.

The article Euler and Hamiltonian Paths by GeeksforGeeks (2025) summarizes the concept of Euler Paths and Circuits in the following way.  Each defines a way through a knowledge graph where each connection or edge is utilized only once.  The Euler path will end at a place other than its start whereas a Euler Circuit stops at the same node it started at.  A Euler path can be found in a knowledge graph if precisely none or two of its nodes have an odd number of connections to other nodes.  Whereas a Euler Circuit can only exist if every node has an even number of connections.

The book's second chapter gives an overview of knowledge graph modeling methods.  In doing so it covers two primary concepts: the Resource Description Method (RDF) and the Wikidata model.

An article by Loshin (2022) gives an excellent overview of RDF.  According to that article, RDF is a way of representing connected data on the web based on relationships.  In RDF, statements are made about the relationships between different resources on the web.  These are statements describing the relationship between two objects consisting of a subject, a predicate, and an object.  The subject is the item being described by the relationship while the object is the related item.  The relationship between the two is described in the predicate.

Wikidata differs from this in three primary ways.  First, rather than just a set of three simple statements, wiki data stores richer details about each.  Almost like a set of three tables rather than three statements.  Second, wikkdata can have two different types of nodes: items and properties.  Items are specific things being described while properties are attributes that describe those items.  Finally, the connections between items or statements in wikidata contain claims, references, and qualifiers rather than just a describing word (Kejriwal, 2021).


References

GeeksforGeeks. “Euler and Hamiltonian Paths: Engineering Mathematics.” GeeksforGeeks, February 3, 2025. https://www.geeksforgeeks.org/euler-hamiltonian-paths/. 

Gupta, Raja. “Let’s Understand Knowledge Graph in 5 Simple Points.” Medium, November 27, 2024. https://medium.com/@raja.gupta20/lets-understand-knowledge-graph-in-5-simple-points-36999c79df8e#:~:text=A%20knowledge%20graph%20is%20a,tables%20without%20understanding%20the%20relationships. 

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. Knowledge graphs: Fundamentals, techniques, and applications. Cambridge, MA: The MIT Press, 2021. 

Loshin, Peter. “What Is RDF (Resource Description Framework)?” Search App Architecture, February 4, 2022. https://www.techtarget.com/searchapparchitecture/definition/Resource-Description-Framework-RDF#:~:text=The%20Resource%20Description%20Framework%20(RDF,of%20data%20based%20on%20relationships. 
