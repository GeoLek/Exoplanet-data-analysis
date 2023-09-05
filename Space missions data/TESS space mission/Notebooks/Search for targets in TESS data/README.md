Inside this directory you will find notebooks that will help you search for targets that appear certain times (1,2 etc) in TESS data. And then inspect them based on their light curve. 
Data will be in csv format which will be manipulated using the Pandas module. 
Firtsly, you should download the sectors you want to search (or all of them), from the TESS website (https://tess.mit.edu/public/target_lists/target_lists.html) and put them in the same folder with the notebook.
Then you can run the corresponding notebook which will produce the targets (by their TIC IDs) that appear one, two or more times in the TESS data, based on your choice.
Then using your produced csv file you can run the corresponding notebook that will produce a pdf file, where inside will be the light curves of all the targets you have found.
