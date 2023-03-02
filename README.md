# ChatGPTSummary

This script uses the ChatGPT API to summarise long pieces of text.

It does so by splitting the piece of text into smaller chunks, calling the ChatGPT api to summarise each of those chunks, and then summarising one final summary based on all of the other smaller summaries.

You can set how big the chunks you would like, and how big you would like the summaries to be.

For example, a 10,000 word document can be split into 1,000 word chunks, and then each of those chunks can be summarised into 120 word summaries.
