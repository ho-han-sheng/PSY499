# PSY499
 Repository for PSY499: Capstone Psychology Project

| Measure        | Tag                        | Description                                                    | Type                  | Example                            |
| -------------- | -------------------------- | -------------------------------------------------------------- | --------------------- | ---------------------------------- |
| Participant ID | PID                        | Nonidentifiable generated participant id                       | String                | P209                               |
| I-PANAS-SF     | T-PA                       | Trait positive affect                                          | Single float value    | 6                                  |
| I-PANAS-SF     | T-NA                       | Trait negative affect                                          | Single float value    | 10                                 |
| History        | TBI                        | Traumatic brain injury                                         | Binary yes/no         | 0                                  |
| History        | DEP                        | Any depressive disorder                                        | Binary yes/no         | 1                                  |
| History        | ANX                        | Any anxiety disorder                                           | Binary yes/no         | 1                                  |
| History        | BIP                        | Any bipolar and related disorder                               | Binary yes/no         | 1                                  |
| History        | FED                        | Any feeding and eating disorder                                | Binary yes/no         | 0                                  |
| History        | PD                         | Any physical disability/injury affecting your hands/fingers    | Binary yes/no         | 1                                  |
| IPIP-NEO-120   | IPIP-O                     | Openness subscore                                              | Single float value    | 23                                 |
| IPIP-NEO-120   | IPIP-C                     | Conscientiousness subscore                                     | Single float value    | 25                                 |
| IPIP-NEO-120   | IPIP-E                     | Extraversion subscore                                          | Single float value    | 12                                 |
| IPIP-NEO-120   | IPIP-A                     | Agreeableness subscore                                         | Single float value    | 2                                  |
| IPIP-NEO-120   | IPIP-N                     | Neuroticism subscore                                           | Single float value    | 9                                  |
| Valence        | PA                         | Self-report positive affect                                    | Intensive time-series | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Valence        | NA                         | Self-report negative affect                                    | Intensive time-series | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Appraisal      | FL                         | Appraised feeling                                              | List of strings       | Happy', 'Sad'                      |
| Appraisal      | FS                         | Start of feeling timestamp                                     | List of float values  | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Appraisal      | FA                         | Feeling apex timestamp                                         | List of float values  | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| Appraisal      | FE                         | Feeling end timestamp                                          | List of float values  | 0, 2, 4, 45, 67, … , 100, 23, 1, 0 |
| EmotiBit       | 2025-03-25_18-41-14-083733 | File passed through DataParser to provide individual csv below | Intensive time-series | See example file                   |
| EmotiBit       | AK                         | Acknowledgement                                                | Recording metadata    | See example file                   |
| EmotiBit       | AX                         | Accelerometer X                                                | Intensive time-series | See example file                   |
| EmotiBit       | AY                         | Accelerometer Y                                                | Intensive time-series | See example file                   |
| EmotiBit       | AZ                         | Accelerometer Z                                                | Intensive time-series | See example file                   |
| EmotiBit       | B%                         | Battery Percentage Remaining                                   | Intensive time-series | See example file                   |
| EmotiBit       | BI                         | Heart Inter-beat Interval                                      | Intensive time-series | See example file                   |
| EmotiBit       | BV                         | Battery Voltage                                                | Intensive time-series | See example file                   |
| EmotiBit       | EA                         | EDA- Electrodermal Activity                                    | Intensive time-series | See example file                   |
| EmotiBit       | EL                         | EDL- Electrodermal Level                                       | Intensive time-series | See example file                   |
| EmotiBit       | EM                         | Emotibit Mode                                                  | Intensive time-series | See example file                   |
| EmotiBit       | GX                         | Gyroscope X                                                    | Intensive time-series | See example file                   |
| EmotiBit       | GY                         | Gyroscope Y                                                    | Intensive time-series | See example file                   |
| EmotiBit       | GZ                         | Gyroscope Z                                                    | Intensive time-series | See example file                   |
| EmotiBit       | HR                         | Heart Rate                                                     | Intensive time-series | See example file                   |
| EmotiBit       | info                       | info json                                                      | Recording metadata    | See example file                   |
| EmotiBit       | LM                         | LSL Marker/message                                             | Intensive time-series | See example file                   |
| EmotiBit       | MX                         | Magnetometer X                                                 | Intensive time-series | See example file                   |
| EmotiBit       | MY                         | Magnetometer Y                                                 | Intensive time-series | See example file                   |
| EmotiBit       | MZ                         | Magnetometer Z                                                 | Intensive time-series | See example file                   |
| EmotiBit       | PG                         | PPG Green                                                      | Intensive time-series | See example file                   |
| EmotiBit       | PI                         | PPG Infrared                                                   | Intensive time-series | See example file                   |
| EmotiBit       | PR                         | PPG Red                                                        | Intensive time-series | See example file                   |
| EmotiBit       | RB                         | Record begin (Include timestamp in Data)                       | Intensive time-series | See example file                   |
| EmotiBit       | RD                         | Request Data, TypeTag in Payload                               | Intensive time-series | See example file                   |
| EmotiBit       | SA                         | Skin Conductance Response (SCR) Amplitude                      | Intensive time-series | See example file                   |
| EmotiBit       | SF                         | Skin Conductance Response (SCR) Frequency                      | Intensive time-series | See example file                   |
| EmotiBit       | SR                         | Skin Conductance Response (SCR) Rise Time                      | Intensive time-series | See example file                   |
| EmotiBit       | T1                         | Temperature                                                    | Intensive time-series | See example file                   |
| EmotiBit       | TH                         | Temperature via Medical-grade Thermopile (only on EmotiBit MD) | Intensive time-series | See example file                   |
| EmotiBit       | timeSyncMap                | timeSyncMap                                                    | Intensive time-series | See example file                   |
| EmotiBit       | timesyncs                  | timesyncs                                                      | Intensive time-series | See example file                   |
| EmotiBit       | TL                         | Local Computer Timestamp                                       | Intensive time-series | See example file                   |
| EmotiBit       | TX_LC_LM                   | Crosstime, used for timestamp comparison                       | Intensive time-series | See example file                   |
| EmotiBit       | TX_TL_LC                   | Crosstime, used for timestamp comparison                       | Intensive time-series | See example file                   |