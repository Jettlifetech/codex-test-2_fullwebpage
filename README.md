# codex-test-2_fullwebpage
testing ChatGPTs new Codex tool by generating a complete web app end to end.

Here is the master prompt:
```
Create a bootstrap 5 web page using CDN Resources that is fully responsive for a great mobile and desktop user experience, make the page full width, and contains a navabar at the top, and include the following global webpage design as a template to include: 
1. Full width, responsive top of the page navbar with this logo on the far left and make image fully responsive: "https://code.jetlifecdn.com/jettlife-custom-themes/logo/jettlife-tech-white-text-menu.png" 
2. Include button links on the far right. add a sample menu with sub menu items and sub-submenu to expand as needed. 
3. add a jumbotron under neath the navbar that has a rounded rectangle in the center with the word "Placeholder" as an h1 centered in the jumbotron, and set the background set to a animated gradient moving in the background behind the text. Put the text in a rounded rectangle box with 70% transparent and white square background, and black text, font type = racing sans one. Add a sub heading text placeholder that is wrapped in a <p> tag but styled and base the color of text and background text based on the final generated theme colors. auto populate with domain the page is being accessed on.
4. Add a black full width footer bar that contains the following text in white; "Created By: Daine Dvorak (add link to "https://dainedvorak.com") d.b.a. JETTLIFE Tech&#169; (Dynamically insert the year based on current date)" 
5. Develop advanced CSS style seperated into its own css file, animations, button animations to help create a modern fun interactive user experience, and other CSS for on-hover states, and click states, and post-click states. Create a theme that enhances the user experience with the colors on Technology, outer space, nebulas, and stars, planets, etc. with a focus on gradients and animated gradients where possible, and neon colors that arent too bright. 
6. The specifications of system limitations and in order to plan for Setup of the web app and customize all setup instructions to run setup and run this webpage on is as follows: ubuntu server 22.04, with the following technologies installed: PHP, NodeJS, NPM, JavaScript, MySQL, Apache2, jQuery, Bootstrap 5 CDN Resources, AJAX, Pyhton3, PIP, and please use other 3rd party CDN packages that already exist to make the build more simple if possible. Webpage Theme: 

Now that covers the template webpage design to use on all pages needed to make the following functions work for the webpage:
1. contains a form in the jumbotron with 2 input
Field #1 - (required): "What Folder Do You Want A Index Created For?"
Field #2 - (Optional); "Provide a desired file name for final report; default value should be the full path entered in Field #1 but replace all "/" with "_", and append the date (Format: "_DATE_MM-DD-YYYY) + time (CDT, format: "_TIME_HH-MM-SS-AM/PM)the report was created. 
2. when the form is submitted, send the command to the server to run as a terminal command generate a report of all files and folders and recursively scan all folders inside user defined path to include all files and sub folders and generate a csv download with the list of folders and files in column A, Column B should indicate "File" or "Folder", and column C should include total file or folder size in kb. Store the report in this folder "/var/www/code2.jetlifecdn.com/index-gen/reports"
3. show a button to "Download Report" when completed that downloads the information above in a text file, comma separated columns, and show the results in a new div element that was hidden but now shows due to the user running the script. 
4. include a "Reset All" button to clear all form entry fields and re-hide the div with results and the download button.
```
