# ChatGPTSummary

This script uses the ChatGPT API to summarise long pieces of text.

It does so by splitting the piece of text into smaller chunks, calling the ChatGPT api to summarise each of those chunks, and then summarising one final summary based on all of the other smaller summaries.

You can set how big the chunks you would like, and how big you would like the summaries to be.

For example, a 10,000 word document can be split into 1,000 word chunks, and then each of those chunks can be summarised into 120 word summaries.

First, you'll need to get an API key from OpenAI. If you do not know how to do that, follow these instructions:

https://elephas.app/blog/how-to-create-openai-api-keys-cl5c4f21d281431po7k8fgyol0

I set the request to ChatGPT as follows:

  "You're a 140 IQ science communicator. Your job is to summarise text, making sure to focus on the most important details. Make sure your summaries are       highly detailed and comprehensive. Do not miss any key details. You can write multiple paragraphs if needed."
  
I have no idea if this is actually a good prompt or not, but hey, why not give it a go? I'd encourage you to try tailoring this prompt to see if you can get better results some other way.
