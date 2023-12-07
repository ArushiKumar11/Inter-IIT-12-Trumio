# TRUMIO
### AI Powered University Based Ecosystem
---

UniConnect is a standalone application built on Trumio's base platform to enhance its ecosystem, upskill student talent, and engage alumni.

---

## Main Features (Both web and app-based)
* **CIA**: Collective Intelligence Agents (CIAs) are LLMs trained upon specialized information, initiated with additional context prompts.CIAs can also be added as team members while creating a new team on Trumio. They can act as project managers, code reviewers, meeting assistants, etc.
* **Mentorship Availability**: Students can explore mentor profiles and view their availability. They can book sessions, connect for personalised guidance and rate their experiences for a transparent learning journey.
* **Communities Page**: Connecting alumni and students through dynamic posts, chats, reactions, and comments, fostering engagement and nostalgia in global and club-specific communities.
* **TruNotes**:Create save and organize notes and acccording to permissions publish it to specific communities.
* **Gamification**: Users earn badges and sparks for their activity and achievements, and compete on the leaderboard for recognition. Tiers will be displayed on the student’s profile and will help clients become aware of their skill level.

* **Extensions**:
    * ChatBot
    * Milestone Tracker
    * Code Summariser





## Setting up the project in your local environment💻

### 1. [Fork]( https://github.com/botketan/Trumio/fork) this repository.<br>
   OR <br>
   
   On GitHub.com, navigate to the [repository]( https://github.com/botketan/Trumio).<br>
         
   In the top-right corner of the page, click **Fork**.

### 2. Clone the **forked** repository:
   
   
   On GitHub.com, navigate to **your fork** of the repository.<br>
         
   Above the list of files, click `<> Code` . Copy the url mentioned. Go to the location where you want the cloned directory.<br>
         
   In the terminal Type -`git clone` , and then paste the URL you copied earlier. It will look like this, with your GitHub username instead of YOUR-USERNAME:<br>
         
   `git clone https://github.com/YOUR-USERNAME/<repo link> `<br>
   
   Press Enter. Your local clone will be created.
      

## Installation

### Prerequisites

1.  [Git](https://git-scm.com/downloads).
2.  [Node & npm](https://nodejs.org/en/download/) _(version 12 or greater)_.

Move to the clonned repository in your local environment

### Steps to Set up Backend
* Move to backend folder - `cd backend `
* Install the required nodes modules package - `npm i`
* Start the development server - ` npm start `

### Steps to Set up Frontend
* Move to frontend folder -`cd frontend `
* Install the required nodes modules package - `npm i`
* Start the development server - ` npm start `
  
  > The model will be served on **http://localhost:3000/**
           

## Directory Structure
```
├───.vscode
├───app
│   ├───android
│   │   ├───app
│   │   │   └───src
│   │   │       ├───debug
│   │   │       ├───main
│   │   │       │   ├───kotlin
│   │   │       │   │   └───com
│   │   │       │   │       └───example
│   │   │       │   │           └───app
│   │   │       │   └───res
│   │   │       │       ├───drawable
│   │   │       │       ├───drawable-v21
│   │   │       │       ├───mipmap-hdpi
│   │   │       │       ├───mipmap-mdpi
│   │   │       │       ├───mipmap-xhdpi
│   │   │       │       ├───mipmap-xxhdpi
│   │   │       │       ├───mipmap-xxxhdpi
│   │   │       │       ├───values
│   │   │       │       └───values-night
│   │   │       └───profile
│   │   └───gradle
│   │       └───wrapper
│   ├───assets
│   │   └───nav
│   ├───fonts
│   ├───ios
│   │   ├───Flutter
│   │   ├───Runner
│   │   │   ├───Assets.xcassets
│   │   │   │   ├───AppIcon.appiconset
│   │   │   │   └───LaunchImage.imageset
│   │   │   └───Base.lproj
│   │   ├───Runner.xcodeproj
│   │   │   ├───project.xcworkspace
│   │   │   │   └───xcshareddata
│   │   │   └───xcshareddata
│   │   │       └───xcschemes
│   │   ├───Runner.xcworkspace
│   │   │   └───xcshareddata
│   │   └───RunnerTests
│   ├───lib
│   │   ├───models
│   │   ├───requests
│   │   ├───screens
│   │   ├───utils
│   │   └───widgets
│   ├───test
│   └───web
│       └───icons
├───backend
│   ├───.adminbro
│   ├───config
│   ├───controllers
│   ├───models
│   └───routes
├───frontend
│   ├───public
│   └───src
│       ├───Assets
│       ├───components
│       │   ├───BookSession
│       │   ├───CIA
│       │   ├───Comments
│       │   ├───Crousel_Achievements
│       │   ├───Leaderboard
│       │   ├───Mentor
│       │   ├───MilestoneTracker
│       │   ├───noteList
│       │   └───NotesComponent
│       ├───hooks
│       └───pages
├───notion-clone
│   ├───.trunk
│   │   └───configs
│   ├───app
│   │   ├───(main)
│   │   │   ├───(routes)
│   │   │   │   └───documents
│   │   │   │       └───[documentId]
│   │   │   └───_components
│   │   ├───(marketing)
│   │   │   └───_components
│   │   ├───(public)
│   │   │   └───(routes)
│   │   │       └───preview
│   │   │           └───[documentId]
│   │   └───api
│   │       └───edgestore
│   │           └───[...edgestore]
│   ├───components
│   │   ├───modals
│   │   ├───providers
│   │   └───ui
│   ├───convex
│   │   └───_generated
│   ├───hooks
│   ├───lib
│   └───public
└───trumio-agents
    ├───.vscode
    ├───API
    ├───media
    │   ├───bot
    │   ├───milestone
    │   └───web
    └───test
        └───suite
 ```

