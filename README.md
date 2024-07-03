# 10x10x10-LED-Cube


An LED cube is a three-dimensional arrangement of light-emitting diodes (LEDs) organized in a cube shape. These cubes can vary in size, often ranging from small 3x3x3 cubes to larger and more complex designs like 8x8x8 or even 16x16x16. Each LED in the cube can be individually controlled, allowing for the creation of dynamic light patterns, animations, and visual effects.

LED Cubes consists of the following main components:
- **LEDs**: Light-emitting diodes (LEDs) will be used for the lighting and visual effects. The number of LEDs needed will be the dimensions cubed (2x2x2 = $2^3$ = 8, 4x4x4 = $4^3$ = 64, 8x8x8 = $8^3$ = 512, etc).
- **Microcontroller**: Main controller subsystem. It will control the LED pattern, logic, and timings.
- **Power supplies**:  Given the amount of current that will be needed, a number of power sources might be required (typically depends on how may LEDs are being used).
- **Resistors**: Will be used to control the current going into the LEDs to prevent them from burning out.
- **Transistors**: Turns current on for each layer. The number of transistors needed it equal to the number of layers in an LED cube.
- **Frame**: A bottom frame will be needed to enclose the electronic circuitry

In this project, we will be creating a 10x10x10 LED Cube, consisting of 1000 LEDs.


