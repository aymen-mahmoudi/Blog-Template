# Template for a scientific blog/Lesson notes website

## Description
This repository offers Python generators for two different blog templates. The first template features a classic website format with a tabbed headline, while the second is more suitable for educational purposes, featuring a contents list on the left side.

## Installation
You just need to get any Python interpreter (tested and verified under the 3.8.0 version). Only native libraries are used.

## Usage
The main idea is to edit individual HTML files separately and then incorporate their content into the body section of the final HTML files. The <head> section and navigation will be handled by the Python script.

### For the classic template: 
You will find a folder called 'tab_content,' where all your work will be saved. In this folder, you'll create your HTML files and organize them into repositories. Each repository will represent a head title, and each HTML file will correspond to a subtitle that appears when the cursor hovers over the head title on the top bar. The content of the Home page (index file) is uniquely added directly in the Python file.
<br>
In the Python file, you need to type the subtitles to be generated (they will appear in the same order you insert them). Finally, just run the file to generate the output and update the folder 'created_tab.


### For the modern template: 
It is quite similar. You will find a folder called 'Update-Here,' where all your work will be saved. In this folder, you'll create your HTML files and organize them into repositories. Each repository will represent a main section, and each HTML file will correspond to a section that will appear permanently in the contents list on the left side.
<br>
You can always open your HTML files from this folder to ensure you're working in the correct one (even though the style will be missing due to the lack of direction to the CSS files). After making changes, you need to run the page_gen.py file. Before doing so, modify the main and sub-section names in the script so that it can locate your HTML files. **Once the Python script is executed, it will permanently overwrite the existing output folder (the folder called 'HTML').**


## Roadmap
 <ul>
  <li>Find a way to link the CSS files to the HTML files in the 'Update-Here' folder</li>
  <li>Integrate the HTML reducing size script in the Python file</li>
</ul> 

## Support and Contributing
Let me know if you have any suggestions/ideas on how to enhance those scripts or add further settings. I want you to know that your suggestions are warmly appreciated.
<br><br>
In case of a problem, it is strongly recommended that an issue be posted. For a more confidential demand, don't hesitate to email me.



