[<<<Back](opening_activity.md) | [Next>>>](elements.md)

# Basic Template for HTML

Below is a basic template for an empty HTML Document. 

```
<!DOCTYPE html>
<html lang="en">

<head>
</head>

<body>
</body>

</html>
```

HTML documents start with a `DOCTYPE` declaration that states what version of HTML is being used. This tells the browser how to read the code below it to render the page. If the webpage were written with a different markup language (i.e. XML, XHTML), it would tell you here.

After the `DOCTYPE`, we see the start of the **Root Element**. EVERYTHING—all content—that you want presented on this page and all information about how you want that information to be organized and styled goes in the root element, and it is demarcated by `<html>` and `</html>`.

The root element begins by indicating which language the document is written in; and in this basic template, `en` tells us and the computer that we are writing in English. 

Within the root element of the basic template above, you'll notice the two main sections of all HTML documents: a head section (demarcated by `<head>` and `</head>`) and a body section (demarcated by `<body>` and `</body>`). 

The **head section** contains basic information about the file such as the title, keywords, authors, a short description, and so on. This is also where you will link to your CSS stylesheet which describes how you want the page styled — colors, fonts, size of text, and positioning of elements on the page.

The **body section** contains the content of the page, including paragraphs, images, links, and more, and indicates how this content is to be structured on the page. 

## Activity

Create a folder called `htmlpractice` in your projects folder (`~/Desktop/projects/htmlpractice`). If you haven't created a projects folder in an earlier session, you can create one now. Inside that folder, create a new text file and save it as `index.html`.

Let's use the command line to create the new folder and file:

1. Open your terminal and navigate to the desktop: `cd ~/Desktop`.
2. If you don't already have a projects folder, create it with this command: `mkdir projects`.
3. Navigate to your projects folder using this command: `cd ~/Desktop/projects` or just `cd projects`, since you're already at `~Desktop`.
4. Create a new folder: `mkdir htmlpractice`.
5. Navigate to the folder you just created: `cd htmlpractice`.
6. Use your VS Code text editor to create a file called `index.html`: `code index.html`. You can also open VS Code directly and create a new file there. (If you get an error when you try creating the file in the terminal, you may have a problem with PATH. If you want to fix the problem, open VS Code, choose Command Palette from the View menu, and search for "Shell Command: Install 'code' command in PATH." Selecting that command should fix things.)
7. Paste the template above (starting with `<!DOCTYPE html>`) into the new file.

The `index.html` file is your default homepage for the website we are creating. This is an industry standard, because web browsers tend to recognize the `index.html` page as the opening page to the directory that is your website. See [here](https://www.lifewire.com/index-html-page-3466505) for more explanation.

Once you've created your new file, open it with a web browser using your graphical user interface:

On Mac OS, click on the Finder in your dock (the apps at the bottom of the screen) and click on Desktop on the left. From there, navigate to `projects`, then `htmlpractice`. Alternately, you can click the projects folder icon on your Desktop and find it from there. Hold control and click on the file, select `Open with...` from the menu, then choose Firefox or Google Chrome from the list of apps that will come up. (If you would prefer to use the command line, you can also type `open -a "/Applications/Google Chrome.app" index.html` from within your `htmlpractice` folder.

On Windows, click the `projects` folder icon on your desktop. Navigate to `projects`, then `htmlpractice`. Double click the `index.html` file. If it does not open in a browser, right click the `index.html` icon and select `Open with...` from the menu. Select Firefox or Google Chrome from the app list that appears.

### What happens?

When you open the empty template, you'll see only a blank web page. Open your secondary menu (right click on Windows, hold control and click with Mac OS) and view the page source. How can you explain what happens when you open the file and view its source? 

When you 'View Page Source', you should see the code for the basic template. 

No content renders on the page, because there is no content in the template at this time.

[<<<Back](opening_activity.md) | [Next>>>](elements.md)
