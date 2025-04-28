# PSY499

Repository for PSY499: Capstone Psychology Project

Measures:

- International Positive and Negative Affect Schedule Short Form (I-PANAS-SF; Thompson, 2007)
- 120-item International Personality Item Pool NEO Personality Inventory (IPIP-NEO-120; Johnson, 2014)
- Emotion Reactivity Scale (ERS; Nock et al., 2008)

|     Measure    |             Tag            |                           Description                          |                 Type                 |               Example              |
|----------------|----------------------------|----------------------------------------------------------------|--------------------------------------|------------------------------------|
| Participant ID | PID                        | Nonidentifiable generated participant id                       | String                               | P209                               |
| I-PANAS-SF     | T-PA                       | Trait positive affect                                          | Single float value                   | 4.7                                |
| I-PANAS-SF     | T-PA-1                     | Active                                                         | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-PA-2                     | Alert                                                          | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-PA-3                     | Attentive                                                      | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-PA-4                     | Determined                                                     | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-PA-5                     | Inspired                                                       | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-NA                       | Trait negative affect                                          | Single float value                   | 4.7                                |
| I-PANAS-SF     | T-NA-1                     | Afraid                                                         | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-NA-2                     | Ashamed                                                        | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-NA-3                     | Hostile                                                        | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-NA-4                     | Nervous                                                        | Single integer value                 | 2                                  |
| I-PANAS-SF     | T-NA-5                     | Upset                                                          | Single integer value                 | 2                                  |
| History        | TBI                        | Traumatic brain injury                                         | Binary yes/no                        | 0                                  |
| History        | DEP                        | Any depressive disorder                                        | Binary yes/no                        | 1                                  |
| History        | ANX                        | Any anxiety disorder                                           | Binary yes/no                        | 1                                  |
| History        | BIP                        | Any bipolar and related disorder                               | Binary yes/no                        | 1                                  |
| History        | FED                        | Any feeding and eating disorder                                | Binary yes/no                        | 0                                  |
| History        | PD                         | Any physical disability/injury affecting your hands/fingers    | Binary yes/no                        | 1                                  |
| Valence        | PA                         | Self-report positive affect                                    | Intensive time-series                | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Valence        | NA                         | Self-report negative affect                                    | Intensive time-series                | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Appraisal      | FL                         | Appraised feeling                                              | List of strings                      | Happy', 'Sad'                      |
| Appraisal      | FS                         | Start of feeling timestamp                                     | List of float values                 | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Appraisal      | FA                         | Feeling apex timestamp                                         | List of float values                 | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Appraisal      | FE                         | Feeling end timestamp                                          | List of float values                 | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| EmotiBit       | 2025-03-25_18-41-14-083733 | File passed through DataParser to provide individual csv below | Intensive time-series                | See example file                   |
| EmotiBit       | AK                         | Acknowledgement                                                | Recording metadata                   | See example file                   |
| EmotiBit       | AX                         | Accelerometer X                                                | Intensive time-series                | See example file                   |
| EmotiBit       | AY                         | Accelerometer Y                                                | Intensive time-series                | See example file                   |
| EmotiBit       | AZ                         | Accelerometer Z                                                | Intensive time-series                | See example file                   |
| EmotiBit       | B%                         | Battery Percentage Remaining                                   | Intensive time-series                | See example file                   |
| EmotiBit       | BI                         | Heart Inter-beat Interval                                      | Intensive time-series                | See example file                   |
| EmotiBit       | BV                         | Battery Voltage                                                | Intensive time-series                | See example file                   |
| EmotiBit       | EA                         | EDA- Electrodermal Activity                                    | Intensive time-series                | See example file                   |
| EmotiBit       | EL                         | EDL- Electrodermal Level                                       | Intensive time-series                | See example file                   |
| EmotiBit       | EM                         | Emotibit Mode                                                  | Intensive time-series                | See example file                   |
| EmotiBit       | GX                         | Gyroscope X                                                    | Intensive time-series                | See example file                   |
| EmotiBit       | GY                         | Gyroscope Y                                                    | Intensive time-series                | See example file                   |
| EmotiBit       | GZ                         | Gyroscope Z                                                    | Intensive time-series                | See example file                   |
| EmotiBit       | HR                         | Heart Rate                                                     | Intensive time-series                | See example file                   |
| EmotiBit       | info                       | info json                                                      | Recording metadata                   | See example file                   |
| EmotiBit       | LM                         | LSL Marker/message                                             | Intensive time-series                | See example file                   |
| EmotiBit       | MX                         | Magnetometer X                                                 | Intensive time-series                | See example file                   |
| EmotiBit       | MY                         | Magnetometer Y                                                 | Intensive time-series                | See example file                   |
| EmotiBit       | MZ                         | Magnetometer Z                                                 | Intensive time-series                | See example file                   |
| EmotiBit       | PG                         | PPG Green                                                      | Intensive time-series                | See example file                   |
| EmotiBit       | PI                         | PPG Infrared                                                   | Intensive time-series                | See example file                   |
| EmotiBit       | PR                         | PPG Red                                                        | Intensive time-series                | See example file                   |
| EmotiBit       | RB                         | Record begin (Include timestamp in Data)                       | Intensive time-series                | See example file                   |
| EmotiBit       | RD                         | Request Data, TypeTag in Payload                               | Intensive time-series                | See example file                   |
| EmotiBit       | SA                         | Skin Conductance Response (SCR) Amplitude                      | Intensive time-series                | See example file                   |
| EmotiBit       | SF                         | Skin Conductance Response (SCR) Frequency                      | Intensive time-series                | See example file                   |
| EmotiBit       | SR                         | Skin Conductance Response (SCR) Rise Time                      | Intensive time-series                | See example file                   |
| EmotiBit       | T1                         | Temperature                                                    | Intensive time-series                | See example file                   |
| EmotiBit       | TH                         | Temperature via Medical-grade Thermopile (only on EmotiBit MD) | Intensive time-series                | See example file                   |
| EmotiBit       | timeSyncMap                | timeSyncMap                                                    | Intensive time-series                | See example file                   |
| EmotiBit       | timesyncs                  | timesyncs                                                      | Intensive time-series                | See example file                   |
| EmotiBit       | TL                         | Local Computer Timestamp                                       | Intensive time-series                | See example file                   |
| EmotiBit       | TX_LC_LM                   | Crosstime, used for timestamp comparison                       | Intensive time-series                | See example file                   |
| EmotiBit       | TX_TL_LC                   | Crosstime, used for timestamp comparison                       | Intensive time-series                | See example file                   |
| IPIP-NEO-120   | IPIP-A1                    | Agreeableness 1: Trust subscore                                | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-A1-1                  | Trust others                                                   | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A1-2                  | Believe that others have good intentions                       | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A1-3                  | Trust what people say                                          | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A1-4                  | Distrust people                                                | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A2                    | Agreeableness 2: Morality subscore                             | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-A2-1                  | Use others for my own ends                                     | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A2-2                  | Cheat to get ahead                                             | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A2-3                  | Take advantage of others                                       | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A2-4                  | Obstruct others' plans                                         | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A3                    | Agreeableness 3: Altruism subscore                             | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-A3-1                  | Love to help others                                            | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A3-2                  | Am concerned about others                                      | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A3-3                  | Am indifferent to the feelings of others                       | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A3-4                  | Take no time for others                                        | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A4                    | Agreeableness 4: Cooperation subscore                          | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-A4-1                  | Love a good fight                                              | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A4-2                  | Yell at people                                                 | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A4-3                  | Insult people                                                  | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A4-4                  | Get back at others                                             | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A5                    | Agreeableness 5: Modesty subscore                              | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-A5-1                  | Believe that I am better than others                           | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A5-2                  | Think highly of myself                                         | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A5-3                  | Have a high opinion of myself                                  | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A5-4                  | Boast about my virtues                                         | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A6                    | Agreeableness 6: Sympathy subscore                             | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-A6-1                  | Sympathize with the homeless                                   | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A6-2                  | Feel sympathy for those who are worse off than myself          | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A6-3                  | Am not interested in other people's problems                   | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-A6-4                  | Try not to think about the needy                               | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-ACI                   | Acquiscience Index                                             | Single float value                   | 2.6                                |
| IPIP-NEO-120   | IPIP-C1                    | Conscientiousness 1: Self-Efficacy subscore                    | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-C1-1                  | Complete tasks successfully                                    | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C1-2                  | Excel in what I do                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C1-3                  | Handle tasks smoothly                                          | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C1-4                  | Know how to get things done                                    | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C2                    | Conscientiousness 2: Orderliness subscore                      | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-C2-1                  | Like to tidy up                                                | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C2-2                  | Often forget to put things back in   their proper place        | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C2-3                  | Leave a mess in my room                                        | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C2-4                  | Leave my belongings around                                     | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C3                    | Conscientiousness 3: Dutifulness subscore                      | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-C3-1                  | Keep my promises                                               | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C3-2                  | Tell the truth                                                 | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C3-3                  | Break rules                                                    | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C3-4                  | Break my promises                                              | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C4                    | Conscientiousness 4: Achievement-Striving subscore             | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-C4-1                  | Work hard                                                      | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C4-2                  | Do more than what's expected of me                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C4-3                  | Do just enough work to get by                                  | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C4-4                  | Put little time and effort into my work                        | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C5                    | Conscientiousness 5: Self-Discipline subscore                  | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-C5-1                  | Am always prepared                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C5-2                  | Carry out my plans                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C5-3                  | Waste my time                                                  | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C5-4                  | Have difficulty starting tasks                                 | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C6                    | Conscientiousness 6: Cautiousness subscore                     | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-C6-1                  | Jump into things without thinking                              | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C6-2                  | Make rash decisions                                            | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C6-3                  | Rush into things                                               | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-C6-4                  | Act without thinking                                           | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E1                    | Extraversion 1: Friendliness subscore                          | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-E1-1                  | Make friends easily                                            | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E1-2                  | Feel comfortable around other people                           | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E1-3                  | Avoid contacts with others                                     | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E1-4                  | Keep others at a distance                                      | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E2                    | Extraversion 2: Gregariousness subscore                        | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-E2-1                  | Love large parties                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E2-2                  | Talk to a lot of different people at parties                   | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E2-3                  | Prefer to be alone                                             | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E2-4                  | Avoid crowds                                                   | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E3                    | Extraversion 3: Assertiveness subscore                         | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-E3-1                  | Take charge                                                    | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E3-2                  | Try to lead others                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E3-3                  | Take control of things                                         | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E3-4                  | Wait for others to lead the way                                | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E4                    | Extraversion 4: Activity Level subscore                        | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-E4-1                  | Am always busy                                                 | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E4-2                  | Am always on the go                                            | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E4-3                  | Do a lot in my spare time                                      | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E4-4                  | Like to take it easy                                           | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E5                    | Extraversion 5: Excitement-Seeking subscore                    | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-E5-1                  | Love excitement                                                | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E5-2                  | Seek adventure                                                 | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E5-3                  | Enjoy being reckless                                           | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E5-4                  | Act wild and crazy                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E6                    | Extraversion 6: Cheerfulness subscore                          | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-E6-1                  | Radiate joy                                                    | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E6-2                  | Have a lot of fun                                              | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E6-3                  | Love life                                                      | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-E6-4                  | Look at the bright side of life                                | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N1                    | Neuroticism 1: Anxiety subscore                                | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-N1-1                  | Worry about things                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N1-2                  | Fear for the worst                                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N1-3                  | Am afraid of many things                                       | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N1-4                  | Get stressed out easily                                        | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N2                    | Neuroticism 2: Anger subscore                                  | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-N2-1                  | Get angry easily                                               | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N2-2                  | Get irritated easily                                           | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N2-3                  | Lose my temper                                                 | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N2-4                  | Am not easily annoyed                                          | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N3                    | Neuroticism 3: Depression subscore                             | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-N3-1                  | Often feel blue                                                | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N3-2                  | Dislike myself                                                 | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N3-3                  | Am often down in the dumps                                     | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N3-4                  | Feel comfortable with myself                                   | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N4                    | Neuroticism 4: Self-Consciousness subscore                     | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-N4-1                  | Find it difficult to approach others                           | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N4-2                  | Am afraid to draw attention to myself                          | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N4-3                  | Only feel comfortable with friends                             | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N4-4                  | Am not bothered by difficult social situations                 | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N5                    | Neuroticism 5: Immoderation subscore                           | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-N5-1                  | Go on binges                                                   | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N5-2                  | Rarely overindulge                                             | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N5-3                  | Easily resist temptations                                      | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N5-4                  | Am able to control my cravings                                 | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N6                    | Neuroticism 6: Vulnerability subscore                          | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-N6-1                  | Panic easily                                                   | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N6-2                  | Become overwhelmed by events                                   | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N6-3                  | Feel that I'm unable to deal with things                       | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-N6-4                  | Remain calm under pressure                                     | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O1                    | Openness 1: Imagination subscore                               | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-O1-1                  | Have a vivid imagination                                       | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O1-2                  | Enjoy wild flights of fancy                                    | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O1-3                  | Love to daydream                                               | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O1-4                  | Like to get lost in thought                                    | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O2                    | Openness 2: Artistic Interests subscore                        | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-O2-1                  | Believe in the importance of art                               | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O2-2                  | See beauty in things that others might not notice              | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O2-3                  | Do not like poetry                                             | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O2-4                  | Do not enjoy going to art museums                              | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O3                    | Openness 3: Emotionality subscore                              | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-O3-1                  | Experience my emotions intensely                               | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O3-2                  | Feel others' emotions                                          | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O3-3                  | Rarely notice my emotional reactions                           | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O3-4                  | Don't understand people who get emotional                      | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O4                    | Openness 4: Adventurousness subscore                           | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-O4-1                  | Prefer variety to routine                                      | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O4-2                  | Prefer to stick with things that I know                        | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O4-3                  | Dislike changes                                                | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O4-4                  | Am attached to conventional ways                               | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O5                    | Openness 5: Intellect subscore                                 | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-O5-1                  | Love to read challenging material                              | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O5-2                  | Avoid philosophical discussions                                | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O5-3                  | Have difficulty understanding abstract ideas                   | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O5-4                  | Am not interested in theoretical discussions                   | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O6                    | Openness 6: Liberalism subscore                                | Single float value                   | 3.9                                |
| IPIP-NEO-120   | IPIP-O6-1                  | Tend to vote for liberal political candidates                  | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O6-2                  | Believe that there is no absolute right or wrong               | (Forward-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O6-3                  | Tend to vote for conservative political candidates             | (Reverse-coded) Single integer value | 1                                  |
| IPIP-NEO-120   | IPIP-O6-4                  | Believe that we should be tough on crime                       | (Reverse-coded) Single integer value | 1                                  |
| ERS            | ERS-1                      | When something happens that upsets me, it's all I can think about it for a long time   | Single integer value                 | 2                                  |
| ERS            | ERS-2                      | My feelings get hurt easily                                                            | Single integer value                 | 2                                  |
| ERS            | ERS-3                      | When I experience emotions, I feel them very strongly/intensely                        | Single integer value                 | 2                                  |
| ERS            | ERS-4                      | When I'm emotionally upset, my whole body gets physically upset as well                | Single integer value                 | 2                                  |
| ERS            | ERS-5                      | I tend to get very emotional very easily                                               | Single integer value                 | 2                                  |
| ERS            | ERS-6                      | I experience emotions very strongly                                                    | Single integer value                 | 2                                  |
| ERS            | ERS-7                      | I often feel extremely anxious                                                         | Single integer value                 | 2                                  |
| ERS            | ERS-8                      | When I feel emotional, it's hard for me to imagine feeling any other way               | Single integer value                 | 2                                  |
| ERS            | ERS-9                      | Even the littlest things make me emotional                                             | Single integer value                 | 2                                  |
| ERS            | ERS-10                     | If I have a disagreement with someone, it takes a long time for me to get   over it    | Single integer value                 | 2                                  |
| ERS            | ERS-11                     | When I am angry/upset, it takes me much longer than most people to calm   down         | Single integer value                 | 2                                  |
| ERS            | ERS-12                     | I get angry at people very easily                                                      | Single integer value                 | 2                                  |
| ERS            | ERS-13                     | I am often bothered by things that other people don't react to                         | Single integer value                 | 2                                  |
| ERS            | ERS-14                     | I am easily agitated                                                                   | Single integer value                 | 2                                  |
| ERS            | ERS-15                     | My emotions go from neutral to extreme in an instant                                   | Single integer value                 | 2                                  |
| ERS            | ERS-16                     | People tell me I have a very short fuse                                                | Single integer value                 | 2                                  |
| ERS            | ERS-17                     | People tell me that my emotions are often too intense for the situation                | Single integer value                 | 2                                  |
| ERS            | ERS-18                     | I am a very sensitive person                                                           | Single integer value                 | 2                                  |
| ERS            | ERS-19                     | My moods are very strong and powerful                                                  | Single integer value                 | 2                                  |
| ERS            | ERS-20                     | I often get so upset it's hard for me to think straight                                | Single integer value                 | 2                                  |
| ERS            | ERS-21                     | Other people tell me I'm overreacting                                                  | Single integer value                 | 2                                  |
| ERS            | ERS-SENS                   | Sensitivity subscale                                                                   | Single float value                   | 1.7                                |
| ERS            | ERS-ARIN                   | Arousal/ Intensity subscale                                                            | Single float value                   | 1.7                                |
| ERS            | ERS-PERS                   | Persistence subscale                                                                   | Single float value                   | 1.7                                |
