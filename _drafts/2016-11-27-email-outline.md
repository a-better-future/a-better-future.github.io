2016-11-27-email-outline


Famous VC Brad Feld [http://www.feld.com/archives/2016/03/help-understand-value-slack-instead-email-list.html](has publicly retreated from Slack). 


Soultions
	** Constraining communication
	** Creating Channels
	** With email the 'channels' are in your head and don't persist
	** Will likely be some kind of Facebook Tech + email. Email just will never die.
	** The SMTP Protocol could creat
	e better headers: dual prioritization, etc.

# Outline:
* Attention Windows
	** Limited attention (<10% of emails are critical / actionable)
	** Lack of prioiritization
* Current Value of Email
	** 'Whole Contact'
	** Internal / External communication (one touch)
	** To - do list
	** Sharing Files
	** Making decision
	** Con-synchronous (can be asynchornous or synchronous)
	** 1 to 1; 1 to many
	** Informal / formality - leaves things up to interpretation
		*** Human language is flexible and unclear - it allows things to get done in a better way
	** Organizational emails - make sure everyone gets it
	** News Feed
	** Identity / Passport
	** Direct Social Communication
	** Deleting - ephemerality
* What jobs does email do?
* Where does it fail? 
	** Presence
	** Push notifications
	** One touch collaboration (video / calling)
	** Screenshare
	** Communities for projects / groups / other ways of organizing
		*** Managing listservs is a pain TBH
	** Providing 'latest source of truth and versioning'
		*** Wikis are really bad at versioning
	** Task management / Kanban
	** Feedback / case management
	** File management
	** Search
	** Information is 'trapped' - if it's not in your inbox, it's hard for you to access
	** Cognitive Separation
	** Prioitization
	** Grouping by social network
	** 'Snooze' messages - return to the inbox (Boomerang, Outlook and Mailbox had this feature)
	** Sort by addressee: (to me alone, to me and others, cc'ed me alone, cc me and others, bcc'ed)
	** Auto-suggest (Google is tackling this)
	** Whitelisting

* Why email isn't 'simply' a to-do list
	** Not all communication is relevant
	** Building relationships is important
	** Employees are PEOPLE, not robots
* Problems with solutions
	** Overengineered
	** Focused on one kind of problem
	** Tasks I've assigned;
	** Tasks and conversations I've created
	** Tasks and conversations I'm following
* What can we do about it?


## The competitors

Slack
Workplace by Facebook
Outlook
Asana

* Boomerang:
Why it works
Boomerang allows you to 'snooze' messages from your inbox - a valuable feature for gmail and others. On top of that, it now has automatic 'respondability' readings, to encourage you to write for humans. It's a pretty powerful tool if you're using it for business.



Email is a single to-do pile - it includes recipes / coupons / receipts / to-dos etc.

"Email is neutral, meaning that anyone can email anyone else with an email address. If you have a person’s email address, your message will be delivered no matter who you are—whether the recipient is your oldest friend, your granddaughter, your boss’s boss, or Beyoncé."

Yoga-Box: You have to add people to do it

"Email is our filing system, our hub for collaboration and task management and calendaring"

Why is no one writing publicly about this? We're satisfied with the status quo - it works well enough.

It's worth considering why email works:
- It's open
- It's permanent without locking you in
- It's neutral - anyone can message anyone
- It's easy to remember - like a phone number
- It's robust - looks good on any device*

Let's consider now where email can improve:
- It has no prioritization
- It has no structure other than subject, message and attachment
- It doesn't summarize
- It doesn't gate-keep


SMTP Exchange:

S: 220 smtp.example.com ESMTP Postfix
C: HELO relay.example.org 
S: 250 Hello relay.example.org, I am glad to meet you
C: MAIL FROM:<bob@example.org>
S: 250 Ok
C: RCPT TO:<alice@example.com>
S: 250 Ok
C: RCPT TO:<theboss@example.com>
S: 250 Ok
C: DATA
S: 354 End data with <CR><LF>.<CR><LF>
C: From: "Bob Example" <bob@example.org>
C: To: Alice Example <alice@example.com>
C: Cc: theboss@example.com
C: Date: Tue, 15 January 2008 16:02:43 -0500
C: Subject: Test message
C: 
C: Hello Alice.
C: This is a test message with 5 header fields and 4 lines in the message body.
C: Your friend,
C: Bob
C: .
S: 250 Ok: queued as 12345
C: QUIT
S: 221 Bye
{The server closes the connection}


Email as command and control:
Unless you're in the military, direct orders don't usually happen in the world. Email preserves communication as it exists in reality - requests without forcing. The thought of assigning tasks presents a mental hurdle, even though that's a lot of what email is doing. 
Instead, we should preserve the tasks as requests, how they might exist now. Having a pointed finger like [www.pyrus.com](Pyrus does) missed a key behavioral point. 

Inbox provides a single point of failure - no need to check 'announcements' vs. todo list vs. forms that needed to be completed. So that's a huge plus, but also ignores how most people think about their work and priorities.

Instead of providing leverage, most email forces you into a specific process. Tech needs to enable better and smarter processing before people will start taking it seriously.


Resources:
https://medium.com/@collinmathilde/why-its-so-hard-to-innovate-in-the-e-mail-space-9874e08e3426#.s3buqvv4a
http://www.emailoverload.com/philosophy/PerfectClient.php
https://news.ycombinator.com/item?id=143828
http://www.radicati.com/wp/wp-content/uploads/2015/02/Email-Statistics-Report-2015-2019-Executive-Summary.pdf
http://www.slate.com/articles/technology/technology/2015/02/email_overload_building_my_own_email_app_to_reach_inbox_zero.html#lf_comment=275492240
https://www.fastcompany.com/3002170/email-new-pony-express-and-its-time-put-it-down

Quora Answers:
-----------
https://www.quora.com/What-better-product-should-replace-email-communication/answer/Ryan-Borker?prompt_topic_bio=1
-----------
OK, here we go. **Email communication won’t be replaced, it will be supplemented.**
The letter didn’t ‘replace’ talking to people in person. The phone didn’t replace letters. Email didn’t replace phones. Messaging (Slack, etc.) hasn’t replaced email.
**INTRO** 
Each of the communication patterns I mention above has a number of variables that it optimizes for:
* Throughput (information per time)
* Fidelity (ability to effectively communicate what you want to) 
* Synchronicity 
* Ease of transmission 
* Cost of composing and sending a message 
* Formality
* Verification mechanism (who said what? how do we know?)
* Retrieval and search mechanism (human memory just isn’t that good)
* Persuasiveness
* Relationship building 
* …many, many, many others
In person communication has the highest fidelity - we react to voices and expressions and can tailor our communication in real time. This is what most of us do naturally. We understand situations and tailor our reactions to them. On the flip side, in-person communication is incredibly costly - it  takes our full attention, is relatively hard to transmit, and without recording mechanisms it’s hard to verify with a 3rd party. It becomes ‘he said / she said.’
Email in many respects represents the other extreme: it can generate very high throughput by virtue of being able to send directly to the right people without having to reach out individually; it’s very cheap to transmit; it’s easy to verify and has great retrieval and search mechanism (compared to human memory).
**PROBLEM: LIMITED ATTENTION WITH AN OPEN FUNNEL**
Mail still has a lot of ‘spam’ or advertisements, but there’s a limit to these: they cost money to send and deliver. So you don’t get 300 advertisements per day, because someone would have to actually print them and pay the postal service to deliver them. 
Email doesn’t work like that - with just a few characters, you can *instantly* reach the top of someone’s inbox. 
Email’s simplicity and openness creates a filtering problem: how do you decide what to open and spend time on? 
Email’s transmission costs means that it is disgustingly easy to create work or tasks for other people, since you have no way of seeing their reaction. Imagine instead a meeting where you asked someone to do something - they’d basically react based on the amount of work they had and you could adjust your request or at least have the cost of seeing them squirm or dissatisfied. With email, there’s no friction so you never see that. You can ask and send without worrying about whether it’s correct or not.
As a result, people’s inboxes get overloaded. With no prioritization by default in the inbox, the ‘stack’ mentality of email (last in first out) creates a disconnect between chronology and importance. 
**EMAIL CLIENTS DON’T HELP, MOSTLY**
Most email clients don’t treat the underlying problem of helping you determine whether something is important or not, or helping you get stuff done. This is smart, since up until recently it’s been very, very hard to determine importance for a human. A cat pic from a coworker may be trash, but from a wife / husband it could be a vital communication tool.
Instead, many messaging clients aim to increase your throughput—allowing you to process messages faster, and sort them into buckets. 
Some interesting innovations are happening, notably with Inbox by Google, Snoozing features for messages, etc. 
But there’s still a long way to go. Part of this is by design: email has to be backwards compatible. If an email client can’t send a message to a previous client, it could be disastrous. 
The search for the ‘perfect’ email client thus continues, as by year smart engineers and product people bang their heads building a new one until they realize they can’t make any money on it. 
**WHAT DO ORGANIZATIONS REALLY DO?**
Human communication in organizations (and let’s limit the scope to this for now) often serves to either **make decisions, ****communication information, manage tasks, or build relationships.** That’s a very simplified framework, but one that will be helpful in understanding what an ‘ideal tool’ needs to do. 
**DOES MESSAGING SOLVE THIS?**
 Asana, Yammer, and Slack took a different approach: abandon email altogether.
Their approach, in essence, was that workplace communication could be ‘channeled’ effectively into different kinds of forms. It works remarkably well for many use-cases.
For internal-only communication, projects (Asana) provide a much easier way to organize communication and keep people up to speed.
Slack provides real time updates in a way that minimizes the amount of time people need to respond. 
Yammer did the same thing basically as ‘groups’ or message boards.
All of these tools ‘unlock’ the inbox, so that groups have access to all of the information they need that needs to be public, thus freeing critical information from the tyranny of the inbox.
At the same time, these two approaches each lose something.
With Asana, you lose the ‘relationship building’ aspect of communication. A quick aside on an email forward or a bcc provides people with subtle but important ways to communicate how they feel about something, not just what they’re doing.
With Slack, you lose the task management side of things. Slack is an all-day meeting with no agenda (I don’t take credit for that observation). It means that once the ‘stream’ has passed, you have to search for what was agreed.  It’s also hard to communicate what decisions have been made.
As a result, both of these tools are very, very good for certain use cases and organizations and cultures, but not very good ‘in general.’
**EMAIL’S REVENGE**
Email allows you to communicate on your own terms in a portable way. Its open format allows you to structure messages however you want and to whoever you want. It’s also ephemeral — an email can be ‘deleted’ by both parties and forgotten. Posts and slack messages are harder to ‘reign in’ once they’re sent. 
This is its blessing and curse.
Until people find a way that ‘feels natural’ allows universal communication, provides a portable way of describing contacts,  allows people to build relationships and manage tasks, etc. etc., we’re going to need to work with email.
**FACEBOOK AND MICROSOFT TO THE RESCUE?**
Workplace by Facebook seems to be the first platform that might have a shot at replacing a large chunk of email. 
Since Identity is taken care of and pretty strictly controlled (it’s hard to create just another facebook account and create enough history to make it real), access control becomes easier.
Facebook’s platform has ‘project boards’ (in the form of groups) that allow collaboration, real time messaging + video chat, a universal address book built in, and smart threading. Your inbox could become a feed of what’s important instead of a stack.
That last bit is very promising and exciting in my opinion, since you finally get what’s important first. 
However, Facebook is still missing the ‘universality’ of contacts (for now), along with easy ways to prioritize content and senders, manage files, and coordinate on tasks.
Microsoft on the other hand, may be the first to actually link everything together at an enterprise scale. With identity from LinkedIn, their new ‘messaging app’ that they can build into 365, productivity software (Word, etc.) and Cloud storage, they could in fact be the first to build out the ‘holy grail’ of person to person communication. 
Allowing seamless switching between channels of communication could provide a revolution if they can pull it off. With MSFT’s history of integrations however, that’s a big IF. 
**NETTING IT ALL OUT**
Ultimately, the ‘simplest’ platform of email ends up being the most flexible and therefore the most adaptable. We haven’t even talked about delegating management of your inbox, presence, versioning, and a host of different problems.
A simple, universal easy to understand form of communication that lets humans be humans: we’re still working on a way to beat that.


 **POSTSCRIPT: A BETTER FUTURE?**
I do believe there are a bunch of ways to improve email, using the header fields that already exist. Many solutions (such as Cloze, Accompany, and Alto) have very good ideas for their products that haven’t yet made it into primetime. I believe that an identity platform (like Facebook, LinkedIn, or Slack) will be able to build some of these features into their products. Smart assistants (like AI or Chatbots) could also come into play very soon. Stay tuned for some more speculation, as this is just a practice foray for a bigger piece on email I’m writing.


==========
ATTENTION ECONOMICS
==========

Chits: 15 second increments - intuitive thinking
Chets: 1 minute increments - can get memory + brief system 2 added to intuitive thinking
Chats: 15 minute focused increments - can get full attention