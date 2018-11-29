# skip-prediction-challenge-starter-kit
<img src="https://dnczkxd1gcfu5.cloudfront.net/images/challenges/image_file/50/Spotify_Logo_Green_Coated_copy.png" alt="Spotify-Logo" width="150"/><img src="http://www.wsdm-conference.org/2019/img/logo.png" alt="WSDM-Logo" width="300"/><img src="https://github.com/crowdAI/crowdai/raw/master/app/assets/images/misc/crowdai-logo-smile.svg?sanitize=true" alt="CrowdAI-Logo" width="300"/>

[![gitter-badge](https://badges.gitter.im/crowdAI/crowdai-mapping-challenge.png)](https://gitter.im/crowdAI/spotify-sequential-skip-prediction-challenge)

# Installation
```
git clone https://github.com/crowdAI/skip-prediction-challenge-starter-kit
cd skip-prediction-challenge-starter-kit
pip install -r requirements.txt
```

# Dataset
Please download the dataset from [https://www.crowdai.org/challenges/spotify-sequential-skip-prediction-challenge/dataset_files](https://www.crowdai.org/challenges/spotify-sequential-skip-prediction-challenge/dataset_files), and extract the files to the `data/` folder. [Untar](http://how-to.wikia.com/wiki/How_to_untar_a_tar_file_or_gzip-bz2_tar_file) them (this might take some time) to have the following directory structure:

```bash
|-- data/
|   |-- training_set/ (training sessions)
|   |-- test_set/ (leaderboard partial sessions)
|   |-- track_features/ (track metadata and audio features)
|   |-- submissions/ (submissions folder - contains sample submissions)
```

# Usage
Now you can refer to the list of Jupyter Notebooks for different aspects of the challenge and the datasets.
You can access all of them by :
```bash
jupyter notebook
```
## Available Notebooks
  
* [Baseline Submissions](https://github.com/crowdAI/skip-prediction-challenge-starter-kit/blob/master/baseline_submissions.ipynb)
  
* [Locally test the evaluation function](https://github.com/crowdAI/skip-prediction-challenge-starter-kit/blob/master/local_evaluation.ipynb)   

# Acknowledgements  
We would like to thank our co-organizers from WSDM and CrowdAI for making this challenge possible.
