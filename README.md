# scribd-downloader
Scrib downloader parses network requests from a .har, then downloads and generates a PDF from the images.

### Usage
1. Open network tab.
1. Reload page.
1. Run through all images, single page at a time with network tab open.
1. Sort by waterfall to ensure order is correct.
1. Right click, select "Save all as HAR with content".
1. `$>./parse-har.sh www.scribd.com.har`

