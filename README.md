
# UT Kidney Dataset

The UT Kidney dataset comprises 570 ultrasound images from 281 different patients. Each image in the dataset includes the following files:

- DICOM file: Original DICOM file for each ultrasound image.
- Original PNG file: PNG format of the original ultrasound image.
- Label PNG file: PNG format of the labeled ultrasound image.
- Segmented points TXT file: Text file containing segmented points for each image.


## Dataset Details


- Total images: 570
- Total patients: 281
- Gender : 
- Age Range : 

<br/>
<p align="center">
    <img src="kidney_sample.png" width = 1442px height = 495px><br/>
	Figure 1. UT Kidney Dataset
</p>

## Dataset Structure

Below is a overview of the UT Kidney dataset.

```bash
UT_kidney_dataset.zip
    |
    |── Images (directories of user_id names)
    |     ├── 1 
    |     |    |── 1.dcm
    |     |    |── 1.png
    |     |── 2
    |     |    |── 2.dcm
    |     |    |── 2.png
    |     |
    |     └── .....   
    └── Masks (directories of user_id names)
    |     ├── 1 
    |     |    |── 1.png
    |     |    |── 1.txt
    |     |── 2
    |     |    |── 2.png
    |     |    |── 2.txt
    |     |
    |     └── .....                      
```

## How to download dataset


You can download the dataset from [here](https://forms.gle/SPYEEmpkX7peAtyB8)

## Contact us

Feel free to contact us for any further information via below channels.

- Email: [*alikarimi120@gmail.com*](alikarimi120@gmail.com)


## Citation

If you use this dataset in your research, please cite the following paper:

```
@article{UT,
  title={Title},
  author={Name},
  journal={arXiv},
  year={2021}
}
```

## License

[Specify the license under which the dataset is distributed, if applicable.]






