# Simon
This is my implementation of Simon, the game.<br>

## Purpose
Be able to practice and showcase what I am learning as I step through the process of replicating Simon, from CS260 Class.

## Project Status

Simon HTML and CSS is done. Now, the website has the more or less visuals (2/16/2023).
Finished, and a final pushed to the server was done on 2/8/2023.
## What I have learned so far

3/4/2023 - When I started writing JS code for this project, I wasn't completely sure how everything would work, but now I know a few commands. For example:

```javascript
    document.querySelector("#name");
```
The code above allows me to find specific elements in my HTML document. Once I locate it, I can access its information and even edit it.

```javascript
    localStorage.setItem("userName", nameEl.value);
```
*localStorage* allows me to store information internally, which for now, this will be very helpful.

```javascript
    const positionTdEl = document.createElement('td'); //Allows me to create an element
    positionTdEl.textContent = i + 1; //Allows me to access the element text
    tableBodyEl.innerHTML = '<tr><td colSpan=4>Be the first score</td></tr>'; //Allows me to insert the element into HTML
```
The line above will allow me to create an element and insert things into my HTML document.
```javascript
    scores = JSON.parse(scoresText); //Allows me to bring JSON information and parse it
```

2/16/2023 - After copying and seeing how to app changes, I was able to discover that I made a few mistakes that I wasn't aware of. I used the HTML debugger, which helped me see where I messed up. I as able to review the structure of Simon, and how it works with CSS and Bootstrap.

2/7/2023 - While I was working on the ***play.html*** and ***scores.html***, I explored a little more between `<table>` and the `<thead>`. Both are the same, but when we include the later one, it becomes a more structured table. 
`<th>` vs `<td>`. The first one is for headings, the second one is for the body of the table.

Finished this part of the project.

2/6/2023 - For the first time, I was able to see how the HTML structure works. At first, it wasn't very intuitive, but as I moved along, I was able to indentify many of the elements I was playing with while learning HTML. For example, the "text" input. Moreover, as I copied the ***deployFiles.sh***, I was able to understand what we are doing every time we deploy our program.
