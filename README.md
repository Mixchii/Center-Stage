# Center-Stage
TSA 26-27 Software Development Theme: Develop a software application that improves how people learn, teach, practice, or develop new skills. Competitors should identify an educational or training challenge affecting learners of any age and design an engaging, effective, and user-centered software solution.


**Center-Stage** is a public speaking and presentation simulator made to reduce speaking anxiety with real time objective feedback. You present directly to your webcam and get feedback on your pacing, filler words, and eye contact. 

This application addresses the theme by helping people improve their public speaking, which is a challenge that affects all ages. This is engaging and effective to maximize the most learning and growth possible.

## Key Features

- **Live Speech to Text and Filler Detection:** Uses the Web Speech API (`webkitSpeechRecognition`) to live stream transcriptions of one’s speech and detect fillers such as ("um", "uh", "like", "you know", "basically", "actually").
- **Pacing in Real-Time and Audio:** FInds the WPM live with an `AudioContext` volume tracker.
- **Computer Vision and Eye Contact Detection:** Uses MediaPipe face mesh for analyzing eye contact and head position.
- **Virtual Stage and Teleprompter:** Practice sessions in many virtual environments (Auditorium, Boardroom, Virtual Panel, Tech Keynote) and a scrolling teleprompter.
- **Post-session analytics report:** Makes session reports with details about how many fillers were used, how one held their posture through the speech.
- **100% Private and client-side processing:** Video, audio, and speech transcriptions are all done locally inside your browser without any data leaving it. Your data is secure.


Because **Center-Stage** runs entirely in the browser, there are no dependencies to install.

### Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/center-stage.git](https://github.com/YOUR-USERNAME/center-stage.git)
