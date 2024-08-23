---
layout: page
title: aiMessage
description: Web app with ChatBot(with History), Semantic Search, Function Calling, QA, Web Scraping
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Built an AI Powered application using OpenAI API, NodeJs and ExpressJs

    ---
    link: https://github.com/Monica-Gullapalli/aiMessage
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This gives a glimpse of the different features this web app has - ChatBot, Semantic Search, Image Generation, Function Calling, Q&A
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This shows how the app has a history of last 10 requests displayed seperately for each function.
</div>

This AI powered web App has a imessage like UI, also where the web app got its name from - aiMessage. This app allows the users to chat with the AI in the form of a chatBot which remembers history i.e the conversations that the user initially made with the chatbot. 
Let's say history wasnt added or carried forward, then if the user told the chatBot about their name, age etc or any detail that they want the chatBot to remember, it wouldn't.
And in the current case, it would remember it and respond accordingly.

The next feature we have is semantic search. This is mainly performed off of movie data with a single line description of each. This allows the user to type keywords that remotely describes the movies and displays the movie according to their interest. 


Another implemented feature involves training the AI on function calling, which allows the model to be trained with calculating complex mathematical expressions. It also trains the model on image generation. But there are ample of functions and models available to perform using different methods using llama, models on hugging face etc. 

The last implemented feature is Q&A. This is a very good feature, where the user can dictate to the ai about all the information they have. This allows the AI to limit its knowledge base and perform within the known set of information. For sources, I experimented with Youtube data in the form of a URL, and pdf data. Both the sources perform well with QA. Other sources like audio, uploads, etc can also be explored.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Description of UI. 
</div>

To implement this and more or try this on your own, clone my repository and run it.

{% raw %}

```html
git clone https://github.com/Monica-Gullapalli/aiMessage.git
cd pathtoproject/
npm install 
node server.js
```

{% endraw %}
