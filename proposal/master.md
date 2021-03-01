<!-- Headline Logo -->
<p align="center">
  <a href="https://github.com/atmos-sphere/atmos">
    <img src="../assets/2000w/atmos-full-name2000px.png"
         alt="ATMOS Sphere"
         width="600" />
  </a>
</p>

<!-- Tagline: a little explanation about the Godzilla app -->
<p align="center">
    <em>ATMOS Sphere: fun, atmospheric, easy to use, open source chat and hang out platform</em>
    <br />
    <strong><a href="https://atmos-sphere.app/">https://atmos-sphere.app/</a></strong>
    <br />
    <strong><a href="https://github.com/atmos-sphere/atmos">GitHub</a></strong>
</p>

## Introduction

The unexpected sweep of the COVID-19 pandemic has driven an invisible barrier
between friends, families and loved ones as widely dreaded curfews, quarantines
and other social distancing procedures are slowly integrated into our daily
lives. Subsequently, social gatherings have become a rare luxury, and as social
beings, humanity’s need for basic human interaction grows exponentially as
people spend increasing amounts of time in isolation and loneliness. A need
which if suppressed, may lead to a steady decline in mental health.

ATMOS is a social app where people can host chat rooms with chill or themed
music and live background wallpapers. Music/chat channels are called "Spheres"
(AtmosSpheres) and they all follow different themes. For example, you could
have a Sphere for low-fi chill beats with an aquarium live stream taking up the
whole screen. Invite your friends and chill out in the chat room while the fish
swim around on screen - even after COVID curfew!

## Related Work

In Debra Umberson studies, it was demonstrated that socializing and human health
have a strong correlation and that interactions with others have positive
benefits on mental health.<sup>[[2]]</sup> We are fortunate enough to have
multitudes of applications that allow interactions remotely where people can
interact with their loved ones across the globe.

As of 2021, the leaders in social messaging, voice and video interaction are
apps like WhatsApp, Facebook Messenger, WeChat, Telegram, Snapchat, Discord,
etc.<sup>[[3]] [[4]]</sup> Among all these choices users intuitively make
selections based on the pros and cons of application usability.

Most of the applications mentioned above allow users to create group chats where
members can communicate via text, voice messages or/and video, but none of these
let the user create their own personalized environment. An example of a
personalized environment is having a group chat with animated wallpapers and
personalized themes and having background music while being in the group chat.
Whatsapp provides a feature similar to this, however only static images can be
selected as a background picture. Discord has an addition to this feature
whereby using extensions a user can add a GIF as background for the chat. This
feature is restricted to the premium version of Discord. None of the
applications mentioned allow the option of adding a live wallpaper as a
background in the chats.

ATMOS integrates with many music streaming applications and that makes the whole
difference. ATMOS can connect to any popular music streaming service like
Spotify or Apple Music. These application allow users to create, edit and delete
playlists connected to their ATMOS Spheres. Most social networking applications
do not integrate with any of the popular music streaming services; using apps
such as Facebook, users can’t configure a group chat that plays music alongside
thematic background imagery - this is the selling point of ATMOS.

## Problem Statement

Based on an [article][1] regarding suicide risk and prevention during the
pandemic, suicide rates during the covid 19 pandemic are expected to rise due to
a decline in mental health cause by fear, self-isolation, and social distancing,
leading to mental illnesses such as depression, anxiety, and post-traumatic
stress disorder(PTSD).<sup>[[1]]</sup>

An application for social interactions in a virtual platform may prove
imperative in improving mental health for its users, not just during the COVID
19 pandemic, but during more normal times as well. By providing users with an
option to connect and interact with other human beings, and by preventing more
people from being deprived of their social needs, ATMOS seeks to elevate moods
and distract users from experiencing negative vibes.

## Hypothesis

To investigate the impact of ATMOS on user's mental health and wellbeing, the
ATMOS team has created a data collection scheme to learn more about the impact
of the ATMOS app our user's daily lives. It is hypothesized that the chill music
and background animations will stimulate users brains positively and improve
their general mood based on colors and sound frequencies. It is also
hypothesized that the live chat will provide much needed social support, and
allow users to release their all of their daily stress.

<br />

## Project Description

The main directive of project ATMOS is to provide users with a comfortable,
virtual space to socialize with friends. This will be delivered in the form of
musical, themed channels called ‘Spheres’, each with customizable animated
backgrounds and music playlist.

A sphere represents a dedicated venue for a group of ATMOS users to socialize
in, either via the integrated text chat, voice chat, or video chat channel in a
similar manner to widely used video chatting applications such as discord or
zoom. Each sphere features a customizable animated background, which can be
selected from the default backgrounds, which is a wide plethora of suggested
high-definition backgrounds (e.g., A livestream of Niagara Falls, fishy
aquariums, fireplace, snowy mountains, mystical forest, coffee shop, etc.), and
additional backgrounds added regularly by the dev team. Backgrounds can also be
custom made with the user’s video of choice (provided either by file upload, or
a link to a video such as a YouTube link) using the in-application video editor,
offering basic video editing functions and certain video customization features
such as adding different ambient filters or borders, allowing the user to
produce a looping animated background to suit their desires.

A sphere can be interconnected with a series of different spheres, allowing
spheres of simmilar / relevant themes to exist in close proximity to each other.
Relevant or nearby spheres can appear in as recommedations when in a user sphere,
and are availanle to be visited easily in a graph-node style navigation.

If a user does not wish to go through the process of customizing a sphere and
only wishes to quickly create a session, a “Quick Start” feature will enable a
user to generate a randomized sphere with relevant music genres and themes,
needing the user to only input a music genre of their choice.

In terms of music, full Spotify integration and syncing will also be available
in the ATMOS applications, allowing users to select a playlist of their choice
from the Spotify platform which already hosts a multitude of music tracks of
varying genres. However, additional audio effects and filters may be applied in
the Sphere audio settings, adding certain effects such as dampening, echoing,
muffling or even integration with other audio effects (e.g., adding a raining
ambient soundtrack to sad music can create a melancholic atmosphere).

Furthermore, instead of operating as individual sessions for private groups, a
life cycle of a Sphere can be extended as dedicated spheres can be maintained
indefinitely for public joining and use, similar to live stream music channels
on YouTube. Dedicated spheres operate similarly to services such as radio
stations, and are public for all users to join. Owners/Administrators of a
dedicated Sphere may offer a range of content in addition to music streaming,
such as news broadcasting (e.g., the CBC news sphere would be available to the
public to join and view live news being reported), podcasts, or live
performances and concerts, providing the application a secondary function
similar to that of a social media platform.

## System Design

### Mechanics and Design Philosophy

The goal of ATMOS is to be ***atmospheric***.

ATMOS will be designed from the ground up to support both long-lived and
short-lived chat room sessions ("Spheres"). Spheres are bound to an owner, who
is the user that created the Sphere. Any number of users can be invited to join
a Sphere and become a member of the chat room. The owner of a sphere has full
admin privileges over his/her Sphere, but may designate another member of the
Sphere as an admin, granting them extra rights to manage the Sphere.

There are 3 central gimicks that make a Sphere unique:

1. Music
    - Each sphere has it's own music.
    - A Sphere admin can manage the music component of a Sphere, adding new
      soundtracks, looping over of a track, connecting to an external
      third-party music service such as Spotify or Apple Music, and more.

2. Environment
    - Sphere's also have an environment.
    - The environment mainly consists of the background imagery and chat room
      decorations.
    - Environment can also be extended, for more advanced client apps, to
      included any visual or auditory imagery such as a VR environment.

3. Users
    - The members of the Sphere are the most unique part!

As a social media platform, ATMOS provides more than just an *atmospheric* vibe.

### System Architecure

The ATMOS architecture is composed of two parts:

1. ATMOS Core
2. Client Apps

#### ATMOS Core

The ATMOS Core represents the core API of ATMOS, encompassing all the web
services for the ATMOS organization and all the publicly exposed APIs, including
the RESTful, GraphQL, and WebSockets APIs exposed by the core ATMOS services.

*APIs Targeted:*

- REST
- GraphQL
- WebSockets

#### Client Applications

*Platforms Targeted:*

- Web
- Desktop
- Mobile

*Tech Stack:*

- ReactJS: JavaScript framework for making
  - React-Native for the mobile app
- Material-UI: provides base React components from which to build the app

## Study Design

As per the hypothesis, the idea is that the music, calm background and a
platform for socializing will positively affect a user's mental health. To test
whether such activities in fact have a discernible impact on mental health, we
shall conduct a study involving 70 participants.

The 70 participants will be split in 7 groups of 10 participants each. The
groups will have each be subjected to a different form of activity, and its
impact will be evaluated based on the users' evolution of mood through and at
the end of the activity.

At the beginning of the study, all participants will be given a questionnaire in
order to determine their mental state, and each given a _happiness level_ based
on their results.

The 7 groups will have the following activities they will be a part of:

|         | Animated Background | Chill Beats | Live Chat |
| ------- | :-----------------: | :---------: | :-------: |
| Group 1 |          X          |             |           |
| Group 2 |                     |      X      |           |
| Group 3 |                     |             |     X     |
| Group 4 |          X          |      X      |           |
| Group 5 |                     |      X      |     X     |
| Group 6 |          X          |             |     X     |
| Group 7 |          X          |      X      |     X     |

After the designated acitivity of 30 minute, the moods or _happiness levels_ of
the 70 participants will be evaluated. If our hypothesis is correct, there
should be a statistically significant enhancement of the participants' moods
after the activity, with the highest effect in group G.

## Biggest Risks

### Risk 1: Copyright Strikes

One of the primary features of ATMOS is that it is supposed to be a location to
chill and play music. An obvious risk that will arise with this is that if users
can choose what songs they would like in their sphere, they might choose
copyrighted music and backgrounds if they are to choose external music which are
not featured on the spotify platform. This isn't necessarily bad since spheres
aren't monetized, but corporations will still want money for letting people
listen to their music or use their content as backgrounds. There will need to be
ads added somewhere for when copyrighted songs/backgrounds play to appease to
the big corporations. This might be harder to handle for when video chat is
implemented since that will add more legality issues when people start streaming
movies.

### Risk 2: Explicit Content

There is a risk that malicious users may pose a threat which can ruin the
experience for other users through inappropriate content. An example of this
maybe be if spheres with content not suitable of children are created. ATMOS
will need clear rules in the terms and conditions stating that either the site
cannot be used for this 18+ content or if explicit content is allowed, then
there will need to be rules on what is acceptable and the restrictions required
to ensure users under the age of 18 do not see this explicit content. Regardless
of which of the 2 rules are chosen, extreme explicit content like real life
blood, gore, and death, as well as illegal pornography like child porn will be
banned and handled with harsher consequences.

### Risk 3: Distribution of Illegal Content

Connecting with the past 2 risks listen above, other illegal content can cause
risks to ATMOS. This includes:

- Distribution of pirated games, movies, and other medias or the use of pirated
  media on any sphere.
- Distribution of content that is illegal according to Canadian and
  International Laws or the use of this content on any sphere.
- Distribution of illegal hacking software such as trojans, malware, or other
  viruses that are cybercrimes.

### Risk 4: Distributed Denial of Service (DDoS) Attacks

There might be a possibility that someone might want to take down the ATMOS
servers by causing DDoS attacks. This can be devastating and will need to be
handled as soon as possible when it happens since it will cause enough network
trafficking that it'd be impossible for users to use ATMOS.

[1]: https://www.thelancet.com/journals/lanpsy/article/PIIS2215-0366(20)30171-1/fulltext

[2]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3150158/

[3]: https://www.statista.com/statistics/258749/most-popular-global-mobile-messenger-apps/

[4]: https://www.zdnet.com/article/salesforce-beats-q4-estimates-slack-adds-record-number-of-paid-customers/

[5]: https://faq.whatsapp.com/android/changing-wallpaper/?lang=en
