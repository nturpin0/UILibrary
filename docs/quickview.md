# Quickview

## ShowCard 
Show result/images in a nicely formatted card with an icon
Shows a Card has a blue title block, where you can put an icon, and a title. Markdown wont work inside the card. Use the <code> ```<br>``` </code> tag to break up text. 

INPUT
```
- Process: ShowCard
- Background: (optional) Background color
- Icon: (optional) Name of the icon to be shown. Icons are from font-awesome, and require the font-awesome name eg book-open, home.
- Title: (optional) Title to be shown on the card, and at the top of the QuickView window.
- Text: (required) Text to be shown on card.
- Image: (optional) Base64EncodedImage
```
OUTPUT
Outputs the html created

## Show Result - Simple formatted results
Show result is for a simple showing of text/markdown but nicely formatted. Just send text in to show text with nice formatted fonts.
```
INPUT
- Process: Show Result
- Title: (optional) Title to be shown at top of the quick view window
- Background: (optional) Background color, you can use web color names, or hex values
- TextColor: (optional) Color of text, web color names.
- TextSize: (optional) XL, XS etc
- Text: (required) Text to be shown, this can include Markdown.
```
OUTPUT
Output the html created

## Show List
Show a list of results in quickview.
```
INPUT
- Process: ShowList
- Text: Markdown list to be shown
- Title: Title to be shown
- Background: (optional) Background Color
- TextSize: (optional) XL/L/M/S/XS
```

## Highlight
Highlights a particular word in displayed text.

INPUT
```
- Process: Highlight
- Text: Text to highlight and show
- Search: Search term
- HighlightColor: color of highlighted text
- Title : (optional) 
- Background: (optional)
- TextColor: (optional)
- TextSize: (optional) 
```

OUTPUT
Count of matching words

## SpeedRead
A speed reader, based on the spritz speed reader to allow you to read a large amount of text quickly.

INPUT
```
- Process: SpeedRead
- Text: Text to Read
- Speed: (optional) 250 is default
- Title: (optional) Title for quick view window
```
OUTPUT



OUTPUT
Generated html


## Beep - A beep
The sosumi beep, not sure about using system sounds, access might not always be there. Maybe

INPUT
- Process: Beep
OUTPUT
None
