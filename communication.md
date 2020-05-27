# Communicating

## General Communication

- **Provide all the information you can for the recipient.** We are a remote-first company. This means that when you send a message, someone may not get to it until a later time, perhaps when you are unavailable to answer clarifying questions. Provide all the information you can in your message to ensure the recipient understands, and has all the information they ned to respond or take action.

- **Collect all questions together.** When discussing complex topics, you may have several questions throughout your message. It’s much easier to process (and track responses) if you collect them together and present them at once instead of peppered throughout your message.

- **Collect next steps at the end of your message.** If you’ve got next steps that are either outlined for yourself or someone else, place these at the end of the message so it’s clear what actions are required to move forward.

- **Use numbering wherever possible.** If you’re listing questions, discussing multiple things, or requesting next steps, use numbering wherever possible. 
	- Instead of peppering things in a sentence or using bullet points, it’s easier to review a numbered list. 
	- People are able to respond to each individual item easily by referring to the number in further communication (i.e. “In response to #3, the answer is yes”)

- **If possible, avoid multiple messages.** This will result in fewer notifications/emails to the recipient, and will be easier for them to mark messages as unread or to link to a specific comment later. This applies whether you’re sending email, sending Slack messages, or commenting on a project management board.

This is bad (5 messages):
```
pavan: the way to test the new feature is a bit tricky.
pavan: first, you have to log in to a dummy account
pavan: then, you need to create a new project
pavan: after that, create a ticket and assign it 
pavan: let me know if you have any questions!
```

This is good (1 message):
```
me: The way to test the new feature is a bit tricky. Here are the steps:

1. First, you have to log into a dummy account.
2. Then, create a new project.
3. After that, create a ticket and assign it to the admin of the dummy organization.

Let me know if you have any questions!
```

- **Use screenshots wherever possible.** If it’s easier to show something than describe it, do so! Even if you are describing something, including screenshots to accompany your description will make it easier to understand and reduce unnecessary back & forth. Use a tool like [Cloudapp](https://www.getcloudapp.com/) to rapidly create a screenshot, annotate, and provide a link to a person.

## Asana / Github Issues / Other Project Management Tools

- **Assign a ticket to someone else if you need a response or action from them.** Simply tagging someone in the comments can get lost, but if you explicitly assign the ticket to them, they’ll know the next step is on them. Then, when they’re done with their next step, they can assign it back to you and you can pick the ticket back up.

- **When submitting a ticket for review, always include the PR and QA link.** This way, when you’re assigning it to someone else for reviewing, they don’t have to go searching somewhere else on how to find your work. 
	- Link PRs / Issues together in Github if you’re using that as a project management tool. 
	- For other tools, like Trello or Asana, drop the PR & QA links into a comment.

## Slack

- **Always ask the question in your first message.** Don’t say “Hi, can I ask you a question?” This is vague, unclear, and unactionable. Plus, it discourages asynchronous communication. Instead, in your first message to a person, include the actual question, along with the information they’ll need to answer the question. This saves both you and the recipient time, allows them to respond immediately with the information that _you_ need, and doesn’t require both of you to be at your desk at the same time.
	- Bad: “Hi, are you there?” Or “Can I ask you a quick question?”
	- Good: “Hi <Person>! Can I ask you a question? When do you think the latest code will be deployed to production? I tested it on staging, but I need to make sure the legacy accounts on production will work well also. I’ll be here from 2 - 4 PM PDT in case you have any questions.”
  
- **Think twice before sending something in Slack.** This one is a tricky one, and takes a judgement call on your part. Slack is great for realtime communication, but can be easy to lose track of things. If you need a response, consider creating a ticket in your project management tool. If it's urgent, you can ping someone in Slack with the link to the ticket you've created so you get a more prompt response.