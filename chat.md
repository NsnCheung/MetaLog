AI Interaction Overview:
- [Kimi K2 Thinking]([url](https://kimik2thinking.org/)) for the initial prompt.
- [Github Copilot]([url](https://github.com/features/copilot)) for refining the website.

Prompting Details:
- Kimi K2 Thinking initial prompt:
  ```
  I am writing a frontend for a hackathon
  
  The idea is a chatbot that scans a student's homework or records the process of a student doing their homework
  and determines the likelihood that they have autism spectrum disorder based on their habits
  
  Front-end only (HTML, CSS, JS, or any framework).
  
  No live functionality needed — focus on design and presentation.
  
  Bonus points if your landing page is mobile-friendly.
  
  a) Homepage
  b) Page to upload file or take a snapshot (after uploading the essay file and analyse)
  c) Chatbot asking question, and users can reply d) Result page where users can download the test report)
  
  i want something similar to chatgpt or this website (kimik2thinking.org/chat)
  but with an autism friendly design if possible
  ```
  Response:
  Outputted Homepage (index.html), Upload Page (upload.html), Chatbot Page (chat.html), Results Page (results.html).
  Follow-up:
  Some refinements to the name and linking functionality of buttons.
  
- Github Copilot refining prompt:
  ```
  check if the tabs are centered or visually centered,
  remove built for hackathon and for education purposes only text,
  change to 2025
  ```
  Response:
  Changed the tabs to look more centered and removed unnecessary/wrong text.
  
- Github Copilot refining prompt:
  ```
  add a button to try out the chatbot without uploading or taking a picture
  ```
  Response:
  Added a feature to use the chatbot without uploading or taking a picture.

Project Evaluation:
- For the initial code I used Kimi K2, a relatively new and promising model, which generated a pretty good looking website
  and surprisingly it was able to pick up on the "autism friendly design" requirement quite well, having an aesthetic that
  was clean and definitely won't overwhelm the user.
- For refining the website I went for Github Copilot which was more robust and integrated with Github nicely
  (I tried Cursor but had some issues trying to get it to work). It was able to complete basic tasks like
  adding or removing tabs, changing text, and adding buttons with zero resistance.
