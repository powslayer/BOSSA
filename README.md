BOSSA fortytwo-1.0.0
--------------------

BOSSA is a flash programming utility for Atmel's SAM family of flash-based ARM microcontrollers.
The motivation behind BOSSA is to create a simple, easy-to-use, open source utility to replace Atmel's SAM-BA software.
BOSSA is an acronym for Basic Open Source SAM-BA Application to reflect that goal.

The software was created by Scott Shumate with contributions from several
[contributors](https://github.com/shumatech/BOSSA/graphs/contributors).

FortyTwo Systems added support for the SAMC21/SAMC21N line of microcontrollers.

The software is released under the terms of the BSD license as specified in the LICENSE file.

Supported Device Families
-------------------------
 * SAM7S
 * SAM7SE
 * SAM7X
 * SAM7XC
 * SAM3N
 * SAM3S
 * SAM3U
 * SAM4E
 * SAM4S
 * SAMC21
 * SAMC21N
 * SAMD21
 * SAMD51
 * SAM3X\*
 * SAM3A\*
 * SAM7L\*
 * SAM9XE\*
 * SAMR21\*
 * SAML21\*
 * SAME51\*
 * SAME53\*
 * SAME54\*
 * SAME70\*
 * SAMS70\*
 * SAMV70\*
 * SAMV71\*

The following individuals and companies graciously provided development boards to assist the BOSSA project.
 * Atmel Corporation (SAM3N, SAM3S, SAM3U)
 * David Crocker (SAM4E, SAM4S)
 * Adafruit Industries (SAMD21, SAMD51)

When building bossac for arduino (```make arduino```), pass the system architecture and processor to the make command according to the following list:
 * ARM Linux 32-bit (arm-linux-gnueabihf),
 * ARM Linux 64-bit (aarch64-linux-gnu),
 * macOS 64-bit (x86_64-apple-darwin),
 * Windows (i686-mingw32),
 * Linux 32-bit (i686-linux-gnu),
 * Linux 64-bit (x86_64-linux-gnu)