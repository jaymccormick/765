### Kultima, A. (2009). Casual game design values. In *Proceedings of the 13th International MindTrek Conference: Everyday Life in the Ubiquitous Era*, MindTrek '09, pages 58-65, New York, NY, USA.

#### Overview
Casual games are higher in: Acceptability (social norm conformity), Accessibility (cognitive, physical, economic), Simplicity (in game rules and environment; also, automating processes like saving) and Flexibility (change devices, locations, attention level)
20% AGR in casual games; 51% of 200MM online players are women;
casual game design and "hardcore" or "traditional" games "form a valence"
- in graph theory: the number of edges incident to a vertex (with loops counted 2x)
- in psychology: the attractiveness (positive valence) or aversiveness (negative valence) of an event. (ambivalence thus can be seen as a conflict between positive and negative valence carriers)
- in linguistics: the number of arguments controlled by a verbal predicate
  - It rains. 0 valence
  - He sleeps. 1 valence.
  - He gave her a flower. 3 valence.
- in chemistry: the measure of an element's combining power with other elements when it forms chemical compounds or molecules

#### Hits
- game design is "second-order design": game rules are designed directly, and the game experience is a result of game rules. game rules do not have entirely predictable effects, so the design of a game is not an exercise in logical but rather in normative assessments and decisions.
- "any simple, small, or easy game can be categorized as 'casual'". true, and good to recognize early in the paper to support the inquiry: what, more specifically, characterizes a category of games that feels eminently recognizable.

#### Misses
- mis-titled subsection (3.3.4 should be Flexibility, not Accessibility (which is discussed in a prior section))
- "The rise of casual game industries indicates a transformation in games cultures..." what is that culture, and what is the change?

### Crabtree, A. & Tolmie, P. (2016). A day in the life of thinkgs in the home. In *Proceedingsof the 19th ACM Conference on Computer-Supported Cooperative Work & Social Computing*, CSCW '16, pages 1738-1750, New York, NY, USA. ACM.

#### Overview
The authors' endeavor is "[O]pening up the methodical assemblage of things"
Based on "observations in 2 ostensibly middle-class UK homes" - ostensibly: evidently, professed (rather than demonstrably true). are they not middle-class?
Method: Counted the interactions with things - anything and everything, from tea kettles to iPads to couches - over several 3-hour periods
Summary: One can see how events flow in a space by observing the "methodical assemblage of things"; seeing a use pattern across IoT devices will be difficult for machines because there is no intrinsic logical connection among devices' use

#### Hits
- the Internet of Things is "marked largely by the design of *individual things*", resulting in a "*fragemented ecology*" that ignores in its design framework the methodical assemblage of things.
- designing for the home means (or should mean) designing for methodical assemblages of things from multiple categories
- detecting the unique, local methodical assemblage of things is a challenge for algorithms, e.g. machine learning

#### Misses
- too much *italics* (one randomly picked page had 9 instances of *italics*)
- perplexing language use ("The study reported here is rooted in a long tradition of empirical studies.... [which] are 'incommensurate and asymmetrically alternate' to theoretical treatment of whatever colour, shade or hue.")

### Heer, J. & Schneiderman, B. (2012). Interactive dynamics for visual analysis: A taxonomy of tools that support the fluent and flexible use of visualizations. *Queue* 10(2): 30:30 - 30:55.

### Resources

[Iris AI on Value-Based Strategies](https://the.iris.ai/map/81291507-1275-4902-94f1-15e72406cc4f)

[NY Times 2013 Oscar Contenders](http://www.nytimes.com/interactive/2013/02/20/movies/among-the-oscar-contenders-a-host-of-connections.html?_r=1&)

[D3](https://d3js.org)

[Tensor Flow Data Flow Graph](https://www.tensorflow.org/)

#### Overview
Taxonomy:
- Data & View Specification
  - Visualize
    - expressiveness of formal grammars; but also "steep learning curve"
  - Filter
    - "dynamic query widgets", e.g. radio buttons, sliders, categories
    - "incremental exploration": is that just 'guess-and-check'?
  - Sort
    - "The goal is to reveal underlying structure (e.g. clustering) within the data."
    - **seriation**: arranging in order by size
  - Derive
    - include tools for deriving new data based on input data to continue the exploration and analysis process
- View Manipulation: patterns within patterns and across data
  - Select
    - limited; don't have the gaze, gestures available (but maybe AR?)
  - Navigate
    - Overview, Zoom and Filter, Details;
    - Search, Show Context, Expand on Demand
    - "How analysts navigate a visualization is in part determined by where they start"
    - 'Linked navigation' that manipulates multiple views simultaneously
  - Coordinate
    - easier to integrate data across views than to add data to a single view
  - Organize
    - managing views, legends, and interactive controls
- Process & Provenance: "iterative data exploration and interpretation"
  - Record
    - interaction histories
    - pattern of exploration
  - Annotate
    - if not "data-aware", become meaningless
  - Share
  - Guide
    - onboarding
    - linking expert creators to novice audience
    - **tacit tutorial** e.g. NY Times

#### Hits
- Generally good hierarchy of actions and related affordances for designing and developing a visualization interface
- nice overview of different visualization technologies. a challenge in describing something dynamic in a static medium (describing dynamic visualization using text) is maintaining clarity without excessive detail. generally the article succeeds at this.
- lays out the interaction steps to think about in designing a visualization platform.
- navigation as Overview->Filter and Zoom->Details-on-demand
- thinking about coordinating multiple views as easier to comprehend than adding variables to a single view

#### Misses
- dry. i don't think anyone else read the article (based on class participation before we discussed this article, during the discussion, and the discussion after it. participation went from high to zero back to high.)
- too much undefined terminology. maybe for the audience it is written for, that is good. and adding definitions and explanations for each term (like data-flow graph, or "operator") would have added at least a few pages to the article.
- no discussion of heuristics; i think visualizations take advantage of humans' powerful visual pattern recognition, and should build in indicators of statistical significance to guide users away from mistaken interpretations of data

### Puntambekar, S. & H&uuml;bscher, R. (2005). Tools for scaffolding students in a complex learning environment: What have we gained and what have we missed? *Educational Pyschologist 40*(1), 1-12.

#### Overview
Scaffolding is a theory of teaching and learning. The teaching theory is the teacher's understanding of the problem at hand and how it can be approached and solved. The learning theory is the teacher's understanding of the student's skills and progress. The teacher uses these two theories to calibrate her support to keep the student in the "zone of proximal development". Moreover, the support is more inclusive than a purely academic model would capture. It includes perceptual, cognitive and affective domains.

Key Features:
- ZPD. The teacher keeps the student in the zone of proximal development, "the distance between the child's actual developmental level as determined by independent problem solving and the higher level of potential development as determined through problem solving under [teacher] guidance and in collaboration with more capable peers"
- Multidimensional & Shared Goal. The teacher is an expert and a facilitator knowledgeable about the skills, strategies and processes required for effective learning. The teacher provides:
  - Motivation by providing just enough support to enable the student to accomplish the goal;
  - Modeling to highlight the critical features of the task;
  - Hints and questions that encourage learner reflection.
- Dynamic. Calibrated support through ongoing interactions. This is accomplished through the "dialogic and interactive nature of scaffolded instruction".
- Fading. When the learner has internalized the responsibility of solving the problem

#### Hits
- In general, challenging the notion that human-to-human interaction can be replicated with human-computer interaction, and discussing the limitations of an HCI implementation of scaffolding
- The discussion of the limits (really, the lack) of fading in HCI scaffolds: "fading is not automatic but has to be explicitly initiated by the student"
- The idea that fading in the context of scaffolding software could mean removing the software tool altogether.
- Peer support is not the same as tutor support. Peer interactions may encourage exploration and performance and motivate learners. Expert-novice interactions entail an assessment of the learner's skills and tailored support (interactions absent in peer interactions)

#### Misses
- I would like to have seen more of a design proposal for a solution to the problem of (1) the difficulty of scaling scaffolding beyond 1 teacher and one learner and (2) the limitations of scaffolding as implemented in an HCI model
- "[E]ffective scaffolding needs to be distributed, integrated and multiplied": yes, true (although it's unclear what "distributed", "integrated" and "multiplied" means here). But *how* can we do that? Or, what sources have attempted or described the path to doing that?

### Medhi-Thies, I., Ferreira, P., Gupta, N, O'Neill, J. & Cutrell, E. (2015). KrishiPustak: A social networking system for low-literate farmers. *CSCW 2015*, 1670-1680.

#### Overview
Exponential user growth in social networks' membership is based on a zero cost model. Joining and using Facebook are free. Interestingly, Twitter is bringing the NFL to users; the social network that has the most existential angst is the one that has to do the most work generating content to keep its users engaged. Facebook must be offering its users more, because it focuses on its websites architecture and interactions rather than its content. Facebook is a teeming city; Twitter is an empty mall.

So with that as a background, let's imagine the next frontier for social networking. What about a social network for farmers? But not just any farmers... they're farmers with no infrastructure around them; they live in huts and don't have running water. Also, they speak an obscure dialect, and they can't read.

What struck me is the lack of human-centered design principles. The research question is "How can we design a social network for illiterate farmers?" That's an interesting question (that feels decidedly less academic since 3 of the 4 coauthors are Microsoft employees). (As an aside to the thin academic gloss on this project: what exactly do the researchers mean when they say they obtained "informed verbal consent" from the farmers? I would be surprised if the farmers, who have no experience with digital technology or general information sources like newspapers, let alone academic articles, actually understood what they were consenting to.) But it wholly ignores a much broader question: What do illiterate farmers need help doing? The authors make a tenuous connection to a local organization that is using videos and other digital tutorials to disseminate farming and animal tending best practices. Peter F. Drucker, in Entrepreneurship and Innovation (1985), shares a story of European motorbike manufacturers who introduced motorbikes to India, thinking that India's weak transportation sector and poor population were a perfect environment for the cheap, convenient travel afforded by a motorbike. Sales were poor, except in an agricultural area in India. Farmers in the agricultural area were buying the motorbikes for their motors, which they stripped from the motorbikes and used to run irrigation pumps. The engineer who discovered this founded an irrigation pump company and was incredibly successful. Here, we are introducing a social network to India; I wonder what they would do with it if they could strip it for parts.

Then the researchers advise that without "mediators", people who can read, have phones, and have a basic understanding of technology and social networks, this social network would not have worked. Tellingly, the section devoted to the importance of mediator participation is entitled "Incentivization of Mediators Crucial". Even with the mediators, it's not clear that the social network can actually be called a "success" - mediators were responsible for signing up farmers to the social network, but neither the mediators nor farmers could articulate what exactly they received by joining this network. One mediator, who had signed up 35 farmers, "could not tell the farmers what the system was for as he did not know himself." Further, incentives are hard to get right, or it's hard to discern the effects of incentives from what they enable. Salaries partly are incentives to work; they also enable work, providing enough resources for a person not to have to do something else. In any case, there's more to a person's motivation than the "incentive" she receives.

#### Hits
- There is no current good solution for passwords for illiterate and low-literacy users. Whatever one might think of this project, the insight is an important one. Imagine low-literacy users trying to access basic information about themselves, like accessing government aid, or finding out health information.
- "[T]echnological interventions will be more effective if they take into consideration the underlying infrastructures such as intermediation that are embedded in the community." I think this means, Think of communities you are designing for, rather than individuals, because individuals receive support from their communities.

#### Misses
- The idea of informed consent from illiterate farmers about participating in a social network using mobile phones.
- Asking the farmers what they wanted (pictures of gods and actors; religious songs) as a way to "iterate" the next version of the network. Since when did asking users for specific product recommendations yield product features that are innovative, or even actually helpful?

### Bae, J., Lim, Y, Bang, J. & Kim, M. (2014). Ripening Room: Designing Social Media for Self-Expression. *DIS 2014*, 103-112.

#### Overview
Industrial design students in South Korea assert that the fundamental design flaw of social media is that it does not "support users' self-reflection". To remedy this design flaw, they propose a social network website that requires users to select a "ripening time", between 1 minute and 48 hours, during which the post is visible only to them. While the ripening window is open, they can edit the post as much as they like. Once it is posted, they cannot change it.

The students built in a scoring process - a combination of ripening time and votes from other users on a post's "maturity". They intended the scoring process "to motivate users to earn higher points, and an increase in score would give positive feedback, resulting in a a sense of achievement in the social media context."

#### Hits
- The premise is interesting. Why do we carelessly share personal information? Why do we heedlessly interact with others online? Perhaps some sort of delay is helpful.
- Interesting user insights: not interacting with her phone was "40 minutes of endless pain." And "I've tried to get away from smart phones and computers, and focused on reading books. But in 10 minutes, my hand got impatient to touch my phone!"
- The recognition that social media "provide[s] purposeless connectedness and the hedonic pleasures of gossip, not... the pursuit of.. self-reflection. Will users' desire to use social media" fall when the platform encourages self-reflection?

#### Misses
- The assumption that social media can, and should, encourage personal growth: "It is important that social media encourage users to express their inner thoughts and emotions if they are to collect meaningful resources for self-reflection, because it is not always guaranteed that users' activities will create meaningful resources."

### Gentner, D. & Nielson, J. (1996). The Anti-Mac Interface. *Communications of the ACM 39*(8) 71-82.

#### Overview
Is the Windows-Icons-Menu-Pointer model the final innovation in GUIs? Gertner and Nielson hope not - but in the 20 years since this article, I don't see that much has changed.

#### Hits
- The Mac interface is "good enough to be criticized". I think that's a useful way to think about criticism, that we're only criticizing what is good and can become better. We aren't spending time on interfaces that aren't even good to begin with.
- Metaphors are not as helpful as they seem. Cars were originally controlled by reins, like horses, but that metaphor constrained the design without helping drivers. Maybe metaphors are there most helpful when we are working with novel concepts. Learning and adaptation build new mental structures that are better constructs than the original metaphor. Gentner and Nielson strain their analysis here, describing metaphors in terms of mappings between the target and source domain.
- "The dark side of direct manipulation is that you have to manipulate everything."
- If applications arrange themselves to fit our needs, they are dynamic yet feel dependable.
- They make a general point about how much rote work GUIs saddle us with.

#### Misses
- Although their observation that we lack the power of language, and instead must communicate primitively by pointing and clicking, rings true, their design solution - that we should spend as many years mastering interactions with computers as we do with other humans (20, in their estimation) - is absurd and contradicted by their other points that computers should be more responsive to our needs. I also doubt that computers could be programmed with language capability that would evolve with our own. (Until A.I. enables that, at which point there will be other issues to deal with than using natural language to manipulate files on our PCs).
