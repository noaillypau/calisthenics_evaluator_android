# calisthenics_evaluator_android

This is a small android app that consist on an evaluator of calisthenics mouvement. \
When a picture is selected, by clicking on `evaluate`, a deep learning model is run on few rotation of the image. \
Then we take the rotation that gives the best detection of the body parts (head, arms, hips, legs). \
We extract center of gravity for each ones and apply deterministic rules to detect the name of the movement. \
We then calculate some quality metrics such as body alignement (alignement of the center of gravity for head, hips and legs), as weel as parallelism (body parallel to the ground).

