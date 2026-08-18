# Chess-Engine-With-Automated-Move-Generation
This is a prototype for a chess program I finished senior year of high school (2022) using java in Eclipse. I wrote the project from scratch and worked on it for about nine months. 

There are two game modes. One is a fully functional two-player game mode. The second is one player versus a primitive chess bot. The bot can only play random moves. A tree data structure is implemented to store possible future board combinations. The tree is made up of nested arraylists of nodes that each store a reference to the parent node, an instance of the chess board object, the move count, and the depth level of the node. The system is implemented for a bot that plays random moves using an implementation of the tree data structure that looks one move deep. All chess rules and promotions are implemented such as castling, en passant, and promotion. 

Install all .java files and run ChessGame.java to play. 
