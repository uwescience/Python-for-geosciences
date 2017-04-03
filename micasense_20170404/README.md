## 2017-04-04. Cloud-Based Platform for Drone-Based Multispectral Imaging

**[Adrian Prananda](https://github.com/map34) and Brent Bradbury, [MicaSense](https://www.micasense.com)**


In the bigger picture, we are going to talk about a cloud-based data platform for processing, storage, management, presentation, and analytics of multispectral data captured with multispectral cameras like the MicaSense RedEdge and Parrot Sequoia. The platform generates orthomosaics and vegetation index maps to help researchers and farmers interpret and understand the condition of their fields. 

In detail, we will be talking about the actual software tools and architecture. The tools include the languages we use (Python, Go, Ruby, and Javascript), and how they fit in our processing pipeline. For the architecture side, we will talk about Airflow as job workflow manager, AWS services such as ECS and EFS for resources, and Terraform to create our infrastructure.

Lastly, we will also talk about the basic ingredients in drone-based multiple imaging. Briefly, the platform needs raw images taken by multispectral cameras, downwelling light sensor samples and panels to improve the reflectance calibration of the data, and images metadata to determine the orientation and location of the images.
