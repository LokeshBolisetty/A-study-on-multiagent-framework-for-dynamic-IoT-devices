# The internet of Things and Multiagent systems
MAS - Multiagent systems

Iota - IoT enabled application

Current MAS research is not compatable with modern distributed computing. 

Agent based models also enable the abstraction of important data which makes this a social process and enables information goverance. 

Challenges relating to asynchronous communication and decentralized enactments have been ignored until now. So we need to develop on decentralized multiagent systems. 

IoT shows a natural synergy with mobile computing. Very often IoT devices operate in a low power mode while the mobile device acts a high power node for doing the computations. 

In today's IoT systems, there are many agents which help in making a decision. But there is no multiagent system. Each agent uses a shared database where the information will be gathered, processsed and the required output will be actuated. This is all a single locus of control. 

However in a decentralised system, each agent contributed some information and consumes some information and provides services to others. 

They interact with each other on the basis of interaction protocols: rules of encounter. 

This interaction protocol infact specifies a MAS. Specifying an application in terms of a protocol is the key to decentralization. 

# Asynchrony and decoupled enactment

## Challenges in communication between agents
1. Messages may be lost
2. Messages may be delayed
3. Messages may be reordered
4. Duplicate messages may be received. 
5. Different agents would observe different messages in incompatable orders. 
6. Due to concurrency, distinct instances of a protocol may be interleaved

All these can cause the agents to end up in incompatable states during a protocol enactment leading to a failure in interoperablity. 

# Goverance: Security, Accountability and Privacy
An Iota has to work in a manner that it meets the stake holder's expectations. Abstraction of crucial information and its access to only its stakeholders is an essential requirement because multiple agents now hold the data communicating it with each other. 

All the agents are governed by an Org which provides a computational basis for representing autonomy and accountability. 

* Autonomy - Ability to take decisions on its own
* Accountability - The agent may be calle upon to account for its actions

It is important to note that the current notion of traceability is neither necessary nor sufficient for accountability. 

# MAS vs Unitary computation models
## Agents as service endpoints
* MAS provides ways to deal with autonomy and heterogeneity. 
	* Heterogeneity mentions that the information modesl underlying the agents need not be in agreeement. 
* MAS has developed approaches for trust. (Not clear) 
* Collective intelligence helps in better decision making. 
##  Decentralization via information protocols
* A decentralized MAS refers to a a MAS in which the agents can maintain their goals separately and privately and autonomously act as they deem appropriate. 
* Here we assume that the hardware supports all that we require i.e the agent does not wait to send a message because of the infrastructure though they may wait if the application wants it to. This brings the notion of asynchronous communication where an agent can send a message to another agent at any point of time and it can use the message at any point after recieving the message. 
* one of the main concerns in a decentralized system is that the information flow is asynchronous. The only currency of the MAS being information makes the instructions order differently.

## Norms
Norms can be seen as a way to capture accountability relationships between two parties. 

## Meaning based protocols
* A higher level challenge than information protocols is to assign meaning to the information exchanged. 
* Meanings are commonly expressed in terms of norms eg: Authorization, prohibition and power

# Scope for research
1. Programming models for agents
2. Interaction-oriented software engineering
3. Enlightened governance
