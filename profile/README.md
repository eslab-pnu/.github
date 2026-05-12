# ESLab @ PNU Dashboard

ESLab @ PNU의 GitHub Organization 내부 대시보드입니다.

## Quick Links

| Category | Repository | Purpose |
|---|---|---|
| 운영 | [lab-guidelines](https://github.com/eslab-pnu/lab-guidelines) | 운영 규칙, 권한, 템플릿 |
| 주간보고 | [lab-weekly-reports](https://github.com/eslab-pnu/lab-weekly-reports) | 구성원 개인별 주간보고 |
| 회의 | [lab-meetings](https://github.com/eslab-pnu/lab-meetings) | 랩 전체 회의록 |
| 세미나 | [lab-seminars](https://github.com/eslab-pnu/lab-seminars) | 세미나 기록과 자료 링크 |
| 공통도구 | [lab-common-tools](https://github.com/eslab-pnu/lab-common-tools) | 공통 코드, 스크립트, 템플릿 |
| 프로젝트 | [Project repositories](#project-repositories) | 연구실 공동 프로젝트 저장소 |

## Recent Guideline Updates

- [Seminar AI output template](https://github.com/eslab-pnu/lab-seminars/blob/main/templates/seminar-template.md)
- [Seminar AI generation guide](https://github.com/eslab-pnu/lab-seminars/blob/main/templates/seminar-writing-guide.md)
- [Student GitHub organization guide](https://github.com/eslab-pnu/lab-guidelines/blob/main/github-org-student-guide.md)

## Seminar Note Policy

세미나 노트는 사람이 처음부터 직접 작성하는 문서가 아니라, agent가 발표자료와 관련 논문을 바탕으로 자동 생성한 뒤 사람이 검토하고 보정하는 문서입니다.

- 논문 노트의 기본 구조를 유지합니다.
- 발표 슬라이드는 논문 내용을 보완하는 근거로 사용합니다.
- 슬라이드에 없는 구현 조건, 실험 수치, 한계, 외부 코드는 임의로 생성하지 않습니다.
- Appendix, 추가 실험, 데모, 프로젝트 적용 내용이 있으면 별도 섹션으로 정리합니다.
- 관련 연구실 repo는 가능하면 `https://github.com/eslab-pnu` 안에서 연결합니다.

## For Students

1. 세미나 발표자료와 관련 논문을 agent에게 제공합니다.
2. agent는 AI 출력 템플릿과 생성 가이드라인에 따라 세미나 노트 초안을 만듭니다.
3. 관련 연구 repo가 있으면 노트의 식별 정보에 링크합니다.
4. 원본 발표자료, 대용량 파일, 민감한 데이터는 GitHub에 직접 올리지 않습니다.

## Main Repositories

- [lab-guidelines](https://github.com/eslab-pnu/lab-guidelines)
- [lab-seminars](https://github.com/eslab-pnu/lab-seminars)

## Project Repositories

| Repository | Topic |
|---|---|
| [project-ondevice-slm](https://github.com/eslab-pnu/project-ondevice-slm) | On-device SLM |
| [project-edge-rag](https://github.com/eslab-pnu/project-edge-rag) | Edge RAG |
| [project-mcu-npu-benchmark](https://github.com/eslab-pnu/project-mcu-npu-benchmark) | MCU / NPU Benchmark |
| [project-speech-edge-ai](https://github.com/eslab-pnu/project-speech-edge-ai) | Speech Edge AI |
| [project-timeseries-anomaly](https://github.com/eslab-pnu/project-timeseries-anomaly) | Time-series Anomaly Detection |
| [project-industrial-audio-ad](https://github.com/eslab-pnu/project-industrial-audio-ad) | Industrial Audio Anomaly Detection |
| [project-tiny-vision-models](https://github.com/eslab-pnu/project-tiny-vision-models) | Tiny Vision Models |
| [project-crossmodal-distillation](https://github.com/eslab-pnu/project-crossmodal-distillation) | Cross-modal Distillation |
