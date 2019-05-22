# AI Appraisal and Hype

### Articles and resources that appraise versus hype machine learning, deep learning, and artificial intelligence

Throughout my career, I have found "[artificial intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence)" to be an interesting buzzword. Of course, almost every buzzword that enters corporate jargon (e.g. "Big Data", "Internet of Things", "Blockchain", "BitCoin", etc) is often hyped beyond actual value. But "artificial intelligence" is different because unlike other buzzwords, "AI" has already gone through cycles of AI booms and "[AI Winters](https://en.wikipedia.org/wiki/AI_winter)" over several decades. 

While many of my colleagues in operations research circles dismiss the "artificial intelligence" buzzword as media hype and tabloid, such hype has still had an effect on society. Many Fortune 500 executives, law makers, venture capitalists, the general population, and even technology professionals are under the impression [Skynet](https://en.wikipedia.org/wiki/Skynet_(Terminator)) is upon us. Billions of U.S. dollars are poured into AI research, but most people funding such initiatives do not quite understand the technology or what it actually is good at. Anecdotally, I have also noticed programmers, data scientists, and other technology professionals become invested in AI but rarely scrutinize its capabilities and limits. 

My Pocket bookmarks are getting full with these articles, so I am going to start dumping them here on this GitHub page for my own organization and to share with others. Feel free to contribute your own too.  It is fascinating to compare these two narratives and how they contrast each other, and it will be interesting to see how things play out as investors and CEO's start demanding financial return from AI technologies. 



## Summarizing the Narratives

Based on the articles and resources listed below, here are the bullet points that objectively summarize proponent and critical perspectives on contemporary "AI" trends tied to machine learning:

### Proponent Points

* Useful applications have been developed with machine learning, particularly image recognition, natural language processing, and image/audio generation. 

* Machine learning has unlocked new ways to perform more powerful regressions that were impossible to do before, like fitting a regression to the pixels on an image. 

* Having more data and computing power (e.g. quantum computing) will create more applications in the future.


### Critical Points

* Machine learning requires large amounts of labeled data that may not be practical to obtain in real-world applications. This is one reason why AI research is fond of applying machine learning to games like Chess, Go, Super Mario, and StarCraft. With these games, it is easy to generate enormous amounts of data from virtual players playing against themselves. However, this is not something that can be done in most real-world applications.

* Heuristics and other algorithms that leverage business domain knowledge will outperform machine learning approaches in most cases, in terms of cost and resources as well as effectiveness. While heuristics do not guarantee a perfect solution, they are far less data-hungry than machine learning and can be far more effective. 

* Machine learning is primarily only good at two things: regression and categorization. It quickly has a diminishing return in other spaces like the [Traveling Salesman Problem](https://www.youtube.com/watch?v=j1s69yf4a9Y). The most interesting problems in the real world are not regression and categorization, but rather require a broader system of intuition, human experience, domain knowledge, and unquantifiable ideas. 

* Machine learning (and algorithms in general) need a single task with a single objective to be practically useful, and trying to generalize multiple unrelated objectives and tasks will quickly have a diminishing return ([No Free Lunch Theorem](https://en.wikipedia.org/wiki/No_free_lunch_theorem)). This is another reason why AI research gravitates towards board games and video games, as there is a single quantifiable objective and a confined world structure, with only a fixed number of moves, inputs, and outputs. 

* Machine learning (and nondeterministic algorithms in general), need manual tuning and human experimentation with many hyperparameters before they can behave "intelligently" when applied to a tightly scoped problem.

* The nature and definition of "intelligence" and "consciousness" is currently philosophical, meaning we have little to no idea how we understand this human phenomena much less replicate it on a machine. The pursuit of "general artificial intelligence" is guided by speculations and philosophy, and even leads [AI researchers to wonder if their iPhone has feelings](https://getpocket.com/explore/item/why-can-t-the-world-s-greatest-minds-solve-the-mystery-of-consciousness). Philosophy has a way of eluding practical matters and creating unproductive rabbit holes. If you are following Elon Musk, [a high-profile investor towards AI research](https://en.wikipedia.org/wiki/OpenAI), one moment the conversation can be how to strategically leverage AI in a business, and the next [it regresses into funding research to break out of the Matrix](https://www.forbes.com/sites/janetwburns/2016/10/13/elon-musk-and-friends-are-spending-millions-to-break-out-of-the-matrix/#107f8c275ce1) or [summoning the AI demon](https://www.washingtonpost.com/news/innovations/wp/2014/10/24/elon-musk-with-artificial-intelligence-we-are-summoning-the-demon/). 



## Appraisals of Artificial Intelligence 

|Article|Author|Summary|
|---|---|---|
|[Deep Learning: A Critical Appraisal](https://arxiv.org/ftp/arxiv/papers/1801/1801.00631.pdf)|Gary Marcus|An authoritative appraisal of deep learning's limitations|
|[In Defense of Skepticism About Deep Learning](https://medium.com/@GaryMarcus/in-defense-of-skepticism-about-deep-learning-6e8bfd5ae0f1)|Gary Marcus|A followup to Gary Marcus' appraisal of deep learning capabilities|
|[Rodney Brooks' Scorecard for 2019](http://rodneybrooks.com/predictions-scorecard-2019-january-01/)|Rodney Brooks|Rodney, the creator of iRobot and the Roomba vacuum, does his yearly audit of his predictions for deep learning, driverless cars, AI winters, and other technology cycles|
|[AGI Has Been Delayed](https://rodneybrooks.com/agi-has-been-delayed/|Rodney lists more recent appraisals of deep learning and artificial general intelligence capabilities|
|[The Limitations of Deep Learning](https://blog.keras.io/the-limitations-of-deep-learning.html)|Francois Chollet|An excerpt from a book describing in detail the limitations of deep learning and why we misguidedly anthropomorphize algorithms.|
|[Greedy, Brittle, Opaque, and Shallow: The Downsides to Deep Learning](https://www.wired.com/story/greedy-brittle-opaque-and-shallow-the-downsides-to-deep-learning/)|Jason Pontin|A four-pronged breakdown on the limitations of deep learning|
|[The Seven Deadly Sins of AI Predicitions](https://www.technologyreview.com/s/609048/the-seven-deadly-sins-of-ai-predictions/)|Rodney Brooks|Rodney gives a commentary on the flawed sensationalism of AI media coverage|
|[Does AI Include Constraint Solvers?](https://www.optaplanner.org/blog/2017/09/07/DoesAIIncludeConstraintSolvers.html)|Geoffry De Smett|The creator of OptaPlanner argues constraint solvers should still be considered "AI", and deep learning has not solved the Traveling Salesman Problem|
|[Is Deep Learning Already Hitting its Limitations?](https://towardsdatascience.com/is-deep-learning-already-hitting-its-limitations-c81826082ac3)|Thomas Nield|My article highlighting practical problems deep learning fails to solve and pose the possiblity of another AI Winter|
|[It's Either a Panda or a Gibbon: AI Winters and the Limits of Deep Learning](https://warontherocks.com/2018/05/its-either-a-panda-or-a-gibbon-ai-winters-and-the-limits-of-deep-learning/)|Robert Richbourg|Fascinating commentary on AI limitations and AI winters from a retired military officer with a PhD in Computer Science and Artificial Intelligence|
|[The Discourse is Unhinged](https://www.theguardian.com/technology/2018/jul/25/ai-artificial-intelligence-social-media-bots-wrong)|Oscar Schwartz|An analysis of the past and present of media, hype, and AI|
|[Approximately Correct](http://approximatelycorrect.com/)|Zachary Lipton|A blog by a musician-turned-ML PhD emphasizing the hype of ML shadowing actual problems with ML|
|[The Hard Thing About Deep Learning](https://www.oreilly.com/ideas/the-hard-thing-about-deep-learning)|Reza Zadeh|An explanation of the difficulties of deep learning from an optimization perspective|
|[Why We Are in Danger of Overestimating AI (Financial Times)](https://amp.ft.com/content/4367e34e-db72-11e7-9504-59efdb70e12f)|Richard Waters|A Financial Times story describing the expectation disconnect with AI|
|[Why Can't the World's Greatest Minds Solve the Mystery of Consciousness?](https://getpocket.com/explore/item/why-can-t-the-world-s-greatest-minds-solve-the-mystery-of-consciousness)|Oliver Burkman|Does your iPhone really have feelings?
|[In What Ways Is Machine Learning Overrated](https://www.forbes.com/sites/quora/2017/12/21/in-what-ways-is-machine-learning-overrated/#6070d0d91b1a)|Forbes|A Forbes republishing of a Quora post describing how marginal machine learning's role is in products|
|[AI is Harder Than You Think](https://www.nytimes.com/2018/05/18/opinion/artificial-intelligence-challenges.html)|Gary Marcus and Ernest Davis|The two authors point out why AI is hard at pinning down the complexity of human language, and points out Google Duplex as an example|
|[If it Works, It's Not AI](http://dspace.mit.edu/bitstream/handle/1721.1/80558/43557450-MIT.pdf?sequence=2)|Eve M. Philips|Highlights how 1980's AI firms struggled to turn "AI" into commercial products and managing expectations|
|[Why the AI Hype Train is Already Off the Rails](https://builttoadapt.io/why-the-ai-hype-train-is-already-off-the-rails-and-why-im-over-ai-already-e7314e972ef4)|Dat Tran|A former Accenture Data Scientist expresses frustration over AI disillusionment and misguided investments|
|[AI Winter is Well On Its Way](https://blog.piekniewski.info/2018/05/28/ai-winter-is-well-on-its-way/)|Filip Piekniewski|Filip expresses his frustrations over AI predictions and problems with self-driving vehicles|
|[How It Feels to Learn Data Science in 2019](https://towardsdatascience.com/how-it-feels-to-learn-data-science-in-2019-6ee688498029)|Thomas Nield|Latter part of the satire comments on machine learning and StarCraft AI|
|[Why DeepMind's AlphaZero Has Trouble in the Real World](https://www.quantamagazine.org/why-alphazeros-artificial-intelligence-has-trouble-with-the-real-world-20180221/)|Joshua Sokol|Understanding how game AI and AlphaZero struggle to deal with real-world contexts and ambiguity
|[Statistics vs. Heuristics](https://shapeofdata.wordpress.com/2014/09/17/statistics-vs-heuristics/)|Jesse Johnson|A data scientist shares a rare insight comparing heuristics to statistics and machine learning|

## Promotion of Artificial Intelligence

This is just a small sampling of a vast trove of apocalyptic and sensational articles about AI. I also included some more reputable sources like WSJ. I'm going to keep this list short because there are plenty of articles promoting and sensationalizing AI. 

|Article|Description|
|---|---|
|[Brainlike Computers Learning from Experience](https://www.nytimes.com/2013/12/29/science/brainlike-computers-learning-from-experience.html)|An article about biologically-inspired computers, but really are just neural networks|
|[AI APOCALYPSE](https://www.dailystar.co.uk/news/latest-news/716305/ai-artificial-intelligence-autonomous-weaponry-arms-race)|Robots are a greater threat than nuclear war|
|[DeepMind's AlphaZero Now Showing Human-like Intuition](https://news.yahoo.com/deepmind-apos-alphazero-now-showing-190000147.html)|DeepMind researchers using anthropomorphizing words to describe AI|
|[China Vows to Become AI World Leader](https://www.thesun.co.uk/tech/4067800/china-vows-to-become-artificial-intelligence-world-leader-by-2030-but-will-it-spark-a-killer-computer-arms-race/)|A bleak outlook for humanity as the US and China enter an AI arms race
|[WSJ - How AI is Transforming the Workplace](https://www.wsj.com/articles/how-ai-is-transforming-the-workplace-1489371060)|AI is making hiring decisions for managers.|
|[Wired - Inside the First Church of Artificial Intelligence](https://www.wired.com/story/anthony-levandowski-artificial-intelligence-religion/)|Several Silicon Valley execs have created an AI-worshipping church.
|[Elon Musk - With Artificial Intelligence We Are Summoning the Demon](https://www.washingtonpost.com/news/innovations/wp/2014/10/24/elon-musk-with-artificial-intelligence-we-are-summoning-the-demon/?utm_term=.5347098e53b3)|Elon Musk gives a strangely-delivered warning about AI|


## News Stories

|Article|Description|
|---|---|
|[The Long and Lucrative Mirage of the Driverless Car](https://www.theringer.com/tech/2019/5/16/18625127/driverless-cars-mirage-uber-lyft-tesla-timeline-profitability)|Silicon Valley giants and Detroit automakers alike have sold the public visions of a utopia featuring autonomous vehicles. That reality is still far off.|
|[Facebook AI is Far From Able to Moderate Live Video](https://www.theverge.com/2019/5/20/18632260/facebook-ai-spot-terrorist-content-live-stream-far-from-solved-yann-lecun)|Facebook's AI is far from able to screen terrorist activity on Facebook Live|
|[Did IBM Overhype Watson Health's Promise](https://www.computerworld.com/article/3321138/did-ibm-put-too-much-stock-in-watson-health-too-soon.html)|IBM is being questioned for not following through on its promise of AI capability in healthcare|
|[Nearly Half of So-Called ‘AI Firms’ in Europe Never Use Artificial Intelligence, VC Firm Says](https://www.ccn.com/40-percent-ai-firms-europe-never-use-ai-vc-says)|London venture capital firm MMC Ventures has conducted a damning survey|

## Videos

#### P vs. NP and the Computational Complexity Zoo 

[![](https://img.youtube.com/vi/YX40hbAHx3s/hqdefault.jpg)](https://youtu.be/YX40hbAHx3s)

#### The Thinking Machine (1960's Pre-AI Winter)

[![](https://img.youtube.com/vi/aygSMgK3BEM/hqdefault.jpg)](https://youtu.be/aygSMgK3BEM)

#### The Lighthill Debate (1973)

[![](https://img.youtube.com/vi/yReDbeY7ZMU/hqdefault.jpg)](https://youtu.be/yReDbeY7ZMU)


#### The NotHotDog App (Silicon Valley - HBO)

[![](https://img.youtube.com/vi/ACmydtFDTGs/hqdefault.jpg)](https://youtu.be/ACmydtFDTGs)

## Social Media Posts

Examples of sound expert advice, as well as the blind leading the blind.

|Article|Platform|Description|
|---|---|---|
|[Can Neural Networks Solve Optimization Problems?](https://www.quora.com/Can-neural-networks-solve-optimization-problems#)|Quora|
|[In What Ways Is Machine Learning Overrated?](https://www.quora.com/In-what-ways-is-machine-learning-overrated/answer/Tikhon-Jelvis)|Quora|A computer scientist compares machine learning to heuristics and established technologies|
|[Why Are You Suggesting ML for That?](https://www.reddit.com/r/learnmachinelearning/comments/a49pk1/simple_general_tasks_that_you_solved_using/ebd1w6r)|Reddit|Anecdotal evidence of ML being misguidedly prescribed for problems outside its domain, due to common displaced expectations of the technology|
|[Your Brain Has Them!](https://hackaday.com/2018/10/22/jump-into-ai-with-a-neural-network-of-your-own/#comment-5337983)|Hackaday|A commenter asks if there are no useful problems neural networks can solve, and another commenter says "your brain has them", implying "no"|

## Wikipedia Articles

[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence)

[AI Winter](https://en.wikipedia.org/wiki/AI_winter) 

[No Free Lunch Theorem](https://en.wikipedia.org/wiki/No_free_lunch_theorem)

[Curse of Dimensionality](https://en.wikipedia.org/wiki/Curse_of_dimensionality)

[Heuristic](https://en.wikipedia.org/wiki/Heuristic_(computer_science))

[Metaheuristic](https://en.wikipedia.org/wiki/Metaheuristic)
