
#  Human Psychological Counselling Platform

## Overview
"PsycoCouncil" is an innovative psychological counseling platform designed to enhance the counseling experience by integrating advanced technologies. It leverages Computer Vision to precisely recognize emotions, analyzing facial expressions and micro-expressions for accurate emotional assessment. Additionally, Signal Processing is employed to monitor heart rate, offering real-time physiological insights. These technologies work together to provide a detailed and comprehensive analysis, enabling counselors to better understand and support their clients. The platform generates personalized reports for patients, summarizing the findings and recommendations based on the collected data.

## Cite
  ```
    TY  - CONF
    TI  - Human Psychological Counselling Framework using Computer Vision
    T2  - 2024 11th International Conference on Computing for Sustainable Global Development (INDIACom)
    SP  - 745
    EP  - 750
    AU  - Subhajit. Dutta
    AU  - Vedant. Shukla
    AU  - Yashi. Pant
    AU  - Vikas. Tripathi
    PY  - 2024
    DO  - 10.23919/INDIACom61295.2024.10498255
    Y1  - 28 Feb.-1 March 2024 
  ```

## Project Link
  [Webapp](https://counsellingplatform-byyashi.streamlit.app/) 
   *Reboot if faced with memory issues*

## Research Paper
  [Human Psychological Counselling Framework using Computer Vision
](https://ieeexplore.ieee.org/document/10498255)


## Usage
1. Start Monitor, and get live data of emotion recognition.
2. Stop Monitor, and get emotion tracking and heart metric reports.
3. Go to Counsel Tab, Select informations that you want to give to the chatbot.
4. Fill-up required values, press counsel button, and recieve feedback from AI.

## Technology used
- Streamlit for web application
- DeepFace Facial Atrribute Analysis
- GPT-4 for LLM integration (Clarifai Model wrapped in LangChain)
- rPhotoplethysmography (rPPG) for heart rate analysis
- AssemblyAI speech recognition and GTTS



## Running the App Locally

1. **Clone the Repository**:  
   ```
   https://github.com/yashi-star/CounsellingPlatform.git
   ```

2. **Install Virtual Environment**:  
   ```
   python -m venv venv
   ```
   Activate the virtual environment:
   - On Windows: `venv\Scripts\Activate`
   - On macOS and Linux: `source venv/bin/activate`

3. **Install Required Packages**:  
   ```
   pip install -r requirements.txt
   ```

4. **Run the Streamlit App**:  
   ```
   streamlit run app.py
   ```

5. **Open the App**:  
   The app should now be running. Open your web browser and go to `http://localhost:8501/` to interact with the app.

## Applications

1. **Mental Health Assessment**: Useful for psychologists and therapists.
2. **Fitness and Wellness**: Monitor cardiovascular health.
3. **Telehealth Services**: Provide real-time data to healthcare providers.

## User Trust & Ethics
- Immediate deletion after processing speech transcription.


##DEMO Video
https://drive.google.com/file/d/1ySUDMsItClW0wXAk5010xfMbLfZnION6/view?usp=sharing
