# SeriesData
Method for creating immutable series data using IPFS.

# Overview
Many science experiments involve creating time series data. For this first section we will be ignoring time, and only concentrating on the serial nature of the data. While there are many choices of Block chains we are choosing the Inter Planetary File System (IPFS) for our first effort. It provides a permanent record of data submitted to the system for each record, and tracks changes. We desire to create a linked list of measurements, this can be thought of as personal blockchain measurements. 

# The Flow: 
* Create a measurement chain -- a genesis block
** Insert how to make a block
* Make a measurement
* Record a measurement
* link the measurement to the previous measurement

# Goals:
* Data is immutable -- IPFS
* Data is authenticated -- Public Key digital signature on each measurement
* Data series is enforced
* Data is easily retrievable
* Data is easily shared
* Data is searchable -- more on this at higher levels
