# Menus

## MenuList
Images in your lists/menu. Send lines of text to show a list with images, or just use it for a left justified menu with no images, or just use the name of an icon and dont use any images.

You can retrieve either the Title, or the Subtitle selected from any of the menus except the P.


[List of icons names that can be used](https://gist.github.com/nturpin0/32e74627f47da91dd9aa979506d6d8f7)

INPUT
```
- Process: MenuList
- List: list to be shown 
  - Example of formats used in list.
      - Title,Subtitle,Base64EncodedImage
      - Title,Subtitle,IconName    
      - Title,Subtitle
- Title: Title to be shown at the top of the list displayed.
- Type: (optional) IconName
  - If IconName is used you can enter  a name of an icon rather than use the Base 64 encoded option
```
OUTPUT

Selected item as a vcf card

## PercentageBars
INPUT
```
- Process: PercentageBars
- Title: (optional) Title to be shown above the list
- Data: Data to be shown
      - Data should be in the following format  Subtitle, PercentageAsNumber

Q1 Sales,67
Q2 Sales,89
Q3 Sales,99
```

OUTPUT

Selected Item as a vcf card.


## ChooseShortcut
Shows a list of your Shortcuts in Alphabetical Order, with a Search function at the top.
```
INPUT
- Process: ChooseShortcut
- Title: Text to be shown above the choose shortcut list.
```
OUTPUT

.shortcut file selected

## ColorPicker
Choose a color from a tile of color files, or input a Color Hex Value

INPUT
```
- Process: ColorPicker
```

OUTPUT

Hex Value entered or selected

## Choose Reminder List
Shows your Reminder lists and allow to select one/many.

```
Process: ChooseReminderList
Type: (optional)Single/Multiple  Use to select if returning allowing one or several reminder lists to be returned.
```

## PaginateList
Paginates a list, for using in a Widget so that you can use a next at the bottom to see the whole of the list.
```
INPUT
- Process: PaginateList
- List: Use a list action, a text action with items on new line, or a variable containing a list. 
```
OUTPUT

item on list  file selected


## GetAllNotes
Returns all the notes, as currently the Find Notes only returns 26. Use a choose from list immediately afterwards to choose from the notes, or search through them with a repeat action.
''
```
INPUT
- Process: GetAllNotes
```
OUTPUT
Notes

