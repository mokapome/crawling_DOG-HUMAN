# 크롬드라이버로 크롤링 사람 및 강아지 사진 얼굴 인식, 바운딩박스(JSON)

제작계기는
데이터 라벨링을 하나하나 하기 시간도 오래걸릴 뿐더러 수집된 데이터의 정확성도 낮고 어렵기 때문에 이렇게 만들게 되었습니다.

첨부된 폴더에 크롬드라이버를 다운받아 적절한 곳에 저장 한 뒤
다운 받아 사용하면 됩니다. 그 후 경로 수정하시면 됩니다.

강아지와 사람얼굴을 인식하여 각각 폴더에 저장하는 코드이며,

필요시 코드를 약간 수정하여 json파일로 인식된 얼굴 바운딩박스 정보도 같이 저장 할 수 있습니다.

이미지 크기 수정코드도 같이 있어 학습 시에 적절하게 조정하여 사용하면 됩니다.

사람얼굴인식은 dlib를 사용하였으며
강아지는 TensorFlow Hub에서 SSD 모델에서 18번 id를 사용하여 얼굴인식이 가능하도록 하였습니다.
