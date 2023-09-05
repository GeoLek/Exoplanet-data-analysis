Inside the notebook you will find a script that goes through the csv we have created before with all the TIC IDs that appear only one time in the TESS data.
We have set some limits (you can change them) on the light curve, normalized flux values so that we can exclude some light curves with strong outliers and possibly pick up some signals.
Both the light curves that we have preserved and the excluded ones are saved in different pdf files.
Also, before I run the script for thousands TIC IDs, I run a "warmup script". I noticed that the script for many TIC IDs runs faster if you first run the "warmup script". 
Possibly a bug, but not figured it out yet.
