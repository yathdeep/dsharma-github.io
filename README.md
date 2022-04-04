## Data 608 - Module 5 - Assignment Links

[Part 1 - Assignment Link](Module5Part1.html)

[Part 2 - Assignment Link](Module5Part2.html)

### Approach and Analysis

* I used Markdown documentation to help me develop this part of the assignment. Ref: 5.

* For Part 1, Question 1, I developed an HTML text field, button, and div. The button has an onClick function reference to reverseString(). The function checks for an empty string and returns an error message if it exists. Otherwise the function will perform a for-loop that reverses the string input. The resulting string is outputted to the DIV target1. 

* For Part 1, Question 2, I developed an HTML text field (which only accepts numbers), button, and div. The button has an onClick function reference to calcMultiples(). The fuction checks for an empty number and returns an error message if it exists. Otherwise, the function will output the first 20 multiples of the inputted number. The HTML table is created in a 5x4 structure and the HTML table is displayed in DIV target2.

* The output for Part 1 looks like this:

![Part 1 HTML](img1.png)

* For Part 2, upon start up of the HTML file, I called javascript function d3.csv to load presidents.csv directly (Ref: 1) and store the incoming data in a Javascript object called presArray. That object will be used to answer both questions of Part 2.

* The d3.csv function, I also wanted to populate the HTML select for Question 2 by dynamically adding the options using the Presidents' names (Ref: 3).

* For Part 2, Question 1, I developed an HTML button and div. The button has an onClick function reference to loadData(). The function will iterate through the presArray and put each President's name, height, and weight in a row of data in HTML table. The resulting HTML table is outputted to the DIV target1.

* For Part 2, Question 2, I developed an HTML select, button, and div. The button has an onClick function reference to getInfo(). The function will return an error message if no President is selected. Otherwise, the function will use the index of the selected President to get the row data from the presArray object. The selected President's name, height, and weight will be displayed in DIV target2 as an informative, formatted string sentence.

* You will notice that the Question 2 HTML page is split into two columns for ease of view (Ref: 2).

* The output for Part 2 looks like this:

![Part 2 HTML](img2.png)

* I initially developed the code in Microsoft Edge web browser. However, I had to debug and solve issues with the code when I tried to display this in Google Chrome and Mozilla FireFox. These web pages were successfully tested and viewable in Microsoft Edge, Google Chrome, and Mozilla FireFox.

### Reference(s)

1. **Data Loading in D3.** Retrieved from website: [https://www.tutorialsteacher.com/d3js/loading-data-from-file-in-d3js](https://www.tutorialsteacher.com/d3js/loading-data-from-file-in-d3js)

2. **How To Create a Two Column Layout.** Retrieved from website: [https://www.w3schools.com/howto/howto_css_two_columns.asp](https://www.w3schools.com/howto/howto_css_two_columns.asp)

3. **How to populate the options of a select element in javascript.** Retrieved from website: [https://stackoverflow.com/questions/6601028/how-to-populate-the-options-of-a-select-element-in-javascript](https://stackoverflow.com/questions/6601028/how-to-populate-the-options-of-a-select-element-in-javascript)

4. **HTML Select Tag.** Retrieved from website: [https://www.w3schools.com/tags/tag_select.asp](https://www.w3schools.com/tags/tag_select.asp)

5. **Mastering Markdown.** Retrieved from website: [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)



