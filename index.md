---
layout: project_page
permalink: /

title: 3D Reconstruction of SNU’s <br><span style="color:red">Haedong Building</span>
# authors:
#     A. M. Turing
affiliations:
    Seoul National University
video: https://zang09.github.io/snu_haedong_3d/
# code: https://github.com/topics/turing-machines
data: https://zang09.github.io/snu_haedong_3d/
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>About the Project</h2>
        <div class="content has-text-justified">
This project was carried out to introduce the Haedong Advanced Engineering Hall, a new building at Seoul National University. This project page was created to capture the exterior of the Haedong Advanced Engineering Hall and visualize the reconstructed results.
We generated a LiDAR prior map using a LiDAR SLAM-based method and estimated the camera poses through our point cloud-based Structure-from-Motion (SfM) technique. By accurately determining the camera positions, we reconstructed large-scale outdoor scenes in block units. This process allowed us to produce a high-quality, colorized point cloud and achieve high-fidelity rendered videos using 3D Gaussian Splatting. You can explore more detailed results on the webpage below.
        </div>
    </div>
</div>

---

## Rendering Result
<div style="width: 100%; height: 100vh; display: flex; justify-content: center; align-items: center;">
    <iframe width="80%" height="80%" src="https://drive.google.com/file/d/1EDS38R3zVn-J_wuNoweKen_IhNnFiVpt/preview" frameborder="0" allowfullscreen></iframe>
</div>

## Colourized Point Cloud
![Whole Scene](https://zang09.github.io/snu_haedong_3d/static/images/whole_scene.gif)

![Front](https://zang09.github.io/snu_haedong_3d/static/images/front.gif)

![Parking Lot](https://zang09.github.io/snu_haedong_3d/static/images/parking_lot.gif)
