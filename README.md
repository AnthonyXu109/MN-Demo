# MotherNets-Demo
A showcase of MotherNets

There are two demos, a real-time-training demo and a pre-trained demo.

The first demo (real time training) is built based on ConvNetJS library. To see the effect, run demo/demo_FC_Realtime.html in Firefox. After user specify up to five ensembles of networks and up to seven layers, the MotherNetwork will be generated and both the MotherNets method and the Baseline method will start training at the same time. But in both of these methods, nets are trained sequentially. Chart1 shows the training accuracy of networks while training; Chart2 shows the training time of each of these nets until converges; Sample prediction part will show 5 predicting samples in test set for each ensemble size using ensemble averaging. Chart3 shows the generalization accuracy of MotherNets method and Baseline method after all the networks of a current ensemble size are convergenced.

The second demo has the same training visualization but just plot the pre-trained models. Run demo/demo_CNN_preTrained.html in Firefox to see effects.

Users can also swich between these two demos by clicking on the nav bar.
