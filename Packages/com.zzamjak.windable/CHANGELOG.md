# Changelog

이 프로젝트의 주요 변경 사항을 기록합니다.

형식은 [Keep a Changelog](https://keepachangelog.com/ko/1.1.0/)를 따르며,
버전은 [Semantic Versioning](https://semver.org/lang/ko/)을 따릅니다.

## [1.0.0] - 2026-08-15

### Added

- 최초 UPM 패키지 배포
- **Windable 컴포넌트**: SpriteRenderer / UI Graphic 자동 감지, 노이즈 텍스처 기반 바람 변위 효과
- **CAT_Windable 셰이더**: UV 회전, 노이즈 변위, Sprite Atlas UV 보정, ClipRect(ScrollView) 클리핑 지원 — half precision 모바일 최적화
- **WindableEditor**: 커스텀 인스펙터 (프리셋, 머티리얼 에셋 저장 — 빌드 셰이더 스트리핑 방지)
- **기본 Noise 텍스처** 포함 (Runtime/Resources)
