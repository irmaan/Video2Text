# Video To Text using Deep Learning

- Video captioning, a complex undertaking involving the translation of a video to generate a coherent and meaningful summary of its content, poses numerous challenges within the realm of computer vision and machine learning. The conventional approaches employed in video captioning have not yielded many triumphs, failing to effectively capture the essence of the video content. Nevertheless, the recent surge in artificial intelligence, underpinned by the advancements in deep learning, has sparked a renewed interest in video captioning, propelling it to the forefront of research and development. The amalgamation of convolutional neural networks, which excel in processing visual data, and recurrent neural networks, which excel in processing sequential data, has opened up new avenues of possibility, allowing for the creation of end-to-end, enterprise-level video-captioning systems that encompass the entire spectrum of video analysis and summarization. Indeed, this recent progress has paved the way for the realization of more accurate and comprehensive video captioning, revolutionizing the field and inspiring further exploration into this captivating domain.

## Dataset:
- Training videos can be downloaded from http://www.cs.utexas.edu/users/ml/clamp/videoDescription/YouTubeClips.tar

# How to run:
- python VideoCaptioningPreProcessing.py process_main --video_dest 'your training voideos diectory path' --feat_dir 'a desired path' --temp_dest 'a desired temprary folder' --img_dim 224 --channels 3 --batch_size=128 --frames_step 80

- python Video_seq2seq.py process_main --path_prj 'your training voideos diectory path' --caption_file video_corpus.csv --feat_dir features --cnn_feat_dim 4096 --h_dim 512 --batch_size 32 --lstm_steps 80 --video_steps=80 --out_steps 20 --learning_rate 1e-4--epochs=100













 






