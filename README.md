# Demo of Handwriting Analysis using Machine Learning

PLease Follow the Instructions:

### 1.Make Sure Environemental setup is done.Creating a new conda Environment using the file environment.yml will be good to avoid the conflict.

### 2.Download the Trained Model:
[Models](https://drive.google.com/open?id=1H1isE1lKPPub0b8ZUR8JkSbY_N7V2r7X)

### 3.Check the models are present under `models` folder.

    (HML) roshan@roshan-ThinkPad-T440p:~/Submision/models$ ls
    char-clas  freeze_graph.py  gap-clas  graph_optimizer.py  word-clas

    here, char-clas ,gap-clas and word-clas is the Trained-model.

### 4.Back to same Submision Folder and launch Jupyter lab.

    (HML) roshan@roshan-ThinkPad-T440p:~/Submision$ jupyter lab

### 5.Go to notebooks and start the OCR.ipynb and select your kernel.$
    
    For ex. Python[conda env:HML)

### 6.Press Shift+Enter all along.

### 7.In the second cell,you can use the Image from the `data` folder.Please refer below.

    (HML) roshan@roshan-ThinkPad-T440p:~/Submision/data/pages$ ls

        page01.jpg  page03.jpg  page05.jpg  page07.jpg  page09.jpg  test1.jpg  test3.jpg  test5.jpg  text22.jpeg  text3.jpg  text52.jpg  textlyrics.jpg
        page02.jpg  page04.jpg  page06.jpg  page08.jpg  page10.jpg  test2.jpg  test4.jpg  text1.jpg  text2.jpg    text4.jpg  text5.jpg

### 8.Finally step all along will be: 
                
                1.Load the Image 
                2.Crop the Image and detect Bounding boxes 
                3.And Recognize the Words from the text.
                
## Source Code:

[SourceCode](https://drive.google.com/open?id=1cW6qeRI__o9bb6WrApip7BrXqqrA_qne)

## DEMO VIDEO
[Demo](https://youtu.be/AoCWl9N_2A4)
