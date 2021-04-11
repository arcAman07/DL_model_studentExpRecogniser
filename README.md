# DL_model_studentExpRecogniser

# Problem we are trying to solve:
 For keeping an eye on every student during the online sessions hosted on any platform, we have created a python program using OpenCV library, which will take the video feed of live class as input and give tags to everything it identifies as human. The tags will be - attentive, not attentive, confused, and speaking. Keeping in mind the struggles faced by students in primary schools, like in muting or unmuting themselves during online classes. Also, many students get unnoticed during classes as they don’t know about the feature of raising their hands and many don’t know how to raise their hands virtually. We have created another deep learning model, which will also take the live feed of online class as input. It will try to identify hand gestures of students, and will classify them as “raising hand”, “mute” and “unmute”.
 final_model1 is for the raise hand/mute/unmute deep learning model.
 final_signal is for the attentive/doubtful/unattentive deep learning model.
 
# How did we make the model:
 We gathered thousands of photos from all over the internet and along with our team-members to create this deep learning model using open-CV,tensorflow and then we categorised them into labels and trained the deep learning model with a 90+ accuracy.
 Hence here are two deep learning models final_signal refers to finding whether a student is: 1)attentive 2)doubtful 3)unattentive and hence it can be of a great help to teachers all around the world.
 The second one is for primary to high school students who dont know how to raise hand,mute and unmute on any video conferencing platform due to lack of tech savy knowledge. Hence this model can be used by all the students around the world and help them in a major way. Here the classes are 1)Raise Hand 2)Mute 3)Unmute
 
 
# How can you use it:
 1) Just use the code in the repository in your python IDE/google colab or in ananconda and it will work perfectly. 
 2) Install the necessary libraries in your command path and it will work perfectly work in your local host PC. 
 3) We will definately improve on this and we have many more features that we want to add but we were unable to due to time constraints.
 4) We were also able to deploy this in our website(local host) using flask and video capture from OpenCV but due to time, resource constraints, we were not able to implement.
 5) This is the building block of our much bigger and ambitious project, we will make it bigger and better.
 
 Hope this DL  models will bring a change in Edtech track in the world.
 
 
