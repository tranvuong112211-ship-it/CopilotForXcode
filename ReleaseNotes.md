### GitHub Copilot for Xcode 0.44.0

**🚀 Highlights**

* Added support for new models in Chat: Grok Code Fast 1, Claude Sonnet 4.5, Claude Opus 4, Claude Opus 4.1 and GPT-5 mini.
* Added support for restoring to a saved checkpoint snapshot.
* Added support for tool selection in agent mode.
* Added the ability to adjust the chat panel font size.
* Added the ability to edit a previous chat message and resend it.
* Introduced a new setting to disable the Copilot “Fix Error” button.
* Added support for custom instructions in the Code Review feature.

**💪 Improvements**

* Switched authentication to a new OAuth app "GitHub Copilot IDE Plugin".
* Updated the chat layout to a messenger-style conversation view (user messages on the right, responses on the left).
* Now shows a clearer, more user-friendly message when Copilot finishes responding.
* Added support for skipping a tool call without ending the conversation.

**🛠️ Bug Fixes**

* Fixed a command injection vulnerability when opening referenced chat files.
* Resolved display issues in the chat view on macOS 26.
