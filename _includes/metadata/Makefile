##
## Programmer:    Craig Stuart Sapp <craig@ccrma.stanford.edu>
## Creation Date: Thu Jun  8 19:45:08 PDT 2023
## Last Modified: Thu Jun  8 19:45:11 PDT 2023
## Syntax:        GNU Makefile
## Filename:      _includes/metadata/Makefile
## vim:           ts=3:nowrap
##
## Description: Download metadata for SCORES from the Google Spreadsheet.
##              Update the SID variable below when the deployment of the
##              Google Apps Script has changed.
##
##              Type "make" in this directory to download the JSON files for the metadata.
##

SID = AKfycbw3C-1VEObsDfzPGKLOSY2GynDVWpuKlLpQfCDs-vjAwl_4JOF5Br_ysu7jpKH7Ga4zDA

all: download

download: works

works:
	curl -L "https://script.google.com/macros/s/$(SID)/exec?sheet=works" > works.json
