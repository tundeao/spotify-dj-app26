# Spotify Integrated DJ Sets Application

## User stories and conditions of satisfaction: {#user-stories}

1. **Song Linking/Queue Building:** As a user of the application, I want to be able to visually create a queue of songs that can connect to each other through criteria or audio characteristics, creating a cohesive DJ-style set or learn how songs can relate to one another
   1. [ ] There should be an interface that allows users to visually add, remove, and reoder songs through search and drag-and-drop *(Essential)*
   2. [ ] There should be a metric that indicates the "connection strength" between adjacent songs, calculated through selected audio features *(Essential)*
   3. [ ] Users should be able to select certain features (tempo, energy, key, mood, etc.) that are used to dynamically create a list of songs that can be mixed together *(Essential)*
   4. [ ] There should be the ability to search for and add songs from Spotify'a catalog to the set *(Essential)*
   5. [ ] Users should be able to integrate their own Spotify accounts, giving the ability to import existing playlists into set builder *(Essential)*
   6. [ ] If 2 songs have a weak connection, system should sugges intermediate "bridging" songs that create a smoother path between them *(Essential)*
   7. [ ] Users should be able to view a representation of the features being considered to build a queue, such as a graph showing tempo/energy/mood progression over time *(Desirable)*
   8. [ ] Users should be able to save built queues to their Spotify accounts *(Desirable)*
   9. [ ] Users should be able to set a "destination" target song, allowing the system to navigate and suggest a path from the current song to the target (Desirable)
   10. [ ] System should warn users when adjacent/upcoming songs may have jarring transitions (awk changes in key, large bpm jumps, etc.) *(Desirable)*
   11. [ ] There should be the ability for annotating certain songs with custom tags that allow for personal organization *(Extension)*

2. **Transition and Mixing Suggestions:** As a user of the application, I want to view suggestions for how and/or when to transition between songs in the que, allowing me to learn mixing techniques or enjoy seamless listening experiences.
   1. [ ] There should be a toggleable crossfade transition available between all songs with an adjustable duration *(Essential)*
   2. [ ] Users should be able to preview how a transition will sound before committing to it *(Essential)*
   3. [ ] The system should suggest transitions based on characteristics of adjacent songs *(Essential)*
      > e.g., try a long blend—similar BPM and energy" or "quick cut recommended—tempo mismatch"
   4. [ ] There should be a plethora of options for transition types, like hard cuts, crossfades, overlaps/blends with configurable parameters *(Essential)*
   5. [ ] System should use the circle of fifths to identify songs with that share the same or compatible musical keys, and highlight them as strong harmonic matches *(Desirable)*
   6. [ ] Users should be able to view tooltips or explanations for what makes a recomended transition to boost learning of DJ mixing principles *(Desirable)* 
   7. [ ] Users should be able to manually annotate transition points within songs for more precise control *(Extension)*

3. **Autopilot Mode/Playback:** As a user of the application, I want to listen to my queue with smooth transitons applied in real-time, with the option to automatically continue generating the set when I'm not actively making choices, allowing me to enjoy an uninterrupted DJ-style listening experience
   1. [ ] There should be a playback mode that allows the queue to play with transitions automatically applied between songs *(Essential)*
   2. [ ] There should be an autopilot mode that selects and connects songs based on the current song's audio features and user preferences when the queue is empy or unattended *(Essential)*
   3. [ ] Users should be able to intervene and change the order of autopilot suggested songs to override the selection or adjust parameters *(Essential)*
   4. [ ] Users should be able to set parameters on features to guide autopilot, through the selection of characteristics like target mood, energy trajectory (like build up, maintain, wind down) and genre constraints *(Essential)*
   5. [ ] There should be a history kept of the songs played in each session, allowing users to view the order, reccomendations for songs that were queued, etc. *(Desirable)*
   6. [ ] Users should be able to enter "discovery mode" on autopilot, where songs that are not in a user's taste profile are prioritized and mixed with songs they may be more familiar with, while maintaining connection quality *(Desirable)*
   7. [ ] Autopilot should be able to be constrained by user selected session constraints like total duration, ending song, or general genra directives *(Desirable)*
   8. [ ] Autopilot should be able to learn from user overrides in ordere to improve future reccomendations in a session *(Extension)*