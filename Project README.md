Added a title to the game of "Ring-a-Neck" surrounded by h1 tags that has title set as id. HTML
Added nine holes and moles to the grid in the game as div elements. HTML
Added a start button and styled it. HTML.H2 / CSS.#STARTER
Added the missing query selectors for the score and timer. JS
Added randomInteger() function to implement the randomInteger(min, max). JS
Added setDelay() function that returns the correct values when a difficulty is set. JS
Added chooseHole() function that returns a random hole so it doesn't return the last hole. JS
Added toggleVisibility() function that uses hole.classList.toggle() to add or remove the show class. JS
Added showAndHide() calls toggleVisibility() to show or hide a mole after a delay of time using the setTimeout() function provided. JS
Added showUp() function that calls setDelay() and chooseHole() to set a delay and hole used to call showAndHide(). JS
Added gameOver() function to determine if the game should continue or stop. JS
Added startGame() function that starts the game when the start button is clicked. JS
Added updateScore() function to score points by increments of 1, and that updates the scoreboard. JS
Added clearScore() function that sets the points to 0, and updates the scoreboard when the game finishes and the player wants to play again. JS
Added setEventListeners(moles) adds a click event listener to each of the moles. JS
Added whack(event) that calls updateScore() when a player clicks on a mole. JS
Added startTimer() and updateTimer() functions using setInterval() to create a timer that informs the player how many seconds they have left. JS
Added audio music while playing the game. HTML.AUDIO / JS
