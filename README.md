# Research Task 06 – AI Street Interview (Premier League 2022–23)

## 📌 Overview
This project is **Research Task 06**, which builds on earlier work from Task 05 part 1 and part 2.

- In **Task 05 - part 1**, I analyzed the Premier League 2022–23 dataset without grouping, generated descriptive statistics for the first 10 rows, designed LLM prompts, and compared AI responses with Python results.  
- In **Task 05 - part 2**, I extended the analysis to the full dataset by **grouping by stadium**, producing pivot-style summaries, targeted visualizations, and Python scripts for more complex queries.  

**Task 06** takes a creative turn by applying those insights to an **AI-generated “street interview”** with Arsenal manager **Mikel Arteta**, reflecting on team performance during the 2022–23 season and looking ahead to the future.

---

## 🏟 Task 06 Objective
- Create a **street interview script** based on dataset insights (Task 05 focus: no grouping).  
- Generate **AI audio interview** with distinct voices for interviewer and manager.  
- Document multiple approaches attempted, including failures and final workflow.  
- Deliver a final **merged audio interview** simulating a realistic media interaction.

---

## 📂 Repository Contents

| File Name | Description |
|-----------|-------------|
| **script.txt** | Interview script used as input for audio/video generation. |
| **Task_06_Street_Interview.mp3** | Final merged audio interview (from Narakeet + Clideo). |
| **Mikel Arteta Discusses Arsenal's Progress and Aspirations-mp4** | Final video interview (Wavel AI) with subtitles and stock footage. |
| **experiments/** | Documentation of all attempts (ChatGPT, Gemini, ElevenLabs, Narakeet, Wavel AI). |
| ├── **README.md** | Detailed log of experiments and outcomes. |
| ├── **chatgpt_attempts.txt** | Notes from ChatGPT/Gemini trials. |
| ├── **elevenlabs_attempts.txt** | Notes from voice cloning test. |
| ├── **narakeet_clips/** | 10 generated audio clips before merging. |
| └── **clideo_merge.txt** | Notes on merging Narakeet clips into one audio file. |

---

## 🛠 Workflow & Approaches

### Tools Explored
1. **ChatGPT** → Could not generate audio/video, but suggested other tools.  
2. **Gemini AI** → No audio/video interview support.  
3. **ElevenLabs** → Successful voice cloning of Arteta using sample from `voicy.network`, but full TTS required paid subscription.  
4. **Narakeet** → Generated 10 separate clips (Interviewer + Arteta).  
5. **Clideo.com** → Merged clips into single interview.  
6. **Python (pydub)** → Attempted merging locally, but required FFmpeg installation. Not pursued.
7. **WavelAI** → Generated a video Interview.

### ✅ Final Workflow
1. Drafted street interview script (Interviewer + Mikel Arteta).  
2. Tested multiple platforms (ChatGPT, Gemini, ElevenLabs, Narakeet).  
3. Produced audio-only interview with Narakeet + Clideo.  
4. Produced a **video interview with Wavel AI**, including auto-subtitles and contextual football clips.  

---

## 📊 Reflection
This task demonstrated:  
- How **analytical insights** can be transformed into narrative storytelling.  
- The process of **evaluating and troubleshooting multiple AI tools** (balancing free vs. paid features).  
- How **different platforms add different value**:  
  - Narakeet gave controlled dialogue (audio only).  
  - Wavel AI added creativity, recent football references, and stock visuals for a realistic video.  

The final result is a combination of **audio and video deliverables**, showing both technical adaptability and creative application of AI tools.

---
