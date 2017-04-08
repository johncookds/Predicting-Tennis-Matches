These four pictures were created using rstudio and Gephi.

They are meant to vizualize the patterns in a year of tennis matches to allow for better understanding of the sport and who plays who.

Each node is a professional who played a match in 2015.
Each edge means the two professionals(nodes) played against each other in 2015.

firstpic.png:
This is the raw picture to give a starting point.

secondpic.png:
This is after ForceAtlas has been applied which seperates the nodes. ForceAtlas keeps highly connected nodes together whereas nodes with little connection are spread out. The nodes are colored by degree, to highlight the fact that ForceAtlas keeps high degree nodes close to each other(assuming they are highly interconnected as is the case here). Thus, we see that there is a core nucleus of players, these are players that participated in most of the 2015 tournaments.

thirdpic.png:
The network has been filtered to nodes with degree over 40. I then assign names to the nodes. We see that these nodes represent the most famous players in the game. This makes sense, because tennis is structured in terms of tournaments so those who win play more games as they advance to higher rounds.

fourthpic.png:
This picture is the same as the third picture(with slightly more filtering of nodes). However, it is colored by eigenvalue centrality instead of degree. Eigenvalue centrality can by thought of as nodes that are highly connected to nodes that are highly connected. Thus nodes with the highest eigenvalue centrality should be the best in the game because they not only play many matches but advance far enough to play other top players in the tournaments. The highest eigenvalue centrality is Andy Murray, one of if not the top player in proffesional tennis.