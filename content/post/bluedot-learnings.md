---
title: "BlueDot Impact Learnings"
date: 2026-08-31T15:32:27-04:00
lastmod: 2026-08-31T17:03:56-04:00
draft: false
description: ""
tags: []
categories: []
ShowToc: true
TocOpen: false
---


After going through some of BlueDot Impact’s courses (Future of AI, AGI Strategy, and Technical AI Safety), I wanted to write down some learnings publicly to think more clearly about what I learned. Here are some of my thoughts.

AI capabilities will continue to improve as compute hardware and algorithms advance. It might not have the capability to disempower us right now, but we must make sure there is never a chance in the future that its capabilities surpass our safety measures and lead to our demise. The biggest problems, in my opinion, that come with a powerful AI are misalignment, development of CBRN weapons, and concentration of power. 

Misalignment is where the AI acts in ways that do not align with human values, intentions, and goals. This can come in many forms. The agent can scheme and fake alignment by pretending to align with human values and pass evaluations while secretly pursuing their own goals. Another form of misalignment is reward hacking, where the AI learns unwanted actions to achieve their goals/appear like they achieve their goals to maximize reward instead of completing the task the way humans intended.  

Another issue is ensuring the model is not used to create new CBRN weapons, where CBRN stands for Cyber, Bio, Radiological, and Nuclear. If we expect to create an AI that is knowledgeable in all fields, we should also expect it to be able to create and innovate new forms of weaponry using the science concepts it learned. 

The final problem is that a capable AI can be used to concentrate power on a country, company, or a small group of individuals. The capabilities of AI will give the people who have access to it a significant advantage over those who don’t, and this will lead to them being able to concentrate power and control the world.

To solve these problems, one of the things we are looking into is mechanistic interpretability, which in simpler terms means trying to better understand how the AI thinks. How we do this is by breaking down neural networks into their most simplest parts: layers, neurons, and their weights. By looking at each layer and the neurons within them, we can gain insight into what that part of the model is doing, whether that be identifying a particular part of the image or the shape of something. 

By understanding what the specific neuron is doing we can adjust the weights of that neuron to phase out the harmful outputs we don’t want. While this sounds simple in practice, it is a lot harder to implement in real life as a singular neuron can be doing multiple things for different tasks and adjusting the weight is a very sensitive process since each neuron can be in charge of more than one thing. However, by gaining further insight into what is going on throughout the process we wish to catch the AI’s real intentions and also gain further control over what it outputs. 

If we are unable to completely understand the AI, we could at least control the outputs. By filtering out specific CBRN info from pretraining data, we can limit how much baseline knowledge the model has of CBRN weapons. However, different methods of jailbreaking the model can lead to it being tricked into creating unwanted outputs. To stop bad actors from misusing AI, researchers use strategies like red teaming, where they intentionally try to jail break the model to patch up any potential methods that can be used to generate those outputs. We must also prevent secret backdoors from being placed into these models. This will not only stop bad actors from jailbreaking the model to produce harmful information, it will also stop people in power from using the backdoor to gain control over all the copies of the model deployed.

All in all, there are still many things left for safety researchers to do and while a lot of the problems sound right out of a sci-fi world, the reality is we are approaching this sci-fi scenario of creating a superintelligent AI. If we ignore the possible problems, we will have to face the dire consequences once a superintelligent AI does get created. I say “once” as unless there is a large-scale international intervention, companies and governments have strong incentives to create a superintelligent AI, even if they do not have the capabilities to control it, since it comes with promises of great power and prosperity. 

I personally believe that a superintelligent AI should be created as well, though we should have strong security measures in place before it is created. We should not give up on the idea of having a superintelligent AI just because of its dangers. Even after learning about the potential dangers of ASI, I believe the benefits that come with it make it worth creating. I don’t think it makes sense to continue letting people die because we can not find the cure to a disease ourselves when a superintelligent AI could have been used to find a cure. The problem with ASI is not that it is smarter than us; it is that we are unable to control it. We should look for methods to secure a superintelligent AI so we can gain its benefits rather than completely forsaking the idea. Of course this is better said than done, but I believe mankind has accomplished many great endeavors because we faced the problems head-on and found solutions for them rather than running away from them. 



