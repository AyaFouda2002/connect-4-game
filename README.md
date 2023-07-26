# connect-4-game
## Link PowerPoint 

https://www.canva.com/design/DAFosi0Qunk/iwgxg5y2apaJEzEYmpILFA/edit?utm_content=DAFosi0Qunk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

## Abstract 
This paper presents the development of a graphical user interface (GUI) for playing Connect Four, a popular two-player board game. The GUI incorporates three levels of difficulty: easy, medium, and hard. Each level utilizes different algorithms and strategies to provide varying gameplay experiences. The implementation of the GUI aims to provide an interactive platform for users to play Connect Four against computer opponents of different skill levels.

## Introduction
Connect Four is a strategic board game that requires players to strategically drop colored tokens into a grid to connect a line of four tokens horizontally, vertically, or diagonally. With its inherent complexity, Connect Four has been a subject of interest in the field of artificial intelligence, offering a challenging environment for developing intelligent gameplay algorithms. In this paper, we present the development of a graphical user interface (GUI) for playing Connect Four. The GUI incorporates three levels of difficulty: easy, medium, and hard. Each level utilizes different algorithms and strategies to provide a distinct gameplay experience. The easy level serves as an introductory level, where the computer opponent makes random moves. This level allows novice players to familiarize themselves with the game and its dynamics, without facing a strong strategic opponent. The medium level employs the Minimax algorithm with alpha-beta pruning. This algorithm explores the game tree to determine the optimal move by considering all possible future moves and their outcomes. By utilizing alpha-beta pruning, the search space is significantly reduced, leading to improved computational efficiency and more challenging gameplay. The hard level employs a combination of move evaluation, heuristics, and randomization to enhance gameplay. Move evaluation involves assigning values to potential moves based on their desirability, while heuristics guide decision-making by incorporating domain-specific knowledge. Randomization adds an element of unpredictability, making the computer opponent's moves more varied and challenging. Through the development of this GUI, players can now engage in Connect Four matches against computer opponents of different skill levels. The GUI not only provides an interactive platform for gameplay but also offers an opportunity to experience the varying degrees of difficulty and strategic decision-making involved in Connect Four.

## literature survey

# The random algorithm 

The random algorithm is a beginner-friendly Connect 4 strategy, suitable for minimal strategy and experimentation, but may not be effective against skilled or advanced algorithms.
how it works : The computer player selects a random column to drop its token into, without considering any strategic decision-making. chances of winning.
                                
# Minimax Algorithm

The minimax algorithm is used in game theory and decision-making to determine the best course of action provided that the adversary plays effectively as well. 

how it works : The algorithm creates a game tree with a heuristic function, evaluating nodes and choosing the highest and lowest scores for maximizing and minimizing players. It explores the tree recursively until a terminal state, where it assigns a score based on the heuristic function.

<img src="R1.PNG" alt="Image" width="620px" height="auto">

# Alpha Beta pruning
The alpha-beta pruning algorithm is a powerful technique for searching game trees and finding optimal moves in games with multiple alternative moves. It reduces the search tree size and eliminates the need to analyze all potential game pathways. 

how it works : The algorithm evaluates nodes in the game tree using a heuristic function, tracking alpha and beta values. It prunes branches with scores below beta and higher alpha values, updating until reaching maximum depth or pruning unlikely branches. It selects the highest score move as the best for the player

<img src="R1.PNG" alt="Image" width="620px" height="auto">

## Methodology


## Result 

file:///C:/Users/aelne/Desktop/UGRF/WhatsApp%20Video%202023-07-18%20at%2012.23.19%20AM.mp4

## Conclusion

In this paper, we presented the development of a graphical user interface (GUI) for playing Connect Four. The GUI incorporates three levels of difficulty: easy, medium, and hard. Each level utilizes different algorithms and strategies to provide a unique gameplay experience.The easy level allows novice players to learn and enjoy the game without facing a strong opponent. The computer opponent makes random moves, providing a simple and introductory gameplay experience. The medium level employs the Minimax algorithm with alpha-beta pruning, offering a more challenging gameplay experience. The computer opponent considers future moves and optimizes decision-making, creating a stronger strategic opponent. The hard level combines move evaluation, heuristics, and randomization to enhance gameplay. This level offers the most advanced and unpredictable gameplay experience, incorporating strategic decision-making, domain-specific knowledge, and varied moves from the computer opponent.The development of this GUI provides players with the opportunity to play Connect Four against computer opponents of different skill levels, offering a range of challenging gameplay experiences. The GUI serves as a platform for users to engage with the game and explore the strategies and decision-making involved in Connect Four. Overall, the development of this GUI enhances the accessibility and enjoyment of Connect Four, while also showcasing the potential of different algorithms and strategies in the field of artificial intelligence and game theory. The GUI encourages further exploration and innovation in developing intelligent gameplay systems for board games like Connect Four.





