# Fitness-Tracker
This is an AI model which helps you maintain the track of your fitness exercises which is built using the mediapipe library
## What's this project all about
 Its basically an AI model used to help with the workout session by keeping track of counts and movement using the mediapipe library . Then using the appropriate body part angles , the count of exercise is determined.
Maybe you can consider this model as your frnd/partner in gym and start excercising which makes a count of ur exercises and even tells whether you are doing the exercise or not.
We have mainly considered 4 types of exercises
1.Push-up
2.Pull-up
3.Sit-up
4.Squat
5.Walk 

*Pushups are a basic exercise used in civilian athletic training or physical education and, especially, in military physical training and will develop the pectoral muscles and triceps, with ancillary benefits to the deltoids, serratus anterior, coracobrachialis and the midsection as a whole.

*A pull-up is an upper-body strength exercise. The pull-up is a closed-chain movement where the body is suspended by the hands, gripping a bar or other implement at a distance typically wider than shoulder-width, and pulled up.

*Situps are classic abdominal exercises done by lying on your back and lifting your torso. They use your body weight to strengthen and tone the core-stabilizing abdominal muscles.

*The squat lift exercise is arguably one of the best overall weightlifting exercises for building lower body and leg power and strength. Because this is a compound exercise that engages multiple muscles and joints at once, it takes some instruction and practice to master safely

*Walk is basically a step counter

### To Run the code dynamically 
Juz enter this

python main.py -t [exercise_name]

### Interesting thing is that you can also record your perfomance exercise videos and run the application,this model runs the video and outputs a dynamic counter for you
TO run this using video output

python main.py -t [exercise_name] -vs [video_source]
