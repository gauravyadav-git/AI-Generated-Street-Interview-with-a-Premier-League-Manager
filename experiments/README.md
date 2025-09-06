# Experiments Log – Task 06 (AI Street Interview)

This folder documents all experiments, trials, and alternative approaches explored while creating the AI-generated street interview for Research Task 06.

---

## 🔎 Approach 1: ChatGPT
- **Tool Used**: ChatGPT  
- **Goal**: Directly generate an AI street interview (audio/video).  
- **Result**: Not possible in this environment.  
- **Outcome**: ChatGPT suggested alternative tools such as **ElevenLabs** and **Narakeet** for TTS and video interviews.  
- **Status**: ❌ Did not produce final audio/video, but helped identify next tools to try.

---

## 🔎 Approach 2: Gemini AI
- **Tool Used**: Google Gemini AI  
- **Goal**: Attempt audio/video generation.  
- **Result**: Unable to generate full audio or video interview.  
- **Status**: ❌ Abandoned after initial test.

---

## 🔎 Approach 3: ElevenLabs (Voice Cloning)
- **Tool Used**: ElevenLabs  
- **Extra Resource**: Uploaded an **audio sample of Mikel Arteta** from [voicy.network](https://voicy.network).  
- **Goal**: Clone Arteta’s voice and generate full text-to-speech interview.  
- **Result**: Voice cloning successful, but **text-to-speech feature requires a paid subscription**.  
- **Status**: ❌ Stopped at cloning stage due to paywall.

---

## 🔎 Approach 4: Narakeet (Text-to-Speech)
- **Tool Used**: Narakeet TTS platform  
- **Goal**: Generate interview audio with two distinct voices (Interviewer + Mikel Arteta).  
- **Process**:  
  1. Uploaded each question and answer separately.  
  2. Generated **10 audio clips** (5 interviewer + 5 Arteta).  
  3. Used available sample voices (since Arteta’s cloned voice couldn’t be uploaded).  
- **Result**: Produced realistic audio, but only in separate files.  
- **Status**: ✅ Partial success.

---

## 🔎 Approach 5: Combining Audio Clips
- **Goal**: Merge 10 Narakeet audio files into a single continuous interview.  
- **Attempts**:  
  - Tried AI/audio tools → most required **paid subscriptions**.  
  - Tried Python with `pydub`, but needed **FFmpeg installation**.  
- **Final Solution**: Used **Clideo.com** (free online editor) to merge the 10 clips into **one complete interview**.  
- **Result**: **✅ Final audio interview successfully created**.

---

## 🔎 Approach 6: Wavel AI
- Uploaded a fresh interview script into **Wavel AI**.  
- **Strengths:**  
  - Generated a **video output** with **auto-subtitles**.  
  - Added **contextual content** beyond the script (e.g., references to Arsenal matches from just days ago).  
  - Included **stock football and Arsenal visuals**, enhancing realism.  
- **Limitations:**  
  - Only **one voice** used (same for interviewer and Mikel Arteta).  
  - Script role indicators (e.g., “Interviewer - …”) were read literally as part of the dialogue.  
- **Final Output:** `Mikel Arteta Discusses Arsenal's Progress and Aspirations-mp4`.

---

## 📊 Summary
- Multiple tools were tested (ChatGPT, Gemini, ElevenLabs, Narakeet, Python).  
- The final working workflow: **Script → Narakeet TTS (10 clips) → Clideo (merge) → Final Interview Audio**.  
- This iterative process highlights both **technical challenges** (paywalls, limitations of free tools) and **problem-solving** (finding alternate free solutions).  

---

