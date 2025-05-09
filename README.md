```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/pwri-opera/repo/jammy-humble-amd64/ ./" | sudo tee /etc/apt/sources.list.d/pwri-opera_repo.list
echo "yaml https://github.com/pwri-opera/repo/raw/jammy-humble-amd64/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-pwri-opera_repo.list
```
