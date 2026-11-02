# AI비서 음성인식 모델

AI비서 앱이 처음 실행할 때 내려받는 음성인식 모델 파일입니다.

- 원본: [OpenAI Whisper large-v3-turbo](https://huggingface.co/openai/whisper-large-v3-turbo) (MIT License, Copyright (c) 2022 OpenAI)
- 변환: ONNX 형식, 채널별 8비트 양자화 (인코더·디코더)
- 이 저장소에는 모델 파일만 있으며, 음성·대화·개인 정보는 들어 있지 않습니다.

## 파일 (릴리스 `whisper-v1`)

| 파일 | 크기 (바이트) | SHA-256 |
|---|---|---|
| encoder.int8pc.onnx | 676035942 | 5cb8a8db259a1716025b2f2f47cfe5efd0645114e0508a26c10fe219588f728f |
| decoder.int8pc.onnx | 227819974 | eb990380fb03700d691eff7b973cfdfde850f81c041ae6086bc77c2a6e7586fa |

## 라이선스

원본 모델과 같은 MIT License 를 따릅니다 (LICENSE 참고).
