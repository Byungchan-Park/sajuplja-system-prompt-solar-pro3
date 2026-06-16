# CHANGELOG

모든 주요 버전 변경사항을 기록합니다.

## [1.0.0] - 2026-06-16

### ✨ Features
- **AI 사주 상담사 기본 역할 정의**
  - 성별과 생년월일 기반 사주 풀이
  - SUSE 솔루션 매칭
  - 이메일 발송 기능

- **게이트 제어 시스템**
  - gender, birthDate 필수값 검증
  - 누락된 값만 선택적 요청
  - 도구 호출 전 조건 확인

- **도구 규칙**
  - gender 정규화 (male/female 통일)
  - full_reading 단일 호출 정책
  - 중복 호출 방지

- **출력 템플릿**
  - 성향, 강점, 약점 분석
  - 연간 흐름 (일/돈/관계/건강)
  - 오늘의 운세
  - SUSE 제품 추천

- **응답 스타일**
  - 한국어 기반, 쉬운 표현
  - 전문 용어 설명 금지
  - 사주 원문 노출 금지
  - 사용자 친화적 재해석

- **이메일 규칙**
  - 조건부 이메일 발송
  - 안전한 HTML 포맷
  - Payload 생성 규칙
  - 중복 발송 방지

### 📋 Initial Setup
- 디렉토리 구조 설계
- system-prompt.md 작성
- README.md 작성
- CHANGELOG.md 작성

---

## Version History

| Version | Date | Status |
|---------|------|--------|
| 1.0.0 | 2026-06-16 | ✅ Released |

---

## Roadmap

### Planned for v1.1.0
- [ ] 기간별 운세 (주, 월, 분기)
- [ ] 사용자 피드백 기반 개선
- [ ] SUSE 제품 추천 로직 고도화
- [ ] 이메일 템플릿 커스터마이징

### Planned for v2.0.0
- [ ] 타로 카드 통합
- [ ] 호환성 분석 (궁합)
- [ ] 멀티모달 출력 (이미지, 차트)
- [ ] 실시간 통계 대시보드

---

**Current Version**: 1.0.0  
**Last Updated**: 2026-06-16  
**Maintainer**: Byungchan-Park
