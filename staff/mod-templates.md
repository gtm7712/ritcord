# Moderation Templates

## How to respond to a Townhall

### Pawprint Response Template

```markdown
### Townhall [Date] - Pawprint

**Suggestion**: <Message-Link>
**Status**: Accepted|Implemented|Compromised|Denied|Needs Further Discussion
**Reasoning**: A thorough explanation on why the staff team thought it was a good idea and will work on it, if it’s already been to be implemented, why we decided to compromise on it, or thought the suggestion would not work with our server
**Plan for Implementation**: If we accepted a situation, we’ll outline our plan on how to implement it here
```

### Not a pawprint

```markdown
### Townhall [Date]

**Update**: <Subject-of-townhall>
Body here
```

**Always add a thread to the townhall and name it `"[Subject] Discussion"`.**

### Suggestion Commands

#### Aprove

```
/suggestions approve <suggestionid> <reason>
```

#### Deny

```
/suggestions deny <suggestionid> <reason>
```

## Events Within Server / On Campus

```markdown

**Event Name**: The name that you want to have appear in Events
**Location**: Where will this event be held? Is it online/in person?
**Start time & date**: When is your event?
**Description**: What is the event about?

[optional]
**Event Image**: An image to show off what your event is about!
**Discord Invite**: A permanent invite to your clubs discord server, if applicable
```

## Alt Text Warnings

### Heads-Up

```
;warn 0123456789 This is to let you know that you have reached 5 un-alt-texted images. At 10, a 12h image mute will be applied. For a refresher on our alt text rules, see `/altrules.` If you would like the bot to remind you how to add alt text, enable `/usersetting Reminder`. If you have any questions, please open a #⁠modmail.
```

### Image Mute

```
;warn 0123456789 You have passed <NUMBER> un-alt-texted images and have been image muted for <NUMBER> <hours/days>. For a refresher on our alt text rules, see `/altrules`. If you would like the bot to remind you how to add alt text, enable `/usersetting Reminder`. If you have any questions, please open a #⁠modmail.
```