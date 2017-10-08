## Inspiration
There are approximately *10 million* Americans who suffer from visual impairment, and over *5 million Americans* suffer from Alzheimer's dementia. This weekend our team decided to help those who were not as fortunate. We wanted to utilize technology to create a positive impact on their quality of life.

## What it does
We utilized a smartphone camera to analyze the surrounding and warn visually impaired people about obstacles that were in their way. Additionally, we took it a step further and used the *Azure Face API* to detect the faces of people that the user interacted with and we stored their name and facial attributes that can be recalled later. An Alzheimer's patient can utilize the face recognition software to remind the patient of who the person is, and when they last saw him.

## How we built it
We built our app around *Azure's APIs*, we created a *Custom Vision* network that identified different objects and learned from the data that we collected from the hacking space. The UI of the iOS app was created to be simple and useful for the visually impaired, so that they could operate it without having to look at it.

## Challenges we ran into
Through the process of coding and developing our idea we ran into several technical difficulties. Our first challenge was to design a simple UI, so that the visually impaired people could effectively use it without getting confused. The next challenge we ran into was attempting to grab visual feed from the camera, and running them fast enough through the Azure services to get a quick response. Another challenging task that we had to accomplish was to create and train our own neural network with relevant data.

## Accomplishments that we're proud of
We are proud of several accomplishments throughout our app. First, we are especially proud of setting up a clean UI with two gestures, and voice control with speech recognition for the visually impaired. Additionally, we are proud of having set up our own neural network, that was capable of identifying faces and objects.
 
## What we learned
We learned how to implement *Azure Custom Vision and Azure Face APIs*  into *iOS*, and we learned how to use a live camera feed to grab frames and analyze them. Additionally, not all of us had worked with a neural network before, making it interesting for the rest of us to learn about neural networking. 

## What's next for BlindSpot
In the future, we want to make the app hands-free for the visually impaired, by developing it for headsets like the Microsoft HoloLens, Google Glass, or any other wearable camera device.
