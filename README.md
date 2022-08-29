# Pepsitech_G7
# Buy a Thrustmaster.

Originally designed to reduce the CLACK of the G27. This project transformed itself into customizable platform, that main goal is to support OSW (if the stock board dies I can just slap an H-brige and a stm32 board and be ready to go)

All of the 3d printed parts are printed in PLA, with efficiency and strength in mind. Steering column support, simply named front and back plate are designed to allow various gear ratios, and make alignment of back-front rods easier.

Belts used are HTD3M 8mm 330mm, they don't slip or stretch.

Rotation limiting is done by transmitting wheel rotation using a herringbone gear to a lead screw at the bottom, that hits stops after specified distance. It it entirely possible to make the wheel turn 1080 deg or 360 deg.
PC software will obv still think that it is 900 deg, but in most sims you can/ or have to set maximum wheel rotation, and it's the sim calculating when you should hit a soft stop after reaching max steering angle with the car.

Deadzone is still there, that's how brushed DC motors work, unfortunately. However by using smaller rated voltage motors there is possibility of reducing it, if not removing completely.


Thats all for now, I'll update this readme as the project continues