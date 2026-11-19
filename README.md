# Querydog

**Querydog는 SQL 편집, DB 간 DDL·데이터 전송, 행 차이 비교 및 선택 동기화를 지원하는 Windsoft 데스크톱 도구입니다.** Oracle, MySQL, MariaDB, PostgreSQL, Microsoft SQL Server, SQLite를 한곳에서 관리할 수 있습니다.

[공식 제품 소개](https://windsoft.co.kr/querydog.html) · [최신 설치 파일과 운영체제 요구사항](https://windsoft.co.kr/querydog-download.html)

## 주요 기능과 에디션

- **SQL 편집과 조회** — 연결과 스키마를 선택해 SQL을 실행하고 결과를 확인합니다. 조회 결과를 CSV 또는 Excel로 내보낼 수 있습니다.
- **DB 간 DDL·데이터 전송** — 같은 종류 또는 다른 종류의 DB 사이에서 구조와 데이터를 옮깁니다. 실행 전 DDL 미리보기에서 컬럼 타입과 키를 점검하고, 전송 중에는 테이블별 진행 상태를 확인합니다.
- **행 비교 및 선택 동기화** — PK·UNIQUE 또는 지정한 비교 키로 원본과 대상의 행을 대조합니다. 추가·갱신·삭제 후보를 검토하고 필요한 변경만 반영합니다. 복사조건을 사용하는 동기화에서는 삭제가 지원되지 않습니다.
- **Pro 자동화와 이관** — 유료 Pro는 증분·예약 전송, DB 구조 비교, Oracle PL/SQL 마이그레이션을 제공합니다. SQL 편집, 기본 전송, 비교 후 수동 동기화는 무료 Community에서 사용할 수 있습니다.

## 처음 사용하는 순서

1. 운영체제와 CPU에 맞는 설치 파일을 내려받습니다. 배포용 설치 파일은 별도 Python 설치 없이 실행할 수 있고, DB 종류에 따라 클라이언트나 드라이버 설정이 필요할 수 있습니다.
2. 연결 관리에서 DB 종류를 선택합니다. 서버형 DB는 주소·포트·서비스 또는 데이터베이스·계정을 입력하고, SQLite는 DB 파일을 지정합니다. 연결 확인 후 대상 스키마를 선택합니다.
3. SQL 에디터에서 실행 대상 연결을 확인하고, 결과 행을 제한한 SELECT부터 실행합니다. 운영 DB를 처음 조회할 때는 조회 권한 계정 또는 읽기 전용 연결을 사용하세요.
4. 데이터를 옮기려면 원본·대상 연결과 테이블을 선택한 후 DDL 미리보기에서 키·데이터 타입·정밀도를 확인합니다. 시험 테이블로 먼저 실행하고 완료 리포트에서 처리 결과와 실제 값을 대조합니다.
5. 동기화할 때는 비교 키와 컬럼 매핑을 확인합니다. 추가·갱신·삭제 상세를 확인하고 적용할 작업만 선택한 뒤 결과를 검증합니다.

## 다운로드

아래 버전은 GitHub 릴리스에 첨부된 배포본입니다. 최신 배포 버전과 지원 환경은 공식 다운로드 페이지를 확인하세요. 같은 설치 파일에서 라이선스에 따라 Community 또는 Pro 기능을 사용할 수 있습니다.

| 운영체제 | 배포 버전 | GitHub 설치 파일 |
| --- | --- | --- |
| Windows 10/11 64비트 | 1.2.0 | [EXE](https://github.com/Windsoft-Glazir/Querydog/releases/download/website-downloads-2026-11-19/Querydog-Setup-1.2.0.exe) |
| Ubuntu Linux 26.04 x86_64 | 1.2.1 | [DEB](https://github.com/Windsoft-Glazir/Querydog/releases/download/website-downloads-2026-11-19/querydog_1.2.1_amd64.deb) |
| Amazon Linux 2023 / Fedora x86_64 | 1.2.1 | [RPM](https://github.com/Windsoft-Glazir/Querydog/releases/download/website-downloads-2026-11-19/querydog-1.2.1-1.x86_64.rpm) |
| macOS 14 이상, Apple Silicon | 1.0.92 | [DMG](https://github.com/Windsoft-Glazir/Querydog/releases/download/website-downloads-2026-11-19/Querydog-macOS-KO-1.0.92.dmg) |

- [공식 다운로드·요구사항](https://windsoft.co.kr/querydog-download.html) · [GitHub 릴리스](https://github.com/Windsoft-Glazir/Querydog/releases)
- [시작 가이드](https://windsoft.co.kr/querydog-getting-started.html) · [가져오기·내보내기 및 전송 안내](https://windsoft.co.kr/querydog-import-export.html) · [사용 설명서](https://windsoft.co.kr/querydog-manual.html)

## English summary

Querydog is a cross-platform SQL client for Oracle, MySQL, MariaDB, PostgreSQL, SQL Server, and SQLite. Connect to a database, run SQL, export results, or preview and transfer schema definitions and data between engines. Community includes row comparison and selective manual synchronization. Pro adds incremental and scheduled transfers, structure comparison, and Oracle PL/SQL migration. Official installers are available as Windows EXE, Ubuntu DEB, Linux RPM, and Apple Silicon macOS DMG.

- [Product overview](https://windsoft.co.kr/querydog-en.html) · [Getting started](https://windsoft.co.kr/querydog-getting-started-en.html) · [Official downloads](https://windsoft.co.kr/querydog-download-en.html)
