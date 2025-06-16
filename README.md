## [AI Desk Object Sorter]

## Project Description
This project uses Google's Teachable Machine to classify common objects found on my desk. The objects classified were:

Pens
<br><br>Storage Media
<br><br>Cables

1.  **Model Performance & Iteration:**
The first model was 100% accurate. The training data was comprised of close to 10,000 images of 3 classes of object: pens, storage media, and cables. To test generality, a novel object, a pen not used in the training set, was uploaded to the model. The model was accurate in identifying the novel pen.
<br><br>Due to the high number of training images, there doesn't seem to be the need to iterate on model performance.
<br><br>
2.  **Challenges & Observations:**
I tried to chose easily identifiable objects, the most complex object being the cables. All of the objects were easily identified by the computer vision model. I used a couple of novel objects to test generality, and each object was identified correctly. 
<br><br>Depending on the variability in features and characteristics of the other students' mugs, the computer vision model might have a difficult time identifying other students mugs, or it might have a relatively straightforward time. There are some defining characteristics of mugs: their shape is toroidal, with an opening on the top with the ability to hold liquids. Some have handles, some don't. Color and size can vary, as well as patterns on the mug. If the color pattern is not obstructive to the defining characteristics, then a model trained on one mug might not have a difficult time identifying other mugs. 
<br><br>
3.  **Bias in AI:**
If there is a complex pattern on the mug, like a photograph or some sort of checkered pattern or houndstooth, then identification might become difficult, or at least consume additional time and resources. The complex patterns might introduce bias into the computer vision model. It doesn't necessarily make the model ineffective, it necessitates additional training images with different features and characteristics to mediate bias. A similar effect might be seen with lighting - bright light might cause different visual patterns on a mug as opposed to a dimly lit room.
<br><br>
4.  **Model Limitations & Usefulness:**
Easily identifiable objects were selected for the computer vision model. The most likely limitations might be if objects were complex patterns are introduced, or a dramatic change in lighting.
<br><br>Sharing trained model files enables colaboration. Colaboration allows for quick and distributed iterations. The possiblity of innovation is enhanced.
<br><br>
5.  **Real-World Applications & Ethics:**
Potential real-world applications of a similar image classification model:
A warehouse fulfillment line might be a real-world application of a similar image classification model. Items could be scanned and identified, giving either workers or automated machines the ability to match the items to the appropriate locations in the warehouse. A similar use could be seen in grocery stores. In airports, the X-rays could possibly have automated object detection to assist inspectors.
<br><br>One of the largest ethical considerations of image recognition is when applied to a person's likeness. The ability to perform computation on a person's likeness creates a new world and mentality of how far someone's likeness extends beyond them and how much control they have over it. If the same image recognition capability experimented with in the lab's computer vision model were applied to a person over some span of time, an image of their life and characteristics could be compiled. That image could be used with intentions unbeknownst to that person, and potentially with malicious intent, in the worst case scenarios. There is a type of social contract when anyone enters a public space; however, as time moves forward, the ability to perform computation on a person's likeness, even when obtained in a public space, might have to be tempered with that person's ability to control it or at least have knowledge of how their likeness is used.
<br><br>
## (Optional) Challenges Faced / Interesting Discoveries
I was mostly surprised at the level of accuracy of the computer vision model. I've trained models on similar images and had an interesting time training.
<br><br>
## (Optional) Screenshot
![Screen Shot 2025-06-15 at 8 25 29 PM](https://github.com/user-attachments/assets/cb850a0a-17c1-4cb0-8c18-5366c57bd9a4)
<br><br>

