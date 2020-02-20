# Code Refactor - Homework Assignment 1 UNC Coding Bootcamp

Working with basic front-end development tools to become farmiliar with implementation of updating code, ensuring sustainability and functionality of the new code, and organize all the HTML and CSS elements.  Becoming farmiliar with changing existing elements as a front-end developer to resolve issues that may happen on-the-job.  Reorganizing existing code to be more in-line with standards by applying HTML and CSS semantic elements.  Ensure functionality of all the code by making sure that images were loading properly, links worked as intended, and the style is applied properly.  Making the code clean so that future updates and changes can be implemented quickly and easily.  


## User Story

`````
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

As the instructor
I WANT to see that the appropriate changes to the cod were made as outlined
SO THAT I understand that you have a grasp on the concepts learned
`````

## Acceptance Criteria

`````
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
`````

## Assignment Details - Steps I took to fix the code

I started from the bottom up working on the title element first.  I changed the title that was given to be more descriptive and in-line with the company page.  I reloaded the website to make sure that the changes saved.  Once confirmed I started on to the next task.  

My next task was to fix the heading attributes.  Putting the h tags in sequential order from top to bottom.  I put them in order as they appear in the elements.  For example the heading has an h1 tag for the heading of the page.  The next element is in my main area, and within that I have a section and article that has h1, h2, and h3 tags for the headings.  My side element has h1, h2, and h3 tags for the headings to fall in order there.  Finally my footer has an h1 tag since there is only 1 heading in that element.  I structured the h elements this way to provide structure throughout the page, and to allow for more subjects to be picked up by search engines.

My next task was to add alt attributes to all image elements on the page.  None of the images had an alt associated with them, so I added alt attributes that would display in case of loading issues.  

Next I worked on the structure of elements.  I rearranged the code to be more fluid and clean looking.  The code now shows proper indentation and spacing when viewing in order to make future updates and changes easier to apply.

The last acceptance criteria task was to implement semantic elements into the source code.  I renamed a lot of the div tags and removed some classes altogether.  I made a main element that has a section, article, and an aside built into it.  I changed the header and footer from div tags with classes to just being a header section and footer section.  I also added a nav element within the header for the ul and li elements and kept it in-line with the page layout. 

After all of that was finished I then stared to fully clean up the code.  Grouping or nesting CSS elements together that have the same attributes (ie. width, height, font-size...).  Cleaning up the code helps to identify future problems that might arise.  Now any updates can be made with simplicity and ease.

## Usage

Access the project by using the following this link:  https://richardkessler.github.io/Code-Refactor/

## Built With

Built using HTML5 and CSS and using Visual Studio Code for editing.

### Credits

Eric Meyer - https://meyerweb.com/eric/tools/css/reset/ - For providing the reset.css file.
Eddie Saunders - For hosting a study group session and providing input
Travis Cultreri - For input during the study group session
Yalmar Mairena - For input during the study group session

### Author 

Richard Kessler
