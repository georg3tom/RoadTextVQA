# RoadTextVQA

# Ground Truth Format
```json
{
  "dataset_name": "RoadTextVQA",
  "dataset_version": 1.0,
  "data": [
    {
      "questionId": 6, // Unique identifier for each question
      "question": "What is the name of the shop that is seen before the Gregorys coffee, on the same side?", // The question text
      "answer": ["cava"], // List of possible answers
      "video": "19.mp4", // Filename of the video clip
      "videoId": 21, // Unique identifier for each video
      "split": "val" // Dataset split ["train", "val", "test"]
    },
    ...
  ]
}
```

## Download Links

### Annotations
- Train: [train.json](http://cvit.iiit.ac.in/images/datasets/RoadTextVQA/train.json) 
- Val: [val.json](http://cvit.iiit.ac.in/images/datasets/RoadTextVQA/val.json) 
- Test: [test.json](http://cvit.iiit.ac.in/images/datasets/RoadTextVQA/test.json) 


### Videos
- Videos: [videos.zip](https://github.com/georg3tom/RoadTextVQA.git)

### OCR
- OCR: [ocr.zip](http://cvit.iiit.ac.in/images/datasets/RoadTextVQA/ocr.zip)


## Citation
```
@inproceedings{tom2023reading,
  title={Reading Between the Lanes: Text VideoQA on the Road},
  author={Tom, George and Mathew, Minesh and Garcia-Bordils, Sergi and Karatzas, Dimosthenis and Jawahar, CV},
  booktitle={International Conference on Document Analysis and Recognition},
  pages={137--154},
  year={2023},
  organization={Springer}
}
```