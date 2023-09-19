0:00
Welcome to the complete HTML and CSS course. In this course, we're going to learn how to build websites from a beginner to a professional
0:07
level, and by the end of this course, we're going to build youtube.com. Now you don't need any previous coding or technical experience.
0:16
This course is designed to be your first step to becoming a software engineer. We're going to start from the very basics of HTML and CSS and build our way up
0:24
step by step. And along the way, we're going to learn all the major skills that we need to create websites at a
0:30
professional level. You can find the different sections of this course below the video here and
0:36
here. And after each section, I'm going to give you a bunch of exercises that you can do on your own to
0:42
practice the skills that we learned in total. This course is going to have more than 100 exercises. Lastly,
0:49
you don't have to worry about taking notes. I created an HTML and CSS reference that will list everything that we learned in
0:56
this course. With that said, let's get started.
## 1. HTML Basics
1:04
I am going to be doing this course on a Mac, but everything is the same for a Windows computer. Before we begin,
1:10
we're going to need two pieces of software, a web browser and a code editor.
1:15
A web browser lets us view websites on the internet. It's also going to let us view the website that we create in this course.
1:22
The most popular web browser for web development is Google Chrome. A code editor helps us write our HTML and CSS code.
1:30
The most popular code editor for web development is called VS. Code or Visual Studio Code. To install both of these,
1:37
we can go to google.com and then search for Google Chrome or for VS code and then
1:47
open the first result and follow the instructions to download and install.
1:53
Once we have those two installed, we can start the course. We'll begin by learning what is html. HTML stands for
2:01
hypertext markup language. You don't have to worry about what that means. Just know that it's a tool that we use to create websites.
2:09
Every website from YouTube to Google to Amazon uses a combination of
2:14
HTML and CSS to create everything that we see on the website.
2:20
The easiest way to understand what HTML is, is that we're simply giving instructions to a computer.
2:27
We're telling the computer what to do step by step. The computer will then follow our instructions to create our website.
2:35
So I find the best way to learn HTML is to jump in and give it a try. So we're going to create our first HTML file and our first website.
2:44
Let's go to our computer and we're going to create a new folder. So this folder is going to contain all the code for this course.
2:52
I'm going to call this HTML dash CSS dash course.
2:59
Next, we're going to open this folder in our code editor. So I'm going to open vs code,
3:08
and then I'm going to click file open and I'm going to find the folder that we just created, which is this one.
3:19
Now once that's open, you should see the folder name at the top here and on the side here.
3:25
Now let's create our first HTML file. We're going to click this icon to create a new file and we're going to call this
3:33
file website dot html. So we have to make sure that this file ends with html.
3:41
This tells a computer that this file contains HTML code rather than just text.
3:47
So as I mentioned, HTML is basically some instructions you give to the computer.
3:52
We're going to learn our first instruction, which is less than button greater
3:59
than, and we also need to type lesson slash button greater than, but our code editor might auto complete this for us.
4:07
So this is an instruction to create a button and inside the button we're going to have the text. Hello.
4:16
Now let's save our file and we're going to learn how to open this in our web browser. To open our new website,
4:22
we're going to go to the folder that contains our code. We're going to find our HTML file.
4:29
We're going to right click open with Google Chrome.
4:35
And now you can see that we have our first website that has a button with a text Hello inside. And if we look back to our code,
4:43
that's exactly the instruction that we gave to the computer. So as you can see, HTML is pretty straightforward. It's pretty easy to understand what's going on.
4:53
Now let's try another instruction. We can give to the computer on a new line. We're going to type less than P, greater than,
5:02
and we also need to type less than slash p greater than, and our code editor might auto complete this for us too.
5:08
So the P here stands for a paragraph. This is a paragraph of text.
5:13
Inside our paragraph, we can put some text. So let's put the text paragraph of text.
5:20
Now we can save this and to get our website to reflect our most current code,
5:25
we're going to go to our webpage and refresh. And now you can see that our website is displaying a paragraph of text just like we told the computer to do.
5:35
So that's basically how HTML works. The computer reads our HTML code from top to bottom and then
5:43
follows those instructions and creates a button and a paragraph of text.
5:50
If we reverse the order of these lines, for example, if I put the paragraph up here and I save it and refresh
5:59
the page, then the paragraph will appear on top because again, the computer is just following our instructions one by one.
6:09
Now I'm going to introduce some terminology. So each of these things that we're displaying on the webpage is called an HTML
6:16
element. So a button is a type of HTML element and a paragraph is another type of
6:22
HTML element. So element is just a generic term that we use to describe anything that we can
6:28
display on the webpage, and we're going to be using this term element throughout this course. So now I
6:34
want to explain why we have to write all of these symbols that's less than this, greater than, and this less than slash This is something called syntax.
6:43
Syntax are the rules for how a coding language like HTML should be written. If you think of a language like English, we have something called grammar,
6:52
which is the rules of the language. Syntax is basically the same thing except for coding languages. Now,
6:58
the biggest difference between a language like English and a coding language is that in English, you don't have to follow the rules of grammar perfectly.
7:06
People can still understand you, but in a coding language, if you don't follow the rules of syntax,
7:12
the computer won't understand your code. For example, let's break the rules of syntax by deleting this greater than symbol,
7:21
and now we're going to save our file and we're going to go to our website and refresh. And now you notice that our button is gone,
7:28
and that's because we're not following the proper syntax. So the computer doesn't understand our HTML code anymore.
7:36
So let's put that greater design back so that we're following the proper rules of syntax and we don't need this.
7:43
So let's save and refresh our page. And now our button is back because we're following the rules of syntax.
7:50
So what exactly are the syntax rules for H T M L? So this part of the code is called an H T M L tag.
7:58
It basically tells a computer what we're trying to create. We write a tag by writing the less than symbol. This is the tag name,
8:06
which tells a computer what kind of element we're trying to create, and then the greater then symbol.
8:11
So every element consists of two tags in opening tag and a closing tag. The closing tag is the same as the opening tag,
8:20
except it has a slash in front of the tag name. That's how you can tell it is a closing tag.
8:27
You can think of the opening tag as the start of the button and the closing tag as the end of the button.
8:33
And then in between is a content or the text inside the button.
8:38
And the same thing for the paragraph. The paragraph has an opening tag, a closing tag, and some content inside the paragraph.
8:47
So as long as we follow these syntax rules for html, we have an opening tag and a closing tag,
8:53
and the closing tag starts with a slash in front of the tag name. Then our computer will know what to do and display our elements on our webpage.
9:02
The next element that we're going to learn is a link to another website. For example, if we go to Google and we search for something on Google,
9:11
it will give us a bunch of links and when we click these links, it will take us to another website.
9:17
So we're going to learn how to do that in our HTML code. So we'll go back to our website here and in our code we're going to type less
9:25
than a greater than. So this A here represents an anchor element.
9:32
An anchor is basically a link to another website. So inside this anchor we're going to put the text of our link.
9:40
So let's put the text as link to YouTube.
9:45
We're going to save this and the refresh, and now we have a link, but if we click this, it doesn't actually take us to YouTube,
9:54
and that's because we haven't told the computer where this link is supposed to take us. Right now we just have a link without a destination.
10:02
So to set a website to link to, we have to learn a little bit more HTML syntax.
10:08
So we're going to go into the opening tag and we're going to type space HREF equals double quotes, double quotes.
10:18
So inside these quotes we're going to copy and paste YouTube's website url. So to get that we can go to our webpage and then type in youtube.com.
10:29
And at the top here we have the url. So we're going to copy this and paste this into our quotes.
10:37
And now we're going to save our file. We're going to go back to our website and refresh.
10:45
And now we have a link that we can click. So when we click this link, it's now going to take us to youtube.com.
10:52
So that's how we create a link to another website with html.
10:58
Now let's go back here and explain what this syntax means. So this is called an HTML attribute.
