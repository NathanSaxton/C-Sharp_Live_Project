# C-Sharp_Live_Project

## Introduction

  As I write this, I have just completed the last day participating in my final live project with The Tech Academy. During my 2-week sprint I joined this project mid-lifecycle. During this project we used Microsoft's Azure DevOps for project management, Visual Studio 2019 for the IDE, C# for the language (as the title suggests), with the .NET framework, and MVC pattern. My contributions to this project include setting up a database using a code-first Entity Data Model, adding CRUD fuctionality for said model, adding the ability to store and retrieve photos for objects in that database, and sorting those database objects by property and displaying them on the sub-index made for that model.
  
## CRUD with .NET MVC
  
  For this project I started adding to it by adding a class to create my code-first model, I then used the Entity Framework to create the database and added a model controller to work with that model. 
  
![image](https://user-images.githubusercontent.com/72226252/171965184-409c319d-b21c-47f9-b9e1-76420be479b5.png)
  
  That also added the CRUD fuctionality, using Visual Studio 2019 it was much simpler than it was in Python as the CRUD pages built themselves. I was able to include some of my own Razor Pages Fuctions which will be seen in some of the images below, this includes setting up the BeginForm fuction and getting a better understanding of other Html functions such as ActionLink. 

![image](https://user-images.githubusercontent.com/72226252/171965312-3d50b795-a8bd-4a6f-916c-e52fab6bcfd0.png)
![image](https://user-images.githubusercontent.com/72226252/171965454-3961a228-a7f2-4f18-854a-03ed251b5087.png)
![image](https://user-images.githubusercontent.com/72226252/171983287-98b6ab0e-9ee5-4ea8-ad88-8991d65fc696.png)

## Styling Group Project

  Styling in this group project was much different from my last, as with my last I could style my section of the website in anyway I chose, and I went with my own style of course. This project was quite different as this was the first project where I needed to style based on the existing project. We were given specific colors to stick to (as I imagine will happen working with any company) and we were asked to style it using the pre-existing root variables. 
  
![image](https://user-images.githubusercontent.com/72226252/171983630-f2523308-e668-4e59-a7e0-ca0f1085102e.png)
![image](https://user-images.githubusercontent.com/72226252/171981512-b005cd4c-a5e4-4817-9524-59d1cde71399.png)
![image](https://user-images.githubusercontent.com/72226252/171983242-9c93d372-4544-443e-b6e8-66e2ca3063a1.png)


## Photo Storage & Retrieval

  The next big task I had for this project was adding a method to store an image file (.png, .jpg, .jpeg, etc.) into a byte array and retrieve it again. This was entirely new to me as I've never worked with the data in any type of image file before outside of a photo editor. My first task was to figure out how to convert the file into a byte array. While this was challenging, I was able to find an answer that was unique and accomplished the task I also ended up adding a default photo that I converted as well. 
  
![image](https://user-images.githubusercontent.com/72226252/171982302-1e572217-9792-4673-a30e-92710ac935a3.png)

  After converting the file and storing it in an array I had to be able to retrieve the photo while also converting it back to an image rather than an enormous string of number. Using the Razor Pages syntax I was able to call a function that converted it back to an image in one line (highlighted in the next image). In the images below you will also see how I grouped the model objects by a property and displayed them by group.
  
![image](https://user-images.githubusercontent.com/72226252/171982488-ab4ff77a-c23e-4b1d-98e8-d79008ee1d59.png)
![image](https://user-images.githubusercontent.com/72226252/171982332-b1c57172-668c-47d0-99b8-d516fc8d8e4a.png)


## Experience/Reflection

  Orienting myself to the project itself is something that I specifically remember was a bit more challenging than I remember with my previous projects. After getting my bearing I came to realize that as the projects I work on get bigger keeping them organized will become increasingly important. I also learned about the ability to add mulitple MVC Patterns to a project, which I somehow missed during my Python project, increasing the scale immensely and making it easier to organize the project by compartmentalizing.
  
  Prior to my time with The Tech Academy I had already done my own research and self-teaching with C#, however I never really got to building anything noteworthy that I could proudly present to anyone, and I felt like I was going in circles learning the same thing over and over again. Going through this Live Project and learning the .NET framework more in depth and getting a hands on experience using in a larger project it makes it so much easier to see how a project will come together when all the smaller pieces mesh.
 
  With this project, I got a lot of hands on experience using C#'s Separation of Concerns MVC. Just before this project, I learned about Razor Pages, and I ended up diving into quite a bit of self learning with these Razor Pages fuctions to get the pages to display as I wanted. This was extremely encouraging as I could tell I was doing a lot better with the direction of my self learning than I was prior to The Tech Academy.
