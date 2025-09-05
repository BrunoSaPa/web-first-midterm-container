This file is to explain the AI usage on this project, the only place where i saw neccesary the use of AI was when i wanted to change the color in an img, or in this case svg when hovering in the social icons in the footer. I din't know how to change the color so I asked an ai how could i do this, it came up with this solution:


    filter: brightness(0) saturate(100%) invert(64%) sepia(77%) saturate(466%) hue-rotate(125deg) brightness(91%) contrast(89%);


Which pretty much is applying a fitler to the image when hovering, each field works like this:

brightness(0) - makes it black
saturate(100%) - keeps saturation
invert(64%) - inverts colors
sepia(77%) - adds sepia tone
saturate(466%) - increases saturation
hue-rotate(125deg) - rotates hue to get the teal color
brightness(91%) contrast(89%) - fine-tunes the final color


👍🏿