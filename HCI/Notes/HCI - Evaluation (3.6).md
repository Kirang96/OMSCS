2024-09-11

Tags: #HCI, #UX #UI 
Topic: [[Human computer Interaction]] 

Evaluation is where we take what we've designed and put it in front of users to get their feedback.

**Qualitative feedback**: Emphasizes the totality of a phenomenon.
What do they like, what do they dislike, what's easy and what's hard etc.

**Empirical evaluation**: Based on numeric summaries or observations of a phenomenon
Here we conduct some controlled experiments and evaluate the results quantitatively.

**Predictive evaluation**: Systematic application of pre-established principles and heuristics
This is evaluation without users.

Terminology:

**Reliability**: Whether a measure consistently returns the same results for the same phenomenon.

**Validity**:  Whether a measure's results actually reflect the underlying phenomenon. A result can be reliable (consistent) but wrong. 

It is similar to **generalizability**. It is whether a measure's results can be used to predict phenomena beyond what it measured.

Precision: It is the level of detail a measure supplies. 

Tips: 

1. Efficiency: Time taken to accomplish a task using an interface
2. Accuracy: Number of errors users commit
3. Learnability: How much time users take to reach a level of expertise
4. Memorability: How much users remember about how to use the interface
5. Satisfaction

#### Evaluation timeline

Most of the time our evaluation method is **formative**. Which means the primary purpose is to help us redesign and improve interface.

At the end we change it to **summative** to demonstrate that the new interface is better.

Early evaluations tend to be more qualitative which are more interpretative and formal. Their goal is to help us improve or understand the task. As we move forward, evaluation become more empirical, controlled and formal. Their goal is to demonstrate or assess change. Predictive evaluation is also similar to qualitative and help us improve our interface over time.
Setting of the evaluation can also be different. It can either be in a lab or in field. Low fidelity prototypes are usually evaluated in lab setting. But later as the development progresses, we can develop a higher fidelity prototype like a wireframe and test it in field.
Some aspects of the application can only be seen in the field like a navigation app, which requires more cognitive load while travelling (field) as compared to the lab setting.

##### Evaluation design

1. Define the task: It can be small or big
2. Define performance measures: Qualitatively like feedback taken about experience or quantitatively like counting the number of mistakes.
3. Develop the experiment: Qualitatively we can do a survey after they're done or quantitatively what will we measure or what will we control.
4. Recruit participants
5. Do the experiment
6. Analyze the data\
7. Summarize the data

#### Qualitative evaluation

This is similar to needfinding. We do interviews, think aloud protocols, focus groups, surveys, post event protocols etc. to ask questions about the experience of using the interface.
There are several decisions we can need to make while designing an interface as well:

![[Pasted image 20240911200614.png]]

#### Capturing qualitative evaluation

1. Video recording: 
		Pros: Automated, comprehensive and passive
		Cons: Intrusive (users might be conscious about it), Non-analyzable (Difficult if the videos are long) and screen-less.
1. Note-taking: 
		Pros: Cheap, non-intrusive, analyzable
		Cons: Slow, manual and limited
3. Software logging:
		Pros: Automated, passive and analyzable
		Cons: Limited (only things on screen are captured), Narrow and tech-sensitive
Tips:
1. Run pilot studies: Try it out with friends before users
2. focus on feedback: Don't try to teach or correct user's criticism.
3. Use questions when users are stuck: we get information on why they're stuck
4. Instruct users what to do, not how.
5. Capture satisfaction

#### Empirical evaluation

Here we're trying to get numerical values about our interfaces. Most empirical evaluations are comparisons. We can try to find out if gestural interactions has a tougher learning curve than visual interaction.

Process:

The process of empirical evaluation is different from qualitative evaluation. Instead of making users go through a single interface one by one and getting feedback, here we have two interfaces called **treatments** that has subtle differences that we want to compare. Then we make users use the treatments and get the responses.

Between subjects design: comparison between two groups of subjects receiving different treatments. The participants are split into two groups and each group is given a treatment interface. The interfaces are mixed between groups.

Within subject design: Here all the participants use both the treatments one after the other. 
It is beneficial because we get twice as much data as between subject design. In this design the order in which the participants get to use the treatment might affect their performance and to solve this, we randomly assign each participants treatments without order. This is called random assignment. It also has other benefits like to avoid gender biases.

#### Hypothesis testing


Testing whether or not the data allows us to conclude a difference exists.
In this method, whenever we're trying to prove something, we initially make a hypothesis that the opposite is true. 
So if we're trying to prove that two values are different, we first hypothesize that they're the same. This is the **null hypothesis**. This is the hypothesis we accept if we accept if we cannot find sufficient data to support the alternative hypothesis.
We accept the alternative hypothesis when there's less than 5% chance that the difference could have arisen by random chance.
Then we say the difference is statistically significant.

In a test, the things that we're comparing are called independent variables. It is the categories we have. For example: Online or traditional.
Dependent variables are the features of each category we're comparing.

There are different types of hypothesis testing. The type of hypothesis testing we do depends upon the data we have collected.
1. Nominal data
	Chi-squared tests: It helps us test if the distributions of values in categories are comparable.
	Fisher's exact test and G-tests are alternatives
2. Ordinal
	Kolmogorov-Smirnov test: They're similar to Chi-squared tests but they're sensitive to order of values.
	Chi-squared test and Median tests are alternatives
3. Interval and ratio (They're both similar and can be considered one).
	Student's t-test: Here the independent variables are categories but dependent variables are average of outcomes. We can only use this when the data distribution is normal (Bell curve distribution). It requires us to calculate the standard deviation.
	Alternatives would be: MWW test, Kruskal-Wallis test

#### Special statistical tests

When we want to compare more than two categories, there are complications. If we compare pairwise and get the results, it raises the likelihood of a type 1 error. Type 1 error is the false rejection of null hypothesis. Performing multiple tests, raises our overall likelihood of finding a false positive.
For ordinal and nominal data, chi-squared tests can handle more than 2 categories. Chi-squared test tells us there is a difference between some category but it doesn't tell us which category it is. So we'll need to do one round of pairwise testing to find which category it is after the overall test.

For Interval and ratio test, we need to use a different test called Analysis of variance (ANOVA) test.
With one-way ANOVA, we can test 3 or more categories.
With two-way ANOVA, we can have 2 dimensions of independent variables. We can have variables in row and columns and compare between all of them. 
But this also gives us overall difference and we'd need to do pairwise testing to find which one is actually different.

For interval and ratio test, if the independent variables are interval or ratio data, these tests do not work. Then we'd need to do linear regression. Alternatives would be logistic regressions, polynomial regression etc.

Binomial data will be obtained sometimes in HCI. For example, if we gather data that if the interface is success or failure.
We cannot do t-tests here because we cannot get the standard deviation as each value is either 1 or 0.
So, here we use **binomial test**. Two-sample binomial test can test two different trails with different success rates. 

![[Pasted image 20240921084104.png]]

Tips:
1. Control what you can, document what you can't.
2. Limit your variables.
3. Work backwards in designing your experiments: Get the question you want answered, then decide the analysis to use and then find the data you need to gather.
4. Script your analyses in advance: Decide analyses to do on data beforehand. If it doesn't work, don't keep on reanalyzing it.
5. Pay attention to power: Power is the size of the difference that a test can detect. Small effect: more participants, big effect: fewer participants.

##### Predictive evaluation
No participants required but can be used for rapid prototyping. It shouldn't be used where qualitative or empirical can be used, but where there are no tests that can be done. This is just better than nothing.
1. Heuristic evaluation: We pass all the guidelines like discoverability, simplicity etc. and interface to an expert to get a feedback. 
2. Model based evaluation: Here we compute what a user will do with our new interface in a GOMS model. Then we can compare it with another GOMS model of the old method side-by-side and evaluate its efficiency.
3. Simulation based evaluation: Create AI that will interacts like human and evaluates it.
4. Cognitive walkthrough: We will mentally simulate a user using the interface screen wise and think about the gulf of execution and evaluation.
