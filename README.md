# wow_auction_house
It's my first real data science project, designed to track World of Warcraft's commodities prices and quantities in the Auction House in order to make purchase decisions based on statistics and profit margins.

The project revolves around Python and SQL, with python doing an initial extraction by requesting an OAuth token for Blizzard APIs, calling the commodities Auction House API which returns snapshots of all current regional auctions on the commodity. We later aggregate this data at an item level into minimum and executable prices, as well as all quantity traded at that given moment.

The idea is to take periodic snapshots of the commodities auction house in order to visualize and identify price trends and liquidity, meaning, will a "profitable" item actually sell or not.
Additionally, it includes a join with the Blizzard "Item" API in order to get item names, classes and subclasses, in order to segment auction information by specialization.

Although this all revolves around a videogame economy, it is a practical project that involves all things Data Science: from extracting, transforming and loading data, as well as making "business" questions and trying to answer them via queries, visualizations and statistics.
