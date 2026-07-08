# LineWatch Workspace

LineWatch는 제조 라인의 품질 이벤트와 센서 데이터를 운영 대시보드로 연결하는 서비스 프로젝트입니다.

## 저장소 구조

```text
linewatch-workspace/
  linewatch-fe/  # Next.js 운영 대시보드
  linewatch-be/  # FastAPI + Tortoise ORM REST API
```

FE/BE는 Git submodule로 연결되어 있습니다.

## 프로젝트 링크

- FE: https://github.com/linewatch-labs/linewatch-fe
- BE: https://github.com/linewatch-labs/linewatch-be
- Personal mirror: https://github.com/cyjoon68/linewatch-workspace

## 실행

```bash
git clone --recurse-submodules https://github.com/linewatch-labs/linewatch-workspace.git
```

## 프로젝트 포인트

React/Next.js 기반 제조 운영 UI와 Python REST API를 분리해 실제 서비스형 repo 구조로 구성했습니다.
