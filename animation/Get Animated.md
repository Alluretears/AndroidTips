#### android.view.animation

* Only run in the draw pass (@Deprecated)
* Window animations
* Fragment animations reqiuring measured size

#### Animator

* ObjectAnimator - general purpose,property animator
* ValueAnimator - custom animation
* ViePropertyAnimator
  - Multiple properties on the same View
  - Fire and forget
* PropertyValuesHolder - multiple properties on the same object
* AnimatorSet - choreograph a set of animations
  
#### AnimatedVectorDrawable

* Vector Drawable + animator(s)
* run on RenderThread from API 25
* Icon animation
* 'Fire & forget' animations
* Performance critical

#### Physics-based Animation

* Interruptible
* Continuity
* Realistic look

#### Transitions

*  Shared emement activity transitions
*  Windown content enter/exit
*  Modularize animations
*  Simple changes

#### MotionLayout

* Complex coordinated layout
* Gesture to Animation