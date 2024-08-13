# Template for a scientific blog/Lesson notes website

## Description
This repository offers Python generators for two different blog templates. The first template features a classic website format with a tabbed headline, while the second is more suitable for educational purposes, featuring a contents list on the left side.

## Installation
You need just to got any python interpreter (tested and verified under the 3.8.0 version). Only native libraires are used.

## Usage
The main idea is to edit individual HTML files separately and then incorporate their content into the body section of final HTML files. The <head> section and navigation will be handled by the Python script.

### For the classic template: 



### For the modern template: 
It is quite similar. You will find a folder called 'Update-Here,' where all your work will be saved. In this folder, you'll create your HTML files and organize them into repositories. Each repository will represent a main section, and each HTML file will correspond to a section that will appear permanently in the contents list on the left side.
<br>
You can always open your HTML files from this folder to ensure you're working in the correct one (even though the style will be missing due to the lack of direction to the CSS files). After making changes, you need to run the page_gen.py file. Before doing so, modify the main and secondary section names in the script so that it can locate your HTML files. **Once the Python script is executed, it will permanently overwrite the existing output folder (the folder called 'HTML').**


## Roadmap
 <ul>
  <li>Find a way to link the CSS files to the HTML files in the 'Update-Here' folder</li>
  <li>Integrate the HTML reducing size script in the python file</li>
</ul> 

## Support and Contributing
Let me know if you have any suggestions/ideas to enhance those scripts or add further settings. Your suggestions are warmly welcomed.
<br><br>
In case of a problem, It is strongly recommended to post an issue. For a more confidential demand, don't hesitate to email me.



