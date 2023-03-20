# LLM-Notes

This is a cool behind the scenes example of LLM output being fed back into LLM.
They ask LLM "what does code {x} do?"  Then they ask "What tests should you have for code that does {y}?" Then for each they ask: "Given code X write a python unit test of aspect Z
They can use different LLM for different questions.  The code-understanding question doesn't have to use the code-generating LLM.
https://github.com/openai/openai-cookbook/blob/main/examples/Unit_test_writing_using_a_multi-step_prompt.ipynb


https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/

Random Links
This was interesting to me b/c it highlights how confident and wrong LLM can be.  Also points out how they can be really bad at somethings.
https://stratechery.com/2022/ai-homework/

Suggests connecting LLM to other services so those services can help supply the facts.
Stephen Wolfram talks about that a little here:
https://writings.stephenwolfram.com/2023/01/wolframalpha-as-the-way-to-bring-computational-knowledge-superpowers-to-chatgpt/

This is a paper that connects LLM to outside API and lets the LLM call into them:
https://arxiv.org/abs/2302.04761

Or this example from Self-Ask I found in the prompt-engineering link above
https://arxiv.org/abs/2210.03350

Lets do the ReAct thing:
https://interconnected.org/home/2023/03/16/singularity
https://til.simonwillison.net/llms/python-react-pattern


This link is funny, highlights how ChatGPT seems like it really knows what its doing and then jumps to wrong conclusions.  Is this "Thinking: Fast And Slow"?
https://jameswillia.ms/posts/chatgpt-rot13.html

https://blog.seekwell.io/gpt3

Not everything has to have a reason:
https://arstechnica.com/information-technology/2022/11/herzog-and-zizek-become-uncanny-ai-bots-trapped-in-endless-conversation/

We might be able to build tomorrow's technology today:
https://twitter.com/shubroski/status/1587136794797244417

Sex sells:
https://theconversation.com/chatgpt-and-tinder-do-smart-chatbots-make-dating-online-better-or-worse-198454

I liked the never say die attitude used to get the LLM to write the sql queries.  They ask multiple times for queries, then try running the queries and ask the LLM to fix the errors,  they do that in a loop (5 times?) and collect the generated queries that don't have errors.  They give examples of the db schema and call out specific gotcha's the sql generator should try to avoid.
https://www.patterns.app/blog/2023/01/18/crunchbot-sql-analyst-gpt/

I've already lost the link but I came across a post written by an MBA prof about basically embracing ChatGPT ability to write essays and requiring students to publish their ChatGPT prompts along with the essays.   The post highlighted various levels of sophistication in the prompt writing styles.  It would be interesting to see the prompts students used if they were graded not on a currated/edited version but on the next randomly generated essay from their crafted prompt.  
