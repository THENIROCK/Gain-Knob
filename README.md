It's just a gain slider. I used C++ and the JUCE framework to code this audio plugin.
Humans hear in "decibels" which means I can't just multiply the incoming signal by a given amount chosen by the user. However, it's still pretty simple, you just take the log magnitude by dividing by 20 and multiplying by 10.

