---
title: "Achieving Artificial General Intelligence: Gaming"
tags: [Artificial Intelligence,Gaming,Machine Learning]
published: true 
layout : post
---


<p>Over two decades ago we have made significant progress on how machine learns, 
capable of superhuman performance and efficiency.However, the road to achieving artificial general intelligence (AGI) may not 
be a long one if challenges with compute catches up with the software.Here are curated events on how machines have 
matched human intelligence and surpassing it on a gaming task.</p> 

### 1996: Deep Blue 

<p>Deep Blue was a chess playing machine designed by IBM which started in Carnegie Mellon University. 
Chess is a 2 player strategy game that requires the king to be captured, each player begins with  16 pieces: one king, one queen, two rooks, two knights, two bishops, and eight pawns.</p> 

<p>Deep Blue was designed using the Monte Carlo search tree MCST to first calculate all the possible moves it could make, then consider all the possible human player moves in response, then consider all its possible responding moves. The hardware composed of 30-processor designed by IBM containing 480 single-chip chess search engines, with 16 chess chips processor operating at 120 MHz, 28 nodes and 135 MHz,2 nodes respectively. The chess chips are capable of searching up to 2.5 million chess positions per second. It relies on many of the ideas developed in earlier chess programs which includes quiescence search, iterative deepening, transposition tables. These ideas and others formed a very sound basis for designing and building a chess-playing system. Deep Blue solved the search problem under two guiding principles, first the search should be highly non-uniform and secondly the search should provide “insurance” against simple errors meaning the all move sequences are searched with the shortest time .Since it is known that strong chess players are able  to  calculate  well  beyond  the  depth  reachable  by  a  uniform searcher of any conceivable speed.</p> 


More on [Deep Blue](https://reader.elsevier.com/reader/sd/pii/S0004370201001291?token=E57B555CBB055680615B5BA1C12A4C8F56E3931C789D0C033825ECAE75315D2F61E86AF4906C6F992B3B83224020AD02)



### 2015: Alpha Go

<p>Go is two player board game with black and white stones, 181 and 180 stones respectively totaling up to 361 stones. Go is played with a different goal in mind compared to chess, the main objective is to is to surround and capture the opponent's stones or strategically create spaces of territory. Once all possible moves have been played, both the stones on the board and the empty points are tallied. The highest number wins.As simple as the rules may seem, Go is profoundly complex. There are an astonishing 10 to the power of 170 possible board configurations - more than the number of atoms in the known universe. This makes the game of Go a googol times more complex than chess.</p>

<p>AlphaGo, a computer program designed by DeepMind with combines the use of advanced search tree with deep neural networks. The neural network takes the 19×19 grids of the board as an input and process it through a number of different network layers containing millions of neuron-like connections. The neural network is designed to two one part as the “policy network”, selects the next move to play and the other as the “value network” that predicts the winner of the game.</p> 

<p>According to the DeepMind Research AlphaGo was first subjected to playing amateur games to develop understanding of reasonable human play and then it played against different versions of itself thousands of times, each time learning from its mistakes. The concept of self-machine learning is known as reinforcement learning. With this reinforced learning AlphaGo improved and became better at learning and decision-making.AlphaGo became the first program to defeat a world champion in the game of Go. Designed using neural network trained by supervised learning from human expert moves, and by reinforcement learning from self-play. AlphaGo becomes its own teacher: a neural network is trained to predict AlphaGo’s own move selections and also the winner of AlphaGo’s games. This neural network improves the strength of tree search, resulting in higher quality move selection and stronger self-play in the next iteration. However, a new program AlphaGo Zero achieved superhuman performance, winning 100-0 against the previously published, champion defeating AlphaGo.</p>


More on [Alpha Go](https://deepmind.com/research/publications/mastering-game-go-without-human-knowledge)



### 2019: DOTA 2

<p> DOTA 2 is multiplayer online battle arena (MOBA) video game. It is played in matches between two teams of five players, with each team occupying and defending their own separate base on the map. Each of the ten players independently controls a powerful character, known as a "hero", who all have unique abilities and differing styles of play. During a match, players collect experience points and items for their heroes to successfully defeat the opposing team's heroes in player versus player combat. A team wins by being the first to destroy the other team's "Ancient", a large structure located within their base.</p>


<p> OpenAI developed a program, OpenAI Five is a team of five artificial neural networks, simulating individual player without prior knowledge of playing Dota.OpenAI Five sees the world as a list of 20,000 numbers which encode the visible game state (limited to the information a human player is permitted to see) and chooses an action by emitting a list of 8 numbers. Once trained, these neural networks are creatures of pure instinct their neural networks implement memory but do not otherwise learn further. They play as a team, but we do not design special communication structures only provide them with an incentive.</p>

<p> OpenAI Five’s neural networks start out with random parameters, and uses our general-purpose training system, Rapid, to learn better parameters. Rapid has OpenAI Five play copies of itself, generating 180 years of gameplay data each day across tens of thousands of simultaneous games, consuming 128,000 CPU cores and 256 GPUs. At each game frame, Rapid computes a numeric reward which is positive when something good has happened (e.g. an allied hero gained experience) and negative when something bad has happened (e.g. an allied hero was killed). Rapid then applies our Proximal Policy Optimization algorithm to update the parameters of the neural network—making actions which occurred soon before positive reward more likely and those soon before negative reward less likely. The program can intelligently handle long-term  and short-term planning through  hierarchical reinforcement learning. OpenAI Five learns professional-level strategies from scratch—no human data provided.</p>

More on [Dota 2](https://openai.com/five/#overview)

<p> The long-standing goal of artificial intelligence is a system that learns with superhuman proficiency. However, the long road is to achieve artificial general intelligence may not be far off, but hardware requirements will have to catch with the growth on how intelligent systems are built.</p> 
	