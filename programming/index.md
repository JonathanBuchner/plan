# Program project ideas

## GPS wildlife or pet tracking

### Idea
Create a small device that has power and sends GPS coordinates to ioT server.

### Who it helps

There are a lot more possible uses, but I wanted focus on options that would explore low power usages and far away from service towers.  Honestly, this has so many possible uses.  My first idea is tracking pets and wild life.

### Stack

Again, lots, but I vote for Wilderness Lab boards and Azure IOT,

### MVP

Create a small device that has power and sends GPS coordinates to server.

## Get help now box

### Idea

We use Rasberry pi or esp32 chip to create a device that when someone turns it on, it provides resources specific to their area and need.  A resource could be a link to help or even a button that makes an auto dial phone call.  This could be more of an emergency stand or something to hand someone.

### Who it helps

We decided on a target audience.

### Language / Stack

So many possibilities, by my vote would be Electron, so Node, JavaScript, Chromium.  Essentially it could be device agnostic and more like a webpage.  Electron is one part Chromium, one part Node.JS and basically allows you to create a desktop app using web technologies.

### MVP

A device with a screen that you turn on that gives you a menu with at least one useful option.

## Audio sentiment translation tool

### Idea

This device records audio.  It could store the audio on the cloud.  It then uses a sentiment engine to evaluate the audio.  The sentiment engine could be changed over time, but would first be an API call to like an Azure Cognitive service.  It would be cooler if the engine ran on the device, not the server, but I don’t think that is realistic. Eventually I like the idea of transcription and then a tool like ChatGPT to provide feedback.

### Who it helps

Variety of uses, but one would be a neutral source as a self counseling tools.  Meaning, you turn it on when you are having a difficult discussion with a partner and it would provide like two pieces of feedback or let you know how combative your tone was.  There are some powerful features of audio analysis tools out.  If this was to include ChatGPT or other service, the feedback would be a lot more interesting.

### Stack

My vote is an IoT device, Azure IoT hub, Azure cognitive services.

### MVP

Can listen and audio is stored somewhere and at least one thing is done with the audio, even as simple as an API transcription call.

## Custom markdown processor

### Idea

This would take a markdown file and compile it to display on a react page or as an eBook.  This tool would be more specific to needs we identify rather than some of the tools already out there.  This is similar to how Microsoft Docs work.

### Who it helps

I personally want to write an open source book called the essential developer and I would use a tool like this to convert it from mark down to other formats.  This would support any of use who want to blog, write a book, etc. and put it in markdown and have it display on a page.

### Stack

Markdown…otherwise, really open to any other frameworks or ideas.  This could also be approached as working on someone else’s open stack project.

### MVP

Can compile standard markdown into at least one format.

## Custom markdown processor

### Idea

This would take a markdown file and compile it to display on a react page or as an eBook.  This tool would be more specific to needs we identify rather than some of the tools already out there.  This is similar to how Microsoft Docs work.

### Who it helps

I personally want to write an open source book called the essential developer and I would use a tool like this to convert it from mark down to other formats.  This would support any of use who want to blog, write a book, etc. and put it in markdown and have it display on a page.

### Stack

Markdown…otherwise, really open to any other frameworks or ideas.  This could also be approached as working on someone else’s open stack project.

### MVP

Can compile standard markdown into at least one format.

## ChatGPT (or similar) extender

### Idea

I want to extend a trained model to only provide responses for a subset of topics, such as help directions for using a moon lander fucking keyboard.  Really what I want to do is research and see how hard this is.

### Who it helps

Depends on who we train the model for.  I would vote we explore this space and then come up with an application.

### Stack

IDK?

### MVP

You can ask the model questions either through text or audio and it returns a response as text or audio.

## Extend open source ffmpeg

### Idea

The driver here is I have always wanted to contribute to an open source project and I love ffmpeg.  One simple extension that I have wanted to do is create .wav point files.  I’m not sure how much this idea would interest everyone.

https://www.ffmpeg.org/

### Who it help

FFMPEG is used by everyone who has to do something with audio and video, but it’s pretty unfriendly.   The wave points idea is just something easy that I don’t believe ffmpeg has and it’s a desired feature.

### Stack

This would require writing code in c++.  It’s simple, but would require also learning how lossless and lossy audio formats work.

### MVP

Locally we can create a 4096 points for a .wav file.