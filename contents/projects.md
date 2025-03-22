<style>
    .project-divider {
        height: 2px;
        background-color:rgba(81, 0, 255, 0.12);
        margin: 2rem 0;
        width: 100%;
    }

    .scroll-container {
        width: 100%;
        height: 250px;
        overflow-y: auto;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    }
    .scroll-container::-webkit-scrollbar {
    width: 1px;
    }
        
    .img-container {
        height: 100%;
        display: flex;
        align-items: center;
    }

    .full-size {
        width: 100%;
        height: 100%;
        object-fit: contain;
    }

    .image-caption {
        text-align: center;
        color:rgba(102, 102, 102, 0.3);
        font-size: 0.9rem;
        margin-top: 0.5rem;
        font-style: italic;
    }
</style>

<div class="row mb-8">
    <div class="col-md-8">
        <strong>Crowd-aware Robot Navigation Using Egocentric Looks </strong>
        <span style="float: right;">12/2024 – present</span>
        <p>This research focused on developing an end-to-end social navigation model that imitates human pedestrian behavior in crowded environments. To achieve this, an egocentric dataset of human demonstrations, incorporating crucial gaze data, was collected. The model effectively leverages both egocentric view and gaze information, and its decision-making alignment with human behavior was validated through the integration of gaze data with explainability methods.</p>
    </div>
    <div class="col-md-4">
        <div class="img-container">
            <img src="static/assets/img/cruel.jpg" class="project-img img-fluid rounded shadow" alt="CRUEL Project">
        </div>
    </div>
</div>

<div class="project-divider"></div>

<div class="row mb-8">
    <div class="col-md-4">
        <div class="scroll-container">
            <img src="static/assets/img/VR-Based.jpg" class="img-fluid rounded shadow" alt="VR Gaze Project">
        </div>
        <div class="image-caption">scroll to see a sequence!</div>
    </div>
    <div class="col-md-8">
        <strong>VR-Based Gaze Projection onto RGB-D Videos</strong>
        <span style="float: right;">06/2024 – 11/2024</span>
        <p>For immersive AR, we developed a VR-based gaze projection framework using a VR headset, Unity, and a depth camera. By synchronizing gaze and RGB-D video streams through multi-sensor fusion and spatiotemporal alignment, our system dynamically maps virtual gaze vectors to 3D pixel coordinates, generating real-time gaze heatmaps overlaid on physical scenes. This overcomes the challenge of transferring VR gaze data to real-world AR applications.</p>
    </div>
</div>

<div class="project-divider"></div>

<div class="row mb-8">
    <div class="col-md-9">
        <strong>Collaborative Multi-UAV System for Dense Crowd Monitoring </strong>
        <span style="float: right;">11/2023 – 10/2024</span>
        <p>To address the critical need for efficient crowd monitoring in densely populated areas, this research presents a collaborative multi-UAV system employing MAPPO reinforcement learning for optimized path planning, trained within a comprehensive crowd flow dataset collected in the high-fidelity Unreal Engine 5 simulation environment, enabling intelligent, data-driven crowd management by enhancing the adaptability and efficiency of UAV coordination for real-time tracking and prediction of crowd movements.</p>
    </div>
    <div class="col-md-3">
        <img src="static/assets/img/UAV.jpg" class="img-fluid rounded shadow" alt="UAV Project" style="width: 100%; height: 300px;">
    </div>
</div>