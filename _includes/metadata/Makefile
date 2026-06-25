## Description: Download metadata for SCORES from the Google Spreadsheet.
##              Update the SID variable below when the deployment of the
##              Google Apps Script has changed.
##
##              Type "make" in this directory to download the JSON files for the metadata.
##

SID = AKfycbw3C-1VEObsDfzPGKLOSY2GynDVWpuKlLpQfCDs-vjAwl_4JOF5Br_ysu7jpKH7Ga4zDA
SID2 = AKfycbxYuMmeICcvXiqguS37qF7aE4DNw-wuhpGTWcO2sx1cUrwf0PW1g578log9wkX6r-tY

all: download

download: works pieces dendrogram

works:
	curl -L "https://script.google.com/macros/s/$(SID)/exec?sheet=works" > works.json

pieces:
	curl -L "https://script.google.com/macros/s/$(SID2)/exec?sheet=pieces" > pieces.json

dendrogram:
	curl -L "https://script.google.com/macros/s/$(SID2)/exec?sheet=dendrogram" > dendrogram.json



