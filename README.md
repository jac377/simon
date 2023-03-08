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

## Console Commands
 These are the main console commands I commonly used

| Command | Function | Command | Function | Command | Function |
| :---: | --- | :---: | --- | :---: | --- |
| `echo` | Output the parameters of the command | `cd` | Change directory | `mkdir` | Make directory |
| `rmdir` | Remove directory | `rm` | Remove file(s) | `mv` | Move file(s) | 
| `cp` | Copy files | `ls` | List files | `curl` | Command line client URL browser |
| `grep` | Regular expression search | `find` | Find files | `top` | View running processes with CPU and memory usage |
| `df` | View disk statistics | `cat` | Output the contents of a file | `less` | Interactively output the contents of a file |
| `wc` | Count the words in a file | `ps` | View the currently running processes | `kill` | Kill a currently running process |
| `sudo` | Execute a command as a super user (admin) | `ssh` | Create a secure shell on a remote computer | `scp` | Securely copy files to a remote computer |
| `history` | Show the history of commands | `ping` | Check if a website is up | `tracert` | Trace the connections to a website |
| `dig` | Show the DNS information for a domain | `man` | Look up a command in the manual | `\|` | Take the output from the command on the left and pipe, or pass, it to the command on the right |
| `>` | Redirect output to a file. Overwrites the file if it exists | `>>` | Redirect output to a file. Appends if the file exists |
## Git Commands
Important Git Commands to remeber:

| Command | Function | Command | Function | Command | Function |
| :---: | --- | :---: | --- | :---: | --- |
| `git status` | Tells you what git is doing | `git add` | Ask Git to track a file or folder (by appending .) | `git commit -m` | Commits changes and (-m) is a flag that means note |
| `git commit -am` | It will allow messate to commit but also add what was being tracked | `git log` | It will output the file's history | `git pull` | Searches and downloads latest version |

## DNS
One thing I need to remember is that a domain name is written as follows " `[subdomain.]*[secondary.top]`. 
Also, this is the difference bewteen *address* (`A`) and *canonical name* (`CNAME`). Address is to point from an DNS to IP address. Canonical name is to point from DNS to DNS.

## HTML Elements
| Element | Meaning | Element | Meaning | Element | Meaning |
| :---: | --- | :---: | --- | :---: | --- |
| `html`| The page container | `head` | Header information | `title`	| Title of the page |
| `meta` | Metadata for the page such as character set or viewport settings | `script` | JavaScript reference. Either a external reference, or inline | `include` | External content reference |
| `body` | The entire content body of the page | `header` | Header of the main content | `footer` | Footer of the main content |
| `nav` | Navigational inputs | `main` | Main content of the page | `section` | A section of the main content |
| `aside` | Aside content from the main content | `div` | A block division of content | `span` | An inline span of content | 
| `h<1-9>` | Text heading. From h1, the highest level, down to h9, the lowest level | `p` | A paragraph of text | `b` | Bring attention |
| `table` | Table | `tr` | Table row | `th` | Table header |
| `td` | Table data | `ol,ul` | Ordered or unordered list | `li` | List item |
| `a` | Anchor the text to a hyperlink | `img` | Graphical image reference | `dialog` | Interactive component such as a confirmation |
| `form` | A collection of user input | `input` | User input field | `audio` | Audio content |
| `video` | Video content | `svg` | Scalable vector graphic content | `iframe` | Inline frame of another HTML page |

Special Character:

| Character | Entity | 
| --- | --- |
| &	| `&amp;` |
| <	| `&lt;` |
| >	| `&gt;` |
| \" | `&quot;` | 
| '	| `&apos;` |
| 😀 | `&#128512;` |

## CSS Code
