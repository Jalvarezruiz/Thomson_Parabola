Thomson Parabola Analyzer
=====================
Macro to extract the spectral energy distribution of Ions from a Thomson Parabola image Plates
This macro asigns energies and intensities in PSL to the ion signals collected by the Thomson Parabola.
The software will ask you to:
	1 - Open the *.inf file of the image.
	2 - Ask for Tilting correction of the image.
	3 - Ask for the ion to be analyzed.
	4 - Select the origin of Ion Profile and a few points to trace the parabola of interest.
	5 - Indicate the pixel width of the Zero point.
	Then, it will calculate and assign energies to each pixel.
	Finally, it will store the pixel value in PSL for each bin of energy and plot it.
	
To use it, just copy the file in the plugin directory of ImageJ and restart ImageJ.
NOTE: The sript needs to be edited in order to include the corresponding Thomson Parabola B field and geometries.
To run it, go to the Plugins menu. It should appear at the bottom.

Any comment/improvement about the code will be welcome!

Latest version:
July 29th, 2013
Thomson_Parabola_v2_0.txt

Licence GPL - http://www.gnu.org/licenses/licenses.en.html
Javier Fernandez javier.fernandez-tobias@stfc.ac.uk 
Jesus Alvarez jalvarezruiz@gmail.com
