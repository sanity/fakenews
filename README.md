# Reducing the influence of false information disseminated through social media

#### 1. Overview

##### 1.1 The problem

The excessive promulgation of misleading information through social media, leading to polarization, lack of constructive dialog, and mutual distrust between increasingly disjoint subsets of the population, which could, if unchecked, lead to dangerous social destabilization.

##### 1.2 Motivation

While I've been thinking about this issue in one form or another since before I had the idea that became [Freenet](https://en.wikipedia.org/wiki/Freenet) almost 20 years ago, the political instability that became evident to me in 2016 (but others far before this) makes this problem urgent.

##### 1.3 Purpose of this document 

My purpose here is to summarize my thinking so-far on this problem.  Unfortunately, I do not yet have a solution but I think I am directionally correct.  As part of this I will discuss some potential solutions I’ve ruled out and the reasons I’ve ruled them out.  My hope is that these reasons could form part of a set of design requirements to guide further exploration of the solution space.  

I also hope to persuade readers that a good solution does exist to this problem, but it won’t be easy and probably won’t be obvious.  A bad solution to this problem could be far worse than no solution at all, so a high degree of rigor is warranted.

##### 1.4 What the problem isn't

I think it's critical not to associate this problem with any specific political or social movement.  Firstly, because this would make broad acceptance impossible (it would correctly be perceived as Orwellian).  Secondly, and even more importantly, I don't think we'll find a good solution if we frame the problem that way.

#### 2. Necessary and desirable properties of a good solution to this problem

I think I've identified some ways that any solution can be evaluated, some ways that something could appear to be the solution but actually make things much worse, and perhaps some directional hints about where the solution might exist.

##### 2.1. The solution must pass the "Galileo test"

The system cannot simply suppress information that is provocative, because the most important ideas are always provocative the first time people hear them.  A system that suppresses speech just because it is provocative is dangerous for our democracy.  

###### 2.1.1. It is in Facebook and Twitter's economic self-interest to find a good solution to this problem

Social instability is an existential threat to the long-term economic interests of Facebook and Twitter.  I think this alignment between the public interest and the private interests of today's largest social networks may be reason for optimism.

##### 2.2. The system probably shouldn't rely on "security through obscurity"

Well-designed systems don't rely on keeping their operation a secret to be effective.  If they do, then anyone that knows or figures out the secret will have an unearned advantage in the marketplace of ideas, and that is dangerous for our social cohesion, and for the long-term interests of Facebook and Twitter.

Consequently, any solution to this should be published in the scientific literature, particularly if it is actually deployed, but preferably before it is deployed.  It is in both the public and the social network's private interests to do this.  This should be the mindset of the team tasked with solving this problem, they should think of it as pure research, despite its real-world importance (or, perhaps, because of it).

##### 2.3. The system should not treat truthfulness as an attribute of people or organizations, because nobody is objective on every topic at all times

For example, imagine we designated certain organizations as "ground truth", and then tried to identify and suppress contradictory information.  This would be dangerous because it's impossible to make any such designation without imposing our own biases, and everyone has biases even if we think we don't (actually, especially when we think we don’t ;)

Having biases is ok, but using the power of Facebook's newsfeed to impose them quietly on everyone else is not ok, regardless of who is doing it or how noble their intentions.  We must have a free and diverse marketplace of ideas.

It may be tempting to try to come up with objective criteria to designate organizations as trustworthy, but any accurate criteria will find that no person or organization is trustworthy at all times on all subjects (which we already know), or we'll have picked bad criteria.  That's exactly the situation we must avoid.

Suppression of a good idea is much worse than promulgation of a bad idea.

Promulgation of a bad idea is a harm that can be remedied through individual skepticism and/or the subsequent promulgation of a better idea.  In contrast, there is no equivalent remedy for suppression of good ideas as long as that suppression continues.

Therefore, any solution must weigh both interests proportionate to the potential harm of each, recognizing this imbalance.

#### 3. Some thoughts on the actual cause of this problem

### 3.1 Agreeableness

Agreeableness is one of the [five major dimensions](https://en.wikipedia.org/wiki/Big_Five_personality_traits) of personality structure.  Agreeable people seek consensus, and dislike conflict.  They tend to be pleasant to be around, and are less likely to be skeptical of what others say.

Disagreeable people tend to get into debates with others, which can sometimes cause frustration.  However, these people also tend to point out when the emperor isn't wearing any clothes - which is an essential role in any team or society.

The best teams have a balance of these two personality traits, because even though they are opposites, they are *complimentary*.  Too many disagreeable people and your team can spend too much time arguing and be insufficiently collaborative.  However, too many agreeable people and bad ideas might not get shot down as quickly as they deserve to be.  Balance is key.

##### 4.2 Hypothesis

Using Facebook as an example, I posit that their current algorithm creates a bias towards agreeability in what people see in their newsfeeds.  There is the obvious fact that people frequently unfriend people who say stuff they disagree with.  But I suspect Facebook's (largely opaque) newsfeed algorithm magnifies this effect significantly, perhaps because one of its design goals is to reduce the likelihood of people unfriending each-other.

An expected consequence of this would be that people find themselves in ideological echo chambers where they only see opinions they agree with<sup>1</sup>, and it turns out this is precisely our current situation, which lends a little more weight to my hypothesis :)

So whatever solution we come up with would figure out out how to mix in the right amount of disagreeability for a healthy marketplace of ideas.
 
This is a hard problem but I really believe it is solvable, and the most important part of coming up with a good solution is to frame the problem the right way, which I hope this document helps with.

<sup>1</sup> This echo-chamber may permit caricatures of dissenting opinions - but these don't help, they are also "fake news".

#### 5. Feedback

This is a "Request for Comment", and I will take comments on this document and incorporate feedback.  I'll also accept any pull request which I think will improve the document.  

My preference is that any feedback be delivered in a public forum, but it doesn't have to be attributed, and I will endeavor not to attribute anyone without their permission.

#### 6. About me

Ian Clarke is a Computer Scientist and Entrepreneur, with a track record of both technical and business innovation, and an outspoken thinker and activist on issues relating to freedom of speech, intellectual property law, and technology.

Ian is best known as the founder and coordinator of the Freenet Project; designed to allow true freedom of communication, Freenet was the first decentralized anonymous peer-to-peer network, and a precursor of the “distributed hashtable” data structure.

[More info on Ian](http://blog.locut.us/about/).

#### 7. License

This document is released under [The GNU General Public License v3](https://www.gnu.org/licenses/gpl.html)
