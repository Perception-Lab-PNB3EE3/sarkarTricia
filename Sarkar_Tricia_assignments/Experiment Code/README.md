# **Welcome!**

## **Mindfulness Meditation and Sustained Attention Experiment**

Mindfulness meditation has been shown to have a variety of benefits on attention, working memory, and other cognitive domains. This experiment is testing to see if watching a mindfulness meditation video before a sustained/selective visual attention task has a positive effect on task performance (Reaction time in milliseconds and % accuracy).

**Stimuli/Files (you need to download these for the experiment to run)**

1.  5-Minute Mindfulness Meditation [video](https://www.youtube.com/watch?v=WUASVHlfXeI&t=4s&ab_channel=DeclutterTheMind)
2.  Shapes stimuli (circle, star, triangle) sourced from OSF ([Ferrara, 2023](https://osf.io/d7h5n/?view_only=)).
3.  jsPsych plugins ([here](https://www.jspsych.org/v7/plugins/list-of-plugins/))

**Steps**

1.  Participants are presented a consent form (checkbox)
    -   If a participant does not agree to provide consent, they are presented an alert, and the experiment is aborted.
    -   If a participant does agree to provide consent, they may proceed.
2.  Participants are randomly sorted into 1 of 2 conditions (0.5 chance of either condition, so perfectly even):
    -   [Condition 1]{.underline}: Mindfulness Meditation Video, then the visual attention task
    -   [Condition 2]{.underline}: Just the visual attention task alone
3.  Participants must follow the on-screen instructions depending on the trial.
    -   [Condition 1]{.underline}:
        -   Gets instructions for the mindfulness mediation video (buttonresponse),
            -   The end of the instructions page has an attention task where participants must click "continue" to advance to the mindfulness meditation video,
        -   They will then watch the video (videokeyboardresponse, no_keys),
        -   Then move onto the visual attention task instructions (buttonresponse)
        -   Finally they complete the visual attention task (imagekeyboardresponse)
    -   [Condition 2]{.underline}:
        -   Gets the visual attention task instructions (buttonresponse),
        -   Finally they complete the visual attention task (imagekeyboardresponse).
4.  The visual attention task involves pressing the correct keyboard button when each shape appears on the screen. This task consists of a fixation and the test trial (shape appearing). The shape only disappears when a button on the keyboard is pressed.
5.  Once the participant completes all the steps, their data will download as a .CSV file.

**Extra Notes**

-   The fixation time between the presentation of shapes (in the visual attention task) is [long]{.underline}: between 5-8 seconds. This is [intentional]{.underline}, as the task is meant to simulate paying close attention to any online task (ex. a virtual lecture/class).

-   Participant's reaction time, % accuracy, and respective means for the visual attention task are all calculated on finish of the task.

-   The mindfulness meditation video requires audio to be turned on.

***Enjoy!***
