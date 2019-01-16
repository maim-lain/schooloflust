# School of Lust - Converting Saves

<br>

- The file number of the save you want to convert corresponds to which save you need to click ingame to load the save you converted:
  - file1.rpgsave -> Autosave
  - file2.rpgsave -> Save #1
  - file3.rpgsave -> Save #2
  - etc.

<br>
<br>

## Converting Saves:
- Go to ```/www/saves``` inside your old game folder and find the file#.rpgsave that you want to convert
- In the patched game folder go to ```/www/saves```
- Open ```RPGMakerMVSaveEditor``` then ```index.html``` to bring up the tab and with it open the save you want to convert
- Select all the text and copy it, then open ```/www/saves/save.txt``` and delete any text in it, then save and close the ```save.txt``` file
- Open ```Save Converter``` and select an option
- Open ```save.txt``` and select all the text and copy it
- Delete all the text in the RPGM Save Editor html tab, paste the new text, and click 'save' to download your converted save
- Put the converted save in the save folder you wish to transfer it to
- Finally copy ```config.rpgsave``` and ```global.rpgsave``` from your old save folder to your new save folder
