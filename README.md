# MilwaukeeM18-2-CarCigaretteLighter

![assembly](https://github.com/BrennerLu/MilwaukeeM18-2-CarJack/blob/main/images/assembly.png)

## Description

A small device, compatible with Milwaukee's M18 series of batteries. It contains an undervoltage-lockout as well as a buck converter delivering 14 Volts at 15 Amps to a cigarette lighter outlet, found in most cars. It can be used to power car-ready appliances like USB-PD chargers, camping fridges and inverters.

![pcb_top](https://github.com/BrennerLu/MilwaukeeM18-2-CarJack/blob/main/images/pcb_top.png)

## Features

- Outputs clean 14V / 15A DC
- snaps right into Milwaukee M18 batteries
- current reduction for small battery sizes like 2.0Ah
- two stage overcurrent protection
  - soft overcurrent protection by lowering the duty cycle of the buck converter
  - short circuit protection via LP Mini blade fuse (commonly found in modern vehicles)
- undervoltage-lockout at 15.5V

![pcb_bottom](https://github.com/BrennerLu/MilwaukeeM18-2-CarJack/blob/main/images/pcb_botttom.PNG)

## Thanks to

- My girlfried for helping me model the case

- [oxullo](https://github.com/oxullo) for providing the CAM jobs, design rules and ulps used in this project
