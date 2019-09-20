# TroPy
TroPy automatically scrapes and classifies trophic information from Bugguide. Bugguide using a server was able to go through over 50,000 pages of organism information (in under 24h), scrape information related to their consumption habits and classify the organism into a trophic category. In total there are 15 categories:\
xylophagus\
folivorous\
nectarivorous/palnyvorous\
phytosuccivorous\
algivorous\
frugivorous\
radicivorous\
granivorous\
parasitoid\
entomophagous\
algivorous\
parasitic\
saprophytic\
detrivorous\
fungivore\

# Prerequisites
Python 3 is necessary to run this script as well knowing how to run scripts on command line.

# Installation
Glone this repository into a folder on your system. Repository includes two dpcuments, the script and a dictionary of terms.

# Running
To run, set up a job on your server, and run the command:\
./TroPy_script.py

# Completion
Upon completion a new csv file will be created called Scraped_df.csv with all organisms consumption habits and a final classification category.

# Authors
J Raffington - MBINF Summer Project
