# Lip-sync-using-Wav2lip
Lip-sync using Wav2lip:
*	I have provided with a youtube link and an audio and my task is to Lip-sync them.
*	Here, I have used Google Colab to build this model.
*	I have used pretrained Wav2lip Model
* First import the wav2lip model and their weights.
*	Then import the required libraries and then import the youtube video and get the video trimmed according to the audio.
*	Also import the audio.
*	Then by using wav2lip model I have synced the video.
# Errors that I have faced:
*	In that youtube video, there are some frames where the person not visible only some images occurs.
*	To rectify it, I have skipped those images in inference.py and then run the model.
*	Another error I have faced is due to too many frames, the model shows an ^c error.
*	It seems that the code is running in a loop, and the KeyboardInterrupt is preventing it from continuing.
*	So I have changed the code according to the specifications.
