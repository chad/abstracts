From Homogeneous Monolith to Radically Heterogeneous Microservices: The Wunderlist 3 Story

Homogenous, monolithic code bases are a nightmare to maintain. The more they grow, the "smarter" we get as developers, laying abstractions, metaprogramming, and any other trick we can think of to make it possible to survive under the weight of the giant.  When 6Wunderkinder released Wunderlist 2, its server-side APIs were created as just such a beast. We used every Ruby trick in the book, but as with all such monoliths, it was ultimately unsustainable.

In July of 2014, we replaced our monolith with a swarm of tiny services, written in many different languages.

In this talk, we'll recount the pains and joys of the migration.  How do you maintain a radically heterogeneous system with a small group of developers? How do you monitor a fleet of disparate microservices? How do you make it perform acceptably? How does it change the way you think about deployment?
