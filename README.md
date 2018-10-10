## Idea 
Our idea revolves around predicting and managing flood disasters in India.

#### Our idea can be divided into 3 main parts:

#### 1) Pre-Disaster: 
  1. Using time-series data to study life-cycles of the natural phenomenon (Meteorlogical numerical, social-media texts, news reports, or/and satellite images) 
  2. Once main characteristics are extracted, we can suggest early warnings if a similar life-cycle is detected in areas. 
  3. Using social-media text data, studying the peaks in certain sentiments, we can give a generic warning.
  4. Using satellite imagery, we can study the pre-onset developments that take place, and suggest areas that will get the least affected and areas of maximum impact, based on latitude-longitude.
  5. Using meterological data, we can study the behaviour of certain parameters that result in the calamity, thus warning local stations to alert their local areas to prepare better.

#### 2) During-Disaster: 
  1. Using the extracted life-cycles of previous disasters, their onset, their duration and how they receeded and the casualties and post-disaster effects, we can now predict the best solutions for the current disaster, and thus help in better targeting of relief funds.  
  2. As Connectivity is a big issue during such disasters, we can deploy network boosters using quadcopters.
  3. The quadcopters can also use thermal imaging to locate stranded survivors.
  4. Since network availabilty is an issue, we suggest using FM/AM radio network instead, which are built into all smart-phones and any electronic device, and can be used for 2-way communication even in long-ranges. Survivors can broadcast to a local tower and ping themselves, or/and be relocated to the nearest shelter.
  5. Locating stranded survivors can be enhanced by detecting relief-requests from social-media text data, where family members or friends report missing persons in the affected areas.
  6. Using satellite imagery/offline-Google-Maps, we can generate optimal routes so that relief-groups can deliver help to affected areas more faster.
  
#### 3) Post-Disaster:
  1. Using post-disaster meterological data and life-cycle history, we can suggest the most probable diseases that will spread and how they can be tackled. We can also predict the ares where receeding takes place the quickest and slowest for better targeting of evacuation stratergies.
  2. Using social-media we can suggest what sort of relief help was expected during(food, clean water, sanitary products, batteries, etc) and after(cleaning products, clothes,etc ) the disaster, based on previous experiences. 


We plan on getting our data as:
1. Meterological data from Indian Meterological Department
2. Social media text from Twitter,Facebook APIs and Google analytics for word-clouds
3. Satellite imagery from NASA lat-long public datasets, etc. 

Once we have acquired the dataset, we plan on implementing the idea using image segmentation and feature learing, text mining and swarm clustering data models to use all the data-formats and correlate the trends so that we get more concrete conclusions and predictions. 

We plan on using hadoop big data anlytics, google big query, fast.ai, tensorflow or pytorch, microsoft cognitive toolkits, etc. The dependencies might change as we dive deeper into the dataset.

The deliverables include
  1) a predictive model (in the form of an app, or a website, or a portable service) that takes in the mentioned dataset information through the internet and outputs the mentioned suggestions during pre-disaster and post-disaster. 
  2) a predictive model that makes suggestions during-disaster using historical data, that does not depend on connectivity or real-time data. This will include suggesting optimal routes, thermal imaging, etc.
  3) the app/service will also include a FM/AM-based pinging service to be used by stranded survivors during-disaster, and to communicate with the surveillance quadcopters.
  
Since the service provides predicitions mostly based on extensive historical data, using it in areas of 0 or low connectivity is feasible, without compromising on maximum impact.

### CodeFunDo++ 
Microsoft Academia Accelerator 2018 - Predict Natural Disasters

  





