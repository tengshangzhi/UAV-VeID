# UAV-VeID
"Teng, S., Zhang, S., Huang, Q. et al. Viewpoint and Scale Consistency Reinforcement for UAV Vehicle Re-Identification. Int J Comput Vis (2020)." https://doi.org/10.1007/s11263-020-01402-2

# 1.Data Collection
We simulate real scenarios as much as possible during the UAV videos collection. 
Specifically, UAV videos are collected from different locations with distinct backgrounds and lighting conditions, e.g., including highways, urban road intersections, and parking lots, etc.
For vehicles at parking lots, we adopt various UAV sport modes such as cruising and rotating to record vehicles. 
This strategy introduces viewpoint and scale changes, as well as partial occlusions to images of the same vehicle. 
For moving vehicles, we use two UAVs to simultaneously shoot videos from different viewpoints and heights. 
This strategy introduces viewpoint, scale, and background changes. 
The flying height of UAVs ranges from 15 to 60 meters, leading to different scales of vehicle images. 
The vertical angle of UAV camera ranges from 40 to 80 degrees, which leads to different viewpoints of vehicle images. 
The videos are recorded at 30 frames per second (fps), with the resolution of 2704 × 1520 pixels and 4096 × 2160 pixels, respectively. 
The UAV-VeID is constructed from 80 video sequences selected from raw UAV videos.

# 2.Annotation
We annotate vehicles from collected videos to construct the UAV-VeID. 
In each video clip, 1 video frame is sampled every one second to construct a video frame dataset. 
The dataset annotation is hence conducted based on those sample video frames.
To finish the vehicle annotation, 6 domain experts are involved to manually locate and annotate the identities of vehicles from each video frame.
The data annotation procedure takes 1000 man-hours and finally results in a dataset containing 41,917 vehicle bounding boxes of 4601 vehicles. 
Each vehicle is annotated by at least two bounding boxes. 

# 3.Dataset partition
The UAV-VeID dataset is split into the training set, validation set and testing set, among which the training set contains 18,709 images with 1,797 IDs, the validation set contains 4,150 images with 596 IDs, and the testing set contains 19,058 images with 2,208 IDs. 
The validation set is further divided into a query set ("val_q_label.txt" 3,554 images) and a gallery set ("val_g_label.txt" 596 images). 
The testing set is further divided into a query set ("test_q_label.txt" 16,850 images) and a gallery set ("test_g_label.txt" 2,208 images). 

# 4.Download
Please sign the Agreement(UAV-VeID_AGREEMENT.pdf) and thereby agrees to observe the restrictions listed in this document. After filling it, please send the electrical version to us. After confirming your information, we will send the download link and password to you via Email.

# 5.Contact
Shangzhi Teng, Email: tengshangzhi@126.com
