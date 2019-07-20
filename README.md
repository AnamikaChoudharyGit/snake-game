JavaScript Snake<br/>
By Anamika Chaudhary<br/>


This is a DOM-based game of Snake that I wrote in JavaScript a few months back.

Other than the full screen mode demonstrated in the code, it can also be 
initialized in div tags within a page. Example:

    var mySnakeBoard = new SNAKE.Board( {
                                            boardContainer: "game-area",
                                            fullScreen: false,
                                            width: 580,
                                            height:400
                                        });
                                    
