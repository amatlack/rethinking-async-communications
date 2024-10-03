# Rethinking async communications: Principles and practices for remote teams

For a tl;dr version of this document, see [the companion quick-reference guide](./quick-ref.md).

# Purpose and motivation

In 2020, many companies were thrust into remote work almost overnight, reacting to the pandemic without time to plan or adjust. Instead of intentionally rethinking how they worked, most organizations simply moved in-person rituals — like synchronous meetings and constant check-ins — into a virtual space. As a result, many teams found themselves surviving, but not thriving.

But remote work is about more than just location; it’s a mindset shift. Done well, remote work doesn’t just replicate old workflows online — it transforms them. There’s much we can learn from companies like GitHub, which have always been remote-first. Their experience can help us master the art of asynchronous work, allowing distributed teams to collaborate smoothly across time zones, minimizing disruptions, and maximizing productivity.

This document draws inspiration [from GitHub’s experience](https://github.com/github/how-engineering-communicates) to offer practical guidance on improving the quality and efficiency of communication in a remote-first world. These recommendations are designed as a core foundation to help teams move away from defaulting to synchronous practices. Teams are encouraged to adapt them to fit their specific needs, while maintaining a shared “API” for seamless cross-team communication.

As remote work continues to evolve, so too will this guidance. Contributions and improvements are not just welcome — [they’re encouraged](./github/CONTRIBUTING.md).

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

- Seek feedback _before_ the decision is made (don't make a decision and then ask for feedback on it). Statements should be more in the form of "I intend to" rather than "I decided".
- Documents should be a collaboration between authors (decision-makers) and stakeholders to agree on what the problem is, what constraints exist, and how (and when) the problem is going to be solved.
- Documents should live in a location where they are easy to discover (remember to make work visible!).
- Documents should have sufficient detail, including things like availability, rollout strategy, scaling patterns, and timelines.
- Be generous with links in documents, as they are often part of a larger conversation. It's helpful to link to relevant discussions, tasks, or other artifacts that provide more context to a decision.

## Foster a culture that values documentation maintenance

Keeping documentation up to date is as important as creating it. Whenever teams are reorganized, or when code and processes change, ensure that all relevant documentation is updated, along with any ownership metadata.

Managers might need to allocate time for documentation updates in team work plans, but this investment will save time in the long run. If someone encounters outdated or incorrect documentation, confidence in internal resources decreases, and valuable time is wasted trying to locate accurate information. Leave things better than you found them: If you come across outdated documentation, submit a request to update it or notify the responsible team to address the issue.

That said, document maintenance shouldn’t become a burden. If the effort to maintain a document outweighs its benefits, consider simplifying or removing it.

## Communicate openly, honestly, and authentically

We are humans, and we appreciate communication that is transparent and direct so that we don't have to spend time trying to extract meaning from heaps of corporate buzzwords. Say what you mean, in a respectful way, and listen to understand others. Keep in mind that communication patterns and tone can vary across cultures, so ask for clarification before making assumptions about intent.

For more complex communications, such as announcing a new process or tooling change, anticipate the questions your colleagues might have and consider providing an FAQ. Be open about what you know and what you don’t — it's better to say "we don’t know yet" or "we can’t answer this right now" than to pretend the question doesn’t exist.

### Strive for inclusivity

Strive for inclusivity in all aspects of communication. Prefer universally understood date formats, avoid acronyms without context, and be mindful of time zones when scheduling meetings or sending messages. Be intentional about using inclusive language, and make sure your communications are accessible by adding alt-text for images, using semantic headings, and writing descriptive link texts.

### Use emoji

Emoji are the facial expressions of online communication. They help convey tone, celebrate wins, and make interactions more inclusive — especially for those who might find tone harder to read in text, like the neurodiverse or non-native English speakers. Communication should be professional and respectful, but it doesn’t need to be overly formal.

Don’t worry about using the "wrong" emoji — creativity is welcome! For accessibility, ensure that custom emoji have semantically meaningful names, as some people might convert emoji to plain text.

Lastly, using emoji reactions is a great way to acknowledge receipt asynchronously. You’ll often see people "ACK"-ing a message to **ack**nowledge they’ve seen it, even if they can’t respond right away. (Yes, it’s a nod to the SYN-ACK handshake in networking!)

## Remember practicality beats purity

Remember that these are guidelines, not rigid rules. Process is there to serve the outcome, not the other way around. Focus on intent over strict adherence to mechanics, and always encourage pragmatism.

# Communication channels

This section describes which communication channel to use for which purpose.

## Chat

Chat platforms (e.g., Slack, Microsoft Teams, or similar tools) are commonly used for real-time coordination, quick questions, and staying connected throughout the day. However, chat is inherently transient and doesn’t guarantee message delivery, especially across time zones, which can unintentionally exclude team members. While chat is one of the primary tools for communication and culture-building, it shouldn’t be your sole communication method within your team.

Use chat for informal conversations, team or community camaraderie, water-cooler talk, tactical coordination, amplifying messages communicated elsewhere, and time-sensitive matters best handled semi-synchronously. However, avoid relying on chat for decision-making or as a canonical source of truth, as it lacks permanence and discoverability. A good rule of thumb: if you've been going back and forth on an issue or task without resolution, consider escalating the discussion to a call, and make sure the final decision is documented afterward in a more durable format.

Treat chat as ephemeral, and hold each other accountable for documenting important information elsewhere.

### Tips for making chat more effective

#### General tips

- Chat is asynchronous by nature. [Avoid forcing synchronous interactions](https://nohello.net/en/) (e.g., don’t just send a "hello" without context — share links or ask your question in the initial message). Use `@here` and `@channel` sparingly, if ever, and only for messages that are both urgent *and* important.
- Unless a message is marked as urgent, aim to respond within one business day during your working hours. Treat direct messages (DMs) more like emails or text messages and less like phone calls.
- When seeking an urgent response about a task or issue, include the relevant URL in your message and ask for feedback in the appropriate location (e.g., the task or issue tracker).
- Post in public channels rather than relying on DMs whenever possible. This promotes knowledge sharing, allows others to contribute, and provides visibility into ongoing work. You're more likely to get a better answer, more quickly, and chances are others may share the same question and benefit from hearing the answer. Only use DMs for when the subject requires it, and if it doesn't, encourage moving the conversation to a more public channel.
- Don't be afraid to post in public channels for fear of creating "too much noise", but do try to find the most specific channel for the subject. Use threads and emoji reactions liberally to increase the channel's signal-to-noise ratio.
- Don’t assume that everyone in a channel has read every message. There is no expectation that anyone catch up on channels when returning from time off.
- Update your profile to include your preferred name, pronouns, and "what [you] do here" to help others better understand your role. Pro-tip: Include a link to your [Human User Guide (HUG)](https://github.com/matthewmccullough/human-interaction-templates/blob/master/human-user-guide.md).

#### When chat is effective

- Chat is great for getting real-time feedback from those who are available, but announcements or long-term decisions should always be documented in a more permanent format, such as in a project management tool or document repository. That gives everyone an opportunity to review and be aware of the decision and serves as a more durable, permanent record should you need to refer back to it later.
- Chat is useful for solving temporary technical issues (e.g., "I'm having trouble with my environment, anyone else seeing this?"). If the issue persists or requires a workaround, ensure it’s documented somewhere more durable.
- Using chat to run commands (e.g., through integrations with task management tools) can help bring visibility to work and allow others to observe processes and learn through participation.

#### Tips for notifications

- Set your status and turn off notifications (or log out of chat altogether) when you need focus time or are out of office. Use notification schedules to automatically silence alerts outside of your working hours. Unless you're on-call, there’s no expectation to be available 24/7 (even if the message comes from your manager).
- Be considerate of sending messages outside of others' working hours and use message [scheduling](https://slack.com/help/articles/1500012915082-Schedule-messages-to-send-later) if necessary. Avoid pushing notifications during off-hours unless truly urgent.
- Be mindful of posting links with large previews, especially in busy channels, to conserve screen space.

#### Tips for creating channels

- Prefer named channels (e.g., `#topic-working-group`) over group DMs, as this makes it easier to add people later and track the discussion.
- Prefer creating public (to the company) channels, unless there is a compelling reason for the channel to be private. Public channels foster collaboration and transparency.
- Keep channel topics specific. Smaller, focused channels are often more effective than large, generic ones, allowing people to opt-in to the discussions that matter to them.
- Keep noisy bots out of non-bot channels.
- Ensure each channel has a clear description that explains its purpose and intended audience.
- Archive channels once they’ve served their purpose to keep your workspace tidy and focused.

## Work-tracking tools

Regardless of your work-tracking tool of choice (e.g., GitHub, JIRA, Trello, Linear), [how we work is as important as what we work on](https://ben.balter.com/2023/01/10/manage-like-an-engineer/). Using these tools effectively supports transparency, collaboration, and accountability.

### Issues or tasks

Have a question? Open an issue. Have an idea? Open an issue. Notice something’s not quite right? You guessed it — open an issue. Issues or tasks (depending on your tool of choice) are the atomic unit of work across teams and the primary means by which work is planned, tracked, managed, coordinated, communicated, and shared. They are easy to create and just as easy to close if they turn out to be duplicates or irrelevant. They start conversations, surface alternative viewpoints, and most importantly, create permanent, searchable records of discussions, even if the outcome is "wontfix".

Issues bring the most value to teams when conversations and status updates happen on and around the issue, rather than the issue being used as a "TODO" with only an open and closed state. When issues are long-lived or heavily commented, it's a good practice to keep the issue body (sometimes referred to as the "OP" in internet jargon) up to date for anyone first coming to the issue and to regularly summarize the discussion as a comment that restates the current understanding of the problem and its proposed solution. 

Also note that if there's more ambiguity, questions of "should we even do this", or "we should do this but there are so many ways to implement it that we should consider", a collaborative doc might be a better starting point. Once decisions are made, those documents can evolve into more actionable tasks.

#### Keep issues logically distinct

Unlike email threads that can drift off topic, issues or tasks should focus on one clear purpose. When topics start to diverge, create a new issue to keep conversations focused and teams working on one thing at a time. This helps minimize unnecessary noise and ensures that decisions are made quickly and by the most relevant people.

If a new topic arises that doesn’t relate directly to the original issue, open a new issue and redirect the conversation there. If the sub-task is blocking the main issue, note it as such and move forward.

#### Cross-link related issues and tasks

Cross-linking related issues or tasks is essential for discoverability. Use task lists to break down larger projects and track subtasks. Make sure that all work is tied to an issue, so it’s easier to trace back decisions or progress. If something has a URL, link to it — it saves time for others coming behind you and helps create a network of knowledge across the organization.

### Project boards

The ways different teams track work can vary (e.g., milestones, tracking issues, task lists), but in general, issues track state at the task level and projects track state at the project level — what's on deck, what's in flight, what's done, who's working on what, etc. When using issues (instead of cards) to track work, projects have all the benefits of issues, but offer a perspective one level of abstraction up.

### Pull requests (PRs)

Pull requests (or their equivalent) are the primary means for proposing changes, whether to code, configuration, or documentation. For most changes, directly committing to the main branch is not appropriate. PRs provide a way for teams to review, discuss, and ultimately approve changes in a structured way.

When submitting a PR, be sure to link it to the relevant issue or task. If a review isn't automatically requested from an appropriately responsible team, be sure to `@mention` the team to make ownership clear for anyone who comes by in the future. And if you raise a pull request and notice an unrelated team is pinged for CODEOWNER review, it's your responsibility to update the ownership information as part of your requested change.

To keep things actionable when reviewing a PR, prefer specific in-line comments (ideally with suggested changes) over sweeping, document-wide reviews. Avoid "changes requested" unless you intend to block the PR from merging without your explicit approval.

## Google Docs

Google Docs are a great tool for early-stage brainstorming and collaboration with a small, trusted group. It’s easy to adjust visibility for different people, which makes Google Docs handy when you’re still shaping an idea. However, they’re not ideal as a long-term or canonical source of truth because they lack discoverability, and their closed-by-default permission model can make it hard for others to find or access the information later.

Once an idea is mature enough to be shared more broadly, it’s important to memorialize it in a more permanent, accessible place, such as a project tracking tool, issue, or knowledge repository. Google Docs can be useful for capturing initial thoughts, in-meeting notes, or early drafts, but once the idea takes shape, move the content to a place where it’s more discoverable and easier for the team to track.

Think of collaborative docs as a “top-of-the-funnel” tool — great for ideation, but not for long-term reference.

Here are some additional tips for using Google Docs:

* Include the document owner, status, and shareability information at the top of the document.
* Once the content is moved to a more permanent location, include a link to that source in the Google Doc along with a note about the document’s status.
* Default to sharing documents with the organization (with comment access), unless the content is sensitive.
* For longevity, store documents in shared drives rather than in an individual’s personal account to ensure continued access and visibility.

## Live meetings

When we say "be asynchronous first," we mean it literally. Synchronous meetings shouldn’t be required to kick off an initiative; instead, they should be seen as [points of escalation](https://ben.balter.com/2023/04/20/meetings-are-a-point-of-escalation/) for more complex discussions or when asynchronous methods aren’t enough.

Of course, the percentage of time you spend in meetings will vary depending on your role. Some roles, like that of manager, may require more synchronous connections (e.g., 1:1s with direct reports, cross-functional leadership meetings, coaching sessions) than others. The key is to always use the right tool for the job, and for managers, based on the jobs they have, that might mean more frequent live meetings.

Here are some ways to ensure meetings are effective:

- Meetings can be incredibly valuable when used correctly. Quickly escalate to live meetings when necessary — for example, to resolve interpersonal issues or problem-solve collaboratively, or when asynchronous methods (e.g., chat or project tracking tools) haven’t led to a resolution.
- Keep meeting topics as specific as possible and include the minimum number of the right attendees who remain present and engaged. You are encouraged to leave a meeting if it is not a valuable use of your time.
- Unless it’s an informal/social call, all meetings must have an agenda and clear goals (you’re empowered to decline if they do not). For recurring meetings, consider keeping a shared document with the ongoing agenda and notes. Frame agenda items as questions to ensure goals are clear and met by the end of the meeting.
- Meetings should start and end on time. If you finish early, consider using the remaining time for informal conversations to connect on a human level.
- Use meetings to discuss information, not to convey it. Share necessary background materials ahead of time as pre-reads. Avoid making major announcements in meetings without first sending written communication.
- Meetings shouldn’t be used for status updates or to force someone to complete a task. These are tasks best handled asynchronously.
- Memorialize any decisions made during the meeting in a durable format afterward. Meetings alone don't finalize decisions — especially technical ones — so make sure key takeaways are documented.
- If the meeting isn’t sensitive, consider recording it so those who couldn’t attend can catch up later.

Here are a few additional meeting pro-tips:

- Either enable "speedy meetings" (end 5/10 minutes early) in your calendar settings or schedule meetings to start 5/10 minutes late to allow for a buffer between meetings. Be strict about starting and ending on time.
- For smaller meetings, use the meeting chat for side conversations, and share links or action items outside the meeting (e.g., via chat) so they remain accessible.
- For larger meetings or webinars, consider disabling the meeting chat and using a separate chat channel to ensure discussions don’t interfere with the presenter. This can also help those using screen readers.
- Keep your camera on whenever practical, but to reduce video fatigue, minimize the size of the meeting window or turn off your self-view.
- Practice inclusivity by offering multiple ways to interact (e.g., hand-raising, meeting chat), allowing participants to engage in ways that are comfortable for them.
- Managers, be explicit with your team members about which meetings are considered mandatory and which can be skipped (or which meetings they can catch up on via recording at their convenience). Meeting loads can get out of hand, and sometimes it's hard to figure out what's critical and what's just FYI.
- Be mindful of holidays and working hours, especially across time zones. You can also specify your working hours [on your calendar](https://support.google.com/a/users/answer/9308669?hl=en) to help with scheduling.
- When referring to a meeting time, be sure to include the time zone, and try to avoid location-specific references like "this morning" or "in the Spring". Prefer clear, consistent date formats like the ISO 8601 standard YYYY-MM-DD (except in long-form writing), but anything consistent and unambiguous will do.

### Calendar invites and settings

Scheduling is hard, especially across time zones. To make it easier on your colleagues, you can modify [your Google Calendar settings](https://calendar.google.com/calendar/r/settings) to enable the "modify event" default guest permissions. That way, if something comes up, the person you're meeting with can propose an alternate time that works better for them.

Better still, if your role allows, modify your default calendar's permission by checking the "Make available for the organization" box to allow others to see descriptions of your events. Asking someone if they can reschedule a 1:1 or a task reminder you have blocked off is a lot different than rescheduling a customer meeting or daycare drop off. Of course, if you do that, you'll want to mark any potentially sensitive events as private.

## Video recordings

In the spirit of "be asynchronous first", if you have a unidirectional broadcast (e.g., for readouts, demos, design iteration, or announcements that do not require any interaction or audience participation), consider uploading and sharing a recording, so everyone can watch on their own time, rather than scheduling a live meeting.

Unless you’re discussing sensitive or personal content, it’s also a good practice to record meetings and share the recordings afterward, so those who couldn’t attend live can catch up. Providing transcripts alongside the video helps people quickly find specific information without needing to watch the entire recording.

For a more social experience, consider scheduling optional "watch parties" where people can join, see each other’s faces before the playback starts, and use the meeting chat to interact during the recording.

## Email

Email is an ineffective medium for collaboration and a poor choice for storing organizational knowledge. It lacks opt-in/opt-out mechanisms, can’t be easily cross-referenced, and conversation history lives in personal inboxes — so when someone leaves, the context of the thread goes with them. Use email sparingly, and only when other more transparent tools (like issues or chat) would be inappropriate for the conversation.

In practice, this means email should be reserved for sensitive discussions or external communication. Examples include personnel matters, one-to-one feedback, or conversations with people outside the organization. The same principle applies to other private mediums, like phone calls, which don’t automatically capture and share context. If the conversation can happen in a more open, accessible medium, it should.
