# Generate message

This tool aims to prepare a smart commit message for you at the point you commit. Unfortunately, VS Code does not work with git hooks so this flow only works when commit on the command-line.

This is to take the effort out of writing self-explantory commits, where the machine can write a message I would write for a simple case. And where looking at the diff output is sufficient to see the _why_.

This tool does not require you to always use the auto-generated message - it simply makes it available if you enable it. If there is something that needs to be captured like that a commit is fix or the reason for a fix or a high-level description of the changes made (like renamed variabled), then write the message by hand.
