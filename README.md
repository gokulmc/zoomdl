# ZoomDL
## Goal
Conferences, meetings and presentations held on Zoom are often recorder and stored in the cloud, for a finite amount of time. The host can chose to make them available to download, but it is not mandatory. 

Nonetheless, I believe if you can view it, you can download it. This script makes it easy to download any video stored on the Zoom Cloud. You just need to provide a zoom record URL (starting with _https://ssrweb.zoom.us/rec/play/..._), and optionally a filename, and it will download the file.

## Requirements
Only very standard modules are necessary: `requests`, `re`, `argparse` and `sys`. The 3 latter should be included in any python distribution, while the former is standard, and easy to install (try `pip install requests` or `conda install requests`).