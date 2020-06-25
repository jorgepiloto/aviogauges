Avionics Gauges
===============

This repository holds a bunch of 3D printable parts for building custom avionic
gauges with flight simulation purposes. In addition to that, a simple Arduino
library under the name **AvioGauges.h** has been developed. This library is
supposed to simplify all different gauges testing process.

If final user just wants to use in FSX or XPlane, there exist many interface
software for exchanging data between hardware and flight simulator:

* The LINK2FS project: https://www.jimspage.co.nz/intro.htm
* Mobiflight: https://www.mobiflight.com/en/index.html


About this project
------------------

I became interested in aeronautics after installing the famous flight simulator
"Microsoft Flight Simulator X". It was beautiful to learn how different aircraft
were able to navigate without any visual reference, different real procedures
applied in aviation and trying to build my custom cockpit.

Once I bought a 3D printer (Anet A8 model) it was time to improve some of my
designs and share them with other virtual aviation enthusiasts.


How to contribute
-----------------

Every file must me completely reproducible, meaning no privative design software
or licenses. Final user will be provided with all necessary information within
piece's directory. Each part directory might contain the following structure:

```bash
awesome_gauge/
├── dwg/
├── img/
├── pcb/
├── stl/
└── HOW_TO_BUILD.md
```

Different directories might be included within each gauge folder: drawings,
images, printed circuit boards and standard tessellation language. Also, a
`HOW_TO_BUILD.md` file should be included. This file contains the following
sections:

* A brief device description
* Required "ingredients": type and number of screws, servos...
* Assembly process

If you want your design to be in this repository, please open a pull request or
just send and email to jorge@on-orbit.dev with subject "AvioGauges" so we can be
in contact and discuss about how to proceed.
