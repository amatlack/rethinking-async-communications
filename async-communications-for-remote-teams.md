# Rethinking async communications: Principles and practices for remote teams

For a tl;dr version of this document, see [the companion quick-reference guide](./quick-ref.md).

# Purpose and motivation

In 2020, many companies were thrust into remote work almost overnight, reacting to the pandemic without time to plan or adjust. Instead of intentionally rethinking how they worked, most organizations simply moved in-person rituals — like synchronous meetings and constant check-ins — into a virtual space. As a result, many teams found themselves surviving, but not thriving.

But remote work is about more than just location; it’s a mindset shift. Done well, remote work doesn’t just replicate old workflows online — it transforms them. There’s much we can learn from companies like GitHub, which have always been remote-first. Their experience can help us master the art of asynchronous work, allowing distributed teams to collaborate smoothly across time zones, minimizing disruptions, and maximizing productivity.

This document draws inspiration [from GitHub’s experience](https://github.com/github/how-engineering-communicates) to offer practical guidance on improving the quality and efficiency of communication in a remote-first world. These recommendations are designed as a core foundation to help teams move away from defaulting to synchronous practices. Teams are encouraged to adapt them to fit their specific needs, while maintaining a shared “API” for seamless cross-team communication.

As remote work continues to evolve, so too will this guidance. Contributions and improvements are not just welcome — they’re encouraged.

# Guiding principles

Successful remote work requires intentional communication, grounded in the following core principles:

## Be asynchronous first

Asynchronous communication means that there’s a delay between when the sender shares information and when the recipient processes and acts on it. This approach has significant benefits, especially for remote and distributed teams.

Knowledge workers [are most productive](https://en.wikipedia.org/wiki/Flow_(psychology)) when they have large blocks of uninterrupted time. A two-hour block of focus time is not fungible with four 30-minute chunks. Unlike working on an assembly line, for example, when knowledge work is accidentally or intentionally interrupted — whether by a popup, a meeting, or a "hey, you got a sec?" drive-by — there's a significant context-switching cost. Whenever possible, prefer asynchronous methods like code reviews, issue comments, or chat messages over "just in time" communications, such as last-minute meetings. Reserve synchronous methods for moments when urgency or complexity requires it — like for time-sensitive or business-critical tasks.

And there's an added bonus: Asynchronous mediums enable a distributed workflow. There's no "you had to be there" when "there" is online and accessible anytime.

## Write things down

To be asynchronous first as a globally distributed organization, it’s essential to document everything — especially the "why" and the "how" of decisions — in a durable, searchable, and easily accessible format. Workflows should not require anyone to be in a specific place at a specific time to collaborate. One practical way to achieve this is by ensuring that every task, idea, or decision is properly documented, so if someone asks a question, you can point them to the written record.

There are [a number of advantages](https://ben.balter.com/2015/11/12/why-urls/#the-value-of-giving-concepts-urls) to capturing and exposing processes through URLs. Beyond supporting asynchronous and distributed workflows, writing things down serves as a message in a bottle to our future selves and our future peers, recording what decisions were made and why, capturing and exposing process and decision making.

## Make work visible and overcommunicate

Capturing and exposing processes through URLs also helps make your work more visible, which is crucial for effective asynchronous collaboration. So [work in the open](https://ben.balter.com/2022/02/16/leaders-show-their-work/) and proactively share your work to the widest extent practical, ensuring that others can see and contribute when needed. As teams grow, collaboration points become increasingly important to reduce redundancy and avoid duplicated efforts. Information hoarding slows progress — like in any production system, observability is key. If you create something useful, make it accessible so that others can benefit from it too.

Let others opt-in to the context of your work and subscribe to updates. Make it easy for everyone to stay informed by adding concise summaries (e.g., a tl;dr) at the beginning of communications to ensure your main points get across.

## Prefer tools that capture and expose process

The best way to work openly and make your work visible is by using tools and workflows that naturally capture and expose processes. Choose tools that support transparency and collaboration, but only use them when they make sense (and don’t use them when they don’t). The key is to favor systems that allow others to easily access and understand the context of decisions.

If decisions are made through more synchronous means, such as live meetings or chats, be sure to document and capture the outcomes in a durable, accessible format for future reference.

## Embrace collaboration

Software development is a team sport. Proactively seek input and feedback early and often. Document not just decisions, but also the context, tradeoffs, and consequences, and do so in a way that allows stakeholders to actively participate in the decision-making process.

Simply posting an update or opening a task isn’t inherently collaborative. Here are some tips for more collaborative decision-making:

* Seek feedback _before_ the decision is made (don't make a decision and then ask for feedback on it). Statements should be more in the form of "I intend to" rather than "I decided".
* Documents should be a collaboration between authors (decision-makers) and stakeholders to agree on what the problem is, what constraints exist, and how (and when) the problem is going to be solved.
* Documents should live in a location where they are easy to discover (remember to make work visible!).
* Documents should have sufficient detail, including things like availability, rollout strategy, scaling patterns, and timelines.
* Be generous with links in documents, as they are often part of a larger conversation. It's helpful to link to relevant discussions, tasks, or other artifacts that provide more context to a decision.

## Foster a culture that values documentation maintenance

Keeping documentation up to date is as important as creating it. Whenever teams are reorganized, or when code and processes change, ensure that all relevant documentation is updated, along with any ownership metadata.

Managers might need to allocate time for documentation updates in team work plans, but this investment will save time in the long run. If someone encounters outdated or incorrect documentation, confidence in internal resources decreases, and valuable time is wasted trying to locate accurate information. Leave things better than you found them: If you come across outdated documentation, submit a request to update it or notify the responsible team to address the issue.

That said, document maintenance shouldn’t become a burden. If the effort to maintain a document outweighs its benefits, consider simplifying or removing it.

## Communicate openly, honestly, and authentically

We are humans, and we appreciate communication that is transparent and direct so that we don't have to spend time trying to extract meaning from heaps of corporate buzzwords. Say what you mean, in a respectful way, and listen to understand others. Keep in mind that communication patterns and tone can vary across cultures, so ask for clarification before making assumptions about intent.

For more complex communications, such as announcing a new process or tooling change, anticipate the questions your colleagues might have and consider providing an FAQ. Be open about what you know and what you don’t — it's better to say "we don’t know yet" or "we can’t answer this right now" than to pretend the question doesn’t exist.

### Strive for inclusivity

Strive for inclusivity in all aspects of communication. Use universally understood date formats, avoid acronyms without context, and be mindful of time zones when scheduling meetings or sending messages. Use inclusive language, and make sure your communications are accessible by adding alt-text for images, using semantic headings, and writing descriptive link texts.

### Use emoji

Emoji are the facial expressions of online communication. They help convey tone, celebrate wins, and make interactions more inclusive — especially for those who might find tone harder to read in text, like the neurodiverse or non-native English speakers. Communication should be professional and respectful, but it doesn’t need to be overly formal.

Don’t worry about using the "wrong" emoji — creativity is welcome! For accessibility, ensure that custom emoji have semantically meaningful names, as some people might convert emoji to plain text.

Lastly, using emoji reactions is a great way to acknowledge receipt asynchronously. You’ll often see people "ACK"-ing a message to **ack**nowledge they’ve seen it, even if they can’t respond right away. (Yes, it’s a nod to the SYN-ACK handshake in networking!)

## Remember practicality beats purity

Remember that these are guidelines, not rigid rules. Process is there to serve the outcome, not the other way around. Focus on intent over strict adherence to mechanics, and always encourage pragmatism.
