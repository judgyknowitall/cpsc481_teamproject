---
title: Stage 3
description: Ideation and Lo-fi prototype
layout: default
view_github: "true"
branch: '/tree/stage_3'
download_url: '/releases/tag/v3.0'
download_txt: Download deliverable
---

## Tasks
1. Brainstorm ideas and do 20 sketches
1. Affinity Diagram
1. Select and Polish ideas
1. Storyboard
1. Low-fidelity prototype
1. Task-centered system cognitive walkthrough
1. Prototype Demo
1. Stage 3 presentation

---

## Presentation
[![HCI FALL 2020 - Stage 3 Presentation](http://img.youtube.com/vi/sKIyouqejVw/0.jpg)](https://www.youtube.com/watch?v=sKIyouqejVw)

---

## Stage 3 Report

### Project Description
This project is a mobile application to assist people with caretaking, growing, and managing potted plants that are grown inside homes. There are many reasons people own houseplants, ranging from air purification to house décor. However, owning these plants is not always as simple and easy as it is made out to be. Many houseplants can be tough to grow and keep alive due to a myriad of factors, such as temperature, humidity, and soil conditions. This can result in plants dying due to improper caretaking, and people being discouraged from purchasing and owning houseplants.

This is where the mobile application would come in. The app would primarily display the user’s list of current plants on the Home Page, and upon pressing on an added plant item, a user may set reminders, view and add status updates, and view guidelines on how to manage their plant. It would also provide users with an easily accessible and cohesive source of information for each plant organized in the Plant Info page. Users may browse a catalogue of different plants or search for specific types of plants via the Catalogue. This mobile app would streamline all the aspects of houseplant ownership into one easy to use service, which would help current plant owners get a better idea of how to tend to their plants and remind them to do so. It may also convince prospective plant owners who were held back by their lack of experience and knowledge, to go out and purchase a few plants. 

---

### User Tasks
- Vertical Tasks: 
    1. Add a new plant using the camera. First, the user identifies the plant via camera, then they are shown a list of best matches based on the results. The user may then select a plant to add to their Plant List. If a match is not found, they have the option to try again or use a different method to identify the plant. 
    2. Add a new plant from the Catalogue. After browsing through the Catalogue, a user may select a plant to view its info or add the plant to their Plant List directly using the add button on the plant item. 
    3. Set up Reminders. When adding a new plant, the app will automatically calculate and set reminders based on the plant’s status. The user may turn on/off these notifications and edit or add extra reminders as necessary. 

- Horizontal Tasks: 
    1. View list of currently owned plants, more information about the plant, and its current status. 
    2. View a list of recommended plants in Catalogue that will be derived based on your preferences.  
    3. View plant information of currently owned plants as well as plants in the database/ Catalogue 
    4. Search for a specific plant in Catalogue. The search engine may feature an autocomplete function. 
    5. Add a new plant status to the journal to keep track of the plant’s health. 
    6. Add new plant to the Plant List by taking a survey to identify the plant species. 
    7. Use the camera to find information on a plant. 
    8. Edit a reminder that was previously set. 
    9. Navigate smoothly between different interfaces.

---

### Storyboard
How can we simplify the process of learning how to care for a new plant? 
![Storyboard](assets/pics/stage3_1.png)

---

### Discussion of Cognitive Evaluation
All tasks stated in our Stage 2 report were modified in one way or another in this stage. We either split those tasks into subtasks or elaborated on them further to make them more specific. These changes are as follows:

**Must Be Included Tasks:**
- The ability to set reminders remained the same. This is one of our vertical tasks for this stage. An extra horizontal task was added to describe the ability to edit a reminder. 
- The catalogue portion was divided into a vertical and three horizontal subtasks. These include the ability to add a plant, search for a plant, read information about a plant, and view recommended plants. 
- Plant identification was specified into identification via camera, as it collided with the task of adding plants.

**Important Tasks:**
- Creating a list of plants was subdivided into the tasks: adding a plant via camera, adding a plant via a survey, and view a list of current plants.
- Keeping track of plant health and status via a journal was not changed.

**Could be included Tasks:**
- Since these tasks involved receiving notifications, we did not include them in this report as they could not be prototyped with our abilities and knowledge.

After conducting the cognitive walkthrough of the first version of our low-fidelity prototype, we concluded that we should add optional guides for the less intuitive portions of our app, prioritize showcasing the major functions over the more minor tasks, and decrease ambiguity as much as possible through proper design. Afterwards, we modified the prototype based on some of the suggestions. For example, we added back navigation to allow users to backtrack to the previous screen or added information boxes for the plant identification survey questions. Some of the other suggestions were difficult to implement in a low-fidelity prototype so they should instead be implemented in the high-fidelity prototype or the product itself. These modifications include adding a user manual or guideline on how to navigate within the app and further explain some of the functions. 

---

### Reflection
As there was quite a bit to do in this stage, there were several points in the ideation process that stood out as going well or poorly. Something that really helped the process stay on track was setting up extra meeting times and setting goals for each meeting date at the beginning of the process. We also found that coming to brainstorming sessions prepared with some sketches helped group members to better articulate ideas and gave them some time to think about strengths and weaknesses of their ideas in advance. This also made the revisions process go relatively smoothly. The storyboard step also went relatively smoothly, aided by the tool Storyboard That which simplified the visual aspects of storyboard creation. Finally, for the lo-fi prototyping, splitting up the different parts of the app into a few standalone processes allowed the group to work on the prototype in parallel, which left the group more time to refine the final prototype at the end.  

One area that didn’t go as well was the affinity diagram. As we had to set our schedule before learning more in-depth about affinity diagrams, we needed to adjust for revisions that impacted later stages of the process. In general, the process felt rather rushed. If we were to do the process again, we would have allotted more time to work on the affinity diagram. We would have also taken some time to compile sketches for each task/area together into single documents. This would have made it a bit easier to compare the pros and cons of similar ideas during brainstorming sessions. 

---

### Appendix

#### Cognitive Walkthrough Doc

| Task# | Description of Task Step | Does user have training or knowledge to do this step? | Is it believable that they would do it? | Are they motivated? | Comments (including possible solutions) |  
|:---:|:--- |:--- |:--- |:--- |:--- |  
| 1v | Add a new plant via camera. | Yes, if the user has used any camera applications before. | Yes. | Yes. Leaves most guess work out of the user's hands and allows application to determine the plant for them. | Include instructions and illustrations on how the camera should be angled to better capture an image |  
| 2v | Add a plant to the plant list via the catalogue. | No. This task must be made clear, and simple to use so that users can easily understand and use this function. | Yes. | Yes. As adding plants to the plant list makes it much easier to view the status of currently owned plants. | Users will be able to search the catalogue for specific plants, then easily add plants to their list from there.|  
| 3v | Set a reminder for watering a plant. | No. Not intuitive unless the user is familiar with the interface and has explored the navigation thoroughly. | Yes. | Yes. Allows users to let application keep track of a plants watering schedule. | Notifications by the application may be disabled by the user, in which case the application might need to notify the user of the problem. |  
| 4h | View the list of owned plants and their current status. | No. However, this task can be accomplished by opening the application. | Yes. | Users need to know the status of their plants quickly to check if any of the plants need attention. | This is the main function of our app. Must be most intuitive and illustrative. |  
| 5h | View recommended plants. | No. Viewing the recommended plants does not require complex navigation, as they are found when the catalogue is opened without any search inputs. | Yes. | Yes. The user might like to find plants that they are not familiar with, and thus might browse the recommended plants list in the catalogue. | Adding text to let the user know that the default catalogue items are recommendations may help them understand what they’re seeing. |  
| 6h | View plant information of an owned plant. | No. Current way would involve going to catalogue to search for the plant info and this process is not very intuitive. | No. A new user may not immediately know how the app works or how to navigate properly. | Yes. They may want to learn more about their plant species as a way to care better for them or simply out of curiosity. | Make My Plant Page scrollable where the top half would include plant care functions and the bottom would include plant information. |  
| 7h | Search plant in catalogue. | Yes. If the user as used any type of search function before. | Yes. It is how users will be able to find plants in the catalogue. | Yes. As searching for a plant in the catalogue allows for users to access more functions, such as plant info and adding plants to their list. | Searching through the catalogue should be done through a search bar that will be clearly presented on the catalogue screen. |  
| 8h | Add a new plant status. | No, since this task is not very important, it is hard to navigate to. | Yes. However, it is uncommon. | Yes. Users may want to keep a journal of their plant health at different times. | Since this is a minor task, it does not require as much attention. |  
| 9h | Add a new plant via survey. | Yes. Since all surveys are made similarly, the user may find it intuitive. | Yes. | Yes. If they do not have a name or photo of the desired plant. | Add information about each answer so they are not ambiguous. Include a back button in case, they made a wrong choice. |  
| 10h | Use the camera to find information on a plant. | Yes, the function to use the camera for scanning a plant is intuitive. | Yes. | Yes, they would be, as it would allow them to learn about a plant of theirinterest. | The user might not have a camera, or allow use of camera by the application, which would require the application to return to the previous interface in that case. |  
| 11h | Edit a reminder that was previously set. | No. Not intuitive unless the user is familiar with the interface and has explored the navigation thoroughly. | Yes. | Yes. The user would not want a wrong reminder to remain unedited. But this action should be uncommon. | Make the edit button more inviting to users. Add a user guideline or hints on the reminders page. |  
| 12h | Navigate smoothly between different interfaces. | No. This task must be made intuitively so the user does not need training to learn. Some back navigations don’t exist. | Yes. | Yes. By smoothly navigating between interfaces, the user can avoid frustration and save time. | The addition of a universal navigation bar that persists for all interfaces might make the navigation even more smooth for the users.  |  
| 12’h | Access catalogue from “hamburger” menu. | No. | No. The “hamburger” menu is not immediately intuitive as there are no written descriptors, only images for navigating. | Yes. By using the “hamburger” menu, the user can save time on navigation. | Add a small font written description on each of the images. Keep a legend of the images elsewhere so that users know before accessing the “hamburger” menu what the images are. |  


#### Affinity Diagram

![Affinity Diagram](assets/pics/stage3_2.png)


#### Samples of Ideas and sketches:

![Affinity Diagram](assets/pics/stage3_3.jpg)  
![Affinity Diagram](assets/pics/stage3_4.png)
![Affinity Diagram](assets/pics/stage3_5.jpg)
![Affinity Diagram](assets/pics/stage3_6.jpg)
![Affinity Diagram](assets/pics/stage3_7.jpg)
![Affinity Diagram](assets/pics/stage3_8.png)
![Affinity Diagram](assets/pics/stage3_9.png)


#### Links and Citations
- [Storyboard that](https://www.storyboardthat.com/) (used to create storyboard)
- [Balsamiq](https://balsamiq.com/) (used to create Low-fidelity prototype)
- [Affinity Diagram](https://lucid.app/invitations/accept/3cd5c01f-566b-4b3b-8397-10c54b50354b) made in [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign=en_tier1_desktop_branded_x_exact&km_CPC_CampaignId=1490375427&km_CPC_AdGroupID=55688909257&km_CPC_Keyword=lucid%20chart&km_CPC_MatchType=e&km_CPC_ExtensionID=&km_CPC_Network=g&km_CPC_AdPosition=&km_CPC_Creative=442433236001&km_CPC_TargetID=kwd-55720648523&km_CPC_Country=9001331&km_CPC_Device=c&km_CPC_placement=&km_CPC_target=&mkwid=sVrXnwD0X_pcrid_442433236001_pkw_lucid%20chart_pmt_e_pdv_c_slid__pgrid_55688909257_ptaid_kwd-55720648523_&gclid=Cj0KCQiAy579BRCPARIsAB6QoIbWtBFYmcHLG1KyONwo2kiHybix1wI0vcCVvmLz0JFDW8Df9WfYp9caAoyGEALw_wcB)