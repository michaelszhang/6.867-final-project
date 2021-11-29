# classroom-net

## datalake
build will populate the datalake with waymo data (rgb, range, camera transformations) \\
build will call pretrained models \\
dataset will define dataset class and allow downstream to query for respective data

## teachers
pretrained model implementations \\
each impl should provide function that takes in data and outputs result

## main framework
### experiments
ablation, generalization, teach eval, etc...

### student
main impl of classroom-net framework (see design image in group chat)

### utils
put util functions here e.g. func that compute recall and precision
