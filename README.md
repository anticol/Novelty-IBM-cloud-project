# Novelty
Project Novelty aims to create the news application for people with impaired vision and hearing, and to provide the integration into the application as a service. The concept of voice synthesizing is being progressively more used, but there is no application what would allow the news websites to have their source customized and integrated into the single app that will be used by people with vision impairment. With use of the IBM technologies, we are able to create a scalable solution for news integration, while building a single app that will contain all the news sources and will be used by the end-users. 


# How to run API:
1. cd api
2. npm install
3. Create ".env" file in "api" folder 
  - Set TEXT_TO_SPEECH_API_KEY=
  - TEXT_TO_SPEECH_API_URL=
4. node index.js --> localhost:3000 (localhost:3000/synthesize?text=Hi David?)
