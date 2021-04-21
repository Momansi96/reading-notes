# Read09 

[Return to home page](https://momansi96.github.io/reading-notes/).

## Choosing A Text Editor. 

#### What is a text editor?

A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as a web developer. 

What features should you look for in a text editor? I would say some of the most important features are: 

1- code completion: 

Code completion allows you to start typing, and the code completion feature will display possible suggestions based on what you originally typed, This saves you time by providing a choice, rather than allowing you to finish typing and possibly encounter typos, Also, some code completion includes the closing of tags when you open them, or the closing of brackets when you open them, or the
closing of quotation marks when you open them. 

2.) syntax highlighting: 

Syntax highlighting is a feature that takes the text you
type, and makes it more noticeable by colorizing the text. Attributes are a different color than elements. And elements are a different color than copy. This makes it so much easier when you’re looking for an error and you can’t find it. As well as making your text easier to read. 

3.) a nice variety of themes (to reduce eye strain and
fatigue): 

These themes will allow you to change the color of the background of your text editor, the series of colors in your text, and sometimes themes will affect other aspects of your text editing software as well. Usually, web developers use a dark background and brightly colored text. This combination seems to be easier on the eyes.

4.) the ability to choose from a healthy selection of
extensions available when you need them: 

As you become more familiar with coding, you may want to add more features to your text editor. You’ll want to accomplish more with minimal effort. You want a text editor that can grow with you as your needs grow. This comes in the form of extensions. Extensions are like plugins for your text editor, that allow you to have superpowers that
you wouldn’t have otherwise. 

#### Using The Software That Already Comes With Your Computer: 

Every computer will come with its own text editor. On Mac
computers, the text editor that comes with your computer is called, “Text Edit.” On Windows computers, the text editor that comes with your computer is called, “Notepad.”. 

Since these text editors already come on your computers, why should you download yet another text editor that does essentially the same thing as the text editor that you already have? There are other text
editors that have features that you may be interested in, Usually the text editors that come on your computer don’t have many features to speak of. They’re the barest bare bones text editors you’ll encounter.

- If you want to try using the text editors that come with your computer, there’s a couple of caveats that you should be aware of: 

1- make sure that when you use the text editor that comes on
your computer, that you’re creating code in a plain text editor. You should not see options for making text bold, underlined, or italic. 

2- make sure that when you use the text editor that comes on your computer, that you first create a folder on your computer somewhere to store your entire website.
As you create new documents with the text editor that comes on your computer, save those files in the appropriate folders or sub-folders within the main website folder. 

3- make sure that when you’re saving your file, that they
have the appropriate extension at the end of the file names. 

#### Using Third-Party Options: 

1- NotePad++: 

NotePad++ is a free text editor for Windows Computers only.
NotePad++ has been around for many years. It has syntax highlighting and code completion, as well as word completion and function completion. It has a zoom in an out feature, it’s own online community, It even has its own searchable wiki page for more assistance. 

2- BB Edit: 

BB Edit is software that you purchase. But BB Edit comes with a 30-day free trial. After the 30 days is over, if you still want the free version, simply continue using BB Edit, If you want the full features in BB Edit, the full cost for a full license is $49.99.

3- Visual Studio Code: 

Visual Studio Code is a free text editor made by the folks at Microsoft. It is available for Windows computers, Mac computers and Linux computers. VS Code has the Emmet shorthand for HTML and CSS already built-in with no additional work from you at all. VS Code has everything: syntax highlighting, themes, extensions and code completion. 

4- Atom: 

Atom is a free text editor that’s available for download for Windows computers, Mac computers and Linux computers. Atom is brought to you by the folks at GitHub. Atom also ticks all the right boxes. It has syntax highlighting, themes, extensions, the works!. 

5- Brackets: 

Brackets is a free text editor that’s available for download for Windows computers, Mac computers and Linux computers. It’s made and maintained by Adobe. Brackets only supports HTML, CSS and JavaScript, though more coding capabilities can be added through extensions. Being that
Brackets only supports HTML, CSS and JavaScript. 

6- Sublime Text: 

Sublime Text 3 is a premium software that can be purchased in full for $70. Otherwise you’ll use the free version. It has syntax highlighting, it has code completion, it has themes and extensions. 

#### The Difference Between Text Editors and IDEs: 

A text editor kind of gives away what it does in the title—it edits text. It also manages text, and manages files. 

An IDE (Integrated Development Environment) is really a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package. 


## The Command Line!

A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands. 

Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. 

 When you enter commands, they are actually stored in a history. You can traverse this history using the up and down arrow keys. So don't bother re-typing out commands you have previously entered, you can usually just hit the up arrow a few times. You can also edit these commands using the left and right arrow keys to move the cursor where you want.

 ## Basic Navigation!


- The first command we are going to learn is pwd which stands for Print Working Directory. The command does just that. It tells you what your current or present working directory is.

- It's one thing to know where we are. Next we'll want to know what is there. The command for this task is ls. It's short for list. 

#### Paths: 

In the previous commands we started touching on something called a path. Whenever we refer to either a file or directory on the command line, we are in fact referring to a path. ie. A path is a means to get to a particular file or directory on the system.

- There are 2 types of paths we can use, Whenever we refer to a file or directory we are using one of these paths. Whenever we refer to a file or directory, we can, in fact, use either type of path: 

1- Absolute paths: 

They specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / ). 

2- Relative paths: 

They specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

#### Let's Move Around a Bit: 

- In order to move around in the system we use a command called cd which stands for change directory, If you run the command cd without any arguments then it will always take you back to your home directory.


## More About Files!

- Ok, the first thing we need to appreciate with linux is that under the hood, everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. To begin with, this won't affect what we do too much but keep it in mind as it helps with understanding the behaviour of Linux as we manage files and directories.

- This one can sometimes be hard to get your head around but as you work through the sections it will start to make more sense. A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:

1- file.exe - an executable file, or program.

2- file.txt - a plain text file.

3-file.png, file.gif, file.jpg - an image.

- In other systems such as Windows the extension is important and the system uses it to determine what type of file it is. Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is. So for instance I could have a file myself.png which is a picture of me. I could rename the file to myself.txt or just myself and Linux would still happily treat the file as an image file. As such it can sometimes be hard to know for certain what type of file a particular file is. Luckily there is a command called file which we can use to find this out.

- This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case.

- Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items. They are how we know what is the program name and can identify each command line argument. 

- To wish "file name" to be seen as a single command line argument. There are two ways to go about this, either way is just as valid: 

1- Quotes: 

The first approach involves using quotes around the entire item. You may use either single or double quotes. Anything inside quotes is considered a single item.

2- Escape Characters: 

Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.

- Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden. You don't even need a special command or action to make a file hidden. Files and directories may be hidden for a variety of reasons. Configuration files for a particular user (which are normally stored in their home directory) are hidden for instance so that they don't get in the way of the user doing their everyday tasks.

- To make a file or directory hidden all you need to do is create the file or directory with it's name beginning with a . or rename it to be as such. Likewise you may rename a hidden file to remove the . and it will become unhidden. The command ls which we have seen in the previous section will not list hidden files and directories by default. We may modify it by including the command line option -a so that it does show hidden files and directories.















