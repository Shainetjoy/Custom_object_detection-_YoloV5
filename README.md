# Custom_object_detection-YoloV5
##Create a custom dataset by using roboflow https://roboflow.com/templates
steps:
    Create a new public project 
    Uploaded all images from data set (drag and drop)
    Uploaded all annotation files (if you have annotation file (optional))
    click Generate 
    change name 
    augment the dataset (optional)
    click export 
    select version(YoloV5)
    select show download code 
 The abue steps will genarate a code for downlode like this
   " !pip install roboflow
    from roboflow import Roboflow
    rf = Roboflow(api_key="Your api key ")
    project=rf.workspace("fazle").project("aibodyandpin_001")
    dataset = project.version(1).download("yolov5")"
copy and Past it on your notebook and change your api key 
##How to get api key from roboflow
go to accounts
click on settings 
click on WORKSPACES
select Roboflow API
