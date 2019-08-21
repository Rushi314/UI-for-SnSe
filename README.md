# UI-for-SnSe
Supernova Search Engine (SnSE) is an economical portable 1.2 m off-axis paraboloid dish transit telescope intended to scan the galactic plane daily at 11 GHz and detect radio continuum transients like Supernovae. The supernova rate in Milky Way is expected to be one in thirty years. Owing to interstellar opacity, they are likely to be visible in optical only if they happen within
a few kilo parsec distance. In radio, however, they can be spotted up to the end of the galaxy even with a modest sized telescope such as SnSE. The UI consists of a 2D plot with x-axis representing sidereal days and y-axis representing inclination of the antenna (i.e. direction of arrival of the received signal). The color depth of the point denotes the (normalized) intensity of the 11-GHz signal. The right hand panel consists of a histogram of average-subtracted intensity for a chosen day.

# Procedure to Input and plot the data:
1) Make a .csv file from a particular day’s data. The file should consist of observations on altitudes
starting from 0 degrees to 359 degrees.
2) Name the file as “Day###” where ### represents the day number. Example, “Day001” or
“Day234”. Here, the day number should vary from 0 to 366.
3) Put all the day data files in a single folder. Update the path of the folder at two different
locations in the code.
4) The data in every file is to be normalized. (However this can be changed).
