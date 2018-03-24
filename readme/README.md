

![Lucas Project]("https://github.com/lucasLB7/lucasProject/tree/gh-pages/images/me.jpg")


# MY WEEK 2 PROJECT

This is my __second__ week project. And I must admit it's been a struggle all along:

-My bootstrap keeps overwriting my personal style despite the fact that it's linked __after__ my bootstrap.. This means images & divs did not responded as expected.

## Installation:

To run this website simply pull contents from branches __gh-pages or master__.  Alternatively to __view remotely__ simply follow this link:
 https://lucaslb7.github.io/AnitaKitchen-/

 Inside the document you should find:

|   file name    |   file type   | size  |
| :------------- |:-------------:|:------|
| css            | folder        | 7.7 kb|
| images         | folder        | 2.1 mb|
| fonts          | folder        |247.7kb|
| README.ms      | README file ms|4.6 kb |
| README.ms(copy)| README file ms|3.3 kb |
| abtme.html     | html page     |4.3 kb |
| index.html     | html page (HP)|3.8 kb |

### Links to other projects available in the website:
ANIMAL SHELTER: https://lucaslb7.github.io/animal_rescue/
<br>
TRAVEL AGENCY: https://lucaslb7.github.io/Happy-Trails-Travel-Agency/
other links coming soon....

# A BIT ABOUT THE WEBSITE:

Html code is kept as __simple as possible__ on a css structure based on the ANIMAL SHELTER project.
I chose this layout due to how simple it is to __change or update the style.__
<br>
First is a main class background div that contains the entire page. It serves as a solid backbone in which I build my structure. Styling on this is only padding. In this version there is no flex added. Will try adding this flex wrap in another version.

The rest of the body is composed of two div classes, __elementA & elementB__. More info on this further down.

## The profile image:

The profile image on the right is styled to grow on hover. I wanted to add a text on hover as done in the TRAVEL AGENCY project but due do the structure the
```
: : before {}

```
function did not work ..:/.
<br><br>

## The navbar:

This is an improved version of the navbar used in the TRAVEL AGENCY  project. It has 3 standard buttons & one drop down button with links to other pages (projects) made this week.

All the links are live to other pages in the website. <br><br>


1. Buttons link to local pages in repo
2. Scroll down links to other live (global) github pages.

Navbar is made by having a main navbar div and a dropdown function. <br>
the dropdown function of floated to the left so that on hover the content is shown:<br>

**.dropdown:hover .dropdown-content { display: block }**

## The sectioning, pro's & cons.

I decided to section my main content in two DIV types and call them sectionA and sectionB. They are almost identical but are reversed so that one will float to the left the other to the right.

<br>

I decided not to put the images in a div, instead float them. For this I used the command:

```
  div.sectionA img {
  border-radius: 50%;
  border: 3px white solid;
  float: left;
  height: 600px;
  width: 600px;
  transition: all .2s ease-in-out;
  opacity: 0.5;
}
```
<br><br>

The table below demonstrates how the website is formed:
```
|              Header div                       |
|:-------------:|:-----------------------------:|
|   sectionA    |            SectionA           |
|    image      |              text             |
|:-----------------------------:|:-------------:|
|   sectionB                    |    sectionB   |
|    text                       |      image    |
|:-------------:|:-----------------------------:|
|   sectionA    |            SectionA           |
|    image      |              text             |
|:-----------------------------:|:-------------:|
|   sectionB                    |    sectionB   |
|    text                       |      image    |

```



# CREDITS:

The realization of this website was only made possible thanks to these supports:

1. Moringa School (For support, and classes. Main support base)
Moringa instructure: https://moringaschool.instructure.com
2. GitHub (For remote version control and backup)
Github: https://github.com/
3. Stack overflow (General look up for most questions and issues I had)
https://stackoverflow.com/questions/8608621/how-to-center-div-and-place-at-bottom-of-another-div?rq=1

4. W3school (same as stackoverflow)
https://www.w3schools.com/cssref/sel_hover.asp
https://www.w3schools.com/howto/default.asp
https://www.w3schools.com/cssref/pr_class_clear.asp

5. Youtube



# TESTAMENT

I Paul-Lucas Benoit Lambert (id. ek304470) testify that this project was created, tested and published by me alone.
Although there are elements which I based myself on that was not my work, I have studied the code and __modified__ and __replicated__ it for the purpose of this project.
