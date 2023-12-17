# MGNR: Multimodal Game Narration Recognition by Integrating Game Videos and Narration Speech

# Content

  ## Introduction
  This is the respository of Multimodal Game Narration Speech Recognition. In this repository, we provide pre-training code, network settings for end-to-end visual speech recognition. We trained our model on GND. 
  <div align=center>
  <img src="images/sample.png" width="360" height="480">
  </div>
  ## Framework
  The architecture of multimodal game narration recognition (MGNR) for speech recognition. We set have two phrase, 
  phrase 1 is pre-trained video module by masked token prediction loss. 
  phrase 2 fine-tune the pre-trained unimodal speech recognition model by combing video module in phrase 1.
  <div align=center>
  <img src="images/framework.png" width="720" height="360">
  </div>


We release game narrative datasets (GND) soon......
