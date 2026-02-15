# autarch
Local web interface for AI-assisted development. Because some people prefer to work alone.


## What this is:
* A way to add accountability and resilience to AI-assisted development.
* A set of local web pages and scripts that provide simple integrity checking, project tracking, and change managment functionaltiy.
* A set of instruction files that instruct a LLM on how to interact with the tool.

## What this is not:
* A replacement for full code management tools such as the Atlassian sutie or git.
* At present, a local LLM API interface.

## The Need
As I started testing LLM development functionality, I quickly realized that the ephemeral nature of LLM code environments, along with the extremely limited working memory of the LLMs themselves, was a significant hindrance.
This tool is intended to provide the LLM of your choice with a structured method of accruing development labor that avoids misunderstandings and lost work.

## On Browsers
My first browser was NCSA Mosaic. My second browser was Netscape Navigator. My third browser was Firefox (and occasionally Iceweasel). You might say I am a Mozilla devotee. However, this tool currently only works on Chromium-based browsers.
The sole reason for this is the local filesystem access API. Which normally I would agree is a very, very bad idea. But for this purpose, it is necessary.
I hereby commit to figuring out a way to make this tool function on Firefox in some reasonable fashion - just not in these initial versions.
