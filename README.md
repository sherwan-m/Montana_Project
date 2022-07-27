# Montana_Project
A/B Testing: Improving UX Experience

The Library of Montana State University
The Library of Montana State University has a website that students use to find books and articles. This is how the Home page  like:

![image](https://user-images.githubusercontent.com/56586631/181240259-a49d8a13-a21c-4051-b53f-7d73d2d32355.png)


Below the library picture there is a search bar and three big items: “Find”, “Request” and “Interact”. All three of them contain access to important information and services that the library prides itself in offering. However, the Website Analytics show that the “Interact” button has, ironically, almost no interactions:

![image](https://user-images.githubusercontent.com/56586631/181240301-eaa85d0c-c480-40af-b3f3-cb85c3efdeab.png)


The way to measure how each one of the three categories perform is by click-through rate (CTR), a common term in Online Marketing which typically describes the number of clicks an ad receives divided by the number of times the ad is shown. Here, click-through rate is measured as the number of clicks on each item divided by the total number of visits on the website. The report from the team analysing the website shows the specific numbers and explains how they reacted to them:

During the sample period from April 3, 2013 – April 10, 2013, which included 10,819 visits to the library homepage, there was a large disparity among the three main content categories. The click-through rate for Find was 35%, Request was 6%, and Interact was 2%. This observation prompted a question: “Why are Interact clicks so low?” At this time the content beneath Interact included links to Reference Services, Instruction Services, Subject Liaisons, Writing Center, About, Staff Directory, Library FAQ, Give to the Library, and Floor Maps. The library’s web committee surmised that introducing this category with the abstract term “Interact” added difficulty and confusion for users trying to navigate into the library website homepage. Four different category titles were then proposed as variations to be tested: Connect, Learn, Help, and Services.

In an A/B Test, one of the tasks that usually belongs to the UX team is to perform user research and develop a new version of the website element that needs to be tested. The team had conversations with a few students and asked the following questions:

Have you previously clicked on Interact?
What content do you expect to see after you select Interact?
Does Interact accurately describe the content that you find after selecting Interact?
Which word best describes this category? Interact? Connect? Learn? Help? Services?
Here are some of the responses from three of the students.

Sophomore student:

“I didn’t know that ‘About’ was under Interact.'”
“Learn doesn’t work.”
“Connect is too vague and too close to Interact.”
“Services is more accurate. Help is stronger.”
“Floor maps seem odd here.”
In order of preferences of the choices, this student responded: Help, Services, Interact, Connect, Learn
Junior student:

“I am not a native English speaker, so I look for strong words. I look for help, so Help is the best, then Services too.”
Senior student:

“I’ve never felt the need to click on Interact. What am I interacting with? I guess the library?”
“I never knew floor maps were there, but I have wondered before where certain rooms were.”
“Help makes sense. When I’m in the library, and I think I need help, it would at least get me to click there to find out what sort of help there is.”
“Services also works.”
“Learn doesn’t really work. I just think, What am I learning? I think of reading a book or something.”
“Connect is better than Interact, but neither are very good.”
In order of preferences of the choices, this student responded: Help, Services, Connect, Interact, Learn
After these interviews, how would you proceed to design an experiment that would improve the website? Before moving onto the next lesson, try to answer these questions by reviewing the resources on Experimental Design you read at the beginning of this project:

Would you include all suggested variants in the experiment (Connect, Learn, Help, Services)?
What is the “business value” that performing this experiment would add within the broader strategy of the University?
Which main metric would you choose to measure the success of a variant and perform the experiment on?
Which additional metrics would you choose to track?
How would you define the null and the alternative hypotheses?
What threshold for statistical significance would you set?
What is the minimum detectable effect effect (the smallest improvement you would care about) that you expect to detect?
Do you think this experiment would require a software engineering team to develop a custom platform, or could it be developed with external tools such as Google Optimize?

Explore the Data from the Experiment
After the interviews with the users and some brainstorming, the website team settled on 4 different new versions to test against the original “Interact” button:

Connect
Learn
Help
Services
The metrics that were deemed more relevant to track were the following:

Click-through rate (CTR) for the homepage. Defined as the amount of clicks on the button divided by the total visits to the page. Selected as a measure of the initial ability of the category title to attract users.
Drop-off rate for the category pages. Percentage of visitors who leave the site from a given page, selected as a measure of the ability of the category page to meet user expectations.
Homepage-return rate for the category pages. percentage of users who navigated from the library homepage to the category page, then returned back to the homepage. This sequence of actions provides clues as to whether a user discovered the desired option on the category page; if not, the user would likely then return to the homepage to continue navigation. Homepage-return rate was therefore selected as a measure of the ability of the category page to meet user expectations.
While all the metrics will be relevant for the decision-making process, it was decided that for a version to be considered superior, a minimum increase in click-through rate of 30% had to be detected.

The hypotheses to be tested in the experiment are the following:

Null Hypothesis: all variants have the same CTR.
Alternative Hypothesis: there is a difference in the CTR for the different variants.
The desired Statistical Significance was chosen to be 90%: it is a bit lower than the usual scientific standard of 95% because the consequences of rejecting the null hypothesis when it is true (i.e. concluding there is an effect when there is none) are not tragic, and there are constraints in the amount of time the team of experimenters have: quickness was prioritized over certainty.

Currently, the CTR for Interact sits at around 2%, and the page has around 1650 visitors every day.  With these numbers, a power calculator like this one can be used to decide on the length of the test. The length of the experiment was established at 21 days:

![image](https://user-images.githubusercontent.com/56586631/181240141-e308c737-b4bc-4c1c-be59-f6e94f15f9be.png)


The test ran between May 29, 2013 and June 18, 2013. Attached at the bottom of this lesson, you will find the data that was extracted from crazyegg, a service that tracks traffic to websites and provides insights and well structured data.
