# cieColor
A php class that calculates color values such as CCT, color coordinates and 15 CRIs from a given spectrum

As input a spectrum array in the format $spectrum = [[wavelength in nm, power in W/nm], [...]] in the range of 360 to 830 nm in setps of 1 nm or less is required. The class will calculate varius color parametes such as the corelated color temperature, the color coordinates x and y, all 15 color rendering indices and more. For the CCT a 1 nm step CIE spectrum is used, for the CRI values a 5 nm step spectrum. Therefore the CRI values are less accurate.
The class is ment to estimate color values from simulated light sources.
