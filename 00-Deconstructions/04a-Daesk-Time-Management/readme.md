# https://dae.sk/start

## Home – Splash Page
![dae.sk fallback-img](https://storage.googleapis.com/daesk-campaign/webgl-fallback/mountain-patch.jpg)
Background video

Button and animation: 
Position absolute to line up with video's type.

Login/sign up buttons and CSS animation.

Logo CSS annimation and link to homepage.

Nav button annimation and click-event:
click: Nav overlays webpage, webpage shrinks to ~60vw.

Down Arrow CSS .SVG animation and click-event:
click: page scroll to next section location

## Home – Scroll Down to Section 1
Type content explaining product.
Large bold and light body style.

looping video of people and UI (no audio)
Button CSS .SVG animation, links to watching full-video.

## Home – Scroll Down to Section 2
3-col type and graphic card layout. Full-bleed
Type explains product.
.SVG Graphics with CSS animations

## Home – Scroll Down to Section 3
User quotes JS function type animation.
Type object follows mouse pointer. JS updates rotateX () and rotateY () values, and possibly others.

User Avatar buttons with annimations
Click: changes user quote

Button links to more use cases with animation.

## Home – Scroll Down to Section 4
Type and cta-email registration

## Home – Scroll Down to Section 5
Eye icon with hover animation affecting the type 'DRAG'.
JS functions to alter css depending on Eye Icon drag location.
>>> Center circle/hole grows in size to cover screen
>>> 'Light Speed' animation transition
>>> Once eye ico is dragged and dropped, 'Light Speed' animation transition ends, and video loop plays.
>>> Back Button

## Footer
Button links col-2-of-3: nav, legal, social media ico
CTA and try now button col-3-of-3

## App Interface
![ui](https://raw.githubusercontent.com/vk-webdesign/cp2/master/00-Deconstructions/04a-Daesk-Time-Management/ui.png)
Database that is reactive to user inputs.
Tracks #tags, time/day, and text.

User Input for Time Tracking
Text input form.
Input looks for #symbols and tags the attached word. The word becomes clickable and user is prompted to assign the #tag, Object, Activity, or Technology values. The word is then highlighted to the color of specified #tag.
Time input form.
User inputs a time. The colens to distinguish hour, minute, seconds are static.
Time input hover event:
a slider appears over timer letting user drag and drop to desired time input.
Save button w/ animation.

Posted Form
Inputs from Text and time are then archived to the Posted Form section which documents all time-tracking inputs.
Buttons: Emotion, Edit, Trash.
Emotion button labels task satisfaction to Frustrated/neutral/happy
Edit button lets user edit contents
Trash button deletes the card from database.

Project Dropdown
Adjusts the Posted Form content depending on the Project it is attached to.

>JSON file may be organized as such:
User/Group >> Project (total time, #tag) >> Work event (text/time input, #tag)




Day
Date (click) to calendar (click) changes Day/Task data


