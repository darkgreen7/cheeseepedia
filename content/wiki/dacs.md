+++
title = "DACS"
draft = false
tags = ["Animatronic Control Systems"]
categories = ["Disney Parks"]
startDate = ""
endDate = ""
contributors = ["The 64th Gamer"]
citations = ["[https://archive.org/details/paradiseprogramt0000hade/page/246/mode/2up?q=DACS+animatronic](%22https://archive.org/details/paradiseprogramt0000hade/page/246/mode/2up?q=DACS+animatronic%22)","[https://archive.org/details/mis-newsbreak-v-01-n-02-1979-08/page/n3/mode/2up?q=DACS+animatronic](%22https://archive.org/details/mis-newsbreak-v-01-n-02-1979-08/page/n3/mode/2up?q=DACS+animatronic%22)","","[https://archive.org/details/computersdatapro0000mand/page/444/mode/2up?q=dacs](%22https://archive.org/details/computersdatapro0000mand/page/444/mode/2up?q=dacs%22)","[https://www.disneydocs.net/_files/ugd/5db718_cdd7e71d2eec476d80099e1ed01d216f.pdf](%22https://www.disneydocs.net/_files/ugd/5db718_cdd7e71d2eec476d80099e1ed01d216f.pdf%22)"]
pageThumbnailFile = "aj2ghfZfCCtAnWrKI4uC.avif"
+++
The ***Digital Animation Computer System (DACS)* was an animatronic programming and control system that debuted on October 1, 1971 for the Magic Kingdom located in the utilidors area directly under the *Mickey Mouse Revue* (Now *Mickey's Philhar Magic)*.https://archive.org/details/popularelectroni02unse_0/page/46/mode/2up?q=DACS+animatronic
It would later be implemented at Disneyland some time before 1979, and at EPCOT on its opening day of October 1, 1982. The system is seen being used up until 1995, though it is unclear when it was replaced by later systems.**

## History

Disneyland's Audio-Animatronics used simple mechanical systems to achieve their movement, using various mechanical timers, camshafts, and rotating drums. During Magic Kingdom's development, this was to change with a full digitization of show animation.https://archive.org/details/eev-07-n-29-1977-07-22/page/n1/mode/2up Dave Snyder was head of the project, whom found that older animators were scared of the computerization of the world. He wrote a pamphlet called ***DACS Facts: or A Mickey Mouse Guide Through The Snow* to calm these fears.^(1)^ Most of Magic Kingdom's shows featuring animatronics would use the DACS system, though certain animatronics that were too far away from DACS Central in Fantasyland however would continue to use the older mechanical systems, alongside certain rides like *Pirates of the Carribean* using a mix of both systems.
Disneyland would later integrate the DACS system at an unknown time. The second generation of DACS would begin development around August of 1979, upgrading their computer systems and software with multiple new hires for the project.^(2)(5)^ EPCOT would be the first to use this new system with its opening in 1982, having the system located in the Computer Central area.https://archive.org/details/sim_mis-week_1987-11-30_8_48/page/n11/mode/2up?q=DACS+animatronic^(3)^**

## Hardware

It is currently unknown what systems were originally used for Magic Kingdom and EPCOT, though they most likely ran on the same computers as found for Disneyland.
The original Disneyland DACS system ran off a single [Honeywell DDP-516](https://t-lcarchive.org/honeywell-ddp-516/) minicomputer.https://frankmezzatesta.com/wdi_1979.php^(4)^ The later second generation of DACS switched to a [Data General Eclipse S/250](https://cdn.macrosport.com/books/dtdf/ch12/dtdf_ch12p22.jpg).
By 1995, the Magic Kingdom DACS system can be seen running on something different than the notably short S/250 system, though it is unclear what exactly the minicomputers are.^(3)^

### MACS

The ***Micro Animation Control System (MACS)* was a small programmer created by Steve McIntyre in 1977 to replace the drum and camshaft systems from these farther away rides, being around the size of a suitcase and meant for smaller Audio-Animatronics. It is unclear however if MACS was ever deployed after its testing.^(4)^**

## Programming

DACS shows are programmed either on the central console in the DACS room, or on a portable unit that is wheeled out to the needed show. Multiple other cabinets and devices are needed to be wheeled out as well.https://youtu.be/41kIL7P4q2k

### Data Format

Compatible Audio-Animatronics are built with two different types of movements, digital (on or off), and analogue (any position). DACS data is made up of 16-bit words, where the left-hand byte is the address, and the right-hand byte is data. For analogue, the appropriate Feedback Servo Card is listed in the address, and the 255 possible positions of that servo is sent. For digital, the address specifies the Discrete Channel Card, where each bit in the data byte is used to control a single movement, up to 8 being set in a single command.^(5)^
Data is stored in a frame buffer format, rather than command-based, which means no dropouts occur at the cost of more data being stored. It is unknown what the framerate of the data is stored at.https://archive.org/details/computersdatapro0000mand/page/444/mode/2up?q=DACS+animatronic

### Storage

When a show is being animated, the data is stored on magnetic tape. Show audio is played off of a separate reel and is never mixed with data. Once the final version of a showtape is finished, the data is copied to magnetic disks for continuous playback, while the master tape is stored safely in another location.^(1)^

### Audio Format

Audio tapes were recorded on 2-inch, 24-track magnetic tape, with one of the tracks using a time-code to synchronize with the show computer.^(2)^

## DACS Shows

TODO: Fill out rest of shows

### Magic Kingdom

- Country Bear Jamboree - October 1, 1971^(0)^
- Mickey Mouse Revue - October 1, 1971^(0)^
- Hall of Presidents - October 1, 1971^(0)^
- Haunted Mansion - October 1, 1971^(0)^
- It's a Small World - October 1, 1971^(0)^
- Peter Pan's Flight - October 1, 1971^(0)^
- Sunshine Pavilion - October 1, 1971^(0)^
- Flight to the Moon - December 24, 1971^(0)^
- Pirates of the Caribbean - December 15, 1973^(1)^
- Carousel of Progress - January 15, 1975^(1)^
- Jungle Cruise - (Unknown Renovation, before 1979)^(1)^
