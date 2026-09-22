# extended-kalman-filter-experiment


# README.md を作成
readme_content = """# Extended Kalman Filter Experiment

## Lecture 7: KF/EKF Localization

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Rabbit787/extended-kalman-filter-experiment/blob/main/lecture7_kf_ekf_localization.ipynb%20%E3%81%AE%E3%82%B3%E3%83%94%E3%83%BC)
"""

with open('README.md', 'w') as f:
    f.write(readme_content)

!git add README.md
!git commit -m "Add: Colab badge to README"
!git push
print("✓ README updated with Colab badge!")
