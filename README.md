# The Xen Project

Welcome to the Xen Project, home for everything Xen Related (at least when it comes to comes this specific xen project). It was created for authors, illustrators, voice and body type actors, muscians, 2D and 3D animators for the audience. Basically if you can create or visualize it, we hope to aid in your journey into creating a new world for people to enjoy.

> Project Xen was and is created by an individual and individuals who want nothing more than to create new worlds and to experience those worlds created by others. Whether it's a simple book or novel, coimic or game. We wish to experience it as though it was originally a movie or vr experience.

Xen is an open community type platform for books, movies, comics and games. Not necessarily in that order, nor implemented in the ways you may initally think or hope for. The core goal can be described to create a "Universal" type "script" for content creators to *"easily"* transition their works into different adaptaions.

As project Xen is still in active devlopment, we hope you will be patient as we begin creating something completly different from what you have ever known. Our goal, to unite every possible type of creator and pair them with the resources require to bring their work to live.



## Project Road Map

- Digital Novels
  - Support for basic Mobile and Desktop Novels
    - Including Chapter or Acts Navigation
    - Highlighting and Bookmarking
  - Inline comments and chapter comments (for the community to interact and share)
  - Audio Book Support with **live text**
  - Support for definitions/dictionary
- Digital Comics
  - Support for "limitless scroll" and "page" swipe (up/down or left/right navigation)
  - Support for **live text** with audio
  - Support for **live translations** (text is separate from images to allow quick translations or definitions)
- Text Adventures
  - A text based game where the reader choses the outcome of the story.
- Visual Novels
  - A graphic based game where the reader choses how to the story ends.
- Community Interactions
  - From The Creators
    - Custom "Stickers" allowing the community to post and share in comments and other locations 
      - Support for External Keyboard/ Image Keyboard
      - Support for story linking (allows the user to link back to the origin of the "sticker")
    - TBA (To be Announced)
  - To The Creators
    - Support The Creator
      - Allow Donations directly to the Creators (Authors, Illustrators etc.)
    - Rate The Book/Story/Game/Comic etc.
      - Allow the audience to rate between 1-5
      - Allow the audience to vote between their favorite and currently reading books/story etc.
        - A fair based system where the audience decides currently trending 
  - For The Audience
    - Community Chat
      - Every Story has a community chat for the audince to communicate with each other live with possible support for text translation (or separate chat rooms per language)
      - Limited Chat "Space" and "time"
    - Creators Chat
      - Creators are able to start a live chat room to communicate with their audience
      - Limited Chat "Space" and "time"
    - Audience Chat
      - Allows the audience to directly message each other
      - Allow for group chats
      - Chat is deleted after limited time
    - Public Profile
      - Allows Friends and used for almost everything
    - Private Profile
      - Used when Anonymity is needed. (No friending allowed)
- World Interactions
  - 
- Xen Audio
- Xen Art



## The *.Xen* File

At the core of all Xen projects is the `Xen` file. It contains all the information about the project and serves as the root of the project.

A *.xen* file is a directory with the following structure :

```
projectName.xen
	-> assets
		-> audio
			(contains all audio files for the project *organized and managed by the user*)
		-> images
            (contains all images for the project *organized and managed by the user*)
		-> models
            (contains all 3D models for the project *organized and managed by the user*)
	-> content
		(the core of the project. This is where everything is created)
		-> stories
		-> world
	-> products
		-> novels
		-> comics
		-> visual_novels
		-> text_adventures
	-> schemas
```

