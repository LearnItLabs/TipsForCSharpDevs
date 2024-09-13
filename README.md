# Ten Tips for the C# Developer
This is the repository for the LinkedIn Learning course Ten Tips for the C# Developer. The full course is available from [LinkedIn Learning][lil-course-url].

![banner](https://github.com/LearnItLabs/SiteAssets/blob/78fc8d3e6156de51b8c8cbff35e1e60e7b53b7b9/GitHubBanner.png)


C# and .NET are deep areas. Even if you’ve been a developer for years, there are bound to be features you don’t even know exist. In this course, take a look at some of the hidden or interesting methods that can help you write better code in this multifaceted programming language. Hear tips for improving your everyday workflows in C# development including a method to help avoid race conditions when working with a dictionary. Learn how to use pattern matching to create more expressive and readable code branches. Explore the new C# 8 slice operators and how and when to flatten a one-many relationship. Discover fresh tactics like how to and engage another programmer’s technique, use the DebuggerDisplay attribute to specify what information is shown, and more.

## Tips and Techniques
Discover tips and techniques that can make working with C# simpler, faster, and more interesting. 

## Instructions
This repository contains example code for each of the videos in the courses organized into branches. 

You can use the branch pop up menu in github to switch to a specific branch and view the code at that stage of the course. Alternatively, you can directly access a specific branch by adding `/tree/BRANCH_NAME` to the URL.

# Branches in Visual Studio
While following along with the course, you can use Visual Studio's Git tools to switch between branches. This allows you to easily move to the relevant chapter and topic as you progress through the course. 

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `Tip#`. 

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"



## Installing
1. For this course the instructor uses Visual Studio 2019, any edition is sufficient (Community, Professional, Enterprise). 
2. LINQPad is another tool shown in this course.  Get a free copy at [Linqpad.net](https://linqpad.net)
3. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like Visual Studio or SourceTree.

## About our .NET courses
When you are ready to [learn more about .NET](https://www.linkedin.com/learning/search?entityType=COURSE&keywords=.net) or [Visual Studio](https://www.linkedin.com/learning/search?entityType=COURSE&keywords=visual%20studio), **LinkedIn Learning** has what you need. 

## About the Instructor - Walt Ritscher
Learn-it Labs is a boutique video training company based in the Seattle area. Founded by Walt Ritscher, a long-time LinkedIn Learning staff instructor, Learn-it Labs is dedicated to creating world-class, video-based courses on a wide range of technology topics.

Check out Walt's [other courses](https://www.linkedin.com/learning/instructors/walt-ritscher) on LinkedIn Learning.  Follow on [LinkedIn](https://www.linkedin.com/in/waltritscher/?trk=lil_course) and [Twitter](https://twitter.com/waltritscher). 


![Ten Tips for the C# Developer][lil-thumbnail-url] 


[lil-course-url]: https://www.linkedin.com/learning/ten-tips-for-the-c-sharp-developer-24398014
[lil-thumbnail-url]: https://cdn.lynda.com/course/2863044/2863044-1601574454812-16x9.jpg
