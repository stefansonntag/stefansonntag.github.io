---
title: The Risk of a New AI Winter
feed: show
---
## History has not been kind to AI pioneers who overpromise and underdeliver

Is winter coming?

I speak of an “AI winter”, of course.

They’re part of the boom-bust cycle that we’ve seen in AI history. During an AI boom, computer scientists and firms invent new techniques that seem exciting and powerful. Tech firms use them to build products that promise to make everyone’s lives easier (or more productive) and investors unleash a geyser of funding. Everyone — including starry-eyed journalists — begins overpromising, gushing about the artificial smarts that will be invented. Humanlike! Godlike! Omniscient!

That level of hype can’t be maintained, though — and at some point the industry starts underdelivering. The AI turns out to be surprisingly fail-ridden. Companies and people that try using it to solve everyday problems discover it’s prone to errors, often quite mundane ones.

Then an “AI winter” begins. Customers stop paying top dollar for AI products; investors close their purses. Journalists begin more critically appraising the landscape. And because everyone feels burned (or embarrassed), things slide into an *overly* negative cycle: Even the computer scientists and inventors with legitimately interesting new paths for AI can’t easily get funding to pursue them. This lasts for years.

There have been two big AI winters so far. Here’s a chart of them …

![A chart of AI winters, showing a rise in interest in the 50s and 60s and 70s, collapsing in the mid-70s, recovering in the 80s and rising to the 90s, then collapsing again, then rising again in the 00s](https://miro.medium.com/max/1400/0*wLse8P2YONLAyWnP.png)

From [“The winter, the summer, and the summer dream of artificial intelligence in law”](https://link.springer.com/article/10.1007/s10506-022-09309-8/figures/1), by Enrico Francesconi

It started in 1956, when AI luminaries at a workshop in Dartmouth predicted that [“every aspect of learning or any other feature of intelligence can be so precisely described that a machine can be made to simulate it”](https://home.dartmouth.edu/about/artificial-intelligence-ai-coined-dartmouth). Almost two decades of work followed, with giddy promises along the way: When [the *New York Times* first reported](https://www.nytimes.com/1958/07/08/archives/new-navy-device-learns-by-doing-psychologist-shows-embryo-of.html) on neural nets that the Navy was working on, the reporter described “the embryo of an electronic computer that the Navy expects will be able to walk, talk, see, write, reproduce itself and be conscious of its existence”. In this early upswing, companies and computer scientists were particularly entranced by the idea of automatic translation of text — something that, if they could get it to work, would be worth billions.

But they couldn’t get it to work. By the early 70s, though, it was clear that those prototypical, early-stage AI techniques couldn’t remotely achieve what had been promised. Machine translation, a clunky mess of hand-written rules, couldn’t grapple with grammar of even moderate complexity. Self-learning machines? Still just sci-fi. AI winter came, investors fled, and research money dried up.

Spring didn’t come until the 80s. By then, most tech firms had given up on overcarbonated dreams of creating “self-learning” machines, and instead built “expert systems”. These were much less ambitious: They were mostly just byzantine if-then kluges that tried to automate decision-making for one (and only one) specific problem. Visa would build one to auto-approve credit-card applications; an airline would build one to auto-route airplanes.

Expert systems had one advantage, which is they actually worked, kind of. But they were incredibly expensive to build, and each was a one-off. Worse yet, they failed catastrophically when they hit an unforeseen edge case. I once heard of a credit-card-application system that mistakenly issued a credit-card to a nine-year-old, because the application (obviously full of lies) listed twenty years of work experience. The programmers forgot to make a rule to verify that “work experience” was longer than “age of customer”. This is the problem of hand-crafted rules: The real world is too damn complex to cover everything. As the failures of “expert systems” became apparent, another AI winter set in.

We’re currently inside the third big boom — we’re in an “AI summer”.

It began in the 2010s, when “deep learning” took off. Neural nets had been around for decades, but in the 90s and early 00s they were considered impractical: Not enough data to train them, training was too computationally intense. “Back in the 90s, people were laughing at us and saying this stuff would never work,” as deep-learning pioneer Geoff Hinton told me last year.

But he and a few colleagues around the world beavered away at it, and in the 00s things improved. The amount of training data exploded (as people posted endless photos online, and endless words of prose too). Processing got cheap and fast. Coupled with with some clever neural-net engineering ideas from Hinton and other pioneers, deep learning in the 2010s became *really* good at doing pattern recognition. You could train a neural net on oodles of pictures, and it became a wizard at recognizing objects. Train it on translated pairs of sentences, and it could — finally! — learn to translate languages.

Train it on massive corpuses of writing? Hello GPT-3 — a bot that can so neatly predict the next probable word in a sentence that it can compose humanlike prose, answer questions, and summarize documents. Train a neural net on tons of art? You get Midjourney. Train it on computer code and you get Copilot.

So money has poured into AI, and startups are launching tons of products that incorporate text-generation or code-completion or picture-generation. [I checked Product Hunt just now and it’s jammed with such warez](https://www.producthunt.com/); here are three …

![A screenshot of three products at Product Hunt — “Read Easy.ai”, “Travelmoji”, and “Copilotly”](https://miro.medium.com/max/1400/1*3FHiAl1Wqh57D7eJQvrlmg.png)

But: Could a new AI winter arrive?

I’ve started wondering, because some of these historic patterns seem to be repeating.

First off, we’ve seen some remarkable snafus by the big chat apps. When Google showed off its chat AI recently (desperately trying to catch up to OpenAI), [the chatbot made huge factual blunders](https://twitter.com/astrogrant/status/1623091683603918849?s=20&t=EIy0QovgsoFRM8phoFk4uQ) — and [the stock market promptly shaved $100 billion off of Google’s value, a 7.8% dive](https://financialpost.com/pmn/business-pmn/google-shares-dive-7-8-after-ai-chatbot-bard-flubs-answer-in-ad). Then Microsoft debuted its new Bing product, augmented with ChatGPT — which not only [made countless factual mistakes (including weird ones, like insisting it was actually still 2022](https://simonwillison.net/2023/Feb/15/bing/)), but got super creepy and defiant when confronted with its errors. It’s not surprising to many, including myself, that huge language-models make massive factual mistakes; word-prediction is a powerful technique, but some computer scientists and cognitive scientists suspect it’s only a small part of how true *reasoning* works in humans.

On top of these language-model failures, self-driving cars are increasingly in trouble. [The National Highway Traffic Safety Administration announced a recall of Teslas equipped with “Full Self-Driving Beta”](https://www.nytimes.com/2023/02/16/business/tesla-recall-full-self-driving.html), the software designed to automate driving. Tesla’s software, the government said, poses “an unreasonable risk to motor vehicle safety based on insufficient adherence to traffic safety laws” — which is to say, it’s prone to unpredictably making wild and dangerous moves.

So we’ve got the “underdeliver” part of an incipient AI winter.

We’ve also had “overpromising”. Consider self-driving cars, which inventors have for a decade insisted will arrive any day now (“this is a *trillion dollar* industry,” as one computer scientist told me in 2017), while reporters effervescently pondered their potential impact ([myself included](https://www.motherjones.com/environment/2016/01/future-parking-self-driving-cars/)). Meanwhile, pioneers of large-language-models have insisted that if they keep making their models bigger and feed them more data, the models will transform into genuinely reasoning machines. (One founder of OpenAI [even posited that GPT-3 is already “slightly conscious”](https://www.sciencetimes.com/articles/36093/20220214/slightly-conscious-ai-existing-today-according-openai-expert.htm).)

Such hyperoxygenated promises collide pretty hard with the reality of machines that don’t know what year it is (and which get pissy when you correct them). It’s almost kind of hilarious. Society worried we’d get remorseless all-seeing Skynet annihilators of mankind — but what we’ve actually got are glad-handing bullshit artists that can’t be bothered to get trivial facts straight.

I’m gonna dodge the hard call. The truth is, I have no idea if an AI winter is coming.

After all, even if today’s chatbots turn out to be a bubble, deep learning *—* considered as an industrial technique — remains extremely valuable, in narrow domains anyway. It’s fantastic for building autorecognizers and categorizers. That alone is worth billions. And it’ll remain worth billions, even if OpenAI never manages to get ChatGPT to reliably do middle-school math. So the idea that the AI industry will *fully* deflate seems unlikely.

But there could be a significant correction. Enough people might decide that large-language models are fun to play with (*“write me a shakespearean sonnet about flat-earth theory!”*) but dangerously unreliable for helping to run their businesses. Or a flood of SEO-optimized bullshit online could so clot the Internet with intellectual fungus that it gives AI a bad public rap overall. That could wipe out a lot of capital and investment. Self-driving cars are, again, an instructive example: Despite investors having poured [tens of billions](https://www.bloomberg.com/news/features/2022-10-06/even-after-100-billion-self-driving-cars-are-going-nowhere) into the field, virtually no fully self-driving cars are on the road, and [self-driving-industry startups that have IPO’d in the last two years have lost 81% of their value](https://www.theregister.com/2022/10/18/selfdriving_tech_values/). (It’s also worth noting that lawsuits are targeting a core process in [art-making AI](https://www.theverge.com/2023/1/16/23557098/generative-ai-art-copyright-legal-lawsuit-stable-diffusion-midjourney-deviantart) and [code-generating AI](https://www.theverge.com/2022/11/8/23446821/microsoft-openai-github-copilot-class-action-lawsuit-ai-copyright-violation-training-data), arguing that their creators had no right to hoover up scads of online art and code for training purposes.)

Yet (here I’ll zig again) even a serious crash wouldn’t spell the end of AI by any means. The field has recovered twice. It’d recover again. If it turns out that large language models — as they’re currently crafted — are doomed to error and unreason, good computer scientists will eventually focus on other techniques. That could include, [as deep-learning critics like Gary Marcus suggest, symbolic techniques for abstraction](https://www.noemamag.com/deep-learning-alone-isnt-getting-us-to-human-like-ai/). Or it could be, [as Geoff Hinton recently surmised, specialized hardware custom-grown for individual neural nets, based on the task at hand.](https://www.zdnet.com/article/we-will-see-a-completely-new-type-of-computer-says-ai-pioneer-geoff-hinton-mortal-computation/)

With AI, one should never say “never”. It’ll keep chugging. But if winter arrives and dumps a pile of snow on the path, the only way forward might be to change course.

Source: [Clive Thompson on medium.com](https://medium.com/@clivethompson/the-risk-of-a-new-ai-winter-332ffb4767f0)
