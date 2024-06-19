

# Fork of [Review Object Detection Metrics](https://github.com/rafaelpadilla/review_object_detection_metrics)


Changes:
- corrected depreciated numpy functions 
- added functionality to export PR curve data to a `.csv` in  `src/evaluators/coco_evaluator.py` and `src/evaluators/pascal_voc_evaluator.py` 

## Setup and Running

Create a new environment using the provided `environment.yml`

```sh
conda env create -f environment.yml
conda activate metrics
```
Running `setup.py` is not needed, GUI heavy so recommended to run on local device instead of workstation.

Run the program via. 
```sh
python run.py
```