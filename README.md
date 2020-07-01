# Speaker-voice-Recognition-using-MFCC-algorithm-in-matlab
Detecting the speaker based on his voice. In this project, we mainly deal with Text-Dependent Speaker recognition system i.e., speaker has to speak a specific word to detect his voice.


# Description of Project:
1. We record an audio sample of each speaker and save them in a folder called 'Train' with their Speaker ID
2. During testing phase, we record an audio sample of any speaker and compute MFCC(Mel Freq Cepstral Co-efficients) using mfcc alogorithm and also save it in a folder called 'Test'.
3. We then compute MFFC of all samples saved in 'Train' folder and find Euclidian distance between MFCC of test file and MFCC's of train files.
4. The least distance between the test model and train model gives the speaker ID.
5. To train any speaker model, first go to the directory where this files are located and type the command "name = train('Train/name')". name - speaker ID
6. To find the speaker who is speaking, type the command "test('Test/name')". name - Speaker ID
7. Output will give all the Euclidian Distances and Final Speaker ID.
8. NOTE : Try to record the audio samples in same environment and in same length.
# Speaker-voice-Recognition-using-MFCC-algorithm-in-matlab
