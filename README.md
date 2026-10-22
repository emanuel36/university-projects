# University Projects

Coursework and projects from my Computer Engineering degree at the Federal University of
Ceará (UFC), 2016–2019. Each folder was originally its own repository; their full commit
histories were merged here, so `git log -- <folder>` shows each project's original history.

Build artifacts, IDE caches and large generated data files were removed from history.

## Programming

| Project | Course | Year | Description |
|---|---|---|---|
| [fundamentos_de_programacao](programming/fundamentos_de_programacao) | Programming Fundamentals | 2017 | Exercises and assignments (C/C++) |
| [estrutura_de_dados](programming/estrutura_de_dados) | Data Structures | 2017 | Lists, stacks, trees, sorting and recursion (C) |
| [programacao_orientada_a_objetos](programming/programacao_orientada_a_objetos) | Object-Oriented Programming | 2017 | Assignments and the final cinema project (C++) |

## Embedded Systems

| Project | Year | Description |
|---|---|---|
| [bare_metal_gpio_bbb](embedded-systems/bare_metal_gpio_bbb) | 2016 | Blink an LED on the BeagleBone without an OS |
| [piano_bare_metal](embedded-systems/piano_bare_metal) | 2016 | Piano with buttons, LEDs and a buzzer (bare metal) |
| [piano_linux_embedded](embedded-systems/piano_linux_embedded) | 2016 | Same piano on embedded Linux |
| [parking_system](embedded-systems/parking_system) | 2016 | Parking assistant with ultrasonic sensor, buzzer and LEDs |
| [security_system](embedded-systems/security_system) | 2016 | Intruder detection alarm |
| [rtc_bbg](embedded-systems/rtc_bbg) | 2016 | Clock and date using the RTC (bare metal, Assembly) |
| [scan_memory](embedded-systems/scan_memory) | 2016 | Dump the bytes of a memory region (Assembly) |
| [lcd_16x2_beaglebone_linux](embedded-systems/lcd_16x2_beaglebone_linux) | 2018 | 16x2 LCD driver for embedded Linux |

## Computer Architecture

| Project | Year | Description |
|---|---|---|
| [filtro_assembly_x86](computer-architecture/filtro_assembly_x86) | 2016 | Filter in x86 Assembly called from C |
| [hack_assembly_compiler](computer-architecture/hack_assembly_compiler) | 2017 | Assembler for the Hack processor |
| [thumb_assembly_decoder](computer-architecture/thumb_assembly_decoder) | 2018 | ARM Thumb instruction decoder |

## Microcontrollers

| Project | Year | Description |
|---|---|---|
| [PIC18F4550_LIBRARY](microcontrollers/PIC18F4550_LIBRARY) | 2017–2019 | Peripheral library for the PIC18F4550 |
| [safe_box_pic](microcontrollers/safe_box_pic) | 2017 | Electronic safe box with the PIC18F4550 |

## Networks and Distributed Systems

| Project | Course | Year | Description |
|---|---|---|---|
| [calculadora_socket_udp](networks-distributed-systems/calculadora_socket_udp) | Computer Networks | 2017 | Remote calculator over UDP sockets |
| [projeto_final_RC_BBG](networks-distributed-systems/projeto_final_RC_BBG) | Computer Networks | 2017 | Final project: client/server on the BeagleBone Green |
| [controle_salas](networks-distributed-systems/controle_salas) | Distributed Systems | 2018 | Room control (light, AC) over MQTT |

## Databases

| Project | Year | Description |
|---|---|---|
| [delegacia_banco_de_dados](databases/delegacia_banco_de_dados) | 2018 | Police station database (SQL and Java) |

## Control and Instrumentation

| Project | Course | Year | Description |
|---|---|---|---|
| [pwm_ldr_pid](control-instrumentation/pwm_ldr_pid) | Automation and Control Systems | 2018 | PID light control with PWM and an LDR |
| [ARM_ROBOTIC_COLOR_SENSOR](control-instrumentation/ARM_ROBOTIC_COLOR_SENSOR) | Instrumentation | 2018 | Robotic arm with a color sensor |
| [low_pass_filter](control-instrumentation/low_pass_filter) | Instrumentation | 2018 | Audio low-pass filter with the Fourier transform (MATLAB) |

## Parallel Computing

| Project | Year | Description |
|---|---|---|
| [computacao_paralela](parallel-computing/computacao_paralela) | 2019 | MPI and OpenMP exercises: integrals, pi, matrix products |

The large input and output matrices were removed; regenerate them with the
`src/geradorMatriz.c` programs.

## Mobile

| Project | Year | Description |
|---|---|---|
| [Desenvolvimento_Mobile](mobile/Desenvolvimento_Mobile) | 2019 | Android assignments, including a Firebase contacts app |
