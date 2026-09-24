# D5 Architectural Rendering Skill

SketchUp + D5 Lite 기반 건축 외관 렌더링용 개인 Skill입니다.

## 목적

- 현재 SketchUp/D5 Lite 모델의 형상과 카메라 유지
- 외장재·유리·조명·환경·후처리 조정
- 재료 ALT 비교
- 테스트 렌더와 QA
- 최종 클라이언트 미팅용 이미지 출력

## 설치

이 저장소를 clone/pull하면 프로젝트의 다음 경로에서 사용할 수 있습니다.

`.agents/skills/d5-architectural-rendering-skill/`

## 호출

`$d5-architectural-rendering-skill`

예:

현재 D5 모델 렌더해줘.

렌더 환경:
- 오후 4시, 부드러운 자연광

건축물 특징:
- 샴페인 알루미늄
- 유리 반사 중간
- 건물 형상과 카메라 유지

출력 결과물:
- 실제 준공사진처럼 자연스럽게
- High 또는 가능한 4K 수준
- MaterialID, SkyMask 함께 출력

## 주의

Skill 파일 자체가 D5를 실행하는 것은 아닙니다. 실제 자동 렌더에는 작업 컴퓨터의 D5 Lite와 지원되는 CLI/에이전트 연결이 필요합니다.
