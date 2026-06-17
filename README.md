# Game Server Programming Notes

## 소개

이 저장소는 **『게임 서버 프로그래밍 교과서』**를 주 서적으로 삼아 게임 서버 개발에 필요한 핵심 개념을 정리한 개인 학습 기록입니다.

책을 읽으며 직접 정리한 키워드와 개념을 기반으로, AI를 활용해 내용을 보충하고 마크다운 문서 형태로 재구성했습니다. 단순 요약이 아니라 게임 서버 개발 관점에서 중요한 개념, 주의해야 할 부분, 간단한 코드 예시, 도식화 자료를 함께 정리하는 것을 목표로 합니다.

특히 멀티스레딩, 네트워크, 소켓 프로그래밍, 게임 서버 구조, 데이터베이스, 분산 서버 구조처럼 게임 서버 프로그래머가 반드시 이해해야 할 내용을 나중에 빠르게 복습할 수 있도록 구성합니다.

## 정리 방식

각 장은 다음 기준으로 정리합니다.

* 책에서 다루는 핵심 키워드 정리
* 이해가 필요한 개념에 대한 보충 설명
* 게임 서버 개발에서 실제로 중요한 포인트 강조
* 필요한 경우 C++ 또는 Windows API 기반 간단 코드 예시 추가
* 구조 이해가 필요한 부분은 도식 이미지 또는 Mermaid 다이어그램 추가
* 신뢰할 수 있는 자료를 참고하여 출처 명시

## 주요 참고 자료

주 참고 서적은 다음과 같습니다.

* 『게임 서버 프로그래밍 교과서』

보충 설명에는 아래와 같은 신뢰성 있는 자료를 함께 참고합니다.

* 운영체제 교재

  * Abraham Silberschatz, Peter B. Galvin, Greg Gagne, *Operating System Concepts*
* 네트워크 교재

  * W. Richard Stevens, *UNIX Network Programming*
  * James F. Kurose, Keith W. Ross, *Computer Networking: A Top-Down Approach*
* C++ / Windows 공식 문서

  * Microsoft Learn
  * cppreference
* 성능 분석 및 병렬 프로그래밍 관련 공식 문서

  * Microsoft Concurrency Visualizer
  * Visual Studio Profiling Tools


## 문서 목록

```text
.
├── README.md
├── ch01_multithreading.md
├── ch02_computer_network.md
├── ch03_socket_programming.md
├── ch04_game_server_and_client.md
├── ch05_game_networking.md
├── ch06_proudnet.md
├── ch07_database_basic.md
├── ch08_nosql_basic.md
├── ch09_distributed_server_architecture.md
├── ch10_distributed_server_case_study.md
└── images/
```

## 목표

이 저장소의 목표는 단순히 책 내용을 옮기는 것이 아니라, 게임 서버 프로그래밍을 공부하면서 반드시 이해해야 하는 개념들을 내 언어로 다시 정리하는 것입니다.

최종적으로는 다음과 같은 내용을 빠르게 복습할 수 있는 개인 지식 저장소를 만드는 것을 목표로 합니다.

* 게임 서버의 기본 구조
* 멀티스레딩과 동기화
* TCP/IP와 소켓 프로그래밍
* 게임 서버와 클라이언트의 통신 흐름
* 게임 네트워킹 설계
* 데이터베이스와 NoSQL의 역할
* 분산 서버 구조와 실제 적용 사례

## 주의 사항

이 저장소는 개인 학습 목적으로 작성한 정리 문서입니다.

내용은 『게임 서버 프로그래밍 교과서』를 중심으로 학습한 내용을 바탕으로 하되, 직접 정리한 키워드와 추가 자료를 기반으로 재구성했습니다. 일부 설명은 이해를 돕기 위해 AI를 활용해 보충했으며, 가능한 한 공식 문서와 신뢰할 수 있는 교재를 근거로 검토하고 출처를 남깁니다.
