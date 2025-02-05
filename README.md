# Autogpt - podcast maker
AutoGPT - Podcast Maker is an AI-powered pipeline designed to generate structured solo podcast episodes. It automates the process of creating a podcast agenda, script, and AI-generated cover image, leveraging OpenAI's LLMs and Wikipedia for context enrichment.

![Podcast Cover](https://github.com/Taweilo/autogpt_podcast_maker/blob/main/podcast.png)
[![Listen to the Podcast](https://img.shields.io/badge/Listen%20Now-Click%20Here-blue)](https://github.com/Taweilo/autogpt_podcast_maker/blob/main/final_podcast.wav)

## Dependencies
- OpenAI API
- LangChain
- Wikipedia API
- Google Colab (for userdata usage, optional)
  
## Agent role
1. Podcast Supervisor: Generates a structured agenda for a solo podcast episode, ensuring logical flow and relevance to the given topic.
2. Copywriter: Expands the agenda into a fully developed podcast script in a conversational and engaging style.
3. Visual Designer: Creates an AI-generated image prompt for the podcast cover, capturing the essence of the topic.
   
## Steps of the Chain
The podcast-making pipeline follows these sequential steps:
1. Agenda Generation (Podcast Supervisor):
  - Receives the topic and tone.
  - Creates a logically structured podcast agenda.

2. Script Generation (Copywriter):
  - Uses the topic and agenda to create a natural, engaging monologue.
  - Fetches relevant Wikipedia data for additional context.
  - Ensures smooth transitions and fluid delivery.

3. Image Prompt Generation (Visual Designer):
  - Generates a concise and vivid prompt for AI-based image generation.
    
Example Execution:     
`output = run_podcast_pipeline(topic="The Future of AI in Healthcare", tone="casual")`

## Output 
The final output consists of:
1. Podcast Agenda: A structured outline for the podcast episode.
2. Full Script: A conversational podcast monologue ready for narration.
3. Image Prompt: A descriptive AI-generated prompt for a podcast cover image.

## Result 
