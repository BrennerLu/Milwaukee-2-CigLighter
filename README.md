# MilwaukeeM18-2-CarCigaretteLighter

There will be a redesign in the near future using the findings of [Tool Scientist](https://www.youtube.com/watch?v=q7spzrIbdKY). By using the official M18 battery protocol, the design will be more reliable while reducing cost and complexity.

![assembly](https://github.com/BrennerLu/MilwaukeeM18-2-CarJack/blob/main/images/assembly.jpg)

## Description

A small device compatible with the Milwaukee M18 range of batteries. It contains an undervoltage lockout as well as a buck converter that delivers 14 volts at 15 amps to a cigarette lighter socket found in most cars. It can be used to power car-ready devices such as USB-PD chargers, camping fridges and inverters.

![pcb_top](https://github.com/BrennerLu/MilwaukeeM18-2-CarJack/blob/main/images/pcb_top.jpg)

## Features

- Outputs clean 14V / 15A DC
- Snaps directly into Milwaukee M18 batteries
- Maximum current reduction for small battery sizes such as 2.0Ah
- Two stage over current protection
  - Smooth overcurrent protection by reducing the duty cycle of the buck converter
  - Short-circuit protection via LP mini-blade fuse (commonly found in modern vehicles)
- Undervoltage lockout at 15.5V

![pcb_bottom](https://github.com/BrennerLu/MilwaukeeM18-2-CarJack/blob/main/images/pcb_botttom.jpg)

## Thanks to
- [oxullo](https://github.com/oxullo) for providing the CAM jobs, design rules and ulps used in this project
