# Intel-Edge-AI-Scholarship-Foundation-Course-Nanodegree-Program-Show-Case-Group-Project

Participation in the Intel Edge AI Udacity Scholarship Show Case Group Project  
* Follow Udacity Git Commit Message Style Guide: https://udacity.github.io/git-styleguide/     

[image1]: ./images/ModelOptimizerFlow.png    
[image2]: ./images/TensorFlowObjectCountingAPI.jpg 
[image3]: ./images/VideoTrackingFlow.png 
[image4]: ./images/SSDWithMobilenet.png
[image5]: ./images/result.gif

Collaborators:  

| Name | Slack Name |
| ------------------------- | ------------------------- |
| [Sarah Majors](https://github.com/sfmajors373) | Sarah Majors | 
| [Harkirat Singh](https://github.com/Harkirat155) | Harkirat |
| [Hsin Wen Chang](https://github.com/Polarbeargo) | Bearbear |
| [Halwai Aftab Hasan](https://github.com/ahkhalwai) | Halwai Aftab Hasan |
| [Anshu Trivedi](https://github.com/AnshuTrivedi) | Anshu Trivedi |
| [Frida Rode](https://github.com/fridarode) | Frida |

In this Intel® Edge AI Group showcase project, our goal is to extend our learning experience from Intel® Edge AI Scholarship Foundation Course Nanodegree and Hands-on Implementation from:    
* Import OpenVINO Toolkit, build and compile successfully on Google Colab.  
* Load pre-trained models.  
* Perform model optimization.  
* Integrate with TensorFlow Object Counting API.  
* Perform statistics inference detected objects on video stream.

## Load Pre-trained Models   
TODO

*  You can use public or pre-trained models. To download the pre-trained models, use the Tensorflow Model Downloader or go to [PreTrain Model Download](http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v2_coco_2018_03_29.tar.gz)
* Before running the demo with a trained model, make sure the model is converted to the Inference Engine format (*.xml + *.bin) using [The Model Optimizer](https://docs.openvinotoolkit.org/latest/_docs_MO_DG_Deep_Learning_Model_Optimizer_DevGuide.html)

## The Intel OpenVINO Toolkit Model Optimizer Flow Chart 
TODO  

![][image1]  
### Quantization: 
TODO
---
TODO
### Freezing:
TODO
---
### Fusion:
TODO
---  

### Supported Devices
TODO
The following Intel® hardware devices are supported for optimal performance with the OpenVINO™ Toolkit’s Inference Engine:
| Device Types  | 
| ------------- | 
| CPUs  | 
| GPUs  |
| VPUs  | 
| FPGAs|

---
## Integrate With TensorFlow Object Counting API  
--- 
***The [TensorFlow Object Counting API](https://github.com/ahmetozlu/tensorflow_object_counting_api) is used as a base for object counting on this project, more info can be found on this [repo](https://github.com/ahmetozlu/tensorflow_object_counting_api). And a modified version [repo](https://github.com/Polarbeargo/tensorflow_object_counting_api.git) for run on Google Colab***

---
### System Architecture:  
![][image2] 

### Object Tracking Flow Chart:
![][image3] 
### Model:  
![][image4] 
## Citation  

    @ONLINE{tfocapi,
        author = "Ahmet Özlü",
        title  = "TensorFlow Object Counting API",
        year   = "2018",
        url    = "https://github.com/ahmetozlu/tensorflow_object_counting_api"
    }

## License
This system is available under the GNU - 3.0 license. See the [LICENSE](https://github.com/Polarbeargo/Intel-Edge-AI-Scholarship-Foundation-Course-Nanodegree-Program-Show-Case-Group-Project/blob/master/LICENSE) file for more info.

## Perform Statitcs Inference On Video Stream Result
TODO  

# References

* [OpenVINO on Colab](https://github.com/alihussainia/OpenDevLibrary)  
* [OpenVino For SmartCity](https://github.com/incluit/OpenVino-For-SmartCity)  
* [TensorFlow Object Counting API - on Colab Version](https://github.com/Polarbeargo/tensorflow_object_counting_api.git)  
* [Udacity OpenVINO Exercise on Colab](https://colab.research.google.com/drive/1xla23daYYbTIfbdHF0nyHzHyoAvVtyaG#scrollTo=niqr_H0TD4Ie&forceEdit=true&sandboxMode=true)  
* [The Intel OpenVINO Toolkit Model Optimizer Flow Chart](https://docs.openvinotoolkit.org/latest/_docs_MO_DG_Deep_Learning_Model_Optimizer_DevGuide.html)
* [Supported Devices](https://docs.openvinotoolkit.org/latest/_docs_IE_DG_supported_plugins_Supported_Devices.html)
