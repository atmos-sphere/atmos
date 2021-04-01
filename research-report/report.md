## Introduction

Project Atmos is designed to function as a social media application by allowing
users to host custom chat rooms with themed music and live background
wallpapers.

Prime features of Project Atmos include

- Creation and hosting of "Spheres", which are musical chatting channels with
  voice, video and text chat functionality.
- Customizable animated backgrounds for chatting channels

Project Atmos, Or Atmosphere in its deployed state aims to provided users with
means of social interaction with friends and family, and by doing so reduce
feelings of loneliness. Furthermore, similar to other social media platforms,
this project aims to act as a mainstream media outlet for organizations and
businesses to reach and communicate with their audience in a public chatting
area.

Feelings of loneliness born from social isolation/withdrawal during the covid 19
pandemic are the main problems that project Atmos aims to confront. Such
feelings can easily lead to mood disorders/ illnesses such as depression,
anxiety which can be deteriorating to mental health, which in severe cases leads
to physically harmful behavior. Project Atmos aims to provide these people with
a means to communicate and socialize in not just a pandemic scenario, but any
scenario where one is physically isolated and lacks social interaction. By doing
so, gradually improve mental health amongst users and bring about more positive
emotions stemming from being able to communicate with friends and family.

## Hypothesis

It is hypothesized that using Atmosphere would cause improvements in the feelings
of loneliness experienced in isolated situations. It is believed that the music 
and background animations would have a calming effect on the users, and the 
online chat would provide an avenue for users to socially interact in a relaxed 
environment reducing their feelings of social isolation by elevating their mood.

## Methods

***ATMOS’ core focus will be to create a sociable experience for users***

By focusing on the 3 main aspects: Music, Environment, and Users. The main
functionality of the system is that it should be a hangout for people to
socialize and/or listen to music.

The system will be built using React, the javascript library, and Material-UI
for the frontend UI components like buttons and tables. The backend will be a
Postgresql database that will connect to the frontend. Specific APIs will need
to be installed to handle playing audio on the site. Regular playlists can be
handled using the React Audio Player API, but ATMOS is also planned to allow
Spotify and Apple Music, so there will need to be 2 unique APIs. These will be
the React Spotify API and the Apple Music.js API.

The development of ATMOS will be split into various parts. First would be to lay
down the foundation of the site and then set up a basic sphere and the main page
to look for spheres. Next will be to implement music support which can just be
the regular playlist for now as the Spotify and Apple support can come later.
The addition of animated backgrounds and a chat will come afterwards. When all
is set for a basic user’s sphere, then account creation, management, and
administrative privileges is next. Lastly will be to connect everything to the
backend database so the core functionalities are all functional and can be
tested.

## Background Research

Throughout the initiation phase the team’s motivation of building the project was engaged towards sound arguments. Atmosphere is a hedonistic tool that sprung up based on facts from peer reviewed journals and educational thesis answering the fundamental question on how the application enhances user’s mental and emotional health on daily basis. The answer spans through multiple dimensions ranging from music, communication, socialization, and environment. These aspects are the essence of the conducted research.

Music therapists work in an interdisciplinary team to create a positive dynamism and impact on human brains based on musical tones and frequencies to address mental health challenges and enhances well-being. Atmosphere was influenced based on therapist’s categorization of user-preferred music styles where melody creates a framework of information to be learned and supports memory whereas harmony is used for verbalization purposes and rhythm is to increase body’s vibrations and cue user’s speech and movements, thus, music functions as a mnemonic device [1]. Youtube live have tried to take advantage of music therapy to make it an ultimate feature for its users to destress and relax, however, the flaw was the lack of automation and the playlist was standard and infinite with mixed random music that is not personalized and quit often out of topic. User’s experience was not the best as not everyone can get hooked to it. Atmosphere takes advantage of music therapy by providing a unique experience for each user based on their mood and motivation.

Communication is pivotal to solve all types of challenges therefore, it elucidates in various forms. Online chatting brings an implicit therapeutic well-being. As stated by Torous: “online communication and the ability to connect with others may be an important feature of social media, especially for individuals living with highly stigmatizing health conditions such as serious mental disorders” [2]. Discord provides an audio chat feature where users connect to discuss with each other on their discretion. The downside of discord is that it cannot be personalized in terms of sharing special moments therefore, Atmosphere provides the possibility to stream movies and videos while chatting, this rises communication intimacy and forges a strong virtual peer-to-peer bond.

Based on the research conducted the environment can affect users in one way or the other, people’s mental health [3]. Environment is a major trigger of emotions therefore Atmosphere gave it a special attention by creating different dynamic themes depending on user’s mood, the selected theme will induce a vibration tone that brings an emotional relief to end users. Discord have tried to address this option however it provided yet a static version that can only be customized by the user and the options are limited, therefore, the lack of original interactivity made users experience less enjoyable. Atmosphere brings a new colorful RGB touch to the atmospheric ambiance by implementing a smart way of displaying backgrounds based on current moods and musical playlist. 



#### [1] Swanson, A. L. (2020). Music therapy in schools: Stimulating the mind and body to create positive change. In C. Maykel & M. A. Bray (Eds.), Applying psychology in the schools. Promoting mind–body health in schools: Interventions for mental health professionals (p. 233–244). American Psychological Association. https://doi-org.lib-ezproxy.concordia.ca/10.1037/0000157-016

#### [2] Naslund, J.A., Bondre, A., Torous, J. et al. Social Media and Mental Health: Benefits, Risks, and Opportunities for Research and Practice. J. technol. behav. sci. 5, 245–257 (2020). https://doi.org/10.1007/s41347-020-00134-x

#### [3] Helbich M. Mental Health and Environmental Exposures: An Editorial. Int J Environ Res Public Health. 2018;15(10):2207. Published 2018 Oct 10. doi:10.3390/ijerph15102207

## Evaluation

### OLD

In order to measure symptoms of anxiety and depression, our participants will
fill out questionnaires related to depression and anxiety symptoms, as well as
participate in an unstructured interview to informally evaluate their symptoms.
The questionnaires, “Beck’s Depression Inventory” which measures depression,
and the “GAD-7” which measures anxiety, generate a score based on the severity
of the symptoms, ranging from 0-3. We chose these two tests as they provide
qualitative and quantitative metrics. Together, they will allow us to perform
data triangulation, ensure the accuracy of our results, as well as provide a
holistic view of our application’s effects on the user. As such, we will know
our hypothesis holds true if we notice a significant decrease in both anxiety
and depression symptoms. We believe this ensemble of techniques will help us
to properly evaluate our hypothesis. In the future, we would like to conduct
research within a longer time frame, as this would help us get a better
overview of the application’s effect on mental distress.

---

### NEW

The Atmos-Sphere study is designed to investigate the mood of participants as
they use the Atmos social media app. In particular, Atmos-Sphere is interested
in the relationship between social isolation and feelings of loneliness. The
goal of the Atmos sphere app is to reduce the social isolation of study
participants by providing an engaging online social experience. It is believed
that if study participants feel less socially isolated, through the use of the
Atmos app, then their feelings of loneliness will be reduced.

#### Data Collection

Along these lines, the plan is to execute a comprehensive and robust data
collection scheme that tackles the question from two angles: qualitatively, and
quantitatively. Thusly, data will be collected in 3 formats: by questionnaire,
by interview, and finally by web analytics.

##### Questionnaire

A custom, self-administered questionnaire will be created containing both
open-ended and close-ended questions. Close-ended questions will be be ideal for
generating quantitative data points that can be analyzed using statistical and
data analysis techniques, whereas open-ended questions will provide a
qualitative view. The questionnaire will be based on tried-and-true clinical
screening tools such as the PHQ-9, MFQ, and GAD-7 questionniares. <sup>[[1]]
[[2]] [[3]]</sup> These are clinical tools that are commonly used to screen for
mental health issues such as depression and anxiety. The Atmos questionnaire
will take a lighter approach - it will not be designed to screen for mental
health issues, but rather to test for mood, social isolation, and feelings of
loneliness. Nonetheless, The questions will be in a similar format and wording
as the questions in the clinical questionnaires.

##### Interviews

Upon completion of the study, an exit interview will be conducted with each
study partipant. The exit interview will contain mainly open-ended questions
focusing on participants experience in using the Atmos app. These interviews
will contribute to the qualitative data collected from the open-ended Atmos
questionnaire questions. The interview, in combination with the
self-administered questionnaire, will provide one-on-one, qualitative and
quantitative data from the perspective of the study participant.

##### Web Analytics

Finally, web page statistics will be collected throughout the duration of the
study. Metrics such as clicks, time spent viewing components, and more will be
collected from the app. This data will be quantitative, and will provide a
valuable perspective on the level of engagment that Atmos was able to acheive
with its users. The data will be used to construct metrics for the learnability,
ease-of-use, and level of engagement that users have with a social media app in
the Atmos format.

##### Study Format

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

#### Data Analysis

Analysis of the data obtained in both the open ended and closed ended questionaires will be primarily evaluated on:

* How much the application has affected the users?
* If the application has affected the user in a positive or negative way?
* If the application has affected the user positively, will the user continue to use the application or will they seek an alternative?
* If the application has affected the user negatively:
 * What user needs did the application not meet?
 * what alternative will the user seek to meet their needs?

As such, based upon the content of the responses received, we can determine the overall effect the application has on the users in both qualitive and quantitive terms. And through that analysis, the hypothesis will be proved/disproved.

---

### NOTES

OTHER LINKS:

- <https://www.ncbi.nlm.nih.gov/books/NBK537897/>
  - This one has lots of references to studies on loneliness and whatnot
- Social Support Questionnaire (SSQ):
  - <https://journals.sagepub.com/doi/10.1177/0265407587044007>
  -

We could also do questionnaires for this study, here are some options:

- PHQ-9
  - <https://patient.info/doctor/patient-health-questionnaire-phq-9>
  - This is based on DSM-IV diagnostic criteria for depression.
- MFQ
  - <https://www.corc.uk.net/outcome-experience-measures/mood-and-feelings-questionnaire/>
  - DOWNLOAD: <https://devepi.duhs.duke.edu/measures/the-mood-and-feelings-questionnaire-mfq/>
  - Moods and Feelings Questionnaire
  - Used for children though (6-19)
  -

Something else that you might is to check out the WEEK 4 SLIDES.

In data collection, there are 5 KEY ISSUES:

1. Setting goals
2. Identifying the study population
3. Relationship with participants
4. Triangulation
   - Look at the data from more than one perspective
5. Pilot studies

Also, you might be interested in DATA RECORDING METHODS:

1. Notetaking
2. Interviews
3. Questionnaires
4. Observation
5. Diaries

Compare qualitative vs quantitative techniques:

- See slide 74 of `WEEK-4_MERGED.pdf`

## Biggest Risks

### Risk 1: Copyright Strikes

One of the primary features of ATMOS is that to act as a social hub with 
user-selected background music. An obvious risk that will arise with this is that
if users can choose what songs they would like in their sphere, they might choose
copyrighted music and backgrounds if they are to choose external music which are
not featured on the spotify platform. This isn't necessarily bad since spheres
aren't monetized, but corporations will still want money for letting people
listen to their music or use their content as backgrounds, which may lead to 
arising legal issues which may demand significant resources to resolve. Thus it may
be neccesary for the addition of advertisements during applicaiton usage to appease
the big corporations. This might be harder to handle for when video chat is
implemented since that will add more legality issues when people start streaming
movies.

### Risk 2: Explicit Content

There is a risk of malicous users using the application to post inappriate content
,which can ruin the experience for other users especially if underage users are 
exposed to such content. An example of thismaybe be if spheres with content not 
suitable of children are created. ATMOSwill need clear rules in the terms and 
conditions stating that either the sitecannot be used for this 18+ content or if 
explicit content is allowed, certain rules and regulations will need to be set 
on what is acceptable content and the some restrictions will be  required to ensure
users under the age of 18 are not exposed to any explicit content. Violators which
post explicit content featuring physical blood, gore, and death, as well as illegal 
pornography such as sexual content featuring children/minors will be banned and 
handled with harsher consequences.

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
 servers and may be conducted by malicous users who have the intent of 
 disrupting application services. Thus appropriate security protocols and 
 malware defense software should be deployed in order to prevent such attacks
 from succeeding.
