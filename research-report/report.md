## Introduction

Project Atmos is a social media application that allows users to host custom
chat rooms with themed music and live background wallpapers. Users can create
and host custom "Spheres", which are musical chat and hangout rooms with voice,
video and text chat functionality. Spheres can be customized with animated
backgrounds and music playlists.

Atmos-Sphere aims to reduce feelings of social isolation and loneliness by
providing users with an engaging, atmos-spheric social media app for interacting
with their friends and family. Furthermore, Atmos is also targetting the
enterprise, encouraging organizations and businesses to reach out and
communicate with their audience on the Atmos platform.

Feelings of loneliness borne from social isolation/withdrawal during the
COVID-19 pandemic is the main issue that project Atmos aims to challenge. Such
feelings can easily lead to mood disorders and mental health issues such as
depression and anxiety. Project Atmos will provide these people with a means to
communicate and socialize in not just a pandemic scenario, but any scenario
where one is physically isolated and lacks social interaction. The chill vibes
and social environment of Atmos will help to improve the mental health of its
users, bringing about positive emotions, and reducing feeling of isolation and
loneliness.

## Hypothesis

It is hypothesized that using the Atmos web app will cause improvements in the
feelings of loneliness experienced by users living under COVID-induced social
isolation. It is believed that the music and background animations will have a
calming effect on users, and the online chat will provide an avenue for users to
socially interact in a relaxed environment reducing their feelings of social
isolation and elevating their mood.

## Methods

**_ATMOS’ core focus is to create a social and relaxing environment for users_**

The project will focus on 3 main aspects: Music, Environment, and Users. The
main functionality of the system is that it should be a hangout for people to
socialize and/or listen to music.

The system will be built using React, the JavaScript library, and Material-UI
for the frontend UI components like buttons and tables. The backend will be a
Postgresql database that will connect to the frontend. Specific APIs will need
to be installed to handle playing audio on the site. Regular playlists can be
handled using the React Audio Player API, but ATMOS is also planned to allow
Spotify and Apple Music, so there will need to be 2 unique APIs. These will be
the React Spotify API and the Apple Music.js API.

The development of ATMOS will be split into various parts. First will be to lay
down the foundation of the site and then set up a basic sphere and the main page
to look for spheres. Next will be to implement music support which can just be
the regular playlist for now as the Spotify and Apple support can come later.
The addition of animated backgrounds and a chat will come afterwards. When all
is set for a basic user’s sphere, then account creation, management, and
administrative privileges is next. Lastly will be to connect everything to the
backend database so the core functionalities are all functional and can be
tested.

## Theoretical contribution

We want to address this issue because people around the world are forced to
isolate themselves which could lead to negative effects such as depression, bad
sleep quality, increase chances of premature death, etc.<sup>[[7]]</sup> The opportunity is
to make a virtual environment people come to relax and interact with others.
According to Graeme B.Wilson, music (or background music) can affect social
behavior such as interactions among people.<sup>[[8]]</sup> People feel more comfortable
having interactions with each other when they are put in an environment that
they are comfortable in. Having a good background noise allows better
synchronizations between conversations mainly because it boosts their
self-confidence. Environment plays a big role when it comes to emotions, people
tend to more relaxed, be less shy and more expressive when they are placed in a
desired environment. Most individual tend to relieve stress when listening to
music.<sup>[[9]]</sup> One of the major drawback of the existing applications is that they
don’t incorporate all the features combined. The goal is to build a virtual
environment that allows people to enjoy chill music and different type of
animated background as well as interact with others.

In terms of design, the visual aspect is going to look a little similar to the
Discord where all the spheres are visible on the left-hand side. Once a sphere
is selected, the user is propelled into a new environment. This new environment
includes a dynamic background animation as well as a background music from a
preselected theme. The UI is kept minimalist on purpose,so the user enjoy the
ambiance and a chat option is available if the user needs to interact. So the
background music and animation are the main component of our UI design.

## Background Research

Research efforts were carried out by team members using common group
discussion methods (brainstorming/information sharing etc.). The Atmos team
intends to build the application based on facts from study based soruces such as
peer reviewed journals and educational thesis. Through this,the effects towards
enhancing a user’s mental and emotional health can be elicited based on prime
application aspects such as music, communication, socialization, and
environment.

One of the study goals of project Atmos is to investigate the effect of music on
a user's mood. Along these lines, some of the background research lies in the
field of musical therapy. Musical therapy provides a unique approach in
combating mental health issues by creating a positive impact on human brains
based on musical tones and frequencies. Three components in music: melody,
harmony and rhythm. Melody creates a framework of information to be learned and
supports memory. On the other hand, harmony is used for verbalization purposes.
Finally, rhythm increases the body’s vibrations and cues user’s speech and
movements. Thus, music functions as a mnemonic device and a mood
stabilizer.<sup>[[1]]</sup> In the past, there have been attempts on Youtube
live to feature music therapy as a method of relaxation for Youtube users,
however, generated playlists were overly rigid and often seen as randomly
generated content by users, carrying little context and thus making the feature
seem unappealing to users. Atmos-Sphere aims to correct that flaw by providing a
more unique experience for each user based on their mood and motivation.

Another aim of Atmos is to provide a positive mode of online communication that
increases the well-being of its users. As stated by Torous: "online
communication and the ability to connect with others may be an important feature
of social media, especially for individuals living with highly stigmatizing
health conditions such as serious mental disorders." <sup>[[2]]</sup> Many
social media platforms, such as Discord, provide text and audio chat features
where users can connect with one another. The downside of these features is that
they are limited when you are trying to create special memories with your
friends. You are able to stream videos, but the level of social interaction is
minimal. Atmos-Sphere provides the possibility to stream movies and videos while
interacting with your friends in a relaxed, atmospheric environment. The level
of interactivity between you and your friends is increased, making it easier to
forge strong bonds and create positive memories.

Based on the research conducted, environment is a powerful factor that can
affect users and their mental health, either positively or
negatively.<sup>\[[3](<#[3]-Helbich-M.-Mental-Health-and-Environmental-Exposures:-An-Editorial.-Int-J-Environ-Res-Public-Health.-2018;15(10):2207.-Published-2018-Oct-10.-doi:10.3390/ijerph15102207>)\]</sup>
Environment is a major trigger of emotions, thus special attention is paid
environmental factors in the Atmos app. By creating dynamic themes depending on
user’s mood, the selected theme will create a tone that brings an emotional
relief to end users. Discord has tried to address this option however it
provided yet a static version that can only be customized by the user and the
options are limited, therefore, the lack of original interactivity made users
experience less enjoyable. Atmos-Sphere brings a new colorful RGB touch to the
atmospheric ambiance by implementing a smart way of displaying backgrounds based
on current moods and musical playlist.

## Evaluation

The Atmos-Sphere study is designed to investigate the mood of participants as
they use the Atmos social media app. In particular, Atmos-Sphere is interested
in the relationship between social isolation and feelings of loneliness. The
goal of the Atmos sphere app is to reduce the social isolation of study
participants by providing an engaging online social experience. It is believed
that if study participants feel less socially isolated, through the use of the
Atmos app, then their feelings of loneliness will be reduced. Along these lines,
the plan is to execute a comprehensive and robust data collection scheme that
tackles the question from two angles: qualitatively, and quantitatively. Thusly,
data will be collected in 3 formats: by questionnaire, by interview, and finally
by web analytics.

### Questionnaire

A custom, self-administered questionnaire will be created containing both
open-ended and close-ended questions. Close-ended questions will be be ideal for
generating quantitative data points that can be analyzed using statistical and
data analysis techniques, whereas open-ended questions will provide a
qualitative view. The questionnaire will be based on tried-and-true clinical
screening tools such as the PHQ-9, MFQ, and GAD-7 questionniares. <sup>[[4]]
[[5]] [[6]]</sup> These are clinical tools that are commonly used to screen for
mental health issues such as depression and anxiety. The Atmos questionnaire
will take a lighter approach - it will not be designed to screen for mental
health issues, but rather to test for mood, social isolation, and feelings of
loneliness. Nonetheless, The questions will be in a similar format and wording
as the questions in the clinical questionnaires.

### Interviews

Upon completion of the study, an exit interview will be conducted with each
study partipant. The exit interview will contain mainly open-ended questions
focusing on participants experience in using the Atmos app. These interviews
will contribute to the qualitative data collected from the open-ended Atmos
questionnaire questions. The interview, in combination with the
self-administered questionnaire, will provide one-on-one, qualitative and
quantitative data from the perspective of the study participant.

### Web Analytics

Finally, web page statistics will be collected throughout the duration of the
study. Metrics such as clicks, time spent viewing components, and more will be
collected from the app. This data will be quantitative, and will provide a
valuable perspective on the level of engagment that Atmos was able to acheive
with its users. The data will be used to construct metrics for the learnability,
ease-of-use, and level of engagement that users have with a social media app in
the Atmos format.

### Study Format

The format of the study will have participants engage with the Atmos app thrice
over the course of a week, in short sessions of 5-10 minutes, followed by
administering the Atmos questionnaire at the end of each session. The triplet
combination of questionnaires, interviews, and web analytics will provide
multiple perspectives on the data. The goal is to acheive data and
methodological triangulation, which will create a more robust model of the
effect that Atmos has on feelings of social isolation and loneliness. Each of
the 3 investigatory techniques chosen for the study will provide a unique
perspective, the combination of which will be provide the best understanding of
Atmos' users. This study will provide the ground-work for future endeavors of
Atmos-Sphere and improvements to the Atmos social media platform.

### Data Analysis

Analysis of the data obtained in both the open ended and closed ended
questionaires will be primarily evaluated on:

- How much the application has affected the users?
- If the application has affected the user in a positive or negative way?
- If the application has affected the user positively, will the user continue to
  use the application or will they seek an alternative?
- If the application has affected the user negatively:
- What user needs did the application not meet?
- what alternative will the user seek to meet their needs?

As such, based upon the content of the responses received, we can determine the
overall effect the application has on the users in both qualitive and quantitive
terms. And through that analysis, the hypothesis will be proved/disproved.

## Biggest Risks

### Risk 1: Copyright Strikes

One of the primary features of ATMOS is that to act as a social hub with
user-selected background music. An obvious risk that will arise with this is
that if users can choose what songs they would like in their sphere, they might
choose copyrighted music and backgrounds if they are to choose external music
which are not featured on the spotify platform. This isn't necessarily bad since
spheres aren't monetized, but corporations will still want money for letting
people listen to their music or use their content as backgrounds, which may lead
to arising legal issues which may demand significant resources to resolve. Thus
it may be neccesary for the addition of advertisements during applicaiton usage
to appease the big corporations. This might be harder to handle for when video
chat is implemented since that will add more legality issues when people start
streaming movies.

### Risk 2: Explicit Content

There is a risk of malicous users using the application to post inappriate
content,which can ruin the experience for other users especially if underage
users are exposed to such content. An example of thismaybe be if spheres with
content not suitable of children are created. ATMOSwill need clear rules in the
terms and conditions stating that either the sitecannot be used for this 18+
content or if explicit content is allowed, certain rules and regulations will
need to be set on what is acceptable content and the some restrictions will be
required to ensure users under the age of 18 are not exposed to any explicit
content. Violators which post explicit content featuring physical blood, gore,
and death, as well as illegal pornography such as sexual content featuring
children/minors will be banned and handled with harsher consequences.

### Risk 3: Distribution of Illegal Content

Distribution of illegal content such as the may bring about a plethora of legal
issues:

- Distribution of pirated games, movies, and other medias or the use of pirated
  media on any sphere.
- Distribution of content that is illegal according to Canadian and
  International Laws or the use of this content on any sphere.
- Distribution of illegal hacking software such as trojans, malware, or other
  viruses that are cybercrimes.

### Risk 4: Distributed Denial of Service (DDoS) Attacks

Distributed Denial of Service (DDoS) Attacks pose a serious threat to ATMOS
servers and may be conducted by malicous users who have the intent of disrupting
application services. Thus appropriate security protocols and malware defense
software should be deployed in order to prevent such attacks from succeeding.

<!-- <div style="page-break-after: always;"></div> -->

## References

**\[1\]** Swanson, A. L. (2020). Music therapy in schools: Stimulating the mind and body to create positive change. In C. Maykel & M. A. Bray (Eds.), Applying psychology in the schools. Promoting mind–body health in schools: Interventions for mental health professionals (p. 233–244). American Psychological Association. <https://doi-org.lib-ezproxy.concordia.ca/10.1037/0000157-016>

**\[2\]** Naslund, J.A., Bondre, A., Torous, J. et al. Social Media and Mental Health: Benefits, Risks, and Opportunities for Research and Practice. J. technol. behav. sci. 5, 245–257 (2020). <https://doi.org/10.1007/s41347-020-00134-x>

**\[3\]** Helbich M. Mental Health and Environmental Exposures: An Editorial. Int J Environ Res Public Health. 2018;15(10):2207. Published 2018 Oct 10. doi:10.3390/ijerph15102207

**\[4\]**: <https://patient.info/doctor/patient-health-questionnaire-phq-9>

**\[5\]**: <https://www.corc.uk.net/outcome-experience-measures/mood-and-feelings-questionnaire/>

**\[6\]**: <https://patient.info/doctor/generalised-anxiety-disorder-assessment-gad-7>

**\[7\]** Novotney, A. (2019, May). The risks of social isolation. Retrieved
March 31, 2021, from https://www.apa.org/monitor/2019/05/ce-corner-isolation

**\[8\]** Wilson, G., &amp; MacDonald, R. (2019, June 28). The social impact of
musical engagement for young adults with learning difficulties: A
qualitative study. Retrieved April 01, 2021,from
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6610152/

**\[9\]** Thoma, M., La Marca, R., Brönnimann, R., Finkel, L., Ehlert, U., &amp;
Nater, U. (2013, August 5). The effect of music on the human stress response.
Retrieved April 01, 2021, from
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3734071/

[1]: https://doi-org.lib-ezproxy.concordia.ca/10.1037/0000157-016
[2]: https://doi.org/10.1007/s41347-020-00134-x
[4]: https://patient.info/doctor/patient-health-questionnaire-phq-9
[5]: https://www.corc.uk.net/outcome-experience-measures/mood-and-feelings-questionnaire/
[6]: https://patient.info/doctor/generalised-anxiety-disorder-assessment-gad-7
[7]: https://www.apa.org/monitor/2019/05/ce-corner-isolation
[8]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6610152/
[9]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3734071/
