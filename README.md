                   A PROJECT REPORT ON
#                    Who is Who in Myanmar
                          FOR
                    Geo Mandalar IT
                  SUBMITTED IN PARALLEL
                 FULLFILLMENT OF INTERNSHIP
                        PROJECT
                  UNDER THE GUIDANCE OF
                        Director
                     U Ravi Chhabra
                        Supervisor
                     Dr. Lwin Mar Thin
                 SUBMITTED BY
                     Ma San Thorl
                     Ma Zin Mar Kyaw
                     Ma Hnin Yamone Nwae
                     Ma Aye Thiri Kyaw
                     Ma Lwin Me Me khaing
                     Ma Ei Ei Linn
          University of Computer Studies (Mandalay)
                          4.9.2018
			  
#CONTENTS
<p>Abstract</p>
<p>Acknowledgement</p>
<p>Declaration</p>
<p>List of Figures</p>
<p>List of Tables</p>
<p>CHAPTER 1       INTRODUCTION<br>
1.1         Introduction<br>
1.2         Background<br>
1.2.1   Development Life Cycle<br>
1.2.2   What is Flask ?<br>
1.2.3   What is a Database  ?<br>
1.3         Objectives of the project<br>
1.4         Scope of Proposed System</p>
<p>CHAPTER 2        METHDOLOGY<br>
2.1         Requirements Analysis<br>
2.2         Software Selection<br>
2.3         Project Plan</p>
<p>CHAPTER 3        EVALUATION AND CONCLUSION<br>
3.1        Conclusion<br>
3.2        Advantages of the project<br>
3.3        Disadvantages of the project<br>
3.4        Limitations and Future Work</p>
<p>References</p>

#ABSTRACT

<p>The country of Myanmar is sometime known as Burma, and the two names are often confuse. It consists of 14 provinces: 7 states representing the areas of 7 main ethnic races and 7 divisions. The purpose of project is to know readily and inexpensively about Myanmar’s people such as Parliament, Writers, Directors, Actors and Singers.</p>
<p>On our websites, you can read the information contained on the page, and if there are any interesting hyperlinks, you can follow those links to find more information or to perform a task.
This could lead to save times and costs for the people who interested about  Myanmar’s people.</p>
<p>For admin Panel, admins can insert, data into database, delete and retrieve data for database. Users can use our system with both smart phones and computers. For Front End, the system was implemented using material design (HTML, CSS). For Back End, this system was implemented using JavaScript and jQuery. The project will be implemented using Flask with Python and deploy on Heroku (CLI).</p>

#ACKNOWLEDGEMENT

<p>I would like to deeply thanks my supervisor, Dr. Lwin Mar Thin, Associdate Professor, Hardware Technology Department, University of Computer Studies (Mandalay), for her helpful advice and close guidance throughout this project.</p>
<p>Then respectfully thanks to U Ravi Chhabra, CEO of Geo Mandalar IT Co.Ltd, for his invaluable suggestions, patient comments and detailed technical contribution.</p>
<p>I also thank all my teachers from University of Computer Studies (Mandalay), especially, our rector U Kyaw Zwa Soe , our pro-rector Dr. San San Tin and our teacher Dr. Aye Aye Chaw. I would like to gratefully thank my friends and my dearest parents who have always given great help and support through my life.</p>
<pre><code>                         DECLARATION
</code></pre>
<p>We declare that this project report or part of it was not a copy of a document done by other organization, university any other institute or a previous student’s project group at University of Computer Studies (Mandalay).</p>
<p>Project Details</p>
<p>Project Title _ Who is Who in Myanmar</p>
<p>Project ID _ Geo Mandalar IT Internship</p>
<pre><code>                        Chapter 1
                      Introduction
</code></pre>
<p>1.1    Introduction<br>
A web page is a document that is suitable for the World Wide Web and web browsers. To view a web page requires a browser (e.g., Internet Explorer, Safari, Firefox, or Chrome). A web browser displays a web page on a monitor or mobile device. Web pages usually include information such as the colors of text and backgrounds and very often contain links to images and sometimes other types of media to be included in the final view.</p>
<p>The project provides us the complete and accurate information about the Parliament, Writers, Directors, Actors and Singers who are in Myanmar by the webpages.</p>
<p>The project named “Who is Who in Myanmar” is aimed to widely useful for people who want to know about Myanmar and officially known as the Republic of the Union of Myanmar. It is developed in Flask with Python. Our project is very useful for those who want to save their times in self-accesssing or experimenting about Myanmar people.</p>
<p><strong>1.2 Background of the Project</strong></p>
<p><strong>1.2.1 Development Life Cycle</strong></p>
<p>Development life cycle is used to describe in planning the business processes to create the system development and test and arrange the information system in the project area.</p>
<p><strong>Agile Model</strong></p>
<p>Agile Model breakdowns the project development into small incremental tasks and those tasks are processed in iteration process. The iteration process includes requirements analysis, design, coding and unit testing. Agile Model can apply functional process of developing project rapidly and it is flexible model for developers. Backbone of Agile model is client communication, so if client does not understand what is meant to; the development team can be forward to the wrong direction. Technique I have to need to design the business process notations and make diagrams for the design in the project area.</p>
<p><strong>1.2.2 What is Flask?</strong></p>
<p>Flask is a micro web framework written in Python. It is classified as a micro framework because it does not require particular tools or libraries. It has no database abstraction layer, from validation, or any other components where pre-existing third-party libraries provide common function. However, Flask supports extensions that can add applications features as if they were implemented in Flask itself.</p>
<p><strong>1.2.3 What is a Database?</strong></p>
<p>A database is a collection of information that is organized so that it can be easily accessed, managed and updated.</p>
<p>Data is organized into rows, columns and tables, and it is indexed to make it easier to find relevant information. Data gets updated, expanded and deleted as new information is added. The Firebase Real-time Database is a cloud-hosted database. Data is stored as JSON and synchronized in real-time to every connected client. When you build cross-platform apps with our iOS, Android, and JavaScript SDKs, all of your clients share one Real-time Database instance and automatically receive updates with the newest data. Computer database typically contain aggregations of data records or files, such as attendance transactions, attendance percentage and reports.</p>
<p><strong>1.3 Objectives of the Project</strong></p>
<p>• To help for searching people who is who in Myanmar more efficient than ever</p>
<p>• To convey helpful information to specific users</p>
<p>• To provide the ability for making changes to the site’s information easily  for the operator</p>
<p>• To replace uncomfortable paper system by modern webpages</p>
<p>•To save times and costs</p>
<p><strong>1.4 Scope of Proposed System</strong></p>
<p>The proposed project of Who is Who in Myanmar is prescribed as follow; Manage Home, Political, Writer, Director, Actor, Singer, Help, Features, methodology and FAQ.</p>
*   View Home
*   View Political
*   View Writer
*   View Director
*   View Actor
*   View Singer
*   View Help
<pre><code>                         CHAPTER 2
                         MEHDOLOGY
</code></pre>
<p><strong>2.1 Requirement Analysis</strong></p>
<p>The description of the services and constraints are the requirements for the system. Requirement analysis is the process of deriving the system requirements through observation of existing system, discussions with potential users and procurers, task analysis.</p>
<p><strong>2.2 Software Selection</strong></p>
<p><strong>Chosen Programming Language</strong></p>
<p>I would like to use HTML, CSS, JavaScript, jQuery, material design lite in my project because there are a lot of benefits to pick up languages in our window form  application.</p>
<p>•   HTML describes the structure of Web pages using markup.</p>
<p>•   CSS can control the layout of multiple web pages all at once. It describes how HTML elements are to be displayed on screen, paper, or in other media.</p>
<p>•   JavaScript is a high-level and interpreted programming language.</p>
<p>•   JQuery is a fast, small, and feature-rich JavaScript library.</p>
<p>•   Material Design Lite makes more liberal use of grid-based layouts, responsive animations and transitions, padding, and depth effects such as lighting and shadows.</p>
<p>•   They are readily available and easy to access.</p>
<p><strong>Software Requirements</strong></p>
<p>•   Gitbash</p>
<p>•   Pycharm Community</p>
<p>•   Heroku</p>
<p>•   Github</p>
<p>•   Flask with Python</p>
<p><strong>Hardware Requirements</strong></p>
<p>•   Internet Access</p>
<p>•   PC with windows OS</p>
<p><strong>2.3 Project Plan</strong></p>
<p>In understanding the system requirements and testing some features, we work together. UI/UX, Developer, testing and documentation, we work together. User Access Level/ Access to Pages, project Manager and System Analysis are discussed about the systems to understand the user.</p>
<pre><code>                        CHAPTER 3
                 EVALUATION AND CONCLUSION
</code></pre>
<p><strong>3.1   Conclusion</strong></p>
<p>The app provide a great convenience for all users. Users could get all information that they are interested in at once without moving from site to site.</p>
<p>All people who are famous in Myanmar are collected and presented in the app. In which app including common facts about celebrities, writers, business men and also even politicians.</p>
<p>The app’s contents are human readable form and navigate you to the information store you want to know. It can be accessed from both mobile phones and computers with internet access. Moreover, up to date people’s news are provided for users at any given time.</p>
<p><strong>3.2 Advantages of the Project</strong></p>
<p>The proposed system offers the following advantages:</p>
<p>•   It provides “faster and better” services to visitors.</p>
<p>•   This is helpful in assessing what’s in progress, what has written, the writing style, how it was structured, research methods, and which reference were used.</p>
<p>•   User can satisfy because they can search not only thesis title but also by year, supervisor name.</p>
<p>•   Assisting postgraduate students to write.</p>
<p>•   Provide facility for proper monitoring, reduces paper work and provide data security.</p>
<p><strong>3.3 Disadvantages</strong></p>
<p>•   The cost of computer hardware and software programs can be expensive.</p>
<p>•   As mobile tablets use wireless network, they can disconnect with network if Wi Fi fails.</p>
<p><strong>3.4   Further Extensions</strong></p>
<p>This application has incompleteness from various view-points. But if it is continuously developed with experts, current needs will be covered shortly, then the effectiveness will approve its property. Various functionalities can be embedded within the application.</p>
<p><strong>References</strong></p>
<p>•   https://www.codecademy.com/learn/learn-the-command-line</p>
<p>•   https://www.codecademy.com/learn/learn-git</p>
<p>•   https://github.com/</p>
<p>•   https://github.com/mayeedwin/profile</p>
<p>•   https://vim-adventures.com/</p>
<p>•   https://try.github.io/levels/1/challenges/1</p>
<p>•https://my.wikipedia.org/wiki/%E1%80%97%E1%80%9F%E1%80%AD%E1%80%AF%E1%80%85%E1%80%AC%E1%80%99%E1%80%BB%E1%80%80%E1%80%BA%E1%80%94%E1%80%BE%E1%80%AC</p>
<p>•   https://about.gitlab.com/</p>
<p>•https://docs.google.com/spreadsheets/d/1L82Ozh1JsMHj5rsVLTH9LBiZNVOZ1ZLcD3xQHyX0U0g/edit</p>
<p>•   http://ask.tiide.org/</p>
<p>•   https://mobile.facebook.com/story.php?story_fbid=10155295368772328&amp;id=564487327&amp;_rdc=1&amp;_rdr</p>
<p>•   https://mobile.facebook.com/story.php?story_fbid=10155296307857328&amp;id=564487327&amp;_rdc=1&amp;_rdr</p>
<p>•   https://git-scm.com/download/win</p>
<p>• https://docs.google.com/spreadsheets/d/1Ybc9A5-dejo0K14EgXtdHXyRRT0a6Aty8Bt9OdpU72k/edit?pli=1#gid=0</p>
<p>• https://dashboard.heroku.com/apps</p>
<p>•https://dashboard.heroku.com/auth/heroku/callback?!=&amp;code=da8daab8-227f-4a2b-bd5e-2517cd3c5a70</p>
<p>•   https://pypi.org/project/Flask/</p>
<p>•   https://packaging.python.org/tutorials/installing-packages/</p>
<p>•   https://devcenter.heroku.com/articles/heroku-cli</p>
<p>•   https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial</p>

