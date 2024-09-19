# How I Prepared For FAANG Interviews Without CS Degree.

I received an offer from Amazon (AWS), and my preparation took a total of one and a half years. I started from scratch, and it was a long journey for me. It took this long because:

* I don't have Computer Science degree.; my major was Economics.
* In my previous job as a Software Engineer, I wasn't required to have a deep technical background or prepare for technical interviews since it was my first technical role.

I'd like to share how I prepared for interviews.

## My Study History

**Sep 2022** :
   ![leetcode_history_2022.png](https://github.com/harunawaizumi/ffang-interviews-preparations/blob/main/leetcode_history_2022.png) 
   I started studying algorithms in September 2022, using [Structy](https://structy.net/) to understand the fundamentals. I went through each topic two to three times before moving on to Leetcode, focusing on the [Top 100 Liked Questions](https://leetcode.com/problem-list/top-100-liked-questions/) and [60 Questions To Solve](leetcode.com/problem-list/xo2bgr0r/). I usually studied from 5-7 am before work and put at least 6 hours on weekends. My daily goal was to solve at least one question, averaging two per day. I didn't move on to the next question until I thoroughly understood the current one. 

**2023** :
   ![leetcode_history_2023.png](https://github.com/harunawaizumi/ffang-interviews-preparations/blob/main/leetcode_history_2023.png)
   With the hiring freeze in late 2022 and early 2023, many IT companies paused hiring. I shifted my focus to cloud engineering, anticipating increased demand and the fact that my previous company used AWS. I studied for 6 months and passed the [AWS Certified Solutions Architect - Associate](https://aws.amazon.com/jp/certification/certified-solutions-architect-associate/). From August to October, I took a break, traveled, and resumed my interview prep in November, focusing on system design and algorithm. I increased my study hours, waking upat 4 am to study for 3 hours daily, and studied for at least 6 hours each weekend. I used [AlgoEpert System Design Fundamentals](https://www.algoexpert.io/systems/fundamentals) and took notes on each topic.  

   ![Tech Layoff](https://github.com/harunawaizumi/ffang-interviews-preparations/blob/main/layoff_tech.png)

**2024** :
   ![leetcode_history_2024.png](https://github.com/harunawaizumi/ffang-interviews-preparations/blob/main/leetcode_history_2024.png)
When I encountered questions I couldn't understand, I discussed them with senior engineers who were friends of mine. After these discussions, I realized that Algoexpert's system design fundamentails weren't enough for FAANG interviews. I also read [Alex Xu System Design Interview](https://amzn.asia/d/0Tflea2) and [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/), which provided valuable insights. I started applying for companis in May and received an offer from Amazon in August.

## My Study Schedule
I used excel to create a daily study schedule, planning my tasks for month and tracking whether I complited them. This helped keep me motivated and provided a clear view of my progress. I reserved Sundays for catching up on incomplete tasks to stay on track with my weekly plan. 

During weekdays, I studied in the early mornings, and on weekends, I studied at local cafes I enjoyed. It's important to have a focused study environment, and I found that the quiet of early mornings at home worked best for me. My routine involved waking up at 4 or 4:30 am, makig coffee, and starting my studies - without checking social media!

## Algorithm

### Material I Used
* **[Structy](https://structy.net/)** : This platform is excellent for beginners in algorithm. It goes through different data structures, starting with the fundamentals, builds on each lesson. I went through it three times to strengthen my understanding. If you've studied algorithms in college, you might not need this, but for those who haven't, I highly recommend it.

* **[Leetcode](https://leetcode.com/)** : After becoming comfortable with Structy, I moved on to Leetcode. I recommend getting the premium subscription because some of the good questions are exclusive to premium users, and it saves time. You can also sort questions by how frequently they’re asked by top tech companies, and there are official answers provided. Although many of these answers can be found for free online, paying $160 saves a lot of time.

A Google engineer told me that to pass FAANG technical interviews, you need to solve between 200-300 questions. The ideal ratio is about 10% Hard, 20% Medium, and 70% Easy. I solved 223 questions in total, but I would have needed to solve more "Hard" questions if I were applying for a regular software engineering role. The roles I was interested in were either engineering positions that required some client-facing skills or non-software engineering roles within technical teams. I focused more on fundamental questions and repeated each one multiple times (anywhere from one to six) until I could solve it quickly.

* **[AlgoExpert](https://www.algoexpert.io/questions)** : This is another algorithm questions platform. I used it for topics I wasn’t strong at. For example, I wasn’t confident about Heaps, Recursion, Dynamic Programming, and Sliding Windows. AlgoExpert groups algorithm questions by topics, and its questions are similar to Leetcode with a good selection of questions. It also provides helpful video explanations. After solving Easy, Medium, and Hard questions on these topics using AlgoExpert, I became more confident in tackling any algorithm-related question.

### Which Questions to Practice
I focused on [Top 100 Liked Questions](https://leetcode.com/problem-list/top-100-liked-questions/) and [60 Questsions To Solve](leetcode.com/problem-list/xo2bgr0r/), which are frequently asked in interviews. I tracked my progress in Excel:
* Green: Solved smoothly without any reference.
* Yellow: Took longer but was mostly correct.
* Orange: Culdn't solve.

On the second path, I skipped the green questions and only worked on the yellow and orange ones. I repeated this process three times. 
After three cycles, I identified my weak areas. AlgoExpert helped strength these weaknesses by providing frequently asked questions that were slightlly different from Leetcode's. I focused on solving questions related to these topics multiple times, which helped me improve my approach and boosted my confidence.

https://github.com/user-attachments/assets/9e26bbe8-d44c-4d85-a8c8-b9501755a517


### How I Solved Quesetions
When solving a question, I tried to simulate a real interview as much as possible.
I set 20 minute timer and attempt to solve the question without any external resources. It's ok to extend the time if I couldn't solve it but I didn't waste hours just thinking. I also practiced explaining my thought process aloud, imagining I was talking to an interviewer. 

1. Clearify a Question 
	Ask clarifying questions such as:
	"Can this array/variable/tree be null ?"
	"Can this variable be zero ?" 
	"Can this variable/number be negative ?"
	
2. Explain Your Idea
	* Start with a brute-force solution and explain the time/space complexity.
	* Offer alternative solutions and their time/space complecity. 
	* Compare the solutions, discussing pros and cons. 
	* Pick the most optimized solution and start coding.
This Youtube video by Google was helpful:
[Google Example Coding/Engineering Interview](https://youtu.be/XKu_SEDAykw?si=tD5OTMzfvmszaky7)
	
	
4. Check The Answer
	* Fully understand the solution without memorizing it.
   	* Set another 20-minute timer to solve the same question again, without looking at the answer.  
	* If you still can't solve it smoothly, review the answer and repeat again until you can.
	
### How to Simulate an Algorithm Interview
1. Paper
	I wrote my solution on a paper before coding, explaning my thought process as I went. I always made sure to sketch my answer on paper or a whiteboard before starting with the code.

3. Whiteboard
	I bought a large whiteboard for practice. 
	After solving a procment the first time, I used the whiteboard to write out the solution. 
	I imagined an interviewer in front of me while explaning and writing the solution on the whiteboard.
	
4. Mock Interview
	There are several free mock interview platforms available online. 
	I used [Pramp](https://www.pramp.com/#/) which offers free pair-mocking interview practice. The system matches you with another person, and you both solve questions and give feedback. 
	I completed 7 sessions but eventually stopped using it as I encountered repeated questions. However, it was still helpful for simulating real interview conditions.


## System Design
I needed to start with very basics because I don't have Computer Siecense degree and hadn't studied system design much before.

1. AlgoExport
AlgoExpert has a System Design Fundamentals tutorial consisting of 25 videos. 
I watched each video and wrote a summary for each topic. I also did additional research to deepen my understanding.

https://github.com/user-attachments/assets/6d48d199-9ebd-4ebb-b514-3026808fdde0


3. Review and Retain Knowledge
 After watching this video twice, I created a list of key points to remember. I quizzed myself on each topic, explained the concepts aloud, and tracked my answers to see which areas I understood well or needed more review.
![Tech Basic](https://github.com/harunawaizumi/ffang-interviews-preparations/blob/main/tech_basic_tracker.png)

4. Move To Advanced Topics
I then read [Alex Xu System Design Interview](https://amzn.asia/d/0Tflea2) and [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/). I took notes on what I learned and kept track of key concepts.
![System Design Note](https://github.com/harunawaizumi/ffang-interviews-preparations/blob/main/sd_note.png)


5. Practice
I created my own template to guide system design interviews. Here's the structure I followed:

	1. Clearify the servic
	Begin by explaining the service clearly.
  	*Example: Instagram is a phone and video sharing social networking service.* 

	2. Explain the data needed
	Identify the data the service requires.
	*Example: We need data on posts(text, video, pictures), users and followers.*
    
	3. Ask about the focus and its requirements
    	Clarify which features or functions the interviewer wants you to prioritize.
	*Example: Should we focus on post uploads and viewing, or on following users ?*

	4. Ask about un-functional requirements
	Discuss performance and scalability factors.
	*Example: Do we want to make it scalable, reliable and maintain a low latency ?*

	5. Clearify key metrics
	Gather numerical details about the system. Calculate the size of the service and storage.
	*Example: How many daily users do we have ? What's the size of images and videos ? How long do we store data ?

	6. Draw a high-level design
	Start with a basic architecture, including users, application servers and databases.
	Focus on a simple solution before considering scalability, reliability, or latency.

	7. Discuss the database
	* SQL vs NoSQL: Explain the pros & cons, and choose the best fit for this case.
	* Object storage: Explain why it's suitable for media files like videos and images, and discuss cloud storage options.
 	* RDB for meta data: Explain why relational database are suitable for handling metadata.

	8. Discuss the application Server
	Describe handling high-traffic scenarios.
	Think of high-traffic scenario depending on the service.
	*Example: A popular user posts, causing server overloaded. Introduce the concept of a Load Balancer (LB), discuss the type of LB, how to decide the number needed, and how to distribute traffic.*

	9. Scalability and Reliabiliry
	  - Database replication
	  - Load balancer

	10. Latency
	  - Browser caching (cliend-side)
	  - Database caching (server-side)
	  - CDN (Conetent Delivery Network)
	  - Database sharding

	11. Security (Optional)
	  - Securing the system
	  - Securing APIs
	  - Database security
	  - Addressing vulnerabilities

## Behavioral Question
I spoke with friends working at IT companies to understand how to prepare for behavioral questions. 
Amazon, in particular, expects candidates to answer using STAR method(Situation, Task, Action, Result). To prepare, I focused on using the [STAR method](https://www.amazon.jobs/en/landing_pages/in-person-interview) and documented six key experiences from my last eight years of work.

For each experience, I reflected on the following points: 
- **STAR**: What was the Situation, Task, Action and Result?
- **Motivation**: Why was I in charge of it?
- **Learnings**: What did I learn from this experience?
- **Improvements**: How could I improve if I where to do it again ?
- **Success or Failure**: Why did I succeed or fail in this situation?
- **Challenges**: What was difficult about the actions I took ?
- **Innovation**: How did I make the process more creative, efficient or improved ?

I organized these experiences before I started applying for companies. To keep them fresh, I practiced two or three topics each week. 
When practicing for behavioral interviews, I used a few techniques:
- I rehearsed in front of a mirror to assess my body language and delivery. 
- I recorded my answers to review later and spot areas for improvement.
- I used Zoom or Google Meet to simulate a real interview setting. During these mock sessions, I focused on looking directly at the camera on my Mac rather than at participants on the screen. This makes it appear as though you are maintaining eye contact with the interviewer, even though it can feel unnatural at first. 
Practicing these methods helped me objectively assess my responses, which significantly improved my performance in behavioral interviews.

I summarized how I prepared for interviews based on my personal experience. There are many ways to approach interviews, and this is just one of them that worked for me. The key is to find a method that feels comfortable and effective for you. Though it was a long journey, it was incredibly rewarding and I learned a lot along the way!



