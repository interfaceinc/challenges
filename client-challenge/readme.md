# Client Challenge

_This challenge is part of the engineering hiring process at
[Interface](https://interface.inc)._

## Why this challenge?

Interface is operating with a small team of dedicated & talented people. We are
looking for seasoned engineers with a deep technical knowledge, strong
understanding of their technical stack, and excellent product intuitions to join
our team.

This exercise has been designed to give a glimpse of what it is like to build a
messaging app, and the kind of technical challenges we face and care about.

We expect you to spend 4-6 hours on this challenge, simulating real-world,
time-boxed work.

## Instructions

You are tasked with the implementation of a messaging app that allows the user
to communicate (send and receive text messages) with bots, each in their own 1:1
chat.

A companion server is available for you to use. You can read more about it in
[`./server`](./server). Its documentation contains information on how it can be
run, and what kinds of API endpoints & entities are available.

You can choose a target platform of your choice for this challenge: one of iOS, macOS,
Android, or web.

Functional requirements:

- [ ] The app should start on a screen showing the list of all chats
- [ ] The app should allow opening each chat individually
- [ ] The app should allow sending messages to a chat
- [ ] The app should reflect the messages sent to and received from the server
- [ ] The app should be resilient to bad network conditions (drops & timeouts)

## Bonus

Some topics that we find interesting to dig:

- [ ] Make the app work offline using a persistence layer of your choice
- [ ] Make the app idempotent in regards to what you send and receive
- [ ] Integrate a splashscreen to hide chats while the app is loading
- [ ] Add support for optimistic sending to give instantaneity in the UI
- [ ] Add support for a local read/unread indicator
- [ ] Avoid to block changing states so the app feels fluid & snappy
- [ ] _Anything_ that you feel could improve the UX!

## Design

We have prepared a design to help you during this challenge. You will also
receive the Figma link along with the challenge instructions.

![design](./design.png)

## Challenge Review

We know you only have a limited time alloted to deliver this challenge, and thus
will have to prioritize what you work on. A few things that are important for us
and that will be considered during the review:
- **documentation**: is the readme clear? are important parts of the code
  documented?
- **impact**: what did you consciouslly decided to prioritize?
- **maintainability**: is the code well-structured and easy to read/evolve?
- **robustness**: is the code tested or easily testable? are edge-cases
  considered? is static analysis leveraged?

***

Good luck, and enjoy!
