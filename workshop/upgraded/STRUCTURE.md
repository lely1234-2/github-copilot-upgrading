# upgraded 폴더 구조 설명

이 디렉터리는 레거시 프로젝트의 모든 파일과 폴더를 최신 환경에서 작업할 수 있도록 복사한 공간입니다.

## 주요 폴더 및 파일

- `MANIFEST.in`, `README.rst`, `setup.py`, `distribute_setup.py`: 프로젝트 메타 및 설치 관련 파일
- `guachi/`: 핵심 Python 모듈 및 테스트 코드
  - `__init__.py`, `config.py`, `database.py`: 주요 모듈
  - `tests/`: 단위 및 통합 테스트
- `guachi.egg-info/`: 패키징 정보
- `docs/`: Sphinx 기반 문서
  - `build/`: 빌드된 문서(HTML, doctree 등)
  - `source/`: 문서 원본(rst, conf.py 등)
- 기타: 프로젝트에 필요한 정적 파일(css, js, 이미지 등)

## 활용 방법
- 이 디렉터리에서 코드를 최신 Python 문법 및 패키징 방식으로 리팩터링하세요.
- 테스트 및 문서도 함께 최신화할 수 있습니다.
- 원본 레거시 구조를 그대로 유지하므로, 비교 및 마이그레이션이 용이합니다.
