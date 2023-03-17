# python_course_project

!!! The DAS data is not included as it was too heavy to load on GitHub (1 file = 0.5 GB) but can be downloaded here: https://uppsala.box.com/s/4wjkpch1kf8rll9i3n62ylp5asw4bd1g

Project: reading seismic data stored in an HDF5 file

Some vibroseis seismic data were acquired in June 2022 in Sweden using an optical fibre cable. The data corresponds to strain measurements with respect to time for points along the fibre (channels). These channels correspond to an average strain measurement of a 5m-long section of the cable. The original sampling rate of the data is 20'000 Hz.

Goals:
- read the h5 file for one shooting point and retrieve the matrix for the strain measurements
- plot the data
- resample the data to 1 ms (=1000 Hz)
- plot the resampled data

If sufficient time:
- extract 25s of the data to correlate with vibroseis sweep, which is also 25s-long.
- cross-correlation with theoretical vibroseis sweep.
- extract the data from the shot timestamp + 5s

IMPORTANT UPDATE (2023-03-17): I didn't manage to get as far as I wanted since I had to spend some time on the theory of what I want to do and how to do it properly.
