# Speech-to-Text-Transcription-and-Analysis
<img src="TalkBank.png" alt="GitHub Image" width="550">

This project delves into the realm of speech recognition, aiming to convert spoken language into written text. Leveraging various libraries and technologies, the project transcribes audio from diverse sources, especially focusing on children's voices, and conducts comprehensive analyses of the transcribed data.

---

## Data Source
The project utilizes various audio samples as primary data sources. These samples include live recordings and pre-recorded audio files, especially from the [TalkBank](https://talkbank.org/) project and its `HomeBank` data. The `transcript-conversion-analysis` notebook focuses on the exploration and processing of this data.

---

## Libraries Used
The project utilizes a variety of libraries and services to facilitate speech recognition and data analysis:

- `SpeechRecognitio`n: A Python library for performing speech-to-text conversion.
- `Google Cloud Speech-to-Text`: Google's cloud-based engine for speech recognition.
- `AWS SDK for Python (Boto3)`: Python SDK to interact with AWS services, including AWS Transcribe.
- `IBM Watson Developer Cloud Python SDK`: SDK enabling access to IBM Watson's speech-to-text services.
- `Azure SDK for Python`: Python SDK for interfacing with Microsoft Azure services, including its speech service.
- `Rev.ai Python SDK`: SDK for integrating with the Rev.ai transcription service.

---
## Analysis
The project's primary objective is to transcribe spoken language with high accuracy. 

- `Transcription Engines`: The `comparing-speech-to-text-systems` notebook delves into the comparison and utilization of various online speech-to-text systems.
- `Transcript Conversion`: The `transcript-conversion-analysis` notebook details methods for converting and structuring the transcripts for subsequent analysis.
- `Frequency Analysis`: Within the `transcript-conversion-analysis` notebook, methodologies are provided for evaluating word and phrase frequencies.
- `Sentiment Analysis`: The potential for sentiment analysis is highlighted in the `transcript-conversion-analysis` notebook.
- `Length Analysis`: The `transcript-conversion-analysis` notebook investigates statement lengths and verbosity patterns.
- `Topic Modeling`: Potential topic identification from the transcribed data is discussed in the `transcript-conversion-analysis` notebook.

---
## Key Achievements
- `Versatile Transcription`: The `comparing-speech-to-text-systems` notebook showcases successful transcription of children's voices using multiple services.
- `Detailed Analysis`: The second notebook, `transcript-conversion-analysis`, offers a comprehensive analytical approach to the transcripts.
- `Diarization`: Emphasis on speaker separation is highlighted in the notebooks, enabling detailed breakdowns of spoken content by individual participants.

---
## Conclusion
The `Speech-to-Text-Transcription-and-Analysis` project showcases the capabilities and adaptability of modern speech recognition techniques. By integrating findings from both notebooks, the project offers a comprehensive system for transcribing and analyzing spoken language, especially focusing on children's voices.

---
## Future Work
Potential advancements and extensions for this project include:
- `Advanced Recognition Engines`: Integration with more state-of-the-art recognition engines.
- `Neural Network Models`: Exploration of deep learning-based models for enhanced transcription accuracy.
- `Complex Diarization`: Handling more intricate audio samples with multiple speakers and background noise.
- `Natural Language Processing`: Incorporation of advanced NLP techniques to further refine and structure transcribed content.

---
## Note
For a comprehensive understanding of the methodologies and conclusions drawn in this project, it is recommended to go through both notebooks in detail, including the code and its outputs.

---
#### Author
Jesus Cantu Jr.

---
#### Last Updated
October 10, 2023
