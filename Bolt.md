Programmer: Henry Avink
Date: 5/4/22
Program: Figure Eight
Serial Number: SB-F28B

async function startProgram() {
	await speak("Spinning in a circle", false);
	setSpeed(75);
	await spin(360, 5);
	await spin(-360, 5);
	// Write more code here
	exitProgram();
}
