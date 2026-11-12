---
abstract: |
  The Draft National Artificial Intelligence Policy published for public
  comment in April 2026 was withdrawn within weeks, the stated reason being
  that parts of it were AI-generated and carried errors discovered only after
  publication. It should not have survived a superficial reading. The cost is
  not confined to that document: it set out to build trust in South Africa's
  AI effort, and its failure risks casting suspicion even on the grains of
  truth it contained.

  A policy is nonetheless urgently needed, and it has to be human-centric and
  grounded in our democratic values and freedoms. No single person or
  institution holds the answers; the scope touches everyone and everything.

  This article sets out some of the issues that deserve detailed exploration
  — where AI fits in and which parts of the stack a country like South Africa
  can realistically build, the infrastructure and data centres it rests on,
  models, data, applications, governance and ethics, and why reliance creates
  risk. It is an invitation to a discussion rather than a conclusion.
---

# Towards an IT policy

## Preamble

The Draft National Artificial Intelligence (AI) Policy made available for public comment on 10 April 2026 was a disaster and quickly [withdrawn on 26 April 2026](https://www.sanews.gov.za/south-africa/minister-announces-withdrawal-draft-ai-policy). The official reason given, was that parts (if not all, this is unclear) of the document was {abbr}`AI (Artificial Intelligence)` generated. This introduced errors only discovered later. This is bad enough. The fact is that the document should not have survived the most superficial inspection. [Praelexis](https://praelexis.com/) has commented in detail on some of the more serious issues.

The document lacks substance and cannot be used as a basis for an {abbr}`AI (Artificial Intelligence)` policy. 

What makes this debacle particularly vexing is the fact that the document aims, among other things, to build trust in the South African {abbr}`AI (Artificial Intelligence)` initiative and the use of {abbr}`AI (Artificial Intelligence)` in general. This is not the way to do it. Furthermore, it contains grains of truth that runs the danger of now being viewed with suspicion. There cannot be any doubt that an {abbr}`AI (Artificial Intelligence)` policy is sorely needed. Its goal is to make it human centric based on our democratic values and freedoms (plural), and this is the only way forward.

There should not be any doubt about the complexity and all-encompasing scope of the undertaking. It is incredibly difficult to balance interests of all the different parties - {abbr}`AI (Artificial Intelligence)` will impact on everyone and everything. No single individual or institution, anywhere, have the answers to all the questions that need to be addressed. Perhaps, even our combined wisdom might fall short. 

This makes development of a policy even more urgent.

With this article, I want to point out just some of the issues that, in my view, deserves to be explored in great detail. I invite anyone to join the discussion.

## Where {abbr}`AI (Artificial Intelligence)` fits in

[Yann LeCun, AGI](https://www.youtube.com/watch?v=4__gg83s_Do)

[Demis Hassabis, AGI](https://www.youtube.com/watch?v=SSya123u9Yk)

[Demis Hassabis, future of intelligence](https://www.youtube.com/watch?v=PqVbypvxDto)


{abbr}`AI (Artificial Intelligence)` is not an autonomous entity that can operate by itself. It operates through an agency; with few exceptions, through human agencies. It is also embedded in an environment that is ofter referred to as the {abbr}`AI (Artificial Intelligence)` [stack](https://www.itic.org/documents/artificial-intelligence/ITI_AITechnologyStack.pdf). 

The following simplified image is sufficient for our purposes:
:::{figure} ./figures/ai-stack.png
:label: ai-stack
The {abbr}`AI (Artificial Intelligence)` stack
:::

All of this, and more, is required in order to develop and apply {abbr}`AI (Artificial Intelligence)` models. It is not realistic for a country like South Africa to develop the whole {abbr}`AI (Artificial Intelligence)` stack - it simply doesn't have the resources to do so, as will become clear. On the other hand, all of the stack is required. In practice this means that the part that cannot be built locally, for whatever reason, creates a dependency and with dependencies come vulnerabilities. Again, more of this later.


For now, one important feature of the stack should be highlighted: the 'Ethics' component that embraces the whole stack. The reason for this will hopefully become clear.

I'll now discuss the component of the stack in a little more detail[^1].
[^1]: In order to keep the article contained, only brief descriptions will be provided.

Let's start at the bottom-most layer.

## Infrastructure

>At Davos, Karp told BlackRock CEO Larry Fink that the people building AI infrastructure will be in higher demand than the people using it in many white-collar roles.
>
>-- [Alex Karp, CEO Palantir](https://medium.com/predict/palantir-ceo-says-only-two-types-will-survive-ai-and-elite-degrees-arent-one-of-them-341c222044e0) 

By 'Infrastructure' I loosely mean everything that is necessary to enable the layers above it. It consists of, among others, the following components:

### Power supply

The Data data center layer on the next level consumes an enormous amount of power to keep it running. This power has to be generated. To give an idea, large data centers in the US can increase the land surface temperature by about 9.1{sup}`o` C and may affect up to millions of people.

>The message I would like to convey is to be careful about designing and developing data centres.
>
>--- {abbr}`Andrea Marinoni (Quoted in New Scientist by Chris Stokel-Walker, 27 March 2026)`

This implies a considerable environmental impact. Ethical considerations have a role to play!

### Water usage

Data centers also consume an enormous amount of water for, among other things, onsite cooling. According to the [World Economic Forum](https://www.weforum.org/stories/2025/11/data-centres-and-water-circularity/?gad_source=1&gad_campaignid=22228224717&gbraid=0AAAAAoVy5F66Vf4s8Jor33-LxYIOSyxLk&gclid=CjwKCAjw5NvPBhAoEiwA_2egfplk5Xp2pnXBzXjVU0c0YypUhgahcswEOKe0RqeANzLmc7rfGavO8xoC6QYQAvD_BwE), 

:::{attention} WEF
>Recent estimates suggest that accelerated AI adoption alone could result in an additional
>4.2 of 6.6 billion cubic metres of water withdrawal by 2027, including onsite cooling and
>offsite electricity generation. This projection is equivalent to four to six times the annual
>water withdrawal of Denmark, underscoring the need for urgent action.
>
>--- {abbr}`WEF (World Economic Forum)`
:::


### Computer chips

All the compute runs on computer chips and their avialability is crucial for all processing that takes place. Think Nvidia, the world's largest company. According to [Forbes](https://www.forbes.com/sites/tylerroush/2025/10/29/nvidia-becomes-first-company-worth-5-trillion/), 

:::{attention} Forbes
>Nvidia remains the world’s largest company, ranking ahead of Microsoft (\$4 trillion) and 
>Apple (\$3.9 trillion), which crossed the \$4 trillion threshold for the first time Tuesday,
>as well as Google parent Alphabet (\$3.2 trillion), Amazon (\$2.4 trillion) and Meta (\$1.8 trillion).
>
>--- {abbr}`Forbes (19 October, 2025)`
:::



## Data centers

In order to train the gargantuan models consisting of trillions of parameters, a huge amount of data is required and an equally large amount of computing power. These are provided in the data centers. There is a strong common view (although not everyone agrees) that further progress will be achieved by ever larger models, requiring even more and larger data centers. Erin Griffith captures something about what is at stake:


:::{attention} NYT
>The artificial intelligence boom has one big thing holding it back: energy. A.I. companies
>rely on power-hungry data centers to train their models, and they need gigawatts of power to keep them humming.
>
>--- {abbr}`Erin Griffith (New York Times, 26 April 2026)`
:::

### Training data

As mentioned above, the most sophisticated models need a gigantic amount of training data. Apart from Reinforcement Learning which generates its own training data, this data has to come form somewhere. This poses several challenges. I have aleady mentioned the vast amount of computing power required to process the data during the training process, but there are also problems with the data itself and its acquisition. 

Training data, in general, has to be representative of the problem addressed by the model. Modern models are not restricted to any specific domain and therefore need to be sourced as widely as possible. OpenAI, in their written [presentation](https://committees.parliament.uk/writtenevidence/126981/pdf/) to the House of Lords, put it as follows,

:::{pull-quote}
We believe that AI tools are at their best when they incorporate and represent the
full diversity and breadth of human intelligence and experience.
>
>--- 5 December 2023
:::

Limiting the data to what is available in the public domain, would severely impact on the quality of the models. 

:::{pull-quote}
Limiting training data to public domain books
and drawings created more than a century ago might yield an interesting
experiment, but would not provide AI systems that meet the needs of today’s
citizens.
>
> --- {abbr}`OpenAI (Written statement to the House of Lord, 5 December 2023)`
:::

The data is typically obtained from 3 [sources](https://committees.parliament.uk/writtenevidence/126981/pdf/), (a) Everything that is available on the internet, (2) data sourced from third parties, and (3) feedback from users. This creates [complicated legal issues](https://www.techpolicy.press/how-the-emerging-market-for-ai-training-data-is-eroding-big-techs-fair-use-copyright-defense/) that are still actively investigated.

Another potential challenge derives from the quote above, the data should represent "the full diversity and breadth of *human intelligence and experience". Generative AI systems produce a huge amount of data, already exceeding that generated by humans, and this can potentially lead to a crisis, potentially a [model collapse](https://www.lgt.com/global-en/market-assessments/insights/entrepreneurship/poisoning-the-ai-well-336294#:~:text=As%20generative%20AI%20models%20increasingly%20rely%20on,model%20collapse%2C%20bias%20and%20data%20poisoning%20grow.),  when future models are largely trained on synthetic data generated by generative AI systems. 

:::{pull-quote}
A lot of techniques have been tried, tested and miserably failed. And it’s true, it is impossible to remove SynthID 100%, but it is POSSIBLE to remove portions of it, to a point where detection fails!
>
>--- Alosh Denny in [Medium](https://medium.com/@aloshdenny/how-to-reverse-synthid-legally-feafb1d85da2)
:::

One potential solution for this problem is to provide the synthetic data with a watermark. However, it is unlear if this can be successfully enforced. The whole idea behind the generated data is to be indistinguishable from human generated data. It will therefore be very hard to tell if a watermark is not provided where it should have. 

If you want to experiment with making current watermarks redundent, here is Alosh Denny's [repo](https://github.com/aloshdenny/reverse-SynthID).

Finally, let me remind the reader that a model consisting of trillions of parameters opperate in an unimagineably large optimisation space. A space so large that it is impossible to explore all of it. To find a good configuration of parameters in this space, seems to me, something of a miracle. But large parts remain unexplored even in the vicinity of the configurations the training finally settles on. It leaves "jagged edges" for which Anrej Karpathy introduced the idea of [verifiability](https://x.com/karpathy/status/1990116666194456651?s=03):

:::{pull-quote}
The more a task/job is verifiable, the more amenable it is to automation in the new programming paradigm.
>
>--- Andrej Karpathy
:::



## Models

The most advanced models have a few things in common:

1. They have an unimaginably large number of parameters, up to several trillion, as I mentioned before. Any single model consists of a specific, optimal configuration of these parameters. It is costly to find a good set of parameters and all large models are pre-trained, perhaps with the possibility of some adjustment for one' own use-case. This means that the user is to a large extent limited by what the model has to offer (Karpathy).
2. The models are often probabilistic in nature. This is true for all {abbr`LLMs (Large Language Models)`}. This means that the same prompt will not produce the same answer every time. This probably doesn't matter when you ask it to write a poem but it might matter a lot if you ask for critical advice.

The point is that it is important to know when and how to use these models. To get the best out of these models, users should also be educated how and when not to use it. (Karpathy's three rules).

(cite cases where psycological problems were caused. Nonexisting legal cases were cited. Google search engines are correct 90% of the time.)

[karpaty](https://karpathy.bearblog.dev/verifiability/)

[karpathy](https://www.youtube.com/watch?v=96jN2OCOfLs)



## Data

Here I refer to data that is used for inference. "Inference" means the data that is fed to the model in order to generate some output that the user of the model is interested in. This data is often private data of actual persons. We willingly provide some of our most private data, such as out financial health, to institutions, financial and otherwise. Fortunately, there are strict rules how this data may be collected and use by companies. In South Africa we have the POPI Act, in Europe, DGPR that provide some reassurance that our private date will be handled responsibly. 

Unfortunately, this does not provide total reassurance. For example:

1. DGPR is written in broad terms and the specifics need to be fleshed out in court. This leads to complicated and messy law suits. (Inga Strumke example)
2. Many companies rely on American tech companies like Google, Amazon, Microsoft, etc, to host their data. This is where the US CLOUD Act of 2018 comes into play. (Expand on the danger it poses and the EU response.)
3. Many users of chatbots unwittingly provide detailed information of their innermost thoughts. There is a saying that the AI agents know more about you than you know yourself. There is a grain of thruth in this and this information can be used to manipulate your thinking habits (expand and refer to Robert Cialdini?).
4. It is possible to infer private data from one's personal but public data. Imagine that an AI system can learn with remarkably whether you are prone to depression from your public Facebook interactions. This is most likely not information that most people would like to be widely known. Except, you don't need to imagine it - it has happened (cite Facebook study.)

Any AI policy should probably want to take all of this into account. And note that it goes beyond POPI.



## Applications

Together with the data used for inference, this is probably the area where a South African AI Act should have the most effect.

1. The EU AI Act limits applications not research. (Expand.)
2. A governance balancing act is required. On the one hand harmful use not in line with our value system as a country, democracy (no interference in elections, prevent undue power and influence from big tech companies, citations). On the other hand innovative solutions should not be hampered by well-intentioned rules. 

## Governance

According to many, AI is the most consequential technology ever developed. Some, including Geoffrey Hinton, sees it as an existential threat to human kind. Mustafa Suleyman sees it as a tsunami that will overwhelm us. 

I'm more optimistic and I will not go into all the reasons for my optimism. However optimistic I am, appropriate governance is called for. Even the US, with its deep aversion to any governance, is considering regulations.

Exactly what that should look like, I don't know. Fortunately, the EU with its AI Act is already far advanced meaning that we need not start cold.

Let me mention a few other ideas floating around:

1. Strumke et al argues for a type of hippocratic oath for AI practitioners (expand).
2. Mustafa Suleyman argues for containment (expand)
3. What about legal responsibility for AI agents? This is not feasible. AI agents have no conciousness (despite some arguments to the contrary). Any sanctions on an entity without consciousness is pointless. It does not serve as either a punishment for the aberrant agent nor a deterrent to others.


[Stiglitz](https://www.nber.org/papers/w34994?fbclid=IwY2xjawQ6S4VleHRuA2FlbQIxMABicmlkETFmeW1VUVhUSk5NcjZsV2NVc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHtda-FYr9isYTZYlgJptscQ3XrtO_2BSzuqK14tXr6ZCLQBjE00mSRV7Fk1f_aem_lb0RkOpTtfcxW7B5qtyfaQ)]

[Mike Loukides](https://www.oreilly.com/radar/software-2-0-means-verifiable-ai/)

### EU AI Act of 2024

:::{attention} EU Act Summary
:class: dropdown
>*Banned applications*
>
>The new rules ban certain AI applications that threaten citizens’ rights, including biometric categorisation systems based on sensitive characteristics and untargeted scraping of facial images from the internet or CCTV footage to create facial recognition databases. Emotion recognition in the workplace and schools, social scoring, predictive policing (when it is based solely on profiling a person or assessing their characteristics), and AI that manipulates human behaviour or exploits people’s vulnerabilities will also be forbidden.
>
>*Law enforcement exemptions*
>The use of biometric identification systems (RBI) by law enforcement is prohibited in principle, except in exhaustively listed and narrowly defined situations. “Real-time” RBI can only be deployed if strict safeguards are met, e.g. its use is limited in time and geographic scope and subject to specific prior judicial or administrative authorisation. Such uses may include, for example, a targeted search of a missing person or preventing a terrorist attack. Using such systems post-facto (“post-remote RBI”) is considered a high-risk use case, requiring judicial authorisation being linked to a criminal offence.
>
>*Obligations for high-risk systems*
>Clear obligations are also foreseen for other high-risk AI systems (due to their significant potential harm to health, safety, fundamental rights, environment, democracy and the rule of law). Examples of high-risk AI uses include critical infrastructure, education and vocational training, employment, essential private and public services (e.g. healthcare, banking), certain systems in law enforcement, migration and border management, justice and democratic processes (e.g. influencing elections). Such systems must assess and reduce risks, maintain use logs, be transparent and accurate, and ensure human oversight. Citizens will have a right to submit complaints about AI systems and receive explanations about decisions based on high-risk AI systems that affect their rights.
>
>*Transparency requirements*
>
>General-purpose AI (GPAI) systems, and the GPAI models they are based on, must meet certain transparency requirements, including compliance with EU copyright law and publishing detailed summaries of the content used for training. The more powerful GPAI models that could pose systemic risks will face additional requirements, including performing model evaluations, assessing and mitigating systemic risks, and reporting on incidents.
>
>Additionally, artificial or manipulated images, audio or video content (“deepfakes”) need to be clearly labelled as such.
>
>*Measures to support innovation and SMEs*
>
>Regulatory sandboxes and real-world testing will have to be established at the national level, and made accessible to SMEs and start-ups, to develop and train innovative AI before its placement on the market.
>
>-- [News, European Parliament](https://www.europarl.europa.eu/news/en/press-room/20240308IPR19015/artificial-intelligence-act-meps-adopt-landmark-law)
:::

### Unintended consequences

1. The fear that large parts of the population will loose their jobs are real. It is already affecting certain sectors more than others (cite numbers).
2. The business model of the tech companies is to create a tech addiction (give citation). This is because they make money from advertisements which means that the more you use the app, the more money is generated. Then they  realised, to their dismay, that this also creates an addiction of the mind. A number of countries are considering, or have already implemented age restriction on the use of social media (citations).
3. In the US a few tech companies have amassed enormous riches and with that enormous political power and influence. Also power to influence elections through various means - financial contributions to preferred political parties and candidates, manipulating the minds of voters (Cialdini on how this is done from a psychological perspective, Applebaum, Snyder, oetc, ne how it is done in practice.)

:::{attention} Human involvement
>But as AI expands what people can do, it also raises the premium on good judgment. Most AI users we surveyed recognize this. Asked which human skills are more important as AI takes on more work, they said two topped the list: quality control of AI output (50%) and critical thinking—analyzing information objectively and making a reasoned judgment (46%). And 86% say they treat AI output as a starting point, not a final answer, and that they “stay responsible for the thinking.” They see their role is shifting from generating answers to evaluating, refining, and owning them.
>
>Frontier Professionals are even more aware of the importance of human judgment when working with AI. They rank higher across every measure in the survey related to critical thinking and quality control—and that shows up in how they work. They are more likely than non-Frontier professionals to say they intentionally do some work without AI to keep their skills sharp (43% vs. 30%) and to say they intentionally pause before starting work to decide what should be done by AI versus a human (53% vs. 33%). Frontier Professionals refuse to outsource their thinking—they know long-term success means continuing to build human skills and not letting them atrophy.
>
>-- {abbr}`[Microsoft, 5 May 2026](https://www.microsoft.com/en-us/worklab/work-trend-index/agents-human-agency-and-the-opportunity-for-every-organization)`

## Ethics

Ethical considerations run through the whole AI stack. (To be continued ...)

[Tristan Harris](https://www.tristanharris.com/#:~:text=Tristan%20is%20Co%2DFounder%20of%20the,technology%20with%20humanity's%20best%20interests.)

[Tristan Harris](https://www.youtube.com/watch?v=NufB1LL_rCU)

[palantir](https://x.com/PalantirTech/status/2045574398573453312)

[palantir on jobs](https://medium.com/predict/palantir-ceo-says-only-two-types-will-survive-ai-and-elite-degrees-arent-one-of-them-341c222044e0)

[multi agent risks](https://arxiv.org/pdf/2502.14143)

[Chris W. Kim, dehumanising](https://www.nytimes.com/2026/05/12/opinion/us-china-ai-future.html)


## Why an {abbr}`AI  (Artificial  Intelligence)` Act?

The pupose of the {abbr}`AI  (Artificial  Intelligence)` Act should be carefully specified. It is clear that it is not possible to develop the full {abbr}`AI  (Artificial  Intelligence)` stack. Nor is it good enough to start from a mindset, albeit not explicitly acknoledges, of "everyone is doing it and we cannot fall behind". Misguided motivations such as job creation is best avoided. Trying to sell that to a population that is, with reason, deeply concerned about lob losses, only generates mistrust. Here is a random example.

:::{pull-quote}
The bank’s bottom line, he said, was helped by shedding 1,000 jobs through attrition by “eliminating work and applying technology,” which he repeatedly specified was artificial intelligence. He predicted more of that in the months and years to come.
>
>--- {abbr}`Brian T. Moynihan (Chief executive, Bank of Amnerica, NYT 21 April 2026)`
:::

:::{attention} Full quote
:class: dropdown
>Less than four months ago, Bank of America’s chief executive, Brian T. Moynihan, volunteered in a TV interview what he would say to his 210,000 employees about the chance of artificial intelligence replacing human work.
>
>“You don’t have to worry,” he said. “It’s not a threat to their jobs.”
>
>Last week, after Bank of America reported \$8.6 billion in profit for the first quarter — \$1.6 billion more than the same period a year earlier — Mr. Moynihan struck a different tone.
>
>The bank’s bottom line, he said, was helped by shedding 1,000 jobs through attrition by “eliminating work and applying technology,” which he repeatedly specified was artificial intelligence. He predicted more of that in the months and years to come.
:::

>Daniela Amodei, co-founder and president of Anthropic, has said studying the humanities will become “more essential than ever” and that qualities like emotional intelligence, communication skills, kindness, compassion, and curiosity matter deeply in AI development.
>
>“The things that make us human will become much more important instead of much less important,” she told ABC News. “When we look to hire people at Anthropic today, we look for people who are great communicators, who have excellent EQ and people skills.”
>
>-- [Daniela Amodei](https://medium.com/predict/palantir-ceo-says-only-two-types-will-survive-ai-and-elite-degrees-arent-one-of-them-341c222044e0)

>What bothers me most is the absolutism. Karp says there are “basically two ways to know you have a future.” That is marketing, not analysis. Plenty of people will thrive in an AI economy without being tradespeople or neurodivergent. Nurses, therapists, teachers, managers, salespeople, anyone whose job depends on human trust, judgment, or relationship-building is not getting automated soon.
>
>-- [Tasmia Sharmin](https://medium.com/predict/palantir-ceo-says-only-two-types-will-survive-ai-and-elite-degrees-arent-one-of-them-341c222044e0)

### What should be the goal of an {abbr}`AI (Artificial Intelligence)` Act?

Specifics, in no particular order.

* Put the guard rails in place within which development and applications should take place. That means maximise the benefits and minimise the risk.
* Empower industry to safeguard sensitive data. This might mean that sensitive data must not leave our borders. 
* Enforce measures to safeguard individual data such as the POPI Act. Design a policy for the generation of sensitive information using public data.
* Contain the spread of misinformation. This is widespread practice in order sway public opinion.
* Ensure the future of our democratic values. This, among others, imply that tech companies should not be put in a position where they have undue influence.
* Ensure that development and applications align with our core values, freedom, human dignity, equality, etc.

## Reliance creates risks

>In a small but meaningful break from American technology, DeepSeek said for the first time that its new model had been optimized to run on chips made by the Chinese tech giant Huawei. This was a milestone in China’s long-running effort to develop advanced technologies at home and reduce its reliance on Western innovation.
>
>-- {abbr}`Meaghan Tobin (NYT, 12 May 2026)`


