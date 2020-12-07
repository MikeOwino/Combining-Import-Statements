# Combining-Import-Statements


We can import the collection of objects and functions with the same data.

We can use an import keyword to import both types of variables as such:

import { specialty, isVegetarian, isLowSodium } from './menu';
 
import GlutenFree from './menu';


### QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ


1.
Remove the import statement at the top of missionControl.js.

Once you have removed import, change each variable to its original, unaliased name within the rest of the file.

aircrafts to availableAirplanes
flightReqs to flightRequirements
meetsStaffReqs to meetsStaffRequirements
meetsSpeedRangeReqs to meetsSpeedRangeRequirements
If you see errors in the console, not to worry. We’ll resolve this in our last step!

2.
At the top of the file, we’ll now import all variables from the module.

Use import to import availableAirplanes, flightRequirements, and meetsStaffRequirements between a set of {}

Use import to import meetsSpeedRangeRequirements


Hint
import { availableAirplanes, flightRequirements, meetsStaffRequirements} from './airplane';
 
import meetsSpeedRangeRequirements from './airplane';
