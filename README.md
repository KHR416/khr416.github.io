# Projects

## 1) Faster R-CNN Fine-Tuning (Medical Imaging)
- 수행 내용
	- 의료 영상 객체 탐지/분류용 Faster R-CNN 파이프라인 구축
	- 데이터 전처리, 학습, 평가 단계 구현
- 문제/분석
	- 클래스 불균형으로 FN 증가 및 특정 클래스 쏠림 발생
	- augmentation, oversampling 실험으로 한계와 개선 방향 도출
- Repo
	- [Faster-RCNN-Finetunning](https://github.com/KHR416/Faster-RCNN-Fine-tuning)

## 2) RayTracing in C
- 수행 내용
	- 장면 파싱, 교차 판정, 셰이딩 포함 렌더링 파이프라인 구현
	- C 기반 레이트레이서 핵심 기능 단계별 확장
- 설계/개선
	- 도형별 로직 분리 구조 적용
	- 함수 포인터 디스패치 도입
	- TRS와 좌표계 처리 분리로 정확도/유지보수성 개선
- Repo
	- [RayTracing-In-C](https://github.com/KHR416/RayTracing-In-C)

## 3) Small Shell in C
- 수행 내용
	- 토크나이징, 파싱, 실행, 시그널 처리 등 POSIX shell 핵심 기능 구현
	- 팀 단위 개발로 기능 분담 및 통합 진행
- 협업/개선
	- 이슈/PR 리뷰 기반 협업 프로세스 운영
	- 모듈 경계 정리 및 bash 동작 정합성 개선
- Repo
	- [Small-Shell-In-C](https://github.com/KHR416/Small-Shell-In-C)

---

- 참고
	- 자세한 구현/실험 내용은 각 레포 README에 정리
