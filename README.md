# DiaryManagementSystem
- Login and Signup 

![cd0e137f-f80d-4e39-8417-f70897de68d7](https://user-images.githubusercontent.com/105460398/168177300-ee755f9c-c67b-4f10-a48e-e3e7738181b1.jpeg)

When we run the application the Login Page is first sited, but we didn't register in the system yet so we need to Signup first.

-Signup:

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


-Login:

1. The user can login to the system by entering either a username or email, and a correct password.
(The database checks for a valid'username or email' , and then checks for a correct matching password). 
(invalid username or email)![inusem](https://user-images.githubusercontent.com/105460398/168326800-7c29cbf6-d338-477b-8007-248c0d491e3f.jpg)
(invalid password)![inpass](https://user-images.githubusercontent.com/105460398/168326874-0536af3b-8758-46f2-84eb-9487dd738154.jpg)
2. the user entered the system. ![homee](https://user-images.githubusercontent.com/105460398/168327001-70bbf470-8ad0-4ab6-a4f1-9e47cf8ba602.jpg)

-Forgot Password:

1. If the user forgot his password he can press on 'Forgot password?' and he is then sent to 'Forgot Password' Page ![loggggggggin](https://user-images.githubusercontent.com/105460398/168327441-e2aefe9b-6a58-44bd-b684-1702ccc32b27.jpg) ![4gotpass](https://user-images.githubusercontent.com/105460398/168327520-7f7211e1-fcd7-4409-b4d3-c9628ef8a3bf.jpg)

2. the user is asked to enter his email so he can get a verification code and then he can write a new password (the new password has the same conditions as the password in sign up).![4gotveremail](https://user-images.githubusercontent.com/105460398/168327797-78cc1179-b0a5-486e-b960-c1b0878930a6.jpg) ![newpass](https://user-images.githubusercontent.com/105460398/168327892-a1783700-aa41-45e1-9233-acc4d00737bf.jpg)


- Home Page:
1. When the user log in the following page is first encountered
![homescreen](https://user-images.githubusercontent.com/105460398/168328402-659e3c2c-1a92-4f10-8773-47d6d7e3fbd6.jpg)

(we will indicate parts of the page with colors so we could explain what each part represents)

![homescreenedited](https://user-images.githubusercontent.com/105460398/168328866-f3e2bc39-f1df-439b-97f2-e6fcc7330831.jpg)

  
  1. (As we can see on the left we have a bar with a bunch of icons pressing the menu icon 'indicated in yellow' would display a slider that describes the functionality of each icon).![menuslider](https://user-images.githubusercontent.com/105460398/168329282-d8dc1821-b35f-414c-9a84-d8d232acbd5b.jpg)
  
  2. (at the right edge 'indicated in blue' are the notes that the user has fixed to be displayed on home Page).
  
  3. (at the middle 'indicated in green' are the nearest events and are sorted from the nearest in time to take place to the furthest in time).


- Profile Page:

1. The user can access his profile page from pressing on profile icon.![homescreenprofile](https://user-images.githubusercontent.com/105460398/168334333-8933e4d9-846c-47b6-84ee-36a94af2fb07.jpg) 

![profile](https://user-images.githubusercontent.com/105460398/168334395-a0f057a6-a675-4457-aa0e-2be06b4a2449.jpg)

2. The profile page displays the user information and just like the home page the user can see at the left edge his fixed notes.
3. If the user wishes to edit his information he can press on 'Edit My Profile' and 'My Information' panel would change to the following.![editinfo](https://user-images.githubusercontent.com/105460398/168334914-bd6e64d5-b7c6-4ce0-9d5e-4ccab637fecb.jpg)
4. pressing on 'My Information' would change the panel again to its previous one.


-Calender:

1. the user can access the calender by pressing the calender icon from the bar 'indicated in blue'.![profilepage0000001](https://user-images.githubusercontent.com/105460398/168335515-f38a3753-2622-4454-90a0-b04e58c9b355.jpg)
2. The calender Page is displayed.![calenderhome](https://user-images.githubusercontent.com/105460398/168335657-efacd41f-04e0-4a68-84ea-e7620c18dd4a.jpg)

3. On the left side the user can search for his diaries.![calendersearch](https://user-images.githubusercontent.com/105460398/168336230-85c392bf-72c0-4cf0-a4d6-1adc1cde98bb.jpg)

4. the user can click on one of the diaries he has searched for to display its information.![diarysearch](https://user-images.githubusercontent.com/105460398/168336808-07511098-3924-4745-a099-32db39d2c0c5.jpg)
5. Since the label 'indicated in blue' shows which month and year we are in (by default it is the month and year on your computer) you can add a diary by pressing on any day of the month (you can change the month and year be pressing on their buttons too).![wqdqwdq](https://user-images.githubusercontent.com/105460398/168337403-2cc06427-9098-4a2e-a69f-599dc14f3709.jpg)

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



-Groups:
















 
 


