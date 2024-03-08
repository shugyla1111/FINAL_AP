# FINAL_AP
Speech to Text Converter Project Report Introduction Problem The Speech to Text Converter addresses the need for accurate and real-time transcription of spoken language into text, a technology that benefits accessibility and efficient communication.

Literature Review This field features a variety of solutions, including Google's API [1], IBM's Watson [2], and open-source projects like DeepSpeech [3]. These resources provide a foundation for understanding current technologies and methodologies.

Current Work Our project introduces a web interface, enabling users to record or upload audio for transcription. We designed the interface using HTML5, CSS3, and JavaScript to interact with the users effectively.

Data and Methods Information About the Data User-provided audio is at the heart of our system. We've analyzed sample rates, frequency content, and signal-to-noise ratios, which are crucial for the transcription quality. Visual data representations can be found in Appendix A.

Description of the ML/DL Models The model is developed in Python using TensorFlow and Keras within Google Colab, employing a recurrent neural network with an attention mechanism for improved focus on relevant audio segments. Theoretical background and model details are thoroughly discussed in our Colab notebook [4].

Results The model's accuracy on the test set is presented in the tables and figures below:

Table 1: Accuracy compared to baselines. Figure 1: Training curves for loss and accuracy. Table 2: Transcription latency comparison. Detailed results can be viewed in Appendix B.

Discussion Critical Review of Results The model excels in clear audio settings but underperforms with background noise and accents, pinpointing areas for enhancement.

Next Steps We aim to extend the model's capabilities to handle diverse environments and accents better and support multilingual transcription, with user experience research driving further interface improvements.

Conclusion Our Speech to Text Converter bridges the gap between spoken words and written text, employing advanced ML/DL techniques and offering a user-centric web interface for seamless interaction.

References [1] "Google Cloud Speech-to-Text," Google Cloud. [Online]. Available: https://cloud.google.com/speech-to-text. [2] "IBM Watson Speech to Text," IBM Cloud. [Online]. Available: https://www.ibm.com/cloud/watson-speech-to-text. [3] "Project DeepSpeech," Mozilla GitHub. [Online]. Available: https://github.com/mozilla/DeepSpeech.
