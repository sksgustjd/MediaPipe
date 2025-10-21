# 손 감지기 실행
python hand_detector.py

# 얼굴 감지기 실행
python hand_detector.py

# 감지기 실행파일 변경
cap = cv2.VideoCapture(0)            # 기본 카메라 사용시
cap = cv2.VideoCapture("hand.mp4")   # hand 동영상 파일 사용 시 

cap = cv2.VideoCapture(0)            # 기본 카메라 사용시
cap = cv2.VideoCapture("face.mp4")     # face 동영상 파일 사용 시 