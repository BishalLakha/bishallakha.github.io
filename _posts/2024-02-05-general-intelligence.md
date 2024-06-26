---
layout: post
title:  Generalization Ability as a Criteria of Intelligence
date:   2023-02-05 21:01:00
description: Essay from Phil 497 course at BSU
tags: ai 
categories: essay
---
Intelligence is the ability of an agent to pursue and achieve a goal: be it by imitating humans and fooling them as in the Turing test (Haugeland, 1989,6)  or by understanding knowledge  (Haugeland, 1989,11). However, Chollet refuses the idea of goal-specific criteria for intelligence and proposes a new definition “The intelligence of a system is a measure of its skill-acquisition efficiency over a scope of tasks, with respect to priors, experience, and generalization difficulty.” (Chollet, 2019,27). I consider Chollet's definition of intelligence tackles vagueness and objection associated with the goal-specific definition of intelligence and provides better criteria for intelligence.

To achieve a goal an agent needs to overcome different barriers. The number and difficulty vary according to the difficulty of the goal but still, the agent needs to go through it in order to complete that particular task. The agent can overcome the barrier only if the agent can solve the problems associated with the barrier. To solve a problem an agent needs knowledge about a problem and find reasons and logic for its solution. Once it tackles all the barriers and reaches the goal, it should also know that the task is done. Since it needs, planning, reasoning, and awareness of the situation to carry out this process,  the agent can be considered intelligent. If we consider passing the Turing test, a test based on a game called ‘imitation game’ in which a computer tries to fool a human interrogator acting as a human (Haugeland, 1989,6), as a goal of an agent, the agent has barriers to understanding the language, context, and meaning and then generates a suitable answer. All these tasks require reasoning, understanding, and logic, and if the agent is able to pass the test we can consider it to have the ability to reason, understand and be logical which consequently makes it appropriate for considering it intelligent as intelligence encompasses those traits. 

The problem with goal-centric criteria is that such agents can be programmed with the ability to solve that specific task which can make all the steps taken by the agent to overcome all the barriers associated with the task mechanical, instead of intelligent. Chollet (2019,19) writes that

<blockquote>
    When a human engineer implements a chatbot by specifying answers for each possible query via if/else statements, we do not assume this chatbot to be intelligent, and we do not expect it to generalize beyond the engineer’s specifications. Likewise, if an engineer looks at a specific IQ test task, comes up with a solution, and writes down this solution in program form, we do not expect the program to generalize to new tasks, and we do not believe that the program displays intelligence – the only intelligence at work here is the engineer’s.
</blockquote>

Even when such systems use learning-based algorithms instead of hard-coded logic they can still lack intelligence as these systems might be able to handle situations it has not handled themselves but those situations are encountered by the developer of the system. Chollet (2019,19) adds

<blockquote>
    A learning machine certainly may be intelligent:  learning is a necessary condition to adapt to new information and acquire new skills. But being programmed through exposure to data is no guarantee of generalization or intelligence.   Hard-coding prior knowledge into an AI is not the only way to artificially “buy” performance on the target task without inducing any generalization power. There is another way: adding more training data, which can augment skill in a specific vertical or task without affecting generalization whatsoever.
</blockquote>

To avoid this problem Chollet proposes the generalization strength of an agent as a better criterion for intelligence. Generalization strength in this context means flexibility and adaptability to acquire new skills to tackle unseen tasks in an unseen environment. To elaborate, if we consider two agents which have a similar set of knowledge and a similar amount of past experience, the agent with higher intelligence will end up with greater skills. The generalization he is proposing is a developer-aware generalization which is the ability of a system, either learning or static, to handle situations that neither the system nor the developer of the system has encountered before (Chollet, 2019,10). 


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/blogs/general_intelligence1.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Wozniak’s coffee cup test (Generated using ChatGPT)
</div>



In addition to that, the goal-centric criteria for intelligence can have limitations of incomparability. Intelligence can be manifested in various forms and a single set of goals might not be able to encompass all the differences. For instance, a Turing test is solely dependent on language-based abilities which can incorporate other kinds of perceptual intelligence. Along with that, a system good at one goal might not be compared to another system. How can one compare a Go-playing agent with an image-generating system? Which one is more intelligent if they can be considered intelligent? Adopting generalization ability as a criterion can address this challenge. First of all, generalization can have varying degrees enabling classification and comparison of intelligence. An agent can absolutely lack it, or have a local generalization - good at a single or well-scoped set of tasks, or have a broad generalization ability - the ability to handle a broad range of previously unencountered tasks and environments (able to pass Wozniak’s coffee cup test-without prior knowledge of the house, an agent locates the kitchen and brews a pot of coffee. Which means it locates the coffee maker, mugs, coffee, and filters. It puts a filter in the basket, adds the appropriate amount of ground, and fills the water compartment. It starts the brew cycle, waits for it to complete, and then pours it into a mug. ),  or have an extreme generalization - the ability to handle the entire new task which only vaguely or abstractly resembles the previously encountered task. Secondly, this criterion is not limited by the type of input taken by the system and the output it generates freeing it from the limitations faced by the previous criterion. Lastly, it frees an agent from the necessity to pretend to be human or follow a trait of a biological system to tackle new situations and tasks- it can conjure its own approach and no matter how alien it is, if it can handle the situation then the agent can be considered intelligent. 

To sum up, I think Chollet's objection to the goal-centric criteria of intelligence is valid as goal goal-centric approach has limitations possibility of being programmed and the inability to be comparable and distinguishable with intelligent systems consuming a wide range of input and generating a wide range of output. The generalization ability-based approach better encompasses the multidimensional aspects of intelligence and is system and task-independent making it a better alternative to goal goal-centric approach. It also presents intelligence as a spectrum instead of a binary feature enabling it to incorporate and classify various forms of intelligence. Moreover, despite defining generalization as a spectrum and thus intelligence, this approach still allows distinguishing the absolute absence of generalization and the presence of a varying degree of generalization capabilities in an agent. 

<hr>

<h3>References</h3>

Haugeland, John. 1989. Artificial Intelligence: The Very Idea. MIT Press.

Chollet, François. 2019. [“On the Measure of Intelligence.”](http://arxiv.org/abs/1911.01547) arXiv [cs.AI]. arXiv. 
