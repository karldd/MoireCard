# Moiré Card

Moiré Card is an obfuscated business card that consists of two layers of laser cut material: an encoded design layer and a decoding mask layer. Both layers are required to decode the information on the card into a readable form. A number of my recent projects look at embedding hidden information for communication or tracking purposes, see for example [SideBySide](http://www.karlddwillis.com/projects/projection/sidebyside/), so [moiré patterns](http://en.wikipedia.org/wiki/Moire_pattern) were an ideal way to put this concept across.

A custom Processing program was created to slice separate images together to create the encoded design. The program also simulates the look of the final card by rendering the decoding mask layer above the encoded design. As this could be a useful little tool for making moiré animations, the source code is posted below.


## Setup
1. Add your images to the data folder
2. List their names in the files array
3. Choose a slitSize
4. Run
5. Left/right keys move the mask
6. Space key exports the card to the sketch folder


## Gallery

<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-Name.jpg" alt="Moiré Card Name">
<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-Design.jpg" alt="Moiré Card Encoded Design">
<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-Mask.jpg" alt="Moiré Card Decoding Mask">
<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-Number.jpg" alt="Moiré Card Number">
<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-Email.jpg" alt="Moiré Card Email">
<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-BothClip.jpg" alt="Moiré Card">
<img src="https://www.karlddwillis.com/media/posts/21/MoireCard-Sequence.gif" alt="Moiré Card Sequence">
