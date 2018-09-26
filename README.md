# face_recognition
code to run on example image : ` python recognize_faces_image.py --encodings encodings.pickle \
	--image examples/example_01.png`

for real time face recognition :`python recognize_faces_video.py --encodings encodings.pickle \
	--output output/webcam_face_recognition_output.avi --display 1`

for video file recognition ;`python recognize_faces_video_file.py --encodings encodings.pickle \
	--input videos/lunch_scene.mp4 --output output/lunch_scene_output.avi \
	--display 0 `
	
To create facial embeddings :`python encode_faces.py --dataset dataset --encodings encodings.pickle`
  
