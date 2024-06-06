Entity Cycle RGB Colors
  - requires GetColorNames

  Attempts to read the current color of the bulb, and then cycle to the next (or previous depending on direction) color on that list.
  However when some bulbs are set they alter the value they're set to slightly, so an exact match is not always possible.  Therefore
  it uses color-distance to try to predict which color in the list the bulb is closest to, and then navigate the list from there.  You
  can add any of the colors GetColorNames to the list of colors, but you may need to muck about with the distance calculation depending
  on how your bulbs behave.

  
