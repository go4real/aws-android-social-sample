---
title: "Amazon EKS Wo"
chapter: true
weight: 1
---

<div style="text-align: center"><h2>ECS로 하는 데디케이디드 서버 운영 HoL</h2></div>

# 희망의 시간
우리는 어디서나 즐길 수 있는 실시간 전략 PvP 게임인 "틱-택-토"을 만들었습니다.
탁월한 게임성으로 이 게임은 다음번 국민게임이 될 것이라는 확신에 차 있습니다.
사업팀의 포커스 그룹 테스트는 역대 최고 점수가 나왔고 마케팅팀의 시장 조사 결과도 장미빛 미래 입니다.

사업팀의 예상 수치는 보수적으로 잡아도
**금요일 저녁 동시접속자는 100만이 넘을 것이고, 이때 최소한 30만개 이상의 데디 서버가 만들어질 예정입니다.**


# 동이 트기 전이 가장 어두울때
개발팀은 마냥 기뻐하기엔 걱정이 앞섭니다. 월요일 아침엔 1만개도 안될 데디 서버가 금요일 저녁엔 30만개가 될 것입니다.
서버를 다 준비해놓고 운영하기엔 비용은 둘째치고 관리가 너무 힘듭니다.
기획팀은 벌써부터 6개월치 기능에 대한 플랜을 세웠는데 슬쩍 보니 매주 패치가 될 같습니다.
온 팀원이 잘 나눠서 밤새며 몸빵을 해도 한달을 버티기가 버거워 보입니다.


# 컨테이너로 제시하는 데디케이티드 서버 운영 방법
이 랩을 통해 여러분은 Amazon ECS와 AWS CloudMap을 활용하여 사람의 관리 포인트를 최소한으로 줄이면서도
안정적이고 유연한 운영환경을 만들어보게 됩니다.


