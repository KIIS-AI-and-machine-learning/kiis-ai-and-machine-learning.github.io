## CS 475: KIIS AI and Machine Learning

### Dr. Jan Pearce

#### Summer 2026 Offering in Argentina

---

## Day 4: May 27, 2026, 10:30-11:45

### Day 4 Theme: The Math Behind AI

#### Day 4 class

- Discuss homework from Day 3:
  - How much time did you spend on the homework?
  - What did you think of the two AI tools I give you to try? What did you learn from using these tools?

- My primary goals for today are to complete the [Elements of AI: 3.1 Odds and Probability](https://course.elementsofai.com/3/1) questions and to help you understand the math behind AI, which is important for understanding how AI works and for being able to use it effectively. 

- Probability is a key part of AI and it is not super-hard to understand. Probability is the chance of an event happening, expressed as a fraction, decimal, or percentage. For a fair six-sided die the **probability** of rolling any particular number like 3 is 1/6 ≈ 0.167 or 16.7%. **Odds** compare the number of ways something can happen versus the number of ways it can't happen. They're expressed as a ratio.
For rolling a 3, since there is 1 way to roll a 3 and 5 ways to not roll a 3
the Odds of rolling a 3 are 1:5. **Remember the following key points: Probability can be quantified and it can be right or wrong, but it is usually not possible to draw conclusions about whether a particular number like a weather forecast  probability was right or wrong based on a single observation, unless that probability is 0 or 1.**
  - **Prompt 1**: Explain why it is usually not possible to draw conclusions about whether a particular probability was right or wrong based on a single observation, unless that probability is 0 or 1.

- Complete the [Elements of AI: 3.1 Odds and Probability](https://course.elementsofai.com/3/1)

-  **Bayes Rule** is a powerful tool for reasoning about uncertainty. Bayes Rule is a bit complicated because it is based on conditional probability, and while you can just apply the formula, it is better to understand it. Let's watch [What Is Bayes Theorem In AI? - The Friendly Statistician](https://youtu.be/JOVrcj4a1qc?feature=shared).
- Watch [Seeing Bayes Theorem](https://youtu.be/jRHw_LfQFAY?feature=shared).
- A **conditional probability** is the probability of an event, given some other event has already occurred. Explore [Conditional probability](https://setosa.io/conditional/).
  - **Prompt 2**: Explain conditional probability in your own words. How is it different from regular probability? Give an example of a conditional probability in your own life. Did any of these help you understand Bayes Rule better? Explain.

- Don't forget to **promptly** complete the post-class reflection in your Fieldpad. Reflect on the day’s activities and discussions. What did you learn? Explain.

#### Day 4: Homework

1. Read [Elements of AI: 3.2 Machine Learning](https://course.elementsofai.com/3/2) and [Elements of AI: 3.3 Deep Learning](https://course.elementsofai.com/3/3) without answering any questions. We will work on these together in class next time. Discuss what you learned from these readings as well as any questions in your Fieldpad.
1. Skim the following three articles about AI in Argentina in order to be qable to discuss them in your Fieldpad:
  - **AI-related economic gain**: [Stargate Argentina: OpenAI's Bold $25 Billion Bet on Latin American AI Expansion](https://opentools.ai/news/stargate-argentina-openais-bold-dollar25-billion-bet-on-latin-american-ai-expansion)
  - **AI data center regulation**: [AI Mega Data Centers: How They Are Regulated in Latin America and Europe, and What Might Happen in Argentina](https://pulitzercenter.org/stories/ai-mega-data-centers-how-they-are-regulated-latin-america-and-europe-and-what-might-happen)
  - **AI and the workforce**: [Argentina wants to be an AI powerhouse, but its tech experts are leaving](https://restofworld.org/2025/javier-milei-ai-hub-argentina-talent/)
  - Given these, what do you think about the future of AI in Argentina? On balance, do you think it will be a positive initiative for the country? Explain. (There is no correct answer, so please share your honest reasoning and feelings about this without use of AI.)
1. The above articles identified positive and negative issues related to the economic impact of AI, the regulation of AI data centers, and the potential for a brain drain of technical talent from Argentina. Search on similar issues in the US and compare and contrast the situation in the US with that in Argentina. Discuss your findings in your Fieldpad citing your sources, using at least three reputable sources. You will be reporting on this in class.

---

## Day 3: May 26, 2026, 10:30-11:45

### Day 3 Theme: Search and Problem Solving

#### Day 3 class

- Discuss homework from Day 2:
  - How much time did you spend on the homework?
  - Let's show and tell with what you did with the AI tools you chose. What did you learn from using these tools?
  - What did you learn from the video on Large Language Models?
  - [Peer Instruction PI2](https://runestone.academy/runestone/peer/student.html)

- Working with your partner, complete all the questions from Chapter 2.

- My primary goal for today is to help you to better understand the basics of search and problem solving in AI, and I wanted to make it easier for you to solve the first problem in [Elements of AI: 2.1 Search and problem solving](https://course.elementsofai.com/2/1). So we will discuss it and then I will show you a tool that I used an AI to build... It took a LONG time because my prompt engineering wasn't great in retrospect and the AI kept making mistakes.

- Note that:
  - the Robot can only carry 1 item per trip, 
  - the Fox can't be alone with the Chicken, and
  - the Chicken can't be alone with the Feed. 
- Also note that for each postion:
  - N stands for Near, and 
  - F stands for Far , 
- while the items are positional with: 
  - Robot=1 Fox=2 Chicken=3 Chicken-feed=4.
  - **Prompt 1**: What is the initial state of the problem? What is the goal state? Explain.

  - **Prompt 2**:  Identify some states in the state space that are not valid states. What are they? Explain.

  - **Prompt 3**: Identify some illegal transitions between valid states. What are they? Explain.

  - **Prompt 4**: Try to find the shortest path to the goal state. If you get stuck, I tell the AI the answers in [Rowboat Puzzle: Find the Shortest Path](https://docs.google.com/document/d/186xZNKUMNSMK6xeE38CcaIyGB-0JIl4DujzzAKzWNZE/edit?usp=sharing)

- Continue working through [Elements of AI: 2.1 Search and problem solving](https://course.elementsofai.com/2/1), stopping each time you reach a question. Discuss the questions in your group, and when you reach consensus, have the questions graded. Then move on. Please let me know when you have finished the section. I can't share the chat directly because it uses advanced features, but I want to show it as best as I can so we can discuss it. 

- Read [Elements of AI: 2.2 Solving Problems with AI](https://course.elementsofai.com/2/2).

- If time permits, we will watch a video to better understand the Minimax algorithm. See [Simple Explanation of the Minimax Algorithm with Tic-Tac-Toe](https://youtu.be/5y2a0Zhgq0U?feature=shared). This should help with [Elements of AI: 2.3 Search and Games](https://course.elementsofai.com/2/3).

- Please keep me posted on your progress in the Elements of AI textbook. I will be checking in with you to see how you are doing.

- **Post-class reflection:** Remember to complete your post-class reflection promptly. How far did you get in the textbook? What did you learn today? Explain.

#### Day 3: Homework

1. Read [Elements of AI: 2.3 Search and Games](https://course.elementsofai.com/2/3) and [Elements of AI: 3.1 Odds and Probability](https://course.elementsofai.com/3/1) without answering any questions. We will work on these together in class next time. Discuss what you learned from these readings as well as any questions in your Fieldpad.

1. Play several rounds of [Quick Draw with Google](https://quickdraw.withgoogle.com/). Discuss your experience in your Fieldpad. What happened in each round? How did the AI do? What did you learn from this experience? What do you think the tool learned?

1. Play several rounds of [Google's Say What you See](https://artsandculture.google.com/experiment/say-what-you-see/jwG3m7wQShZngw), which is a game that tries to help you with prompt engineering. Discuss your experience in your Fieldpad. What happened in each round? What did you learn from this experience?

---

## Day 2: May 23, 2026, 10:30-11:45

### Day 2 Theme: AI terms and Related Fields

#### Day 2 class

- I am hoping to give you feedback on your Fieldpad over the weekend.
- Discuss homework from Day 1:
  - How much time did you spend on the homework?
  - How did you define AI?
  - What did you learn from the homework?
  - From Recolletta Outing: How do you see AI and digital
systems increasingly shaping urban life? You were asked to consider how recommendation systems, translation
technologies, and digital archives influence how people experience art and information.

- If you do not already have one, make an account on [Runestone Academy](https://runestone.academy/) and add the book **kiis_AI_2026**. We will use this for Peer Instruction.
  - Go to [PI from Day 1](https://runestone.academy/runestone/peer/peer_question?assignment_id=222668).

- Watch [Machine Learning & Artificial Intelligence: Crash Course Computer Science #34](https://youtu.be/z-EtmaFJieY?feature=shared).
  - **Prompt 1**: While watching the video, take notes on the AI and ML terms that are introduced, so you can look them up afterwards. Which terms did you note?

- Watch [The Turing test: Can a computer pass for a human? ](https://youtu.be/3wLqsRLvV-c?feature=shared)
  - **Prompt 2**: What are your thoughts on the Turing test? Do you think it is a good measure of AI? Why or why not? Explain.

- Working with your partner(s), return to the Elements of AI textbook and discuss the questions in [Elements of AI: 1.2 Related Fields](https://course.elementsofai.com/1/2), When you reach consensus, go ahead and have the questions graded.

- After finishing section, work through the rest of chapter 1 by completing [Elements of AI: 1.3 Philosphy of AI](https://course.elementsofai.com/1/3), stopping each time you reach a question. Discuss the questions in your group, and when you reach consensus, have the questions graded. Then if time permitsmove on to section 2.1, read the whole section, and do the second part. (The first part is harder without paper - we will do it together next time.)
  - **Prompt 3**: This technique of working in groups to answer questions is designed to get you to discuss the material with your peers, which is a great way to learn for many. How did it help you understand the material? Explain.

- **Post-class reflection:** *Remember that the Post-class reflection should be a summary reflection on the course material learned that day. It should be formally written with yourself, your classmates and your professor as the audience.* Reflect on the day’s activities and discussions in your Fieldpad. What did you learn? Explain.

#### Day 2 Homework

1. Read [I tried 70+ best AI tools in 2026](https://www.techradar.com/best/best-ai-tools), and then choose 2 or 3 of these AI tools that you have never used before and give them a try. Note that this was originally written for 2025, but it is well-organized and the tools are still relevant. Write a short description of each of these three tools, why you chose it, and how well it did what you asked it to do, and whether you might use it again in the future. Save and link to each chat if the tool allows it.
1. Watch [Introduction to Large Language Models: Video](https://bit.ly/4tWQuyG)
1. Explore 1-2  additional reading from [Introduction to Large Language Models: Readings](https://bit.ly/4tWQuyG)
1. Take [Introduction to Large Language Models: Quiz](https://bit.ly/4tWQuyG), getting at least 80% correct.
1. If you did not fully complete [Elements of AI: 1.3 Philosphy of AI](https://course.elementsofai.com/1/3), please do so individually, including answering the questions.
1. If you did not finish the reading of [Elements of AI: 2.1 Search and problem solving](https://course.elementsofai.com/2/1), finish the reading for homework, but do not answer the questions alone. We will work on them in class.
1. Discuss what you learned from this homework in your own words in your Fieldpad.

---

## Day 1: May 22, 2026, 10:30-11:45

### Day 1 Theme: Class Overview - What is AI?

#### Day 1 class

- Introductions and logistics:
  - Overview of the course
  - [Google classroom site](https://classroom.google.com/c/ODY0ODMxMzg4MDY4?cjc=5yduehyo). Please add yourself to the classroom.
  - [Course Syllabus](https://www.kiis.org/wp-content/uploads/2025/10/CS475-AI-ML-Pearce-Argentina-2026.pdf?authuser=0)
  - Go to the [AI and ML Fieldpad](https://drive.google.com/drive/folders/17m2U5EBalQ5o_czmR9GUdnk56FUa6z4V?usp=drive_link) and request access to your own fieldpad. This is where you will record your in-class and homework reflections.
  - [Elements of AI](https://course.elementsofai.com/), and [Building AI](https://buildingai.elementsofai.com/). Note that we will be using this **in class**, so please do not work ahead.

- Some questions to keep in mind today and throughout the course:
  - What is AI and how is it built?
  - What about generative AI?
  - What is Machine Learning?
  - What is Deep Learning?
  - What Generative AI tools are useful for various tasks?

- Read [AI Assistance Reduces Persistence and Hurts Independent Performance](https://ai-project-website.github.io/AI-assistance-reduces-persistence/?utm_brand=wired&utm_mailing=WIR_PremiumAILab_050626_UNPAID&cndid=85484935)
  - **Prompt 1**: What is the key takeaway from this article? How have you used generative AI in the past in your learning process? Do you think you have used in ways that enhance rather than hinder your learning? Explain.

- Read [Elements of AI: 1.1 How should we define AI?](https://course.elementsofai.com/1/1) and discuss the questions in your group before having them graded. **Please remember not to work ahead in this text. We will continue in the text next time.**
  - Regardless of how far you got in your reading, answer:
  - **Prompt 2**: What is your own definition of AI? Explain.
- If time permits, read some of [Elements of AI: 1.2 Related Fields](https://course.elementsofai.com/1/2).

- **Post-class reflection:** *Remember that the Post-class reflection should be a summary reflection on the course material learned that day. It should be formally written with yourself, your classmates and your professor as the audience.* Reflect on the day’s activities and discussions in your Fieldpad in your own words. Do not use AI. What did you learn? Explain.

#### Day 1 Homework

1. Finish the reading of [Elements of AI: 1.2 Related Fields](https://course.elementsofai.com/1/2). Feel free to read and think about the questions, but do not answer the questions. We will complete them next time.
1. Go to [Introduction to Generative AI and Large Language Models](https://github.com/microsoft/generative-ai-for-beginners/tree/main/01-introduction-to-genai) and either watch the video or read the lesson.
1. Read [How to Use AI Without Forgetting Everything You Learned](https://www.psychologytoday.com/us/blog/how-we-remember/202506/how-to-use-ai-without-forgetting-everything-you-learned). Note that over this course's duration, I will be challenging you to learn to use generative AI in new ways and to analyze your own learning using metacognition.
1. After watching these videos and doing the reading, use your favorite generative AI tool to further explore at least one idea further. Discuss what you chose and why and be sure to link and reference your chat as described in the syllabus in your Fieldpad.
1. Discuss what you learned from this homework in your own words in your Fieldpad.

**Homework Reflections:**
(Note that unless otherwise stated, all homework is due at 8 am on the day of the next class session.) Use the AI and Machine Learning Field Pad to record your in-class reflections.

---

### In addition to the normal stuff, be sure to pack all of the following in your carry-on bag (not your checked luggage.)

- your laptop and charger
- earphones to use with your laptop

---
###### Copyright © 2026 | Licensed under a Creative Commons Attribution-Share Alike 4.0 United States License
