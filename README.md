<p>This code allows you to perform inference in two ways: using a <span style="background-color:#ffecb3;"><u>single image</u></span> or a <span style="background-color:#ffecb3;"><u>batch of images</u></span> simultaneously. The result of the inference is a list composed of four elements, each with specific information:</p>
<ul>
    <li><strong>Element 0</strong>: This is the output image with overlays, represented as a numpy array. The overlays indicate areas where the model identified potential 'core fold over' defects.</li>
    <li><strong>Element 1</strong>: This element contains the title or name of the original image that was processed.</li>
    <li><strong>Element 2</strong>: This is a boolean value (True/False) indicating whether the model detected a 'core fold over' defect in the image. If True, a defect was detected. If False, no defect was found.</li>
    <li><strong>Element 3</strong>: This element contains the detailed output of the detection performed by YOLOv9. It includes information such as the coordinates of bounding boxes, the score or probability of the defect, among other details.</li>
</ul>
<p>These four elements together provide a comprehensive view of the result of the inference performed by the model.</p>
