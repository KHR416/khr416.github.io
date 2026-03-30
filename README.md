# Projects

## 1) Faster R-CNN Fine-Tuning (Medical Imaging)
- 의료 영상 객체 탐지/분류 실험에서 Faster R-CNN 기반 딥러닝 파이프라인(데이터 전처리, 학습, 평가)을 구축했습니다.
- 클래스 불균형으로 인한 학습 실패(FN 증가, 특정 클래스 쏠림)를 확인하고, augmentation/oversampling 실험 후 한계와 개선 방향을 분석했습니다.
- Repo: [Faster-RCNN-Finetunning](https://github.com/KHR416/Faster-RCNN-Fine-tuning)

## 2) RayTracing in C
- 과제 구현을 시작점으로 장면 파싱부터 교차 판정, 셰이딩까지 렌더링 파이프라인을 직접 구현했습니다.
- 기능을 계속 붙이며 정확도와 유지보수를 맞추다 보니, 도형별 로직 분리·함수 포인터 디스패치·TRS/좌표계 분리 같은 원론적인 구조가 사실상 필수임을 확인했습니다.
- Repo: [RayTracing-In-C](https://github.com/KHR416/RayTracing-In-C)

## 3) Small Shell in C
- 토크나이징/파싱/실행/시그널 처리로 이어지는 POSIX shell 핵심 기능을 팀 단위로 구현했습니다.
- 이슈/PR 리뷰 기반으로 협업하며 모듈 경계 정리, 동작 정합성(bash behavior) 개선에 기여했습니다.
- Repo: [Small-Shell-In-C](https://github.com/KHR416/Small-Shell-In-C)

---

자세한 구현/실험 내용은 각 레포의 README에 정리했습니다.
