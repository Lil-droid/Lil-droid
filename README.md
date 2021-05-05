
function createBoard (cellsArray) {
    cellsArray = [, , , , X, , , , ];
}

// call createBoard function 

function resetGame () {
    //clear cellsArray to reset game
    //and call createboard
}

function checkForWin() {

}

function checkForDraw () {

}

function validatePlay {
	// check if the square attempted has already been played
}

function Oplayer {
	function Oplaying {
		// call validatePlay on square passed
	}

	function Orandomplayer {
		// loop through numbers 1 to 9 to find a square to play
			// call validatePlay
			// if play is valid
				// play square and break loop
			// else
				// continue loop
	}

// Check for tactical play option
	// If tactical option available
		// call Oplaying(tacticalsquare)
	// If no tactical option, 
		// call Orandomplay

// call checkForDraw';
// call checkForWin
}

function Xplayer {
	// check which square was played by user
	// call validatePlay on square played
	// if play is valid
		// play square
		// call checkForDraw
		// call checkForWin 
		// call Oplayer
}
