# Self-Drivig-Car

The following is an implemtation of this [Nvidia Paper](https://arxiv.org/pdf/1604.07316.pdf) wherein i tried to see whether we can sensibly predict the steering angles given the front cam video-feed.The data was collected by [Sully Chen](https://github.com/SullyChen/Autopilot-TensorFlow) by attaching a front cam to his car and noting the steering angles.The following is a wrapper around his code making few changes.Here's a cool visualization.Enjoy......


[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/JeYSUmHCPrA/0.jpg)](https://www.youtube.com/watch?v=JeYSUmHCPrA)



For the orginal [dataset](https://github.com/SullyChen/Autopilot-TensorFlow)

To run the visualization:
`python3 ./run_dataset.py`

To Train the network with your data or new architecture add your data in driving_dataset folder and run :
`python3 train.py'


` 
