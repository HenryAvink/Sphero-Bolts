Programmers: Henry Avink and Zachary Villarimo
Date: 5/3/22
Program: Maze

async function startProgram() {
	// Write code here
	await scrollMatrixText('START', { r: 256, g: 256, b: 256 }, 15, true)
	await delay (2);
	setSpeed(75);
	await delay (2.4);
	setSpeed(0);
	setMainLed({ r: 0, g: 0, b: 256 });
}
