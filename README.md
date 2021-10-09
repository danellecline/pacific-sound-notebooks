[![MBARI](https://www.mbari.org/wp-content/uploads/2014/11/logo-mbari-3b.png)](http://www.mbari.org)
 
## <div align="left">About</div>

Tutorials written in [Juptyer Notebooks](https://jupyter.org) to guide you through both accessing and 
using the data in the AWS [pacific-sound registry](https://registry.opendata.aws/pacific-sound).
 
<details open>
<summary>Tutorials</summary>
 
## Data Access Notebooks
 
* [2kHz Data](http://docs.mbari.org/pacific-sound/notebooks/data/PacificSound2kHz/) ✨ Recommended first step to learn more about the low-frequency data
* [16kHz Data](http://docs.mbari.org/pacific-sound/notebooks/data/PacificSound16kHz/) ✨ Recommended first step to learn more about the low-mid-frequency data
* [256kHz Data](http://docs.mbari.org/pacific-sound/notebooks/data/PacificSound256kHz/) ✨ Recommended first step to learn more about the raw 10-minute data

## Research and Machine Learning Notebooks
 
  * Blue Whales
      * [Blue B call index 🐳](http://docs.mbari.org/pacific-sound/notebooks/bluewhales/classify/blueB/PacificSoundBlueBCallIndex/) Study song occurrence using a signal processing method
      * [Blue A call classification 🐳](http://docs.mbari.org/pacific-sound/notebooks/bluewhales/classify/blueA/PacificSoundClassifyBlueA/) Classify blue whale song A calls with a neural network model
      * Training a model in SageMaker  🚧
  * Humpback Whales
      * [Humpback whale song detection 🐳](http://docs.mbari.org/pacific-sound/notebooks/humpbackwhales/detect/PacificSoundDetectHumpbackSong/) Detect humpback song with a neural network model
  * Shipping Noise
    - [Signal processing method for studying temporal variations](http://docs.mbari.org/pacific-sound/notebooks/shippingnoise/PacificSoundShippingNoiseAnalysis.ipynb)
 

</details>

## <div align="left">Documentation</div> 

See [pacific-sound](http://docs.mbari.org/pacific-sound) for live demos of these notebooks and official
documentation on how to install and use these notebooks.

## <div align="left">Quick Start </div>
 
### [Install in SageMaker](https://docs.mbari.org/pacific-sound/installation/SageMaker/)

### [Install in Colab](https://docs.mbari.org/pacific-sound/installation/SageMaker/)
 
### Install to your computer

[**Python>=3.6.0**](https://www.python.org/) is required with the 
[requirements.txt](https://github.com/danellecline/pacific-sound-notebooks/blob/master/requirements.txt).
 
```bash
$ git clone https://github.com/mbari-org/pacific-sound-notebooks
$ cd pacific-sound-notebooks
$ pip install -r requirements.txt
$ jupyter notebook
``` 
</details>



