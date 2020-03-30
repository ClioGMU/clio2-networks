# Clio 2Network assignment

Your assignment is to take one of the sets of network data provided in this repository (or network data that your provide yourself) to create and interpret a historically meaningful network graph. There is sample code in the `networks-demo.Rmd` file which we will go over in class.

You may choose from several different datasets in the `data/` directory.

- The `abolitionist-*` data describes correspondence in the Boston Public Library between nineteenth-century abolitionists. The nodes are abolitionists, and the edges are the counts of the number of letters sent between them. Use this dataset to ask questions about which abolitionists were most influential in abolitionist circles. Are there people who appear to be influential who are a surprise? How does gender influence the network?

- The `courts-*` data describes the relationship between federal courts. The nodes are federal courts, and the edges are federal judges who served on both of the courts that are connected. (For example, a judge who was on a circuit court who got appointed to the Supreme Court.) Which courts are connected to one another? What is the clearest path to promotion to the Supreme Court?

- The `field-codes-*` data describes relationships between codes of civil procedure. The relationship is formed when one code borrowed legal language from another. The demo code gives an example using the state-level data: for this assignment you must use the more granular code-level data. (States had multiple codes over time.) Which codes were most closely connected to one another? Can you simplify the network to make a good visualization?

You should create at least one production-quality visualization, with nodes colored appropriately, edges appearing manageable, with titles and captions and labels as appropriate. Write about 500 words about what the visualization is and what you can learn from it.

## Credits

The file `PaulRevereAppD.csv` comes unmodified from Kieran Healy's [repository for "Finding Paul Revere."](https://github.com/kjhealy/revere) Please see his [blog post](https://kieranhealy.org/blog/archives/2013/06/09/using-metadata-to-find-paul-revere/). That data originally comes from David Hackett Fischer's book, *Paul Revere's Ride*.

The abolitionist correspondence network data [was scraped](https://github.com/wcaleb/mining-bpl/) from a Boston Public Library collection.

The courts data is taken from the Biographical Directory of Federal Judges.

The Field Code borrowing data comes from [this article](https://doi.org/10.1093/ahr/123.1.132) and [this code repository](https://github.com/lmullen/civil-procedure-codes).
