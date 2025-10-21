# MediaPipe 실시간 손 및 얼굴 감지기
이 프로젝트는 Google의 MediaPipe 라이브러리를 사용하여 실시간으로 손과 얼굴을 감지하는 Python 애플리케이션입니다. OpenCV를 활용하여 웹캠 또는 비디오 파일에서 입력을 받아 감지 결과를 화면에 표시합니다.

# 주요 기능

손 감지: 웹캠 또는 비디오에서 손을 감지하고, 손의 위치를 표시합니다.

얼굴 감지: 얼굴을 감지하고, 얼굴의 위치를 표시합니다.

Selfie Segmentation: 배경을 제거하고 사람의 모습을 강조하는 기능을 제공합니다.

# 설치 방법

1. 이 저장소를 클론합니다.
git clone https://github.com/sksgustjd/MediaPipe.git
cd MediaPipe


2. 필요한 Python 패키지를 설치합니다.
pip install -r requirements.txt

# 사용 방법
손 감지 실행
python hand_detector.py

기본 웹캠을 사용하여 손을 감지합니다. 비디오 파일을 사용하려면 cv2.VideoCapture()의 인자를 변경하세요.



얼굴 감지 실행
python face_detector.py

기본 웹캠을 사용하여 얼굴을 감지합니다. 비디오 파일을 사용하려면 cv2.VideoCapture()의 인자를 변경하세요.



Selfie Segmentation 실행
python selfie_segmentation.py

웹캠을 통해 실시간으로 배경을 제거하고 사람의 모습을 강조합니다.

# 프로젝트 구조
MediaPipe/
├── hand_detector.py        # 손 감지 스크립트
├── face_detector.py        # 얼굴 감지 스크립트
├── selfie_segmentation.py  # Selfie Segmentation 스크립트
├── requirements.txt        # 필요한 패키지 목록
└── README.md               # 프로젝트 설명