awesome-mycroft-community
==========================

**awesome-mycroft-community** is an awesomelist for big, community projects built around Mycroft! It includes companionware, derivatives, and integrations with other systems.

This list is exclusively for third-party projects, for two reasons. First, there is no "authoritative" list of community projects, and the community has grown so large that one is needed.

Second, if something's here, it's explicitly unsupported by MycroftAI. Everything listed is developed or maintained by a community member, so you should not ask the company for tech support, but you should approach the developers on GitHub, the Mycroft forums, or in MycroftAI's official chat. Most of the developers whose projects make this list are (or have been) very active on forums and/or chat.

The primary criterion for inclusion is simple: Projects listed here are large undertakings, with committed developers who can engage with users. This does not mean that projects must be in a usable state, especially if those projects are meant to attract contributors! Everything is in early development at some point.

(Contributors: Please submit all your maintained projects. Please don't submit abandonware. We all have a lot of awesome repos we haven't touched since 2019. Let's not list those.)

----------------------------------------------------------------------------------------------------------------------------------------------

- [awesome-mycroft-community](#awesome-mycroft-community)
    + [Distributions, Images, Projects Shipping Mycroft](#distributions--images--projects-shipping-mycroft)
    + [Mycroft Frameworks](#mycroft-frameworks)
    + [Plugins, STT / TTS Alternatives, Containers & Packages](#plugins--stt---tts-alternatives--containers---packages)
    + [Skill Tooling & Utilities](#skill-tooling---utilities)
    + [Desktop & Mobile Mycroft Integrations](#desktop---mobile-mycroft-integrations)

----------------------------------------------------------------------------------------------------------------------------------------------

### Distributions, Images, Projects Shipping Mycroft
**_A list of Products, Projects, Distributions and Images shipping Mycroft with special emphasis on Voice Input, Voice Assistance targeting specific hardware like SBCs, Smart Speakers, Home Entertainment Systems_**

- **OpenVoiceOS (OVOS)**: Linux distribution for SBCs, purpose-built to showcase the power of Open Source Voice AI for a range of devices. [Project Link](https://www.openvoiceos.com)
- **Plasma Bigscreen**: An open UI stack for your own personal TV box, using various open-source components like Plasma Bigscreen Launcher, Mycroft AI and Libcec. Based on KDE Neon. [Project Link](https://plasma-bigscreen.org/)
- **Chatterbox**: The smart speaker anyone can build and teach! Privacy-first, educational smart speaker to teach kids about coding, artificial intelligence, and privacy. [Project Link](https://hellochatterbox.com/)
- **Mycroft ROS**: This package provides capability to run the Text-To-Speech, Speech-To-Text and Skill functionality of Mycroft AI as ROS nodes providing topics, services and actions for communication. [Project Link](http://wiki.ros.org/mycroft_ros)

### Mycroft Frameworks
**_A list of frameworks built to extend Mycroft's capabilities, which can be used standalone or in conjuction with each other_**

- **HiveMind**: Extends one (or more!) instance/s of Mycroft to as many devices as you like, including thin clients that run on almost anything. Mycroft-native IoT, Mycroft for mobile, satellite devices, nested Mycroft instances. HiveMind: One Mycroft. Many devices. [Project Link](https://github.com/JarbasHiveMind/HiveMind-core)
- **Mycroft GUI Framework**: Mycroft-GUI is a visual and display framework running on top of KDE Plasma technology and built using Kirigami, a lightweight UI framework for convergent applications which are empowered by Qt. [Project Link](https://github.com/MycroftAI/mycroft-gui)

### Plugins, STT / TTS Alternatives, Containers & Packages
**_A list of Plugins, STT, TTS and alternative services that allow you to change the default behaviour of Mycroft in terms of supported voice engines, supported backends, etc_**

- **Mycroft-lib**: Mycroft-lib is a version of Mycroft-core, split into components and repackaged. Aimed at devs and makers who may wish to use only part of the Mycroft stack. [Project Link](https://github.com/HelloChatterbox/mycroft-lib)
- **OpenVoiceOS Local Backend**: Personal Mycroft backend. Alternative to home.mycroft.ai, written in Flask. Meant for personal usage, this allows you to run fully offline. This is NOT meant to be hosted, but rather to run directly on Mycroft devices. [Project Link](https://github.com/OpenVoiceOS/OVOS-local-backend)
- **Mycroft Remote Services Docker**: Mycroft Remote Services is Docker container, comprised of preinstalled packages such as Mycroft Core, Apache, and Mycroft Remote Dashboard, that are configured to serve Mycroft Core services over the local network. [Project Link](https://mycroft.pub/hosting-service/)
- **Dummy Wakeword Plugin**: A simple plugin for disabling wake word. Mycroft will only answer by button_press/bus signal. [Project Link](https://github.com/HelloChatterbox/dummy_wakeword_plugin)
- **Snowboy Wakeword Plugin**: Mycroft wake word plugin for Snowboy. [Project Link](https://github.com/JarbasLingua/jarbas-wake-word-plugin-snowboy)
- **Vosk Wakeword Plugin**: Mycroft wake word plugin for Vosk. [Project Link](https://github.com/JarbasLingua/jarbas-wake-word-plugin-vosk)
- **Nyumaya Wakeword Plugin**: Mycroft wake word plugin for Nyumaya version 1.0.0. [Project Link](https://github.com/JarbasLingua/jarbas-wake-word-plugin-nyumaya-premium)
- **Vosk STT Plugin**: Mycroft STT plugin for Vosk. [Project Link](https://github.com/JarbasLingua/jarbas-stt-plugin-vosk)
- **Chromium STT Plugin**: A STT plugin for Mycroft using the google chrome browser api. [Project Link](https://github.com/JarbasLingua/jarbas-stt-plugin-chromium)
- **ResponsiveVoice TTS Plugin**: Mycroft TTS plugin for ResponsiveVoice. [Project Link](https://github.com/JarbasLingua/jarbas-tts-plugin-responsivevoice)
- **Voice RSS TTS Plugin**: Mycroft TTS plugin for VoiceRSS. [Project Link](https://github.com/JarbasLingua/jarbas-tts-plugin-voicerss)
- **Catotron TTS Plugin**: Mycroft TTS plugin for Catotron. [Project Link](https://github.com/JarbasLingua/jarbas-tts-plugin-catotron)
- **Cotovia TTS Plugin**: Mycroft TTS plugin for Cotovia TTS. [Project Link](https://github.com/JarbasLingua/jarbas-tts-plugin-cotovia)
- **Softcatala TTS Plugin**: Mycroft TTS plugin for Softcatala TTS. [Project Link](https://github.com/JarbasLingua/jarbas-tts-plugin-softcatala)
- **OpenVoiceOS Plugin Manager**: OPM can be used to search, install, load and create plugins for the OpenVoiceOS ecosystem! [Project Link](https://github.com/OpenVoiceOS/OVOS-plugin-manager)

### Skill Tooling & Utilities
**_A list of tools, utilities and alternative intent parsers that can ease your way into Mycroft Skills Development_**

- **OVOS-Utils**: A collection of simple utilities for use across the Mycroft ecosystem. Includes tools and helper functions that extend the Skill API. [Project Link](https://github.com/OpenVoiceOS/ovos_utils)  
- **OpenVoiceOS Skills Manager (OSM)**: Install skills from any appstore! The mycroft-skills-manager alternative that is not vendor locked. This means you must use it responsibly! [Project Link](https://github.com/OpenVoiceOS/ovos_skill_manager)
- **JSON Databases**: Python dict-based database with persistence and search capabilities. For those times when you need something simple and sql is overkill. [Project Link](https://github.com/OpenJarbas/json_database)
- **Nebulento**: A dead-simple fuzzy matching intent parser. Built on top of rapidfuzz. [Project Link](https://github.com/OpenJarbas/nebulento)
- **Palavreado**: A dead-simple keyword based intent parser. [Project Link](https://github.com/OpenJarbas/palavreado)
- **Padacioso**: A dead-simple intent parser built on top of simplematch, inspired by Padaos. [Project Link](https://github.com/OpenJarbas/padacioso)
- **OpenVoiceOS Workshop**: Frameworks, templates and patches for the Mycroft universe. [Project Link](https://github.com/OpenVoiceOS/OVOS-workshop)

### Desktop & Mobile Mycroft Integrations
**_A list of clients, applets, plasmoids, and extensions developed for various Linux Desktop & Mobile Environments_**

- **Mycroft Android Client (Mobile)**: This is the Android companion app to Mycroft-core. It works by opening a websocket connection to the Mycroft-core messagebus and sending and receiving messages from there. It implements voice recognition and Text To Speech (TTS) via Google API's at the moment. [Project Link](https://github.com/MycroftAI/mycroft-android)
- **Mycroft GUI Application (Mobile/Desktop)**: The official Mycroft GUI application that can be run as an application under any Linux desktop environment, Linux mobile environment and even on Android. [Project Link](https://github.com/MycroftAI/mycroft-gui)
- **Mycroft Plasma Applet (Desktop)**: Mycroft applet for Plasma desktop, can be added to any panel or even live on your desktop, It uses Mycroft GUI imports to serve the skills UI right onto your desktop screen. [Project Link](https://invent.kde.org/utilities/mycroft-plasmoid) 

------------------------------------------------------------------------------------------------------------------------------------------------
