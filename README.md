# CardioSonic
------------------------------
TITLE
------------------------------
AngioScope: AI-Enhanced Smart Stethoscope for Blood Vessel Blockage Detection

------------------------------
ABSTRACT
------------------------------
We propose an electronic stethoscope, AngioScope, designed to identify blood vessel blockages as a low-cost, non-invasive alternative to conventional angiography. Our method leverages extensive research done to detect cardiovascular disease (CVD) using heart sound analysis.
Our unique and innovative method is to apply audio processing techniques to analyze heart sound in combination with machine learning to diagnose blood vessel blockages with significant precision. This will allow general practitioners to make confident medical decisions without the use of conventional angiograms. Currently, there are numerous electronic stethoscopes in the market but without any diagnostic capability.
The proposed method involves an electronic chest piece that converts heart vibrations to a digitally encoded signal using transducers such as microphones or acclerometers. Digital signal processing (DSP) hardware will be used to extract unique spectral features from patient heart sounds. Then a trained Convlutional Neural Network (CNN) digital hardware is used to detect blockages by recognizing unique spectral signatures. The result will then be displayed locally on a small display on the stethoscope and transmitted wirelessly using the Bluetooth or WiFi protocol.

Our method of implementation involves first building a model in the Python programming language. A machine learning model is used to train the model with a large dataset of heart sounds from the 2016 Challenge Database of PhysioNet Computational Cardiology (CinC). This has been implemented and the trained model shows 92% accuracy in detecting blockages in blood vessels, proving the feasibility of the proposed solution. This validated model will be implemented on a ESP32 Node MCU or a Raspberry Pi Zero to demonstrate the viability of the proposed solution. In the process of implementation, the architecture will be significantly optimized to use minimal hardware to implement the solution.


------------------------------
TABLE OF CONTENT
------------------------------
1. PROBLEM STATEMENT
2. PROBLEM BACKGROUND
    2.1 Need for an Alternative Technology
3. CARDIOSONIC SOLUTION
    3.1 Technology Background
    3.2 Idea Description
    3.3 Modeling And Training for Feasibility and Viability Analysis
        3.3.1 About the Dataset
        3.3.2 Training the Neural Network
        3.3.3 Technologies Used
        3.3.4 Three Steps to Final Prototype
4. POTENTIAL CHALLENGES and RISKS
5. STRATEGIES for OVERCOMING the RISKS
6. IMPACT AND BENEFITS
7. REFERENCES
8. PYTHON CODE
    8.1 Python Code for training the CNN
    8.2 Python Code for CVD Diagnosis
