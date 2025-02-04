# AssemblyAI Cookbook 🧑‍🍳
The AssemblyAI Cookbook is a resource of code examples, guides, and tutorials for using the AssemblyAI API. Want to learn more about AssemblyAI? Check out this [product overview video](https://youtu.be/UT1sBCuSJxE)!

You will need an AssemblyAI account and API key to use these code examples. [Click here](https://www.assemblyai.com/dashboard/signup) to create and account for free.

Most code examples are written in Python or Javascript, but the concepts contained in these examples can be applied to any language. You can learn more about our various models in features in our [official documentation](https://www.assemblyai.com/docs/).

## Core Transcription 🎙️
[Transcribe an Audio File](core-transcription/transcribe.ipynb)      
[Transcribe from an AWS S3 Bucket](core-transcription/transcribe_from_s3.ipynb)  
[Transcribe a batch of files using AssemblyAI](core-transcription/transcribe_batch_of_files)   
[Use our SDK transcribe a batch of files](core-transcription/SDK_transcribe_batch_of_files)  
[Transcribe multiple files simultaneously using our Python SDK](core-transcription/SDK_transcribe_batch_of_files/batch_transcription.ipynb)      
[Transcribe multiple files simultaneously using our Node.js SDK](core-transcription/SDK-Node-batch.md)   
[Transcribe YouTube videos](core-transcription/transcribe_youtube_videos.ipynb)  
[Transcribe Google Drive links](core-transcription/transcribing-google-drive-file.md)  
🆕[Transcribe GitHub Files](core-transcription/transcribing-github-files.md)  
[Detect Low Confidence Words in a Transcript](core-transcription/detecting-low-confidence-words.md)  
[Translate Transcripts](core-transcription/translate_transcripts.ipynb)  
[Generate Subtitles for Videos](core-transcription/subtitles.ipynb)\
🆕[Generate Speaker Labels with Make.com](core-transcription/make.com-speaker-labels.md)\
[Translate Subtitles](core-transcription/translate_subtitles.ipynb)     
[Specify a Language](core-transcription/specify-language.ipynb)  
[Use Automatic Language Detection](core-transcription/automatic-language-detection.ipynb)    
🆕[Automatic Language Detection as separate step from Transcription](core-transcription/automatic-language-detection-separate.ipynb)    
[Create Subtitles with Speaker Labels](core-transcription/speaker_labelled_subtitles.ipynb)   
🆕[Split audio file to shorter files](core-transcription/split_audio_file)   
🆕[Identify Duplicate Channels in Stereo Files](core-transcription/identify_duplicate_channels.ipynb)\
[Delete a Transcript ](core-transcription/delete_transcript.ipynb)  
[Build a UI for Transcription with Gradio](core-transcription/gradio-frontend.ipynb)  
[Troubleshoot common errors when starting to use our API](core-transcription/common_errors_and_solutions.md)  
🆕[Automatically Retry Server Errors](core-transcription/retry-server-error.ipynb)  
🆕[Delete transcripts after 24 hours of creation](core-transcription/schedule_delete.ipynb)  
[Create a speaker timeline with Speaker Labels](core-transcription/speaker_timeline.ipynb)\
[Route to Default Language if Language Detection Confidence is Low - Python](core-transcription/automatic-language-detection-route-default-language-python.ipynb)\
[Route to Default Language if Language Detection Confidence is Low - JS](core-transcription/automatic-language-detection-route-default-language-js.md)\
[Do more with the JavaScript SDK](core-transcription/do-more-with-sdk-js.md)\
🆕[Do more with the Python SDK](core-transcription/do-more-with-sdk-python.ipynb)\
🆕[Use AssemblyAI with Pyannote to generate custom Speaker Labels](core-transcription/Use_AssemblyAI_with_Pyannote_to_generate_custom_Speaker_Labels.ipynb)\
🆕[Audio Duration Fix](core-transcription/audio-duration-fix.ipynb)\
🆕[Calculate Talk/Listen Ratio of Speakers](core-transcription/talk-listen-ratio.ipynb)\
🆕[Speaker Diarization with Async Chunking](core-transcription/speaker-diarization-with-async-chunking.ipynb)\
🆕[Near-Realtime Python Speech-to-Text App](https://github.com/AssemblyAI-Solutions/async-chunk-py)\
🆕[Near-Realtime Node.js Speech-to-Text App](https://github.com/AssemblyAI-Solutions/async-chunk-js)

## Audio Intelligence 🤖
[Create Summarized Chapters from Podcasts](audio-intelligence/auto_chapters.ipynb)  
[Identify Hate Speech in Audio and Video Files](audio-intelligence/content_moderation.ipynb)     
[Identify Highlights in Audio and Video Files](audio-intelligence/key_phrases.ipynb)      
[Identify Speakers in Audio Recordings](audio-intelligence/speaker_labels.ipynb)      
[Summarize Virtual Meetings](audio-intelligence/summarization.ipynb)      
🆕[Create a redacted transcript with Entity Detection](audio-intelligence/entity_redaction.ipynb)      

## Streaming STT 🕒
[Transcribe files in real-time with Node.js](streaming-stt/file-transcription-nodejs)\
[Use Streaming STT with Python](streaming-stt/real-time.ipynb)\
[Real-Time React Example](https://github.com/AssemblyAI-Examples/realtime-react-example)\
[Use LeMUR with Streaming STT](streaming-stt/real_time_lemur.ipynb)\
🆕[Use LeMUR for Real-Time Translation](streaming-stt/real_time_translation.ipynb)\
[Terminate Streaming STT session after a fixed duration of inactivity](streaming-stt/terminate_realtime_programmatically.ipynb)\
[Use Partial Transcripts](streaming-stt/partial_transcripts.ipynb)\
[Use Twilio with JavaScript SDK](https://github.com/AssemblyAI/twilio-realtime-tutorial)\
🆕[Stream system audio (macOS)](streaming-stt/transcribe_system_audio.ipynb)\
🆕[Real-Time Best Practices](streaming-stt/real-time-best-practices.ipynb)

## LeMUR 🐾
[Process Audio Files with LLMs Using LeMUR](lemur/using-lemur.ipynb)  
[Use LeMUR Specialized Endpoints](lemur/specialized-endpoints.ipynb)  
[Leverage LeMUR for Customer Call Sentiment Analysis](lemur/call-sentiment-analysis.ipynb)     
[Extract Dialogue Data with LeMUR and JSON](lemur/dialogue-data.ipynb)         
[Implement a Sales Playbook Using LeMUR](lemur/sales-playbook.ipynb)   
🆕[Boost Transcription Accuracy with LeMUR](lemur/custom-vocab-lemur.ipynb)  
[Extract Citations from a Transcript with Semantic Search](lemur/transcript-citations.ipynb)    
[Extract Quotes from a Transcript with LeMUR's Custom Text Input Parameter](lemur/timestamped-transcripts.ipynb)    
[Calculating LeMUR Costs by Counting Input Tokens](lemur/counting-tokens.ipynb)  
[Processing Speaker Labels with LeMUR's Custom Text Input Parameter](lemur/input-text-speaker-labels.ipynb)  
[Creating Chapter Summaries with LeMUR's Custom Text Input Parameter](lemur/input-text-chapters.ipynb)  
[How to Pass Context from Previous LeMUR Requests](lemur/past-response-prompts.ipynb)  
[Use LeMUR for Speaker Identification](lemur/speaker-identification.ipynb)  
🆕[Ask questions about a transcript using LeMUR's Task Endpoint](lemur/task-endpoint-structured-QA.ipynb)  
🆕[Create Custom Summaries using LeMUR's Task Endpoint](lemur/task-endpoint-custom-summary.ipynb)    
🆕[Receive AI coaching from LeMUR's Task Endpoint](lemur/task-endpoint-ai-coach.ipynb)    
🆕[Generate Action Items using LeMUR's Task Endpoint](lemur/task-endpoint-action-items.ipynb)

## SDKs and Other Resources 📚
Beyond the code examples here, you can learn about the AssemblyAI API from the following resources:
- [Python SDK](https://github.com/AssemblyAI/assemblyai-python-sdk)
- [JavaScript SDK](https://github.com/AssemblyAI/assemblyai-node-sdk)
- [Java SDK](https://github.com/AssemblyAI/assemblyai-java-sdk)
- [Golang SDK](https://github.com/AssemblyAI/assemblyai-go-sdk)
- [Ruby SDK](https://github.com/AssemblyAI/assemblyai-ruby-sdk)
- [AssemblyAI API Spec](https://github.com/AssemblyAI/assemblyai-api-spec)
- [Command Line Interface (CLI)](https://github.com/AssemblyAI/assemblyai-cli)
- [Discuss the API in the AssemblyAI Discord](https://www.assemblyai.com/discord)
- [Check out our YouTube Channel](https://www.youtube.com/c/assemblyai)
- [Follow us on X](https://twitter.com/AssemblyAI)

***
If you have any questions, please feel free to reach out to our Support team - support@assemblyai.com!
