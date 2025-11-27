# 🐧 Linux Process Management Guide

이 문서는 리눅스 시스템에서 프로세스를 모니터링하고 제어하는 데 필수적인 4가지 명령어(`top`, `ps`, `jobs`, `kill`)에 대한 핵심 가이드입니다.

---

## 📋 목차 (Table of Contents)

1. [top - 실시간 시스템 모니터링](#1-top---실시간-시스템-모니터링)
2. [ps - 현재 프로세스 상태 확인](#2-ps---현재-프로세스-상태-확인)
3. [jobs - 백그라운드 작업 확인](#3-jobs---백그라운드-작업-확인)
4. [kill - 프로세스 종료 및 시그널 전송](#4-kill---프로세스-종료-및-시그널-전송)

---

## 1. top - 실시간 시스템 모니터링

`top`은 리눅스 시스템의 현재 상태를 실시간으로 보여주는 대시보드와 같습니다. CPU 사용량, 메모리 점유율, 실행 중인 프로세스 목록을 갱신하며 보여줍니다.

![Linux top command](https://via.placeholder.com/600x300?text=Top+Command+Interface)
*(실제 스크린샷 이미지 경로로 변경해주세요)*

### 기본 사용법
```bash
top
