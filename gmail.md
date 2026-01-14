---
title: gmail
category: web
tags: web
---

# gmail

## Message Actions

```
E           # Archive
#           # Delete
M           # Mute conversation
!           # Mark as spam
X           # Select conversation
S           # Star message
I           # Mark as read
U           # Mark as unread
⇧I          # Mark as important
-           # Mark as not important
+           # Mark as important
]           # Archive and go to next
[           # Archive and go to previous
Z           # Undo last action
*           # Select all conversations
* then N    # Deselect all conversations
* then R    # Select read conversations
* then U    # Select unread conversations
* then S    # Select starred conversations
* then T    # Select unstarred conversations
```

## Navigation

```
G then I    # Go to Inbox
G then S    # Go to Starred conversations
G then T    # Go to Sent messages
G then D    # Go to Drafts
G then A    # Go to All mail
K           # Move to newer conversation
J           # Move to older conversation
N           # Next message (in conversation)
P           # Previous message (in conversation)
`           # Go to next inbox section
~           # Go to previous inbox section
```

## Compose & Reply

```
C           # Compose new message
D           # Compose in new tab
R           # Reply
A           # Reply all
F           # Forward
⇧C          # Add Cc recipients
⇧B          # Add Bcc recipients
⌘↵          # Send message
⌘⇧C         # Add Cc recipients (compose)
⌘K          # Insert link
```

## Labels & Categories

```
L           # Open label menu
V           # Move to folder/label
⇧U          # Update conversation (sync)
G then K    # Go to Tasks
G then C    # Go to Contacts
G then L    # Go to label
```

## Search & Filter

```
/           # Search mail
.           # Open more actions menu
,           # Move focus to toolbar
?           # Show keyboard shortcuts
```

## Formatting (While Composing)

```
⌘B          # Bold
⌘I          # Italic
⌘U          # Underline
⌘⇧7         # Numbered list
⌘⇧8         # Bulleted list
⌘⇧9         # Quote text
⌘\          # Remove formatting
⌘Z          # Undo
⌘Y          # Redo
```

## Advanced Actions

```
⇧N          # Update current conversation
G then B    # Go to Buzz
T           # Add conversation to Tasks
⇧T          # Add to Tasks
;           # Expand entire conversation
:           # Collapse entire conversation
Q           # Move cursor to chat search
```

## Search Operators

```
from:someone@example.com     # From specific sender
to:someone@example.com       # To specific recipient
subject:meeting              # Subject contains text
has:attachment               # Has attachment
filename:pdf                 # Specific file type
label:work                   # Specific label
is:unread                    # Unread messages
is:starred                   # Starred messages
is:important                 # Important messages
before:2024/01/01            # Before date
after:2024/01/01             # After date
older_than:1d                # Older than (d=day, m=month, y=year)
newer_than:2d                # Newer than
size:5000000                 # Larger than (in bytes)
larger:10M                   # Larger than (M=MB)
smaller:1M                   # Smaller than
cc:someone@example.com       # Cc'd to someone
bcc:someone@example.com      # Bcc'd to someone
in:anywhere                  # Search all folders
is:chat                      # Chat messages
deliveredto:email@domain.com # Delivered to specific address
```

## Tips

- Enable keyboard shortcuts: Settings → General → Keyboard shortcuts on
- Combine search operators with OR: `from:john OR from:jane`
- Use quotes for exact phrases: `subject:"project update"`
- Combine multiple operators: `from:boss is:unread has:attachment`
- Use `-` to exclude: `-from:newsletter@example.com`
