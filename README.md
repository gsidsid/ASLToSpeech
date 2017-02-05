## ASL Sign-to-Text Interface

This program takes hand sign input through a Leap Motion controller and outputs speech for any trained hand sign. Hand sign training, as follows, is relatively simple, and requires minimal effort to complete (although future implementation of ML is desirable, considering a single training session attains only sub-par accuracy at best).

To add a hand sign, click "Add a new gesture" and type in the speech equivalent that the hand sign should generate. Hit enter when finished typing, and wait for the "Record gesture" button to appear. Click the "Record gesture" button and hold a pose or repeat a gesture for 5 seconds in the leap motion's view.

Any number of hand signs and words can be trained in this fashion, ultimately scaling up to a fully responsive interface. The training can be crowdsourced, and a database with training words and letters can be established, although this was out of the scope of what we could accomplish in 24 hours.
