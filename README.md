# DiaryManagementSystem
A desktop application that organizes user's events, notes and memos into their own calendar. Application can send alerts when certain events are approaching. Additionally, you can have dozens of invitation cards that users can create for various events and share with users inside and outside the application. 
 The application also includes creating a public or private group that brings together a number of users in a chat dedicated to group members, in addition to a group calendar that all users can modify.

- Login and Signup 

![cd0e137f-f80d-4e39-8417-f70897de68d7](https://user-images.githubusercontent.com/105460398/168177300-ee755f9c-c67b-4f10-a48e-e3e7738181b1.jpeg)

When we run the application the Login Page is first sited, but we didn't register in the system yet so we need to Signup first.

- Signup:

![Signup Page](https://user-images.githubusercontent.com/105460398/168178351-a03b10ff-d8a3-4c14-8e47-736aeb89cf63.jpg)

In the Signup Page we fill up the information required and we have to take in mind the restrictions of some attribute.
1. 1. We have to enter a valid email (contains '.com','@',no spaces etc...).
   2. We have to enter a valid username (contains only Letters,Digits,'-','.',' _ ').
   3. We have to enter a valid password: ![Password Conditions](https://user-images.githubusercontent.com/105460398/168179354-9e67c15c-c5e0-4eb3-b166-0c0fb2267046.jpeg)
   If any of the required was not applied a Label in red would be set Visible under the textfield that didn't apply one of its conditions.
   (Note : our system deals with dates perfectly as for which months have different days from the rest and as for which year the second month would have 29 or 28 days).
   
   
2. After filling the required information the user press on sign up button so he could get a verification code on his email.![email](https://user-images.githubusercontent.com/105460398/168324461-2a7d0d91-93ae-4580-9249-0dad159c9a3f.jpg)
3. the user then enters the code he received.![confirmemail](https://user-images.githubusercontent.com/105460398/168324668-2ad43154-5f95-4ae9-b983-f6c7c9fde4ca.jpg) (if the user entered an invalid code a label would be set visible asking the user to enter a correct code)
   
   (Note: if the user pressed back or didn't confirm the verification step and tried to log in, it would bring him back to 'Confirm your email' Page).
   
4. the user is brought again to 'Login' Page.![loggggggggin](https://user-images.githubusercontent.com/105460398/168325507-e7c07205-92b3-439e-8e02-a8d4e76c4d0e.jpg)


- Login:

1. The user can login to the system by entering either a username or email, and a correct password.
(The database checks for a valid'username or email' , and then checks for a correct matching password). 
(invalid username or email)![inusem](https://user-images.githubusercontent.com/105460398/168326800-7c29cbf6-d338-477b-8007-248c0d491e3f.jpg)
(invalid password)![inpass](https://user-images.githubusercontent.com/105460398/168326874-0536af3b-8758-46f2-84eb-9487dd738154.jpg)
2. the user entered the system. ![homee](https://user-images.githubusercontent.com/105460398/168327001-70bbf470-8ad0-4ab6-a4f1-9e47cf8ba602.jpg)

- Forgot Password:

1. If the user forgot his password he can press on 'Forgot password?' and he is then sent to 'Forgot Password' Page ![loggggggggin](https://user-images.githubusercontent.com/105460398/168327441-e2aefe9b-6a58-44bd-b684-1702ccc32b27.jpg) ![4gotpass](https://user-images.githubusercontent.com/105460398/168327520-7f7211e1-fcd7-4409-b4d3-c9628ef8a3bf.jpg)

2. the user is asked to enter his email so he can get a verification code and then he can write a new password (the new password has the same conditions as the password in sign up).![4gotveremail](https://user-images.githubusercontent.com/105460398/168327797-78cc1179-b0a5-486e-b960-c1b0878930a6.jpg) ![newpass](https://user-images.githubusercontent.com/105460398/168327892-a1783700-aa41-45e1-9233-acc4d00737bf.jpg)


- Home Page:
1. When the user log in the following page is first encountered. ![uybuvebeubv](https://user-images.githubusercontent.com/105460398/168383034-57c495a7-300c-405f-af88-122ed123c6be.jpg)



(we will indicate parts of the page with colors so we could explain what each part represents)![homescreen](https://user-images.githubusercontent.com/105460398/168382432-12c05704-3151-48dc-ab14-e20212a16a5c.jpg)



  
  1. (As we can see on the left we have a bar with a bunch of icons pressing the menu icon 'indicated in yellow' would display a slider that describes the functionality of each icon).![menuslider](https://user-images.githubusercontent.com/105460398/168329282-d8dc1821-b35f-414c-9a84-d8d232acbd5b.jpg)
  
  2. (at the right edge 'indicated in blue' are the notes that the user has fixed to be displayed on home Page).
  
  3. (at the middle 'indicated in green' are the nearest events and are sorted from the nearest in time to take place to the furthest in time).


- Profile Page:

1. The user can access his profile page from pressing on profile icon.![homescreen](https://user-images.githubusercontent.com/105460398/168382596-8d15675d-5bb3-43d2-beda-3522e9b6457e.jpg)


![profile](https://user-images.githubusercontent.com/105460398/168334395-a0f057a6-a675-4457-aa0e-2be06b4a2449.jpg)

2. The profile page displays the user information and just like the home page the user can see at the left edge his fixed notes.
3. If the user wishes to edit his information he can press on 'Edit My Profile' and 'My Information' panel would change to the following.![editinfo](https://user-images.githubusercontent.com/105460398/168334914-bd6e64d5-b7c6-4ce0-9d5e-4ccab637fecb.jpg)
4. pressing on 'My Information' would change the panel again to its previous one.


- Calender:

1. the user can access the calender by pressing the calender icon from the bar 'indicated in blue'.![invirnvindivr](https://user-images.githubusercontent.com/105460398/168383212-d4d3770c-6fc3-4bfa-b373-5e50dcbdf1cb.jpg)

2. The calender Page is displayed.![calenderhome](https://user-images.githubusercontent.com/105460398/168335657-efacd41f-04e0-4a68-84ea-e7620c18dd4a.jpg)

3. On the left side the user can search for his diaries.![calendersearch](https://user-images.githubusercontent.com/105460398/168336230-85c392bf-72c0-4cf0-a4d6-1adc1cde98bb.jpg)

4. the user can click on one of the diaries he has searched for to display its information.![diarysearch](https://user-images.githubusercontent.com/105460398/168336808-07511098-3924-4745-a099-32db39d2c0c5.jpg)
5. Since the label 'indicated in blue' shows which month and year we are in (by default it is the month and year on your computer) you can add a diary by pressing on any day of the month (you can change the month and year be pressing on their buttons too).![isncidnscidsd](https://user-images.githubusercontent.com/105460398/168383346-066f8c31-ebb0-4559-96e5-f054704a4345.jpg)


![month](https://user-images.githubusercontent.com/105460398/168337793-b011d140-be1a-4505-a4ad-5f1a95217296.jpg)
![year](https://user-images.githubusercontent.com/105460398/168337815-32828dcf-9121-4b92-bb64-56e8bdfcf172.jpg)

(Notice that the Month/Year label changes depending on what you choose)

(As we discussed before about dates in our system it automaticaly deals with different days for certain months and also days for leap and non-leap years for the 2nd month).

6. After you pressed on one of the days, you can see the diaries for that specific day which is the same that you would see when you press on 'My Diary' the user can also edit the diaries or delete them.![mydiary](https://user-images.githubusercontent.com/105460398/168338737-7c9bf3e2-ee60-4524-863b-ca6d6d24aecc.jpg)
(For Edit)
![editsds](https://user-images.githubusercontent.com/105460398/168341225-ff09fb69-a2b8-43f1-9b79-daae699a20c0.jpg)

 
7. the user can add a new diary by pressing on 'Add New Diary' and he can specify that this diary is a Memory,Event, or Note. 


(For Memories and Events you can set a Title, Description, and you can set a notification).![memory](https://user-images.githubusercontent.com/105460398/168339779-210dca0b-7ee7-49dc-8aa8-6933d175a24e.jpg)

- As for set notification button:
  (Aside from setting the date like we discussed the user can set the hour and minute which the notification would notify the user).![notifi](https://user-images.githubusercontent.com/105460398/168340070-73351193-be27-4999-9524-ae0ba169cec8.jpg)
  (If a diary notification time has come the following would be shown accompanied with a notification sound)
  ![notttttttttt](https://user-images.githubusercontent.com/105460398/168340772-db012df3-7c47-4c99-b39c-19a841842fd5.jpg)
  (If the notification is pressed it displays the diary information just like the one we saw in search diary)![cwecww](https://user-images.githubusercontent.com/105460398/168340999-b69e5378-40ae-4860-993d-93da4b459d8c.jpg)




(For Notes you can set a Title, Description, and you can Fix Note to be displayed as we saw before on the home page panel and on the Profile page panel).![note](https://user-images.githubusercontent.com/105460398/168339793-7f66a228-c0ac-43f7-80cc-b5268d12cdbb.jpg)



- Groups:


1. the user can access groups by pressing the groups icon from the menu bar 'indicated by blue'.![dawdaadw](https://user-images.githubusercontent.com/105460398/168374328-bdef72fc-2b62-4081-b164-986777870349.jpg)

   1. on the right edge the user can search for his groups (is an admin/member) the same way he could search for diaries like mentioned before.
   2. at the middle the user can search for public groups (this functionality is provided because there are things like 'institutions and so on' which the system provide to be public).
   3. and the user can check for invites from other groups so he could join from the icon 'indicated by blue'.![groups](https://user-images.githubusercontent.com/105460398/168373987-a9bed0f2-e2c4-451f-82f5-e3f031a48952.jpg) (When pressed the panel for search groups would change for the following panel where the user can accept invites or delete them) ![acceptint](https://user-images.githubusercontent.com/105460398/168374651-d5e832c9-0e46-422c-85ae-a6c171c045ec.jpg)



2. the user can access any of his groups by pressing on its name, and it will open up the group chat.![group](https://user-images.githubusercontent.com/105460398/168374959-89b56fa8-b4ba-4fc9-9d79-726534bc1c0c.jpg) 
3. the user can access the group information by pressing on the groups name (and can edit them if the user is an admin of the group) 'indicated in yellow'.![chat](https://user-images.githubusercontent.com/105460398/168375413-c1f4fc0e-6a5a-4344-9386-a808f964cc85.jpg)

(if the user was an admin he can change the group's name, description, group's image, group's privacy, if the members of the group can send messages through chat or only the admin, if the members can add diaries to the group or to only display the diaries added by the admin, if the user wan an admin of the group he can add members 'which means that they will receive an invitation to the group' or View requests to join the group 'only possible if the group is public' or View members of the group 'if another user is invited but yet not accepted he will show up incase the admin want to delete him or in other words cancel his invitation').![rd dvdvd](https://user-images.githubusercontent.com/105460398/168376239-7ca0d84e-8945-44f5-acf6-88f8e23096ca.jpg)

(the following page will pop up when we press on 'Members' to view members of the group)![members](https://user-images.githubusercontent.com/105460398/168377996-df1d5af8-c8dd-4f09-b39c-3510cb211734.jpg)




4. the user can access the group calender by pressing on the icon 'indicated in blue' (the group's calender is like the personal calender that we explained before).![cece](https://user-images.githubusercontent.com/105460398/168376146-e1e3d0a3-21d3-4897-a38c-7458dffa827d.jpg)

(if the user was not an admin of the group and he wasn't given permission to add diaries his page would be displayed like the following)![membrrrrrrrrer](https://user-images.githubusercontent.com/105460398/168378319-9d9383e5-7f43-43f5-b5b9-842bd7069f80.jpg)

5. the user can create a new group by pressing the icon 'indicated in blue'.![ceavrdv](https://user-images.githubusercontent.com/105460398/168378605-086afe82-eb90-486f-9a23-6bee3eac5700.jpg)

(the following page would pop up, so the user can fill the new information and he can edit them later on).![dbfdbd](https://user-images.githubusercontent.com/105460398/168378787-dd4e3cc1-426c-4e21-bdba-b92923c21cec.jpg)


- invitation: 

1. the user can access the invitations Page from pressing the icon 'indicated in blue'.![evrgvege](https://user-images.githubusercontent.com/105460398/168379034-0e27c7b3-7c0f-409c-bf6c-133d405c86d5.jpg) (the following page would be displayed) ![cuwbecwubc](https://user-images.githubusercontent.com/105460398/168379100-a1ce769e-b868-42c2-928b-c51dc881c134.jpg)

2. the user is intoduced with various options for invitations.
   -the user can create an invitation (different types of invitations each of them has there own unique templates).
      1. Party invitation.
      2. BirthDay invitation.
      3. Wedding invitation.
(upon pressing on any of the templates it will create a new card and the following page would pop up so the user can fill the invitation information).![ivenrivenire](https://user-images.githubusercontent.com/105460398/168380134-6efdafea-59e0-4823-8b2b-6ea7ed1cfafa.jpg)
(if the user enters a '#' in the 'Receives Username' the card will be saved and it will not be sent to anyone).
    -the user can display his cards

the user can display the invitations he sent by pressing on 'Show My Cards'(if the user presses on the invitation itself it will be saved on his computer). ![ivneirev](https://user-images.githubusercontent.com/105460398/168380985-68087bd5-8cfa-4425-b755-41820838505f.jpg)
    -the user can display the invitations he received

when the user presses on 'My Invitations' the page will display invitation cards that has been sent to the user and by pressing on them it will be saved on his computer ![wcuwbeucwu](https://user-images.githubusercontent.com/105460398/168381350-8b011a0f-c494-4bc8-ab33-90a2a8e23eed.jpg)








- Logout

the user can log out of the system by pressing 'out, indicated in blue' in the menu bar.![ywetwyfdtewtftw](https://user-images.githubusercontent.com/105460398/168381632-bc9b0535-4ccd-49d8-9eb2-0695638ec077.jpg)

   














 
 


