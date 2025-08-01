+++
title = "3-Stage Command Format"
draft = false
tags = ["Showtape Formats"]
categories = ["Chuck E. Cheese's"]
startDate = ""
endDate = ""
contributors = ["The 64th Gamer","Ls2018"]
citations = []
+++

## Post-93 Bit Shift

In May of 1993, starting with the {{< wiki-link "Best of CEC TV 1993" >}} showtape, the data placed on the tape would be shifted alongside updating the {{< wiki-link "3-Stage Control System" >}} EPROM chip to read the shifted data. This would be done to invalidate all previous shows from being played.
The format for this shift was applying an XOR mask to the second byte of the movement controls, being XOR 0x1F. This is the same operation for converting pre-93 signals to post-93, and decoding post-93 signals back.
Example:
A movement command, 1@ (ASCII characters) is provided. XOR-ing the second byte, '@', with 0x1F (hex number) will provide an ASCII character '_', making the new command 1_. XOR-ing '_' with 0x1F once again will return it to being '@'.
