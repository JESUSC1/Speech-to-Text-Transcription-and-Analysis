# Speech-to-Text-Transcription-and-Analysis
<img src="TalkBank.png" alt="GitHub Image" width="550">

This project delves into the realm of speech recognition, aiming to convert spoken language into written text. Leveraging various libraries and technologies, the project transcribes audio from diverse sources, especially focusing on children's voices, and conducts comprehensive analyses of the transcribed data.

---

## Data Source
This project employs a range of audio samples as its foundational data sources:

- The `comparing-speech-to-text-systems` notebook primarily employs diverse audio samples to evaluate and compare various online transcription services. These samples encompass live recordings and pre-recorded audio files, including those of children's voices, to assess the transcription efficacy of each service.

- The data in the `transcript-conversion-analysis` notebook predominantly stems from the [TalkBank](https://talkbank.org/) project, specifically its HomeBank component. `HomeBank` is a rich resource of shared recordings documenting children's everyday experiences. This notebook delves deep into the exploration, conversion, and analysis of transcripts derived from this data.

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
The project's primary objective is to transcribe spoken language with high accuracy. Analyses are divided into two Python notebooks. 

`comparing-speech-to-text-systems` notebook:
- `Transcription Engines`: This notebook delves into the comparison and utilization of various online speech-to-text systems such as GCP, AWS, IBM, Azure, and Rev.ai.


`transcript-conversion-analysis` notebook:
- `Transcript Conversion`: Details methods for converting and structuring the transcripts for subsequent analysis.
- `Frequency Analysis`: Methodologies are provided for evaluating word and phrase frequencies.
- `Sentiment Analysis`: Highlights the potential for sentiment analysis.
- `Length Analysis`: Investigates statement lengths and verbosity patterns.
- `Topic Modeling`: Discusses potential topic identification from the transcribed data.

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
For an HTML view of the  `comparing-speech-to-text-systems` notebook click [here](https://nbviewer.org/https:/github.com/JESUSC1/Speech-to-Text-Transcription-and-Analysis/blob/main/comparing-speech-to-text-systems.ipynb) while the HTML version of the `transcript-conversion-analysis` notebook can be found [here](https://nbviewer.org/github/JESUSC1/Speech-to-Text-Transcription-and-Analysis/blob/main/transcript-conversion-analysis.ipynb)

---
#### Author
Jesus Cantu Jr.

---
#### Last Updated
October 10, 2023
