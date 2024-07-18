---
layout: page
title: Multimodal Emotion Cause Pair Analysis in Conversations
description: using Natural Language Processing
img: assets/img/4.jpg
importance: 1
category: work
related_publications: true
---
The Competition of Multimodal Emotion Cause Analysis in Conversations

    ---
    link: https://github.com/tarunannapareddy/NLP-SemEval-2024/tree/main
    ---
   
## Task
We first clarify the definitions of emotion and cause before introducing the task. 
- **Emotion** is a psychological state associated with thought, feeling and behavioral response. In conversations, emotions are usually annotated at the utterance level. In our dataset, emotion categories are Ekman’s six basic emotions including *Anger*, *Disgust*, *Fear*, *Joy*, *Sadness* and *Surprise*. 
- **Cause** refers to the objective event or subjective argument that triggers the corresponding emotion.

Based on the multimodal conversational emotion cause dataset [ECF](https://github.com/NUSTM/MECPE), we define two subtasks, each of which contains two slots.

<img src="https://github.com/NUSTM/SemEval-2024_ECAC/raw/main/example.png" alt="example" width="900" height="600">

### Subtask 1: Textual Emotion Cause Analysis in Conversations
In Subtask 1, an emotion cause is defined and annotated as a textual span. 
- **Slot 1: Emotion Cause Extraction**  Extracting the corresponding textual cause spans given a target emotion utterance in a conversation. As shown in Figure 1, given the Joy emotion in Utterance 3 (U3), the system needs to extract the cause that triggers this emotion in terms of a textual span, i.e., U2\_“You made up!”.
- **Slot 2: Emotion-Cause Pair Extraction**  Extracting all emotion-cause pairs from the given conversation, where each pair contains an emotion utterance along with its emotion category and the textual cause span, e.g., (U3\_Joy, U2\_"You made up!").

### Subtask 2: Multimodal Emotion Cause Analysis in Conversations

It should be noted that sometimes the cause can not be reflected in text only, and we accordingly propose a multimodal subtask to extract emotion cause in all three modalities (language, audio, and vision). For example, the cause for Phoebe’s Disgust in U5 is that Monica and Chandler were kissing in front of her, which is reflected in the visual modality of U5. In this case, cause is defined and annotated at the utterance level.

- **Slot 1: Emotion Cause Extraction**  In consideration of three modalities, extracting the corresponding cause utterances given the target emotion utterance, e.g., given the Disgust emotion in U5, to predict the cause utterance U5.
- **Slot 2: Emotion-Cause Pair Extraction**  In consideration of three modalities, extracting all emotion-cause pairs in the conversation, where each pair contains an emotion utterance along with its emotion category and a cause utterance, e.g., (U5\_Disgust, U5).


If you want to try this code out then you can go and clone the repository at 

{% raw %}

```html
git clone https://github.com/tarunannapareddy/NLP-SemEval-2024.git
```

{% endraw %}
