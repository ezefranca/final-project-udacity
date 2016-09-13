# MCupom
> __*MCDonald's Brazil Cupom Generator*__

This is an iOS app that provides a way to get discount cupoms of MCDonald's Brazil.

**Table of Contents**

* Project Overview
    - Selecting MCDonald
* Installation
    - Getting the Code
    - Running the Code
* Usage
    - Information Detail
    - App Execution
* Udacity Notes
    - Exceed Requirements
    - Additional Features

## Project Overview

This project was developed to satisfy the final requirement for graduating from [Udacity's iOS Developer Nanodegree program](https://www.udacity.com/course/ios-developer-nanodegree--nd003). For this final project, the student is directed to select a project of their own choosing and subsequently design and develop an app that satisfies the course's grading rubric.

## Installation

### Requirements
* Xcode 7.3
* iOS 9.3 SDK
* a Mac that runs the above (OS X 10.11.4)

### Getting the Code
Download or clone the repository using your preferred method. The following command for cloning the repository is an easy way to do this:

    git clone git@github.com:ezefranca/final-project-udacity.git
    
    ps: The final version is not avaliable in Github for now. Use the zip file.

### Running the Code
To set up this project:

Terminal: sudo gem install cocoapods
Terminal: pod install
Open the generated MCCupom.xcworkspace. You can then run it on the simulator from within Xcode.

## Usage
The __MCupom__ app lets you gena discount cupom and use or share.

## Udacity Notes
This app is being submitted with the expectation that it meets and exceeds all the given requirements in the rubric. Sorry if it doesn't!

### Exceed Requirements
Additional detail on meeting the *“exceed requirements”* portion of the specs:

1. **Multiple Networked API** – this application accesses two external API: [FourSquare](https://developer.foursquare.com/docs/venues/search) for the venues list and [MCDonald](http://cupons.mcdonalds.com.br/br) for the cupoms.

2. **A Sophisticated Data Model** – this application contains three model entities (Student, Session, and Venue). These entities have various relations with each other, mostly centering around Session.

3. **Core Data Cache** - To cache some data I used CoreData. 

4. **Push Notification** - The app are able to send push notifications using *PushWizard* (commented for certificates reasons)
5. 
### Additional Thanks

Thanks for yours feedbacks along the all projects, and your time!!

