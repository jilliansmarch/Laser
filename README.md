# Laser
Jupyter notebooks to plot and save files from the laser.

### **LaserScans_ForMovies.ipynb**
Automates the laser/motor setup up to move to different points and gather data from the oscilloscope. Each point recorded saves as a .npy file like "Test_x0_y0.npy" for point (0,0). Then you can make a "movie" from the voltage/time distribution.

### **LaserScans_MiddlePlot.ipynb**
Plots .csv files of the voltage/time distribution from three individual points on each side of the rock, this is to calculate the velocity of the rock using its arrival times and distances across the rock.

### **LaserScans_ReshapedPlot.ipynb**
The .npy files are stored as a 1D array, with time values as the first half and voltage values as the second half. We must reshape. This plots each point on a voltage/time graph.

### **LaserScans_Traveltimes.ipynb**
This is for a linear scan (in the y-direction) of points along the rock. We can see how the arrival times of the wave differ before and after where the transducer is.
