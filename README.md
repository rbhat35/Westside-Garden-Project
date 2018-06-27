# westside-garden-project

## Getting It Working
1. Clone the repository
2. In index.html, scroll to the very bottom and replace <\*\*\*INSERT_KEY_HERE\*\*\*> (including < >) with an Google Maps API Key.

## Spreadsheet w/Data
https://docs.google.com/spreadsheets/d/1IWmwc73x9tjogpnBtetGn6-yAnTdCxXE1w__-g8khzc/edit?usp=sharing


## Adding New Addresses
1. Fill in columns A-F with information of the new garden
2. Fill in column L with "Yes" if the garden is a community garden. Type "No" or leave empty for it to display as a regular garden.
3. If including images: upload the image on site such as Imgur or Flickr (Google Drive and Dropbox will not work). Right click on the image and click "Copy Image Address." Paste the link into one of five image columns. Note: the map is currently set up to display at most 3 pictures. If  NOT including images: leave the columns blank.
4. Refresh the garden page. The Information should update.


## Technical Details
1. A garden will show up with an orange (community garden) marker if you enter any thing in Column L (the one titled "Community?") that is 3 characters or longer. If you typed "No" and it shows up as orange, check for spaces.
2. The "Address" column is not super picky, and you can often leave out a lot of information (e.g. mapping Georgia Acquarium, Atlanta, GA works). A basic rule of thumb is that if you enter the same address in Google Maps and it finds it without trouble, then you can put it in the Address field and it should work correctly.
3. Please do not rearrange/delete any of the columns in the spreadsheet. This will cause the program to stop work (note that Google Sheets stores history, so you can always restore it to a previous version if something is accidentally deleted).


### Many thanks to [crunchprank's blog](https://blog.crunchprank.net/google-sheets-to-html-table/) for the table on the website.

