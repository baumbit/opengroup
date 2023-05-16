# OpenGroup

* This is a draft *

Note: To understand OpenGroup you probably first have to fully grok [PeerCuration](https://github.com/baumbit/peercuration).

## TL:DR
An OpenGroup is a list of identifiers (public keys) of entities (people, bots), which is provided by the Grouper (the entity creating the list). Such a list can be cloned and mutated by anyone, thus creating a new OpenGroup. This simple mechanism makes it possible for a group of entities, to filter and sort a stream of data, which in combination with [PeerCuration](https://github.com/baumbit/peercuration) makes it possible for a group of people to self organize. 

## Why?
In a PeerCuration system, there is no central administrator/moderator. Because of its open and fluid nature, there are not really any formal groups (such as sub Reddits or Facebook groups) either. Yet, one could argue that there is value in grouping conversations, so as to strengthen the bonds within as an example a community.

## An example of an OpenGroup
Take a “Music festival” as an example. People that may or may not know each other arrives at a physical place and then spend a few days together. There could be value in letting people bond before the event (enabling drive pooling, etc), communicate during and also after the event (ask if someone found the missing backpack, etc). You get the point.

In a peer curated system this grouping mechanism could be achieved by someone (one or several entities) becoming a Grouper. Anyone can become a Grouper, by creating a list of Members of the group and making it available. In a Music festival the natural Grouper is the organisation setting up the festival, because they have the list of all the people who bought tickets. But note that once the list is public, anyone could become a Grouper by cloning, managing and serving such a list.

Since anyone can partake in the grouped dialog, there is no hard border between those within the group and those outside. It’s simply the curation by the Grouper and the group members, that keeps the dialog focused. Hence the name, OpenGroup.

## Clarification
It’s an easy concept to understand, but takes a longer time to fully grok. Imagine a PeerCurated global network as a group. Following everyone and consuming the content created by everyone, is simple not possible for a human because it takes to much time. Now imagine drawing a circle around your family, or perhaps the people living on the same street as you, or the people in your sports team and creating a group of these people. Now your app can filter all the content, such that the content created by these people gets the highest priority and content from other entities on the messaging network gets less. Content originating from outside the group, but which the group never the less find have great value, would still penetrate into the group dialog. And that is how a group can be created, without having to close the group of from external sources. 

With OpenGroups the openness and dynamics of the PeerCuration network is preserved, while keeping the group intact.

## ClosedGroups
It’s possible to imagine that the Grouper makes encryption keys available, which only the member can use to decode what other members are writing in the now encoded group messages. But note that it’s always possible for someone to make such decryption keys public and/or copy+paste decrypted messages, so this solution would probably only work for smaller and tightly nit groups.

