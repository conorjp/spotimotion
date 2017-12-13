# spotimotion

In the base-level directory, the Python files are the scripts used to pull data from Spotify. spotifyGrabber.py was the original script, which hit rate limits on the API, so it was broken into several smaller scripts. They are executed in the following order:
1. getTracks.py
2. getTime.py
3. getFeatures.py
4. plotResults.py

The CSV files contain data from the latest run-through of the programs. The file results.txt contains statistical data which was written while executing plotResults.py.

In the Plots folder are scatter plots, generated by Python, for all of the audio features we analyzed, all plotted against months as well as years.

In the Events folder, there are modified versions of the same python scripts, which were customized to find event data. The CSV files hold data for specific dates surrounding significant events. There is also a scatter plot showing the valence of Spotify listens during the time period.

In the gDelt folder is another python script, used to calculate the avgTone feature for certain time periods. There is also event data from the GDelt database, and graphs of the avgTone around certain significant events.
