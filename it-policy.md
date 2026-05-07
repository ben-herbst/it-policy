# Towards an IT policy

## Preamble

The Draft National Artificial Intelligence (AI) Policy made available to the pulic for comment on 10 April 2026 was a disaster and quickly [withdrawn on 26 April 2026](https://www.sanews.gov.za/south-africa/minister-announces-withdrawal-draft-ai-policy). The official reason given, was that parts (if not all, this unclear) of the docuement was {abbr}`AI (Artificial Intelligence)` generated which introduced errors only discovered later. This is bad enough. The fact is that the document should not have survived the most superficial inspection. [Praelexis](https://praelexis.com/) has commented in detail on some of the most serious issues.

The document lacks substance and cannot be used as a basis on which to build an {abbr}`AI (Artificial Intelligence)` policy. 

What makes this debacle particularly vexing is the fact that it is document aims, among other things, to build trust in the South African {abbr}`AI (Artificial Intelligence)` initiative. This is not the way to do it. Furthermore, it contains grins of truth that runs the danger of being viewed with suspicion. There cannot be any doubt that an {abbr}`AI (Artificial Intelligence)` policy is sorely needed. Also, the fact that its goal is to make it human centric based on our democratic values and freedoms (plural), is the only way forward.

There should not be any doubt about the complexity and all-encompasing scope of the undertaking. It is encredibly difficult to balance interests of all the different parties - {abbr}`AI (Artificial Intelligence)` will impact on everyone and everything. No single individual or institution, anywhere, have the answers to all the questions that need to be addressed. Perhaps, even our combined wisdom might fall short. 

This makes development of a policy even more urgent.

With this article, I want to point out just some of the issues that should be discussed in more detail. I invite anyone to join the discussion.

## Where {abbr}`AI (Artificial Intelligence)` fits in

{abbr}`AI (Artificial Intelligence)` is not an autonomous entity that can operate by itself. It operates through an agency; with few exceptions, through human agencies. It is also embedded in an environment that is ofter referred to as the {abbr}`AI (Artificial Intelligence)` [stack](https://www.itic.org/documents/artificial-intelligence/ITI_AITechnologyStack.pdf). 

The following simplified image is sufficient for our purposes:
:::{figure} ./figures/ai-stack.png
:label: ai-stack
The {abbr}`AI (Artificial Intelligence)` stack
:::

All of this, and more, is required in order to develop and apply {abbr}`AI (Artificial Intelligence)` models. It is not realistic for a country like South Africa to develop the whole 
{abbr}`AI (Artificial Intelligence)` - it simply doesn't have the resources to do so, as will become clear. On the other hand, all of the stack is required. In practice this means that the part that cannot be built locall, for whatever reason, creates a dependency and with dependencies come vulnerabilities. Again, more of this later.


For now, one important feature of the stack should be highlighted: the 'Ethics' component that embraces all of the stack. The reason for this will hopefully become clear.

I'll now discuss the component of the stack in a little more detail[^1].
[^1]: In order to keep the article contained, only brief descriptions will be provided.

Let's start at the bottom-most layer.

## Infrastructure

By 'Infrastructure' I loosely mean all that is necessary to enable the layers above it. It consists of, among others, the following components:

### Power supply

Data data center layer above this one consumes an enormous amount of power to keep it running. This power has to be generated. To give an idea, large data centers in the US can increase the land surface temperature by about 9.1{sup}`o` C and affect and may affect up to 340 million people.

>The message I would like to convey is to be careful about designing and developing data centres.
>
>--- {abbr}`Andrea Marinoni (Quoted in New Scientist by Chris Stokel-Walker, 27 March 2026)`

This implies a considerable environmental impact. Ethical considerations have a role to play!

### Water usage

Data centers also consume an enormous amountof water for, among other things, onsite cooling. According to the [World Economic Forum](https://www.weforum.org/stories/2025/11/data-centres-and-water-circularity/?gad_source=1&gad_campaignid=22228224717&gbraid=0AAAAAoVy5F66Vf4s8Jor33-LxYIOSyxLk&gclid=CjwKCAjw5NvPBhAoEiwA_2egfplk5Xp2pnXBzXjVU0c0YypUhgahcswEOKe0RqeANzLmc7rfGavO8xoC6QYQAvD_BwE), 

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
>Nvidia remains the world’s largest company, ranking ahead of Microsoft ($4 trillion) and 
>Apple ($3.9 trillion), which crossed the \$4 trillion threshold for the first time Tuesday,
>as well as Google parent Alphabet (\$3.2 trillion), Amazon (\$2.4 trillion) and Meta ($1.8 >trillion).
>
>--- {abbr}`Forbes (19 October, 2025)`
:::

## Data centers

In order to train the gargantuan models consisting of trillions of parameters, a huge amount of data is required and an equally large amount of computing power. These are provided in the data centers. There is a strong common view (although not everyone agrees) that further progress will be achieved by ever larger models, requiring even more and larger data centers. Erin Griffith captures something about what is at stake:


:::{attention} NYT
>The artificial intelligence boom has one big thing holding it back: energy. A.I. companies
>rely on power-hungry data centers to train their models, and they need gigawatts of power to >keep them humming.
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

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Data

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

### Privacy

Private data derived from public data

#### POPI

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

#### GDPR

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

### US CLOUD Act of 2018

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

### Vulnerability and EU response

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Applications

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Governance

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

### EU AI Act

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

### Regulation and Containment

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

### Unintended consequences

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Ethics

"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Why an {abbr}`AI  (Artificial  Intelligence)` Act?

The pupose of the {abbr}`AI  (Artificial  Intelligence)` Act should be carefully specified. It is clear that it is not possible to develop the full {abbr}`AI  (Artificial  Intelligence)` stack. Nor is it good enough to start from a mindset, albeit not explicitly acknoledges, of "everyone is doing it and we cannot fall behind". Misguided motivations such as job creation is best avoided. Trying to sell that to a population that is, with reason, deeply concerned about lob losses, only generates mistrust. Here is a random example.

:::{pull-quote}
The bank’s bottom line, he said, was helped by shedding 1,000 jobs through attrition by “eliminating work and applying technology,” which he repeatedly specified was artificial intelligence. He predicted more of that in the months and years to come.
>
>--- {abbr}`Brian T. Moynihan (Chief executive, Bank of Amnerica, NYT 21 April 2026)`
:::

:::{attention} Full quote
:class: dropdown
>Less than four months ago, Bank of America’s chief executive, Brian T. Moynihan, volunteered >in a TV interview what he would say to his 210,000 employees about the chance of artificial >intelligence replacing human work.
>
>“You don’t have to worry,” he said. “It’s not a threat to their jobs.”
>
>Last week, after Bank of America reported $8.6 billion in profit for the first quarter — $1.6 >billion more than the same period a year earlier — Mr. Moynihan struck a different tone.
>
>The bank’s bottom line, he said, was helped by shedding 1,000 jobs through attrition by >“eliminating work and applying technology,” which he repeatedly specified was artificial >intelligence. He predicted more of that in the months and years to come.
:::

### What should be the goal of an {abbr}`AI (Artificial Intelligence)` Act?

Specifics, in no particular order.

* Put the guard rails in place within which development and applications should take place. That means maximise the benefits and minimise the risk.
* Empower industry to safeguard sensitive data. This might mean that sensitive data must not leave our borders. 
* Enforce measures to safeguard individual data such as the POPI Act. Design a policy for the generation of sensitive information using public data.
* Contain the spread of misinformation. This is widespread practice in order sway public opinion.
* Ensure the future of our democratic values. This, among others, imply that tech companies should not be put in a position where they have undue influence.
* Ensure that development and applications align with our core values, freedom, human dignity, equality, etc.


