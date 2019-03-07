# Choose Shortcut - Choose, or search a Shortcut
Shows a list of your Shortcuts in Alphabetical Order, with a Search function at the top.

INPUT
- Process: Choose Shortcut
- Title: Text to be shown above the choose shortcut list.

OUTPUT
.shortcut file selected

# ColorPicker - Pick colors
Choose a color from a tile of color files, or input a Color Hex Value
This was originally done, by @heyitzspencer

INPUT
- Process: ColorPicker

OUTPUT
Hex Value entered or selected

# PercentageBars - Show percentages

INPUT
- Process: PercentageBars
- Title: (optional) Title to be shown above the list
- Data: Data to be shown

Data
Data should be in the following format 

Subtitle, PercentageAsNumber

eg 

Q1 Sales,67
Q2 Sales,89
Q3 Sales,99



OUTPUT
Selected Item


# MenuList - List with Icons you can use as a menu
MenuList
Send lines of text to show a list with images, or just use it for a left justified menu with no images, or just use the name of an icon and dont use any images.

[List of icons names that can be used](https://gist.github.com/nturpin0/32e74627f47da91dd9aa979506d6d8f7)

INPUT
- Process: MenuList
- List: list to be shown, 
  - Title,Subtitle,Base64EncodedImage
  - Title,Subtitle,IconName    
  - Title,Subtitle
- Title: Title to be shown at the top of the list displayed.
- Type: (optional) IconName
  - If IconName is used you can enter  a name of an icon rather than use the Base 64 encoded option
 
OUTPUT
Selected item as a vcf card
