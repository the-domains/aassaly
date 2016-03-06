---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
starred: false
keywords: []
description: Deliverable For Class Project
datePublished: '2016-03-06T16:31:27.697Z'
dateModified: '2016-03-06T16:30:26.276Z'
title: |-

  Is there a right way to make complicated applications usable?
author: []
sourcePath: _posts/2016-03-05-is-there-a-right-way-to-make-complicated-applications-usable.md
published: true
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
url: is-there-a-right-way-to-make-complicated-applications-usable/index.html
_type: Article

---
# Is there a right way to make complicated applications usable?

Finding the right tool to use for the job isn't always the easiest task. In the digital world this amounts to trying to figure out which piece of software is the right one to use. This answer is typically subjective as every person has different tastes and varying levels of expertise. This is why designing user friendly applications can be very challenging, even for simple applications. By comparing two applications of equivalent functionality, but with different degrees of user-friendliness, I will generalize a couple of methods developers use to increase the user experience (UX). More specifically I will compare two versions of the OC Transpo Travel Planner to extrapolate generalities about user friendliness. The goal is to make people aware of the techniques used by developers to increase user-friendliness, and hopefully help someone make a more educated decision either when designing an application or selecting software.

## Background Information

It's easier to understand how complicated software can be user friendly when we have a better understanding of User-Centered Design (UCD) and how it's come to be such a critical step in software development. Software usability has seen a shift in recent years towards a more human-centered approach. UCD is not a new, and it's abundant use in today's digital companies was probably best predicted by by R S Nickerson when he said "the need for the future is not so much computer oriented people as for people oriented computers'' in 1969 \[1\]. Having said that 47 years ago (UCD) is not a novel idea, but rather a growing and continually and evolving concept.
![Figure 1. Taken from [2]: "A pictorial summary of some of the fields related to the user. The major fields are shown with solid lines."](https://s3-us-west-2.amazonaws.com/the-grid-img/p/981c694f93d56cc9381638a6db49e45f415c3cbd.png)

In brief UCD combines aspects from each of these fields: cognitive and social psychology, linguistics, mathematics, computer science, engineering, human factors and ergonomics, socio-technical systems design, scientific management, work, industrial, and occupational psychology, human relations, and organizational behaviour\[2\]. Figure 1 above visually demonstrates how each of these different fields relate to each other. Naturally, it comes as no surprise that advancements in any one of these fields, including technological advancements, could beneficially affect the end-user's experience. This is why UCD has become such a crucial part of developing software.

## Usability Comparison

The UX between two functionally equivalent pieces of expert software can greatly differ. My intent is to compare two public transit travel planners to determine if there are any trends which directly affect the UX either in a positive or negative way.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/79f7263b-6470-4fb4-b1c0-0239f16eeeb7.jpg)

OC Transpo recently released their new travel planner. They describe the new planner by saying it "will provide you with some big improvements, compared to the current version" \[3\]. Figure 2 above is a comparison between the two systems. OC Transpo maintains that the core functionality remains the same in that "travel solutions and schedules are identical in all versions of the travel planner"\[3\]. Comparing the two versions it's easy to see why the new travel planner provides a better UX, however it's not as straightforward as it may seem. In addition to providing the same functionality to the end-user the new travel planner also provides the user with a multitude of enhancements including: a full screen google map, and also integrates a new function allowing users to see departure times for all routes at a Transitway station.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/be68668c-a797-4d23-9043-498bea9b61b4.png)

The old Travel Planner allows users to plan a trip, but in order to do so the user must know the name of the bus stops closest to their current address and their destination address. The planner gives the user 6 different ways to enter this information: using an address, an intersection, a landmark, a bus-stop number, a map, or history (previously used queries). My first time using this system was confusing because the form does not provide much useful feedback regarding the advancement from step to step. For example, figure 3 above demonstrates what happens when a user attempts to specify their beginning address. Notice how immediately upon pressing okay the text-field is emptied, and a very small text label appears under the "From" portion of the progress bar. While this does provide some feedback to the user the change is not evident enough. As a first time user of the system myself, I thought that I had to re-enter my address because It didn't provide enough feedback for me to realize that it accepted my original input. It was only after attempting to use the same address again that a warning message appeared to tell me  the destination can't be the same as the origin.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/c9002751-74d7-44af-bceb-7e2a249e6faa.gif)

Another downfall of the old travel planner is that the map is not what the average user has grown accustomed to in today's digital world. Google Maps has become the goto-tool for most people looking directions these days, myself included, due to it's reliable detail and ease-of-use. Figure 4 above is a demonstration of how the original interactive map functioned. As the user moves the mouse a random sized square highlights a section of the map under the cursor.

Clicking on a square zooms in for a closer view of that area as seen in Figure 5 below. At this point the task becomes overly cumbersome as the user is now required to use the buttons/hyperlinks around the map in order to find their desired bus-stop. This means clicking on the "Show Stops" hyperlink, which then reveals an overlay of red dots on the map for the user to click. Clicking on a red dot, however, does not always select 1 station. Instead, a the map switches to a list of possible bus stops the user may be looking for. The descriptions of the bus stops in this list are not very clear as seen in the last step of Figure 5\. What's makes this process so confusing and complicated is the fact that the names of the bus stops presented to the user are too long to be fully read by the user. Regardless of how I attempted to resize the browser window the menu stayed the same size. The only way to tell them apart was to select the text and copy/paste it to a text editor. In this case the last two bus stops have the same name, but opposite directions, and therefore opposite sides of the street.
![](https://s3-us-west-2.amazonaws.com/the-grid-img/p/42314c9ba076b287bc14fc3167955d7981d4061e.png)

Comparing the map functionality between the two version yields some very interesting findings. Attempting to choose a source/destination bus stop using the map on the new travel planner has gone from being a very complicated task in the old version to one of the simplest tasks to perform in the new version. Figure 6 below demonstrates this. Notice how clicking on any area allows you to choose an exact location to leave from, regardless of whether or not there is a bus stop there. The new travel planner allows a user to do this, and will instruct the user where to walk to in the suggested trip plan. This is a huge improvement over the previous map because the old version only allowed you to start your trip at a bus stop. ![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/d553b198-aff1-4a2d-a42c-28c05606b2a7.png)

While the new system is simultaneously aesthetically pleasing and visually informative the new travel planner's website is deceiving. The red-colored menu bar along the top of the new travel planner is not actually part of the new system, but is instead a standard website navigational menu which navigates to other OC Transpo web pages. This design decision seems to positively improve the user experience because it provides answers to commonly asked questions while visually complimenting the travel planner with the company's signature red color. ![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/49b717eb-485c-46ed-aa32-d8b886c8444a.png)

While the new system is considered a huge improvement over the previous version, there is still room for improvement. Clicking on one of these menu items does not perform any function other than redirecting the user to a URL external to the travel planner. The issue here is that any configurations made within the travel planner are instantly lost if the user clicks on "Try the New Travel Planner" URL to return to the application. The only way for a user to keep any information already entered is to use the browser's back button. 

There are several possible solutions which could make this aspect of the system more user friendly. One option could be for each of the menu items to forcefully open their links in new tabs/windows. This would ensure that the user's current session is not accidentally lost when looking at the Route Timetables. Another possibility could be to modify the interface to make it clear that the menubar along the top is not part of the travel planner. This can be done by placing a border, either in the form of a line or empty space, between the menu and the travel planner. Alternatively a pop-up message could notify the user that they are about to leave the page before redirecting the browser to the URL. This is a perfect example of how a seemingly trivial design decision can greatly impact the UX.

Picking one of the proposed solutions above requires some more analysis. Each of these decisions affects the usability of other functions, so it's important to take everything into consideration.  Separating the menu from the application either with a border or empty space could help indicate to the user that the menubar and the travel planner do not interact. There are several issues with separating the menu from the planner. If a solid-colored border is used there is a good chance that the user still thinks the menu is part of the travel planner. If a space is placed between the menu and the travel planner then the page will look like it's not formatted properly. Adding a title to the travel planner could help combat that issue, but then the website starts becoming cluttered. The menu currently visually complements the travel planner, and separating the two using either a border or a space could detract from this visual impact. Therefore attempting to increase usability in this manner could adversely affect the UX. Considering the other option of adding a pop-up message alerting the user about leaving the website also presents potential UX issues. Pop-up alerts can either be modal or modeless. Modal pop-ups force the user to address the alert before re-allowing the user the interact with the anything else. Modeless pop-ups do not force the user to focus on the message, and can typically even be closed without any repercussions. The issue I have with modal pop-ups is they should only be used in critical scenarios where a user's attention is needed for something serious. Forcing the user to answer a question about leaving a web-page while denying functional access to everything else imparts too much restriction on the user. Using a modeless pop-up in this scenario, while slightly less intrusive than it's modal sibling, will still alert the user to the impending loss of data while not restricting the user's actions to "OK" or "Cancel". Taking a closer look at this solutions reveals yet another potential impact this can have on usability. In the current configuration it takes me 1 click to navigate from the travel planner to any of the URLs in the navigational menu. Adding a pop-up now not only forces the user to perform at least 1 additional click, but would only be beneficial for first time users. Any user who frequently uses this new system would know that these links navigate away from the application, and therefore the pop-ups would only annoy the average user. The simplest and most elegant solution out of all of the solutions I proposed would have to be forcing a new tab/window to open. The only potential hiccup with this solution would be if the browser being used is configured to disallow new windows/tabs to automatically be opened. ![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/322a1f29-7542-4fe1-a65f-d267a39f556a.png)

## User-Friendly Software: What to look for?

Comparing OC Transpo's old travel planner to the new version reveals many trends developers are implementing to improve the user experience. While the new version still has some usability issues, it definately has come a long way from the original version. Using the analysis of these two systems I am going to attempt to provide a list of items which improved the UX.

\[1\] R S Nickerson. 1969\. Man-Computer Interaction: A Challenge for Human Factors Research. IEEE Transactions on Man-Machine Systems 10, 4: 164--180\. http://doi.org/10.1109/TMMS.1969.299924

\[2\] Frank E Ritter, Gordon D Baxter, and Elizabeth F Churchill. 2014\. User-Centered Systems Design: A Brief History. In Foundations for Designing User-Centered Systems: What System Designers Need to Know about People. Springer London, London, 33--54\. http://doi.org/10.1007/978-1-4471-5134-0\_2

\[3\] OC Transpo. (accessed March 5, 2016). OC Transpo - New Travel Planner. http://www.octranspo1.com/routes/new\_travel\_planner

\[4\] OC Transpo. (accessed March 5, 2016). OC Travel Planner. https://www.octranspo.com/tps/jnot/linkFromAddress.oci

\[5\] OC Transpo. (accessed March 5, 2016). Travel Planner. http://plan.octranspo.com/plan/?Culture=EN