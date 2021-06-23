# MotionLayout - YouTube

Animation like YouTube playing card using Motion Layout. This demonstrates transitioning between a compact view and a full-screen experience.

![play](https://user-images.githubusercontent.com/78479044/123052593-a065cc00-d420-11eb-8e4e-a8e49742e56f.gif)

##### Components
* ConstraintLayout 2.0 - Allows you to create large and complex layouts with a flat view hierarchy provides richer features in MotionLayout.
* MotionLayout - New class in ConstraintLayout 2.0 library to help Android dvelopers manage motion and widget animations.
* MotionScene - contains one or more Transition elements, each of which defines the start and end state of a motion sequence and the transition between the two.
  * Transition - Must Contain - Specifies the motion sequence to perform. If the MotionScene contains multiple <Transition> elements, the MotionLayout chooses the most appropriate based on the user's interaction.
  * ConstraintSet - Can Contain - Specifies a beginning or ending state for one or more of the Transition nodes.
  * Attributes(Default Duration) - Default duration for all transitions, in milliseconds. Used for any motion sequences that do not specify their own duration.
* Keyframe - To alter the Y position of the view during motion.
