# 프로젝트 제목: PCR Helper

## 📌 개요
PCR Helper는 DNA 서열을 입력하면 핵심 기초 분석 결과를 자동으로 제공하는 웹앱입니다. 입력된 서열을 기반으로 DNA 길이, 염기 조성(A/T/G/C 비율), RNA 전사 결과, 그리고 개시코돈(AUG)부터 STOP 코돈까지의 단백질 서열을 자동으로 생성해줍니다.

## ⚙️ 주요 기능
DNA 서열 입력 시
- DNA 길이 계산
- A, T, G, C 비율 자동 분석
- DNA → RNA 전사 결과 생성
- RNA 서열에서 개시코돈(AUG) 탐색 및 STOP 코돈(UAA, UAG, UGA) 전까지 단백질 아미노산 서열 자동 변환
- 결과를 화면에 즉시 export

## 🛠 기술 스택
- HTML, CSS, JavaScript (Vanilla)
- JavaScript 문자열 처리 및 단순 파싱 로직
- localStorage(입력 기록 저장 시 선택 기능)

## 🚀 실행 방법
1. index.html 파일을 브라우저에서 실행합니다.
2. DNA 서열을 입력합니다.
3. “분석하기” 버튼을 클릭하면 길이, 염기 비율, RNA 서열, Protein 서열이 바로 표시됩니다.


