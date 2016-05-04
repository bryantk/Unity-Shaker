# Unity-Shaker
Perlin noise based shaking - for cameras, hits, and stuff.

### Usage
1. Add Shaker.cs to gameobject
2. Define maximume movement and rodation areas (TODO: Via code)
  * set Default shake power if desired
3. Call 'Shake()' with desired strength (1= minumum, 50=Crazy) and time

### Notes
Script will get mad if you try and move the object while shaking, so child the Camera/object to shake.
Use the parent for normal movement, and the child for shaking only.

Ex.)
* Null Game Object  (move this)
  * Camera          (shake script on this)
  
### TODO:
* Define shake position/roatation via code.
* Remove default shake strength
* rename power to strength
