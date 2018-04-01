---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
# Agile

## On the Shoulders of Giants
I have been inspired by Agile for almost two decades now.  What inspires me is not the way that it is implemented but that a complex problem has been distilled into a few simple but powerful statements.

* Individuals and interactions over processes and tools
* Working software over comprehensive documentation
* Customer collaboration over contract negotiation
* Responding to change over following a plan

-- [Reference](http://agilemanifesto.org/)

This manifesto makes few assumptions.  It simply posits that these guiding principles are an effective means of executing on goals.  

Around these principles, several frameworks have been constructed to help create an efficient working process.  They are used frequently and to good effect across the world in a variety of environments.  But because Agile is, by definition, a process that does (and should) adapt to your organization, it is not uncommon for third-party practictioners to come in and assess your organization in order to make recommendations that are ideal for it.  

## Organizational Frameworks
I cannot help but wonder if there is a framework that is well-defined, abides by Agile principles but still flexible enough to adapt automatically to the uniqueness of each organization.  Can we create a framework that has flexibility built in?  

Over the years of developing and managing, I've started to see some similarities between software frameworks and organizational ones.  

### Software 
Software frameworks that are rigidly defined and heavy like Ruby on Rails or Django allow developers to very quickly create a useable application handling the vast majority of the function that they would need (and more in most cases).  Arguably, these frameworks are sometimes considered too heavy handed for small projects.  Additionally, they perform some magic under the hood that can cause unexpected behavior if you veer too far from that framework's best practices.  On the other hand, they commoditize basic functionality in an effort to give developers time to work on those things that differentiate their project from others.

Closer to the other end of the spectrum are micro-frameworks that do the bare minimum and are essentially a very light wrapper around a language -- Flask and Express come to mind.  They are extremely quick to get up and running for very simple sites but attempt to make few assumptions about you might need.  This gives you the freedom to customize more of the framework, giving you more control and leaving a lot up to the development team as their needs grow.  Because there is more than one way to extend this framework, "best practices" become more diversified and less clear.

As with most things, there's no clear winner here.  It's just a matter of understanding what you're getting and what you need and make sure you match the two correctly.

![monolith vs. components](./assets/monolith_v_components.png)

### Organizations
If you replace "software" with "organizations" you can see that there are a lot of similarities.  There is one huge difference of course which is that organizations are made of people, not code.  And people are, thankfully, not automotons and therefore more chaotic.  Good for diversity and innovation, but not good for predictability. 

Process can act as a suppressor of diversity and, as such, has gotten a bad name.  Actually, even the name suggests that individuality is being stripped in the service of predictability.  

For that reason, let's think of Augur as an *Ecosystem* of which people are an important part.  And like any ecosystem, there are rules, but not more than what's needed to provide some predictability without suppressing creativity.

# Augur Ecosystem

    ec·o·sys·tem
    ˈēkōˌsistəm/Submit
    
    noun - a biological community of interacting organisms and their physical environment.
    (in general use) a complex network or interconnected system.    

The Augur Ecosystem is an attempt to define the rules of a complex network of interconnected systems that make up an organization.

At its most basic, the ecosystem is made up of:

* Environment
* Workers
* Customers

Each of these has more detail which we will detail below.  But the most important thing to remember is that Augur is an attempt to define the relationships between these entities while making as few assumptions as possible about each.

## Environment

### Workflows
The environment is defined by the cause/effect relationships between entities within the ecosystem.  In the natural environment, photosynthesis is a crucial workflow that exists in our ecosystem on which all life on earth depends.  In the same way, Augur Ecosystem contains workflows of its own.

    Augur Entity #1 --> Workflows

Augur makes no assumptions about the workflows that define an organizations environments but does insist that they be well-defined and reflect reality as closely as possible.

### Groups
In the natural environment we have deemed three domains and six Kingdoms that encapsulate all life on earth.  Similarly, Augur has created a grouping mechanism and it simply called _Groups_

    Augur Entity #2 ---> Groups

Augur makes no assumptions about the groups that exist in your ecosystem only that all people are represented by at most one group.

### Teams
As with mankinds taxonomy, there are of course subdivisions of subdivisions.  In the same way, groups are divided into teams that have unique properties but share a common group.

    Augur Entity #3 ---> Teams

Augur makes no assumptions about the teams that exist only that they belong to only one group and that each group has at least one team.

### Staff
Finally, we arrive at the leaf node of our shallow taxonomy - the person.  No explanation needed here.

    Augur Entity #4 ---> Staff

A staff member is one person who is on one team.

### Summary

So the Augur Ecosystem is made up of an environment that contains Groups, Teams and Staff who are interconnected via one or more workflows. 