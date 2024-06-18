# rhlib
[Radiohead Public Library](https://www.radiohead.com/library/) Download Script

Forked in June 2024 from [Andrés Gottlieb's Radiohead Public Library Experiments](https://github.com/andresgottlieb/rhlib) and fixed up to work with yt-dlp. MIT licence remains the same as upstream.

---
## Download all videos

## Works on
1. Mac OS ✓
2. Ubuntu ✓


## Dependencies
1. [curl](https://curl.haxx.se/download.html) (probably already present in your system)
2. [jq](https://stedolan.github.io/jq/download/) (probably already present in your system)
3. [yt-dlp](https://github.com/yt-dlp/yt-dlp) (make sure you have the latest version)

## Installation
1. Install the dependencies above
2. Pull this repo or get both bash scripts
3. Make both scripts executable:

   a. ```chmod +x get.sh```
   
   b. ```chmod +x process.sh```

## Usage
Run ```get.sh```, and then ```process.sh```:
1. ```./get.sh``` (gets video info. from the Radiohead site)
2. ```./process.sh``` (downloads the videos from Vimeo and Youtube)
   
## Results
The videos will be downloaded to the ```./video/``` folder
