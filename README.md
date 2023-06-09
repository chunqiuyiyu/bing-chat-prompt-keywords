# bing-chat-prompt-keywords [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
Use specific keywords to chat with Bing AI more effectively.

> {content} ;keyword1;keyword2;keyword3...etc

__You don't have to use keywords in the above format, just use them in any format you want and have fun!__

## A

`act_as`: simulate some roles.
> storyteller ;act_as

`ascii_art`: generate ascii art.
> dog ;ascii_art

## C

`code`: generate code for a specific language.
> hello world ;code-generator;python;comment

`continue`: continue the conversation.
> Your answer was truncated, the last text I saw was "blah blah". Continue your answer.

## D

`draw`: draw a picture.
> fox ;draw;line-art

`depicted`: describe a picture.
> What is depicted in this picture.

## E

`emoji`: generate output in emoji format.
> dog ;emoji

`expert`: As an extension of the "Act as a ..." prompt you can tell Bing Chat in finer detail what you want that role to be. This is particularly useful for technical content.
> I want you to act as an expert in Python programming with five years of experience ;expert

`explain`: Asking Bing Chat to explain your chosen topic to you as if you were a child.
> Explain the concept of gravity to me as though I am six years old ;explain 

## F

`force_search`: force search for the query.
> I want to search for this ;force_search

## H

`hi` or `hello`: say hi to the bot.
> hello ;hi

`how_to`: get instructions for a specific task.
> how to make a cake ;how_to

## L

`let's_play`: let us play a game.
> tic-tac-toe ;let's_play

## N
`no_search`: don't search for the query.
> I don't want to search for this ;no_search

## O
`outline`: generate an outline for a specific content.
> I want to write an outline for this: text or url ;outline

`only`: output results in a specific format.

> output the result only code

> output the result only emoji

## P
`photograph`: use this keyword with `draw` keyword to get better image results.
> Describe a beautiful photograph of dog

## Q

`quiz`: define a quiz.
> What is the capital of France ;quiz

## S

`similar_to`: find similar things.
> apple ;similar_to

`search_query`: a command that you can use to perform a web search on any topic you want. like `force_search`.
> I want to search for this ;search_query

`summarize`: This is particularly handy when using Bing Chat in the Edge Sidebar.
> Summarize this article or webpage into a bullet point list ;summarize

## T

`translate`: translate a word or a sentence.
> hello world ;translate;French

`topic`: define a topic.
> I want to talk about this: text or url ;topic

> with environment protection as the topic ;topic

`table`: If you're researching something that could be presented in a table, ask Bing Chat to do that. Standard responses will just be a wall of text, so much like bullet points, a table is a much better way to present what it is you're looking for.
> I want to create a table for this ;table

## V

`vs`: compare two things.
> apple orange ;vs

## W

`want`: If you're using Bing Chat to try and learn about a topic or help you create something, this can be a crucial addition to your prompt. Instead of just giving you what it thinks you want to know, tell Bing Chat to ask you questions to help it understand what you want. 
> I want you to ask me questions about this ;want
