# Feedback
A platform for creating art using AI, from concept to final product, driven by you

## Preview
![create-resized-bigger](https://user-images.githubusercontent.com/28934246/176083850-11a0ae0c-be65-41bd-85dd-4ba23735ce8d.gif)

## Motivation
The barrier to entry for interacting directly with ML models is simply too high relative to the power of current models. In order to educate and excite the general public about the current state of AI, interactions with AI that users may not recognize as AI-enabled applications such as recommendation engines and computer vision pipelines should be supplemented with platforms that *centralize available models and allow users to experiment with chains of models with as little friction as possible*. Feedback is one of those platforms, granting users access to algorithmic generation of unique concepts alongside a suite of ML models to interpret those concepts and bring them to life.

## Closed-Loop
Everything you see and read on Feedback is created by a computer. There are no user uploads or comments of any kind, this keeps the state space small and prevents the injection of any inappropriate content.

## Example
![explainer_explained_450x450](https://user-images.githubusercontent.com/28934246/176085952-e57a4490-c03f-41dd-bc89-f3f6f8b664f9.svg)

Images Synthesized by DALL·E mini

![SynthesizedImages](https://user-images.githubusercontent.com/28934246/174739854-43af3b81-8d44-44b4-9e38-438c2b37ccfc.png)

Stories Written by davinci
> She was designed to explore the farthest reaches of the cosmos, and her crew was made up of the bravest and most courageous astronauts. Newton was the most advanced spacecraft of her time, and she was equipped with the latest and most sophisticated technology.

> The Newton was created eons ago, when the universe was still young. It was shaped like a perfect sphere, with a diameter of nearly a hundred thousand miles. It was blue, like the deep waters of an ocean, and it was made of a strange biological material that no one could identify. Its purpose was exploration, and it was dispatched to the farthest reaches of the cosmos to discover new worlds.<br />The Newton orbited a small, rocky planet for many years, gathering data and sending it back to the home world. eventually, the Newton ran out of fuel and was forced to land on the planet. It has been there ever since, its data still being studied by the scientists who created it.

> The huge, ancient spacecraft Newton was destroyed in a spectacular explosion of ethereal blue light. The regular shaped ship had been on a mission of exploration into deep space when it suddenly encountered an unidentified biological material. Upon contact with the material, the ship's hull was breached and the resulting explosive decompression vaporized everything inside instantaneously. There is no known survivors of the incident.

> A huge, ancient, regular blue spacecraft called Newton is discovered orbiting a distant planet. It is of unknown origin, and its purpose is exploration. Upon closer inspection, it is determined to be of biological origin, and is covered in a strange blue goo.<br />The goo is found to be a living organism, and is responsible for powering the spacecraft. It is unknown how long the goo has been alive, but it is determined that it is of extraterrestrial origin. The goo is studied, and it is found to be harmless. However, it is also found to be highly intelligent, and is able to communicate with the researchers.<br />The goo is able to explain that it is an explorer, and that it comes from a planet that is far away from our own. It says that its planet is in a dying state, and that it was sent to find a new home for its people. The goo also says that it has been traveling for a very long time, and that it is the only survivor of its mission.<br />The researchers help the goo to build a new spacecraft, and it sets off into the vastness of space once again, in search of a new planet to call home.

## Summary
The essence of the Feedback platform can be boiled down to **assets**, **concepts**, and **actions**.
- **Concepts** are uniquely generated at the touch of a button
- **Assets** are interpretations of a concept, created by performing an **action** on either a **concept** or another **asset**
- **Actions** are performed on **assets**, feeding one asset into an ML model to create a new asset

###### What is an asset?
An asset is the base unit of the Feedback platform, every asset has a format (text, image, video, etc.) and some content which represents an interpretation of a concept.

###### What is a concept?
On Feedback, a concept is represented using the following format:
1. Opinion
2. Size
3. Age
4. Shape
5. Color
6. Origin
7. Material
8. Purpose
9. Noun
10. Name

###### What types of actions are available?
The actions available to a given concept or asset depend on the format of that asset. Currently only text and images are supported.

###### Actions
* DeepDream - Psychedelic-like exaggeration of features using algorithmic pareidolia (Image -> Image)
* Super Resolution - Upscale an image (Image -> Image)
* Toonify - Convert faces into cartoon versions (Image -> Image)
* Synthesize Image (Text -> Image)
* Synthesize Image (Concept -> Image)
* Write Story (Concept -> Text)

## Action Chains
Because actions are modular, they can be linked together ad infinitum to create complex chains of actions which output an asset at every step of the way, allowing for the alteration & redirection of concept representation at the lowest level.

## Stack
-     Frontend: NextJS (cloud-hosted using Google's Firebase)
-     Backend: NodeJS (deployed on Heroku w/ Redis caching)
-     Database: MongoDB (5NF w/ multi-faceted aggregation pipelines & tables with 1M+ documents)

## Next Steps
The addition of new actions as well as the improvement and forking of preexisting actions is and will forever be the core of Feedback's iterative process. 
The latest dev version of Feedback includes many features, some of which allow users to:
* Visualize action chains as animations
* Automatically generate the entire state space (within a certain depth)

## A Vision for the Future
###### A Thought Experiment
If you've gotten this far and still haven't spent some time just imagining one of the generated concepts, I implore you to do so now. When this project started as just a short python script for randomly generating concepts, I spent countless time just trying to create as many detailed mental images as I could of each concept that caught my attention. How many different ways can you interpret the term 'biological spaceship'? Perhaps you imagine SpaceX's Dragon capsule coated in a vacuum-proof self-healing finish, or maybe even a galactic-sized space-whale swimming through the cosmos. I would argue that our own bodies belong on the list of biological spaceships, aren't they?

###### Atomic Standardization
The spirit of collaboration through git-style forking is baked deeply into the architecture of the Feedback platform. Imagine if every time you used a tool in photoshop, it publically saved the edit for anyone to build on. These chains of tool use, or action chains, let everyone carve their own paths, diverging from and converging with the work of others at every step of the way.

###### An Engine for Model Improvement
The data generated through users interacting with and rating assets creates a heatmap of affection for the observed state space, allowing for the automatic generation of training data to improve the quality of the unobserved state space.

###### Disability-Proof Accessibility From Day One
The modern world treats accessibility as an afterthought. By classifying assets using their formats, users can filter content based on their specific needs. Alt tags are replaced entirely by irreducible format-independent representations, offloading interpretation entirely to the user.

## Comments? Questions? Concerns? Just want to chat?
My inbox is always open and I'd love to hear your thoughts. You can find my email [on my profile](https://github.com/nslinco).
