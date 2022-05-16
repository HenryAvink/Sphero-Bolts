async function startProgram() {
// Write code here
await scrollMatrixText('START', { r: 256, g: 256, b: 256 }, 15, true)
await delay (2);
setSpeed(75);
await delay (2.1);
setSpeed(0);
setMainLed({ r: 0, g: 0, b: 256 });
await spin(90,.5);
await delay (0.5);
setSpeed(75);
await delay (1.35);
setSpeed(0);
await spin(90,.5);
await delay (0.5);
setSpeed(75);
await delay (0.7);
setSpeed(0);
await delay (0.5);
await Sound.play(true);
await spin(40, 0.5);
await delay (0.5);
setSpeed(75);
await delay (1);
setSpeed(0);
await spin(-90,.5);
setSpeed(30);
await delay (0.45);
setSpeed(0);
setMainLed({ r: 256, g: 0, b: 0 });
await delay (0.5);
setSpeed(30);
await delay (1);
setSpeed(0)
await spin(-90, 0.5);
setSpeed(75);
await delay (1);
setSpeed(0);
await spin(90, 0.5);
await delay (0.4);
setSpeed(30);
await delay (0.3);
setSpeed(0);
await Sound.Animal.play(true);
setSpeed(75);
await delay (0.48);
setSpeed(0);
await delay (0.4)

await spin(50, .5);
setSpeed(75);
await delay (.59);
setSpeed(0);
await spin(-90, .5);
setSpeed(30);
await delay (0.8);
setSpeed(0);
setMainLed({ r: 0, g: 256, b: 0 });
setSpeed(30);
await delay (0.35);

setSpeed(0);
await spin(-90, 0.5);
setSpeed(75);
await delay (0.7);
setSpeed(0)
await spin(-50, 0.5);
setSpeed(75);
await delay (0.7);
setSpeed(0);
await Sound.Animal.play(true);
await spin(50, 0.5);
setSpeed(75);
await delay (1.2);
setSpeed(0);
setMainLed({ r: 256, g: 0, b: 256 });
await delay (3);
await scrollMatrixText('Finish', { r: 256, g: 256, b: 256 }, 15, true);
}

