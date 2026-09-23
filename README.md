# 구 버전 지원 종료 안내

안녕하세요, **부산 버스 도착 정보 시스템**입니다.

안정적인 실시간 버스 정보 제공과 보안 및 서버 인프라 개선을 위해, **구 버전 앱에 대한 서비스 지원이 종료**될 예정임을 안내해 드립니다.

---

### 1. 지원 종료 대상 및 일정
* **대상 버전**: **v4.5.x 이하 모든 구버전**
* **지원 종료 일시**: **2026년 10월 1일(목) 00:00부터**
* **영향**: 지원 종료 이후 구 버전에서는 실시간 도착 정보 조회 및 앱 실행이 제한될 수 있습니다. 지원 종료 이후에 구 버전을 사용 중이신 경우 수동으로 업데이트 해야 합니다.

---

### 2. 지원 종료 사유
1. **API 및 보안 정책 강화**: 부산시 버스정보관리시스템(BIMS) 연동 체계 개편 및 데이터 무결성 검증 강화
2. **최신 런타임 최적화**: WinUI 3 및 Qt 6 기반의 안정적인 시스템 유지보수
3. **성능 개선**: 구 버전에서 발생하던 데이터 지연 및 버그 해결

---

### 3. 사용자 조치 안내 (필수)
현재 구 버전을 사용 중이신 사용자께서는 원활한 서비스 이용을 위해 **최신 버전(v5.0.0 이상)** 으로 업데이트해 주시기 바랍니다.

* 📥 **최신 버전 다운로드**: [GitHub Releases 바로가기](https://github.com/3yearscurry/Busan_Bus_Arrival_Information/releases)
* **설치 방법**: 위 링크에서 최신 설치 파일을 다운로드하여 실행하시면 됩니다.

---

앞으로도 더 빠르고 쾌적한 버스 도착 정보 서비스를 제공할 수 있도록 최선을 다하겠습니다.  
감사합니다.

# 부산 버스 도착 정보 시스템

[![API 서버 상태](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/3yearscurry/d179f0445e5df8a51b85c45c5caeda35/raw/server-status.json)](https://github.com/3yearscurry/Busan_Bus_Arrival_Information/releases)

부산광역시 버스 도착 정보를 실시간으로 조회하는 데스크톱 앱입니다.

`본 프로그램은 부산광역시가 제작·운영·후원하는 공식 프로그램이 아닙니다.`

## 요구 사항

- Windows : `Windows 10 21H2 이상 또는 Windows 11`

- Mac : `macOS 14 Sonoma 이상(Apple Silicon 전용)`

## Mac에서 "'BusanBus'은(는) 손상되었기 때문에 열 수 없습니다" 오류 발생 시
터미널에서 xattr -cr /Applications/BusanBus.app 실행 후 프로그램 재실행

## 다운로드

[최신 릴리즈](https://github.com/3yearscurry/Busan_Bus_Arrival_Information/releases/latest)에서 설치 파일을 받을 수 있습니다.

## 스크린샷

<img width="1362" height="812" alt="image" src="https://github.com/user-attachments/assets/14e625aa-3154-4002-b2c8-e25f68569c79" />

<img width="1360" height="805" alt="image" src="https://github.com/user-attachments/assets/78e5cfb5-9293-4b5d-a144-e0a0731b6667" />
