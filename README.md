# arcospheresolution
Factorio Space Exploration Arcosphere Folding Solution

![alt text](https://github.com/noneuclideanent/arcospheresolution/blob/main/Tesseract.png?raw=true)

This solution consists of calculated series of folds which produce a single type of arcosphere product and return the arcospheres back to their original configuration.
Since each arcosphere product process results in two type of outputs each product has two distinct folding solutions. Therefore each product requires two tracked chains of folds and to dynamically switch from one to the other based on the output of the product process. For example:

Let's say side a folds are as follows: 0,1,2,3,4
And side b is: 0,2,1,4,4,0,2,4,4,0,1,2,4
with 0 being the product process and the other numbers representing arcosphere folding or polorizing processes.

You make one product and get the output for side b. So you run 2,1,4,4,0. Now you get the output for side a, so you run 1,2,3,4,0. b again, 2,4,4,0. b again, 1,2,4,0. a this time: 0,1,2,3,4,0. b, 2,1,4,4,0. Each side of the folding process is individually tracked and picks back up from where it left off.

![alt text](https://github.com/noneuclideanent/arcospheresolution/blob/main/arcospheres_authoritative.jpg?raw=true)
https://www.youtube.com/watch?v=gx9QO0yeGt0

[![Arcosphere Bliss - Tesseract](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
