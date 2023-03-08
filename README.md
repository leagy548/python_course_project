# python_course_project

Project: reading seismic data stored in an HDF5 file

Some vibroseis seismic data were acquired in June 2022 in Sweden using an optical fibre cable. The data corresponds to strain measurements with respect to time for points along the fibre (channels). These channels correspond to an average strain measurement of a 5m-long section of the cable. The original sampling rate of the data is 20'000 Hz.

Goals:
- read the h5 file for one shooting point and retrieve the matrix for the strain measurements
- plot the data
- resample the data to 1 ms (=1000 Hz)
- plot the resampled data

If sufficient time:
- cross-correlation with theoretical vibroseis sweep.
- extract the data for the shot time + 5s
