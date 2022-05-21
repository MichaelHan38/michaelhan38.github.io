---
layout: splash
title:  "Bilingual Interface Design"
date:   2022-05-17 21:06:33 -0700
categories: jekyll update
---

Technology is not always designed for the global stage. Those who struggle with English aren’t able to benefit from this digital age. For instance, classes that were conducted virtually due to the recent Coronavirus pandemic pose challenges for such populations. According to this source, “Non-English speakers face challenges in virtual learning” by Sarah Hofius Hall, refugee families in Scranton, Pennsylvania face issues with concurrently learning to use technology as well as English. Many of these refugees are worried about their ability to assist their children who must attend school virtually. According to the article, 9.3% of the students require English services while 25% of students live in a home where English is not the primary language.  

In both little and huge issues, technology has always been a fantastic tool to help us go by. At best, limiting access to such a powerful resource would inconvenience many people; at worst, such a limitation would worsen societal challenges of wealth, class, and equality. If technology was created with solely English speakers in mind, anyone who isn't fluent in the language would be unable to traverse the ever-evolving digital landscape and find opportunities. Ignoring to accommodate the design for non-English speakers would deprive them of their voice and ability to communicate with others. People being unable to access a critical resource will only contribute to our inequality.
We try to make technology more accessible to those that have fallen behind by creating an alternative web interface that will assist non-English speakers in having a platform that they are more readily able to navigate and explore.

## Initial User Research
In order to best serve our users and get a better understanding of their needs, we sent out a survey with the following questions that would impact the choices we made when implementing the design.
- Are you currently enrolled at SFSU?
- What language(s) are you conversant in? (Select all that apply)
- What language(s) are regularly spoken in your family?  (Select all that apply)
- Have you helped someone who struggled with using technology?
- Approximately how often do you interact with said individual(s)?
- Think about the last time you helped someone with technology. What were the difficulties and what did you do to help them?
- What are some of the common problems your friends/families face when using technology?
- What is lacking in current technology and how do you think technology can better address these issues?
- May we contact you for a short follow-up study?

# Findings
The responses that we received from 16 respondents are summarized below:
- Demographics:
 - 9 out of the 16 are students at SFSU
 - Language(s) fluently spoken out of all respondent are: English (16), Spanish(3), Mandarin/Cantonese(5), Korean(1), Danish(1), Urdu(1)
 - 11 respondents speak at least 1 other language
 - 4 respondents families speak only English at home
 - 12 respondents families speak English along and 1 other language at home
 - 14 out of the 16 respondents had helped someone with technology before
- 9 respondents indicated they are open for follow-up, 6 responded to follow-up and were interview
- The following reasons are identified by survey respondents as obstacles for people who are not adept technologically when it comes to using a technology:
  - language limitation (4 respondents)
  - new/unfamiliar applications (6 respondents)
  - not understanding functions (3 respondents)
  - non-intuitive UI (4 respondents)

## Wireframe
Based on the data that we collected, some of the main criteria that need to be present in our web interface are: accessibility for non-native speakers, intuitive layout, clear menu options, and clear documentation for users to take full advantage of the web interface. we created a wireframe of a web interface that incorporated 
In order to prioritize the language aspect of the problem, we used the design from an existing popular website, Tokopedia.com, which is an established e-commerce website in Indonesia. We did this so that we would not have to focus too much on the UI design. An initial rough wireframe sketch is shown in Figure 1.
<div align ="center">
<img src="/docs/assets/hci_project/wireframe.jpg" alt="Wireframe" style="max-width:60%">
<figcaption align = "center"><b>Figure 1. Initial wireframe design</b></figcaption>
</div>
## Prototype Iterations

# Initial prototype
In order to streamline the prototyping process, we decided to make use of the popular prototype development tool Figma. Our initial plan was to base our prototype around Tokopedia.com, like we had with our wireframe, but we were unable to find an adequate, free Figma UI Kit to build off of. Instead, we completely switched gears and created an iPhone 13 e-commerce app based on the Shopee App, a popular Southeast Asian e-commerce service, using a readily available UI Kit. This prototype can be seen in Figure 2.
<p float ="left" align = "center">
  <img src="/docs/assets/hci_project/p1/Home Screen.png" alt="prototype 1 homescreen" style="max-width:328px;margin-right:20px">
  <img src="/docs/assets/hci_project/p1/Categories.png" alt="prototype 1 category screen" style="max-width:328px;margin-right:20px">  
  <img src="/docs/assets/hci_project/p1/Clothing & Accessories.png" alt="prototype 1 clothing and accessory screen" style="max-width:328px">  
  <figcaption align = "center"><b>Figure 2. Screens from prototype 1</b></figcaption>
</p>
# Second prototype	
Following the finalization of our first prototype, we evaluated its usability using the Weinschenk and Barker 2000 classification. From our testing, we found 8 major heuristical problems, addressing 6 of them by implementing changes to our design, which are listed below:
Improved contrast of menu elements
Improved contrast of general translation subtitles
Added additional translations for more confusing loan words
Visualized  categories to reduce clutter
Added Tutorial and FAQ resources
Added missing navbar translations
After carrying out these changes, we came up with our second prototype, which is shown in Figure 3.
<p float ="left" align = "center">
  <img src="/docs/assets/hci_project/p2/Home Screen.png" alt="prototype 2 homescreen" style="max-width:328px;margin-right:20px">
  <img src="/docs/assets/hci_project/p2/Categories.png" alt="prototype 2 category screen" style="max-width:328px;margin-right:20px">  
  <img src="/docs/assets/hci_project/p2/Clothing & Accessories.png" alt="prototype 2 clothing and accessory screen" style="max-width:328px">
  <img src="/docs/assets/hci_project/p2/Hamburger Menu.png" alt="prototype 2 hamburger menu option" style="max-width:328px;margin-top:20px">
  <figcaption align = "center"><b>Figure 3. Screens from prototype 2</b></figcaption>
</p>
# Third prototype	
To test the usability of our prototype, we asked 5 students from a different group in our HCI class to complete the tasks below without any support or direction:
- Add a Harry Potter book to cart
- Add a coffeemaker to cart
- Add a drone to cart
- Add a smart speaker to cart
- Find the FAQ section

Though seemingly simple, because the main text of our prototype was presented in Indonesian and Malay, the tasks would serve to gauge the effectiveness of our bilingual interface since we confirmed that none of the participants had any prior experience with the languages.

After completing these tasks, users were asked to fill out a Qualtrics survey with questions centered around the perceived ease of use and overall usefulness of the prototype. The questions we used were largely based upon the web-based questionnaires for “User Interface Usability Evaluation” by Gary Perlman (https://garyperlman.com/quest/) with some modifications to make them better suit our prototype. These questions are detailed below:
- Level of difficulty of completing each task – between 1 (very easy) and 5 (very difficult)
- What makes a specific task easier than the rest
- What makes any specific task harder than the rest
- Whether the provided subtitles were helpful – between 1 (disagree) and 5 (agree)
- Whether the UI visuals were helpful – between 1 (disagree) and 5 (agree)
- UI organization, intuitiveness, and ease of use of the prototype
- Additional comments regarding usefulness of ease of use
- The most Positive and negative aspects of the prototype

Through all the feedback we collected, we were able to find and address key problems on the usability of our prototype. Summary of the response that we collected is shown below in Table 1-3.
<p align = "center">
  <img src="/docs/assets/hci_project/qualtrics results/t1.png" alt="Table 1. Task difficulty" style="width:50%">
  <figcaption align = "center"><b>Table 1. Task difficulty</b></figcaption>
</p>

<p align = "center">
  <img src="/docs/assets/hci_project/qualtrics results/t2.png" alt="Table 2. Perceived usefulness" style="width:50%">  
  <figcaption align = "center"><b>Table 2. Perceived usefulness</b></figcaption>
</p>

<p align = "center">
  <img src="/docs/assets/hci_project/qualtrics results/t3.png" alt="Table 3. Perceived ease of use" style="width:50%">
  <figcaption align = "center"><b>Table 3. Perceived ease of use</b></figcaption>
</p>

In addition, users commented and identified the following flaws in prototype 2:
- Difficult to find the FAQ section
- Some products could fit into multiple categories
- Misrepresentation of some category icons
- More support information could be added
- Lack of confirmation upon adding to cart

Based on the questionnaire, we made the following modifications to the prototype. The resulting prototype is subsequently shown in Figure 4:
- FAQ navigation button added to the top navbar
- The “Computer,” “Phones,” and “Smart Homes” categories were removed and integrated as subcategories within the greater “Electronic” category
- Icon for “Kitchen” category replaced with more fitting one
- Implemented tutorial pages for prototype onboarding
- Added "add to cart" button to each item

 The resulting prototype is then shown on Figure 4
<p float ="left" align = "center">
  <img src="/docs/assets/hci_project/p3/Home Screen.png" alt="prototype 3 homescreen" style="max-width:328px;margin-right:20px">
  <img src="/docs/assets/hci_project/p3/Categories.png" alt="prototype 3 category screen" style="max-width:328px;margin-right:20px">  
  <img src="/docs/assets/hci_project/p3/Clothing & Accessories.png" alt="prototype 3 clothing and accessory screen" style="max-width:328px">
  <img src="/docs/assets/hci_project/p3/Hamburger Menu.png" alt="prototype 3 hamburger menu option" style="max-width:328px;margin-top:20px">
  <figcaption align = "center"><b>Figure 4. Screens from prototype 3</b></figcaption>
</p>


## Future work
We had trouble with reaching out to more people to participate in our initial study. Consequently, our findings regarding technological challenges that bilingual users and how to incorporate a design that addresses these issues are limited. We had the same issue with limited participation for our usability study as well, resulting in limited discovery of problematic parts of our prototype. Iinitial survey and usability study should be conducted in much larger scale to better capture day to day challenges that bilingual users face as well as the problems that are present in the prototype design. In addition, we suggest future study to be conducted around redesigning government website such as the website of the Interal Revenue Service, Department of Motor Vehicle, or U.S. Citizenship and Immigration Services. Research improvement for these websites could have bigger impact for bilingual populations in the U.S.

## Contributors
Aaron Carlson, Michael Han, Ana Navarro, Nael Yun