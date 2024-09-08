
# ./scene/dataset_readers.py

```bash
def constructCameras_waymo(frames_list, white_background, mapper = {},
                           load_intrinsic=False, load_c2w=False, start_time = 50, original_start_time = 0):
```
中包含的信息，

```python
frame = # time: 0
# transform_matrix: (4, 4)
# file_path: /home/qingpo.wuwu1/Project_2_3dGS_Cars/0_Ori/S3Gaussian/data/waymo/processed/dynamic32/training/022/images/000_1.jpg
# intrinsic: (3, 3)
# load_size: [960, 640]
# sky_mask_path: None
# depth_map: (640, 960)
# semantic_mask_path: None
# instance_mask_path: None
# sam_mask_path: None
# feat_map_path: /home/qingpo.wuwu1/Project_2_3dGS_Cars/0_Ori/S3Gaussian/data/waymo/processed/dynamic32/training/022/dinov2_vitb14/000_1.npy
# dynamic_mask_path: /home/qingpo.wuwu1/Project_2_3dGS_Cars/0_Ori/S3Gaussian/data/waymo/processed/dynamic32/training/022/dynamic_masks/000_1.png
```
`image.shape = <PIL.Image.Image image mode=RGB size=1920x1280 at 0x7F25794949A0>`

<img width="789" alt="截屏2024-09-04 19 46 28" src="https://github.com/user-attachments/assets/9ea71ce0-d573-4113-bb23-e1a99e4909f7">

`im_data.shape = (1280, 1920, 4)`

<img width="789" alt="截屏2024-09-04 19 46 18" src="https://github.com/user-attachments/assets/ce3b7e16-2468-4b31-bca1-b05ef952c8c3">

`depth_map = (640, 960)`

<img width="789" alt="截屏2024-09-04 19 46 45" src="https://github.com/user-attachments/assets/ae0951a5-cfe4-4e06-bae9-8e8cbd1b1b0e">

`dynamic_mask = (640, 960)`

<img width="789" alt="截屏2024-09-04 19 46 56" src="https://github.com/user-attachments/assets/02f682c9-93e4-4ba9-bdd0-2afe3497828f">
