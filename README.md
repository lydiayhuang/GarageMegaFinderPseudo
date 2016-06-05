# GarageMegaFinderPseudo

--Using flask, python 2.7, html5, read csv, sf open data api



-commandline --
#user will enter location in SF via raw input
#pass input to a build-url function to create google api request
#open json received from google and parse request for users lat/long data
#store user's lat/long data (using tuple)
#open csv of garage info - loop over csv to compare user's lat/long to garage's lat/long
#Subtract garage list lat/long to csv lat/long
#sort list lat/long from smallest to largest different
#return top 3 smallest lat long via command line
#end
