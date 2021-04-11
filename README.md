//Chordian.SFZ rev. 2021-04-11
//An Omnichord OM-84-esque instrument/sound documentation.
//
//This is an SFZ v2 instrument. It has been tested in Sforzando.
//
//People who are members of the Omnichord Reddit, Discord, or other affiliated groups that did down an Omnichord OM-36 (or later models) by the 11th of April 2021 are 
//NOT ALLOWED TO USE this instrument.
//You have been literally no help at all.
//
//Exceptions to this are:
//arcticmatt, creator of the http://onlineomnichord.com / https://github.com/arcticmatt/online-omnichord OM-27 documentation.
//beepcreep, who sampled all 84 chords of an OM-84. https://freesound.org/people/beepcreep/packs/10882/
//
//MIDI MAP:
//|            Chord Selection              |         Key Selection (Sticky!)         |         Chord Trigger and Drums         |
//|  Required for Chord Trigger and Harp    |  Required for Chord Trigger and Bass    |   Chord Trigger requires Chord and Key  |
//|   |   | |   |   |   |   | |   | |   |   |   |   | |   |   |   |   | |   | |   |   |   |   | |   |   |   |   | |   | |   |   |
//|   |   | |   |   |   |   | |   | |   |   |   |   | |   |   |   |   | |   | |   |   |   |   | |   |   |   |   | |   | |   |   |
//|   |---| |---|   |   |---| |---| |---|   |   |C#1| |D#1|   |   |F#1| |G#1| |A#1|   |   |---| |---|   |   |---| |---| |---|   |
//|     |     |     |     |     |     |     |     |     |     |     |     |     |     |Chord|     |     |     |     |     |     |
//|Major|Minor| 7th |     |     |     |     |     |     |     |     |     |     |     |Trig.| BD  |Snare|HiHat|     |     |     |
//|-C-0-|-D-0-|-E-0-|-F-0-|-G-0-|-A-0-|-B-0-|-C-1-|-D-1-|-E-1-|-F-1-|-G-1-|-A-1-|-B-1-|-C-2-|-D-2-|-E-2-|-F-2-|-----|-----|-----|
//###############################################################################################################################
//|                                        Bass                                       |                    Harp                 |
//|                                    Requires Key                                   |          Requires Chord and Key         |
//|   |   | |   |   |   |   | |   | |   |   |   |   | |   |   |   |   | |   | |   |   |   | 2 | | 1 |   |   | 1 | | 3 | | 2 |   |
//|   |   | |   |   |   |   | |   | |   |   |   |   | |   |   |   |   | |   | |   |   |   |O.0| |O.1|   |   |O.2| |O.2| |O.3|   |
//|   |C#3| |D#3|   |   |F#3| |G#3| |A#3|   |   |C#4| |D#4|   |   |F#4| |G#4| |A#4|   |   |C#5| |D#5|   |   |F#5| |G#5| |A#5|   |
//|     |     |     |     |     |     |     |     |     |     |     |     |     |     |  1  |  3  |  2  |  3  |  2  |  1  |  3  |
//|Root |     |     |     |     |     |     |     |     |     |     |     |     |     |Oct.0|Oct.0|Oct.1|Oct.1|Oct.2|Oct.3|Oct.3|
//|-C-3-|-D-3-|-E-3-|-F-3-|-G-3-|-A-3-|-B-3-|-C-4-|-D-4-|-E-4-|-F-4-|-G-4-|-A-4-|-B-4-|-C-5-|-D-5-|-E-5-|-F-5-|-G-5-|-A-5-|-B-5-|
//
//NOTE:
//Most VST hosts send notes on the same time in a random order.
//The safest method is to have Chord and Key 1/64th preplaced of everything else.
//
//PLEASE ADVISE: This instrument may be erroneous. All behaviours have been implemented from second-hand sources and association.
