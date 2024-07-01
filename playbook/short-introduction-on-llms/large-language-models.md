# What are Large Language Models

</br>

But first start with the question what are Large Language Models (LLMs)? So let’s start. You have probably heard of the application ChatGPT that is able to answer questions, translate text and to have human like conversations. ChatGPT is built upon a LLM, GPT-3 or GPT-4, an algorithm that enables ChatGPT to perform it’s tricks. So how can such an algorithm do this? Imagine you have a parrot that's been around people its entire life, and it's heard countless conversations about a huge array of topics. Over time, it's learned to mimic human speech pretty convincingly, to the point where it can respond to your comments or questions with relevant phrases it's heard before. If you ask it "How's the weather?", it might reply with "It's raining cats and dogs!" because it's heard that phrase used to describe heavy rain.

However, it's important to remember that this parrot doesn't actually understand what it's saying. It doesn't know what "weather" is or what "raining cats and dogs" means. It's simply learned that certain responses are likely to follow certain prompts, based on the patterns it's observed in human conversation.

In a similar way, Large Language Models (LLMs) like OpenAI's GPT-4 are AI systems that have been trained on a massive amount of text data and code (see figure 1). They learn the patterns, structures, and common phrases in the language, and use this knowledge to generate human-like text based on a given prompt. However, like the parrot, they don't truly understand the meaning of the text they generate - they're predicting the most likely response based on their training.
In the context of a course on prompt engineering, this understanding is crucial. When crafting prompts for an LLM, it's important to keep in mind that the model is trying to predict a likely response based on its training, not truly understanding the prompt or the implications of its response.

And we have taken off! Actually this piece was (mostly) written by ChatGPT-4 (see the screenshot below). The block of the green A represents the ‘prompt’ and the purple block represents the answer to this prompt. The main message of ChatGPT is that LLMs are not ‘smart’ or ‘intelligent’, in fact LLMs are complex statistical models that are trained on a massive amount of text that have been collected from the world wide web, this includes online books and all kind of web-pages. These models have the capacity to generating human-like text in response to prompt. 


```{figure} ./_static/img/datastrategy1.png
---
height: 464px
name: datastrategy1
---
```

The most simple form of Copy and Download is by sending data files, such as excel files or compressed archives, via email or via a public download link. More advanced and secure methods are for example by creating Application Programming Interfaces [(API)](https://www.hl7.org/fhir/http.html) that control access to the data, through a secure or private download link. 

In most cases the _data controller_ and _data recipient_ make a legal agreement in which the limitations of further data usage are being described. Still, Copy and Download poses the problem of losing control over the spread of data, does not impose limitations on resharing or copying of data and does not inherently provide means of tracking data access. This can raise privacy concerns and makes the method unsuitable when dealing with sensitive data. 

Furthermore, Copy and Download works for single projects on the receivers end. Changes made on the data locally prove hard to merge with the remote data state. This poses serious challenges when working with multiple parties on the same data,  since everybody needs to make sure they have the valid (often most recent) version of the data. 

Another problem can be that the data recipient needs to have proper expertise on how to process the data. In some cases, certainly if a data exchange process needs to be automated, standardization according to the appropriate ontologies is necessary although in other cases exchange of a simple text files might be the most straight forward way for data exchange. 

 </br>

:::{seealso}

*Bringing Code to Data: Do Not Forget Governance*, article available on [PubMed](https://pubmed.ncbi.nlm.nih.gov/32540846/).

:::

