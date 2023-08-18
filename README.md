# ChatKeke-Framework
https://github.com/FlyingFathead/ChatKeke-Framework

This is a (to be) repository of the overall ChatKeke framework, a customizable LLM web frontend+backend framework running on `Flask`.

# About

ChatKeke-Framework is a comprehensive chatbot platform offering users a dynamic and interactive conversation experience. Designed with a focus on regional users (such as within a country, region, etc), but is also versatile for broader audiences. It combines a sleek frontend with a robust backend, integrating seamlessly with OpenAI's GPT models or any local LLM of your own choosing.

ChatKeke's core idea is to provide a low-barrier of entry AI that is accessible to almost everyone within a given region that the framework is intended for. This locality enables the chatbot's functionalities to be better primed and aligned for user interests within given region.

# Features

- Localized chatbot backend + frontend framework that is easily modified to suit customers in any given region.
- Dynamic Frontend Interfaces: Multiple versions of chat UI to cater to various user preferences and device capabilities (i.e. eLite versions for ultra-light browsers).
- OpenAI API Integration: Utilizes the `gpt-3.5-turbo-16k` model by default (switchable to `GPT-4`) to ensure high-quality chatbot interactions.
- The backend can also be modified to use any local LLM as the "brains" for the chat interface.
- OpenAI API function call capabilities: use online search engines, fetch and display news from multiple sources ranging from RSS feeds to web sources.
- IP Filtering & Security: Advanced IP filtering system for enhanced security and access control (i.e. specific user groups or regions).
- Token Management: Efficient handling and limiting of token usage, can be implemented when using i.e. OpenAI API (i.e. set usage limits; per user, hourly, daily...)
- Dynamic Text Formatting: Handles complex text structures, including syntax highlighting for code snippets and lists.
- Temporal awareness functionalities: highlights important dates such as national holidays etc.

# Roadmap

I am currently looking forward to sanitizing and refactoring the code for making it easier to deploy. Note: this is a single person project, so it is what it is.

# Demo

ChatKeke is currently available online at [https://chatkeke.fi](https://chatkeke.fi) for all Finnish users (region restricted, available in Finland only).

# Author

[FlyingFathead](https://github.com/FlyingFathead/)
