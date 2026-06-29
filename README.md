# MonkeySign

## About
MonkeySign is a SGSL speed signing platform inspired by Monkeytype

## Project Timeline
| Task | Duration |
|------|----------|
| Finalize requirements | 1 wk |
| Finalize UI/UX | 1 wk |
| Data scraping/ storing/ cleaning | 2 wk |
| ML Model with suitable accuracy | 2 wk |
| Integrate Frontend/ Backend/ ML | 2 wk |
| Rate limiting/ Hosting | 1 wk |

## Tech Stack
- Data Collection: Python
- Frontend: Angular + Mediapipe (Feature Extractor) + TensorFlow.js (Run My Model)
- Backend: Supabase
- ML Model: Python, TensorFlow
- Hosting: Vercel

## Features
1. Generate random words/ words of a quote to sign
2. Use ML to detect sign from webcam
3. Webcam border indicator red: incorrect, grey: unable to detect, green: correct for sign detection

## ML Scope
- Phase 1: Static + Motion Alphabet (A-Z) & Numbers (1-10)
   + └── Establishes MediaPipe pipeline and fingerspelling engine.
- Phase 2: High-Frequency Core SgSL Vocabulary (~100 to 200 common words)
   + └── Teaches LSTM/Transformer model to recognize multi-frame dynamic words.
- Phase 3: Deep SgSL Sign Bank Scraping (All 1,000 words)
   + └── Scaling up data and fine-tuning model accuracy.

## To Do
### Week 1:
- [x] Basic User Requirements
- [x] Data Sources
- [x] Tech Stack
- [ ] System Design

## Data sources
[NTU SGSL Blog](https://blogs.ntu.edu.sg/sgslsignbank/signs/)
[Raw](https://www.kaggle.com/datasets/vignonantoine/combinedasldatasets)
[Google ASL Recognition](https://www.kaggle.com/competitions/asl-fingerspelling)

## Remarks/ Ideas
+ For concerns of camera quality issues on laptop, explore mobile to desktop sync of web application
+ Explore ideas to make application work on mobile and desktop environments

