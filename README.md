# Nav2_config
for fastlio_localization tf
[frames_2026-05-14_19.04.16.pdf](https://github.com/user-attachments/files/27755263/frames_2026-05-14_19.04.16.pdf)

ros2 launch nav2_bringup bringup_launch.py \
    use_sim_time:=false \
    autostart:=true \
    map:=/home/your/project//map.yaml \
    params_file:=/home/your_name/nav2_config/my_nav2_params.yaml
