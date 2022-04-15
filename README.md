# emulator-sun-2
Emulator for Sun-2 workstation

This is the work of: Brad Parker <brad@heeltoe.com>

This is the old release using SDL1 and no 3c400 BPF code found with wayback machine at:

https://web.archive.org/web/20200218020012/https://github.com/lisper/emulator-sun-2

https://codeload.github.com/lisper/emulator-sun-2/zip/master

Newer version using SDL2 and 3c400 BPF code can be found here:

https://github.com/lisper/emulator-sun-2

This is a emulator for the Sun Sun-2 Workstation.  It's designed to
boot SunOS and emulate the display and keyboard found on an original
Sun-2 worksation.

I was frustrated by the original Sun 2 emulator - tme.  It's an amazing
piece of software but really hard to follow internally.  It seems to
be an extreme example of abstraction.  Perhaps too abstract, at least
for me.

So I wrote this to learn about the MMU and, well SCSI.  My goal is to
eventually create an FPGA version of the Sun-2.

It now boots SunOS 2.0, 3.2, and 3.5 cleanly.  You can install from the distribution tapes.
The SCSI emulation code is still shakey for tapes, however.

SunOS 2.0 will boot multiuser and works as you'd expect.

![Bild](https://github.com/petersieg/emulator-sun2-old/blob/main/sun2.png)

Disclaimer:

 * sun-2 emulator
 *
 * 10/2014  Brad Parker <brad@heeltoe.com>
 *
 * Copyright (C) 2014-2019 Brad Parker <brad@heeltoe.com>
 *
 * This program is free software; you can redistribute it and/or
 * modify it under the terms of the GNU General Public License
 * as published by the Free Software Foundation; either version 2
 * of the License, or (at your option) any later version.
 *
 * This program is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of
 * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 * GNU General Public License for more details.
 *
 * You should have received a copy of the GNU General Public License
 * along with this program; if not, write to the Free Software
 * Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA
 * 02110-1301, USA.
