

|

Rasa Certification Exam
=======================

 |



#### *1. Name (first and last)



#### 2. What are the two components that make up Rasa Open Source?

NLU and Rasa X

>NLU and Dialogue Management

Intents and Entities

Machine learning policies and NLU pipelines



#### 3. What does the NLU pipeline do?

It defines your assistant's dialogue management

It makes continuous improvements to your assistant

>It defines how a user message is processed and what information is extracted

It contains if/else statements and other conditional logic



#### 4. What are intents?

A key piece of information the assistant needs to extract

>What the user is trying to achieve

A custom action that the assistant will run

An event that triggers a form



#### 5. What is the domain.yml file?

>It defines the world of your assistant

It is a configuration file for NLU and dialogue policies

It's where code for your custom actions resides

It contains your initial model



#### 6. What is DIET?

It is a form action

It is a machine learning policy that handles sub-dialogues

>It is a neural network architecture for intent classification and entity extraction

It is a conversation design tool



#### 7. What do policies do?

>They control dialogue management and decide which action to take at every step in the conversation

They're a way to set up and configure CI/CD pipelines

They create the NLU model

They do slot filling



#### 8. What's one difference between a sequence model and a non-sequence model?

A sequence model is one where word order is not captured and a non sequence model is where word order is captured

A sequence model is faster to train whereas a non sequence model is slower to train

A sequence model has more data whereas a non sequence model doesn't have as much data

>A sequence model is one where word order is captured and a non sequence model is where word order is not captured



#### 9. When should you use Rasa end-to-end testing?

When you have large amount of training data

When you deploy your assistant in production

When you build a first viable assistant

>Every time you make improvements to your training data and models



#### 10. Which command is used to run end-to-end testing with Rasa?

rasa e2e-test

>rasa test

rasa test e2e

rasa e2e test



#### 11. Which Rasa component is responsible for maintaining the state of dialogue?

slots

dispatcher

entities

>tracker



#### 12. Which of these is NOT a way slots can be set in Rasa?

>By the NLU model

By custom actions

By the lock store

By providing an initial value



#### 13. Does the value of the categorical slot type influence the conversation path?

>Yes

no



#### 14. In which file should you list the names of your custom actions?

Credentials.yml

Endpoints.yml

>Domain.yml

Config.yml



#### 15. You should use forms when:

You want your assistant to always give the same response to a certain utterance

>You need to collect required pieces of information from the user before executing an action

You want your assistant to call an API

The assistant needs to ask the user to rephrase their statement



#### 16. Which Rasa component is responsible for running custom actions?

>Rasa SDK

NLU component

Dialogue management component

Rasa X



#### 17. What does the submit() method in Rasa form action do?

Defines the name of the the form

Validates the slot values

>Defines what should happen when the form is completed

Specifies how many times the assistant should ask for a piece of information



#### 18. What needs to happen after making changes to the actions.py file so your changes take effect?

>Nothing, the updates will be picked up automatically

You should restart your assistant

You should restart your action server

You should restart your action server and your assistant



#### 19. At what point in your development should you start using Rasa X?

It should be the very first thing you set up

>After you have built a minimum viable assistant (a simple assistant that can handle basic conversations)

Once you have run out of all the possible ways you think a user might talk to your assistant

After months of designing and planning without having users try your assistant



#### 20. What is end-to-end testing?

A method for testing your action code

A way of measuring the percentage of users that got frustrated with your assistant

>A format for testing whole conversations to make sure both the NLU and dialogue models make correct predictions

Another name for giving your assistant to real users to test



#### 21. After you connect your assistant to Rasa X, you can:

Only make changes to your assistant in Rasa X

Only edit your assistant's code in your local text editor

>Make changes in Rasa X or in your text editor depending on the nature of the changes

Never update your assistant's code again



#### 22. What is the easiest way to connect your assistant with Rasa X?

Rebuild it in Rasa X

>Connect the assistant's Git repository using Integrated Version Control

Upload file by file

Use FTP



#### 23. What is the relationship between Rasa Open Source and Rasa X?

Rasa X is the latest version of Rasa Open Source

>Rasa X is a set of tools for improving an assistant built with Rasa Open Source

Rasa X replaces Rasa Open Source

Rasa X is the hosted version of Rasa Open Source



#### 24. Which of the following code hosting platforms can you connect with Rasa X?

GitHub

BitBucket

GitLab

>All of the above - you can use any code hosting platform based on Git



#### 25. What is the best way to improve your assistant?

>Train with real user conversations

Keep adding custom actions

Keep adding conditional logic

Always include the Keras policy



#### 26. Which of the following is NOT a benefit of using a CI/CD pipeline?

Tests can be automatically run

>Setup and configuration require a lot of upfront investment

Deployment can occur semi-automatically or automatically

It makes your software development lifecycle faster because your workflows are automated



#### 27. Which of these is false about deploying Rasa on Kubernetes?

>Kubernetes can only be used to deploy the assistant on a single host machine

Kubernetes has the ability to replicate more pods if one host machine goes down

A command line tool called kubectl is used to interact with the cluster

The Helm package manager is used to configure the deployment



#### 28. How do you upgrade to a new version of Rasa X when you've deployed using the one-line deploy script?

Send a request to the /rasax/update API endpoint

>Re-run the one-line deploy script and it'll install the newest version

Export the RASA_X_VERSION="x.xx.x" environment variable, specifying the new version of Rasa X, then run 'kubectl restart'

Run the 'kubectl update' command



#### 29. Which of the following statements about TED (Transformer Embedding Policy) is true?

TED uses RNNs to handle dialogues

TED uses LSTMs to handle dialogues

TED can be substituted for DIET

>TED uses a transformer architecture to handle dialogues



#### 30. Where does Rasa sit in your conversational AI stack?

Rasa is the computation layer

Rasa serves as the application layer for your AI assistant

>Rasa is the standard infrastructure layer for conversational AI

Rasa is a conversation design tool

Done
