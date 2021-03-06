---
title: "ISTQB CTFL 취득"
date: 2020-10-27 00:00:00 +0900
categories: 자격증
comments: true
tags: ISTQB
---
테스트 자격증을 준비하는데 있어 어떤 테스트 자격증을 왜 준비해야하고, 어떻게 준비해야할지 모르는 분들이 꽤 있을 것 같다.
그런분들께 도움이 되고자 누추한 내 경험을 간략하게 풀어보려 한다.🥺  

## ISTQB란?
ISTQB는 국제 소프트웨어 테스팅 자격 협회로 테스트 자격증을 취급하는데, 이는 Foundation, Advanced, Expert 등 다양한 레벨과 Core, Agile, Specialist 등 여러 분야로 나뉘어 있다.
<div align="center">
  <img src="/assets/images/istqb_table.PNG" alt="ISTQB 자격증 소개"><br>
  <span style="color:gray; font-size:small;">출처 : https://www.sten.or.kr/bbs/board.php?bo_table=sten_ist</span>
</div>

## 테스트 자격증을 굳이 왜?
테스트 주도 개발(TDD)에 관심을 가지고, 자격증을 준비하게 된 데에는 크게 2가지 이유가 있다.<br>

<ol>
  <span style="font-size:large; font-weight:bold;"><li>TDD의 중요성</li></span>
  <p><strong>'대형 프로젝트, 대규모 팀을 특징으로 하는 최근 트렌드에 있어 TDD는 선택이 아닌 필수라고 생각한다.'</strong></p>

  <p>TDD는 발생 가능한 결함 비용을 초기에 줄이고, 콘솔 출력문을 통해 일일히 확인하던 방식에서 벗어나 테스트 기법을 체계적으로 자동화하는 하나의 개발 방법론이다.
  물론 조금 규모가 큰 기업이라면 QA 팀이 따로 존재하겠지만, 유닛 테스트 및 통합 테스트 정도는 개발자도 할 수 있어야 <strong>코드의 품질을 확보</strong>할 수 있다고 생각한다.<br>
  (하지만, 일각에서는 TDD를 비판하는 경우도 있습니다. TDD에 대해 더 자세한 내용은 따로 포스팅하겠습니다.)</p>

  <span style="font-size:large; font-weight:bold;"><li>부족한 기초 지식</li></span>
  <p><strong>'자격증 공부는 마치 교과서 공부와 같기에 초심자에게 좋은 접근법이라 생각한다.'</strong></p>
  <p>IT 서비스업계와는 달리, 내가 몸담고 있는 IT 제조업에서는 모던한 SW 기술을 운용하는 팀을 찾기가 힘들다. 가뜩이나 나는 전자공학부 출신이기에 SW 공학을 깊게 배우진 않았었다.
  이대로 있다가는 도태될 것 같아, C언어에서 테스트기법을 적용하는 방법에 대해 찾아보기 시작했는데, 제임스 그레닝의 '임베디드C를 위한 TDD'가 큰 도움이 되었다.
  (나중에 이 책에 대해 한번 다뤄보겠다.) 하지만 테스트에 대한 아무런 지식도 없는 상태에서 기술 활용에 대한 책을 읽으려니 도저히 읽히지가 않아, 테스트 자격증을 준비하며 기본 지식을 쌓기로 결심하였다.</p>

  <span style="font-size:large; font-weight:bold;"><li>스펙</li></span>
  <p>대부분의 학사 졸업자들은 대기업에서 연구개발보다는 <strong>다양한 플랫폼을 대상으로 검증 업무를 수행</strong>할텐데, 이때 테스트 지식이 요구되다보니 ISTQB 또는 CSTS가 있으면 우대해주는 경우가 있다.
  ex) 삼성전자 DS 부문 SW 개발직무</p>
  <div align="center">
    <img src="/assets/images/samsung_ds.PNG" alt="삼성 DS 직무 우대사항"><br>
    <span style="color:gray; font-size:small;">2020 삼성전자 DS부문 S/W 개발 우대사항</span>
  </div>
</ol>

## 근데 왜 ISTQB를 선택했는가?
테스트 자격증에는 국내 자격증인 <strong>CSTS</strong>와 국제 자격증인 <strong>ISTQB</strong>가 있다. 둘다 취득하면 물론 좋겠지만, <strong>QA 직무가 아니고서야 굳이 2개 다 취득할 이유가 없다고 생각</strong>한다. 그럼 두 자격증은 어떤 점에서 다를까?<br>

<p>CSTS는 TTA에서 주관하는 시험으로 내가 응시했을 당시에는 정보가 많이 없었다. 일단 CSTS 교재를 구매하긴 했었는데, 내용을 보니 ISTQB에 비해 <strong>범위는 넓지만 내가 배우고 싶었던 테스트 설계 기법에 대한 내용은 간단하게만 다루고,
테스트 관리 등 그 이외의 내용이 대부분이었다.</strong> 국내 QA 분들에게는 도움이 될 것 같지만, 테스트 설계 기법에 대한 구체적인 정보가 필요했던 내게 CSTS는 그닥 매력적이지 않았다.</p>
<p>ISTQB는 CSTS와 달리, <strong>테스트 설계 기법 파트에 책의 2분의 1에 달하는 양을 할애</strong>하였고, 이로 인해 실무 지식을 필요로 했던 내게 적합한 자격증이라고 생각했다.
이와 더불어 국제 자격증이다보니 외국계 기업에서 어필할 수 있겠다고 생각하여 ISTQB를 취득하기로 결정했다.</p>

## 학습 방법
<strong>2020년 5월 19일 시험을 목표</strong>로 4월 초부터 <strong>약 1달간</strong> 정말 열심히 준비했었다. 사용했던 교재는 다음과 같다.<br>

<ol style="font-weight:bold;">
  <li><a href="http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788994711003&orderClick=&Kc=">개발자도 알아야할 소프트웨어 테스팅 실무</a><<img src="/assets/images/istqb_textbook1.jpg">/li>
  <li><a href="http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788994711027&orderClick=LEA&Kc=">문제로 배우는 소프트웨어 테스팅2 (권원일, 김선준, 정기영)<img src="/assets/images/istqb_textbook2.jpg"></a></li>
</ol>

<p>시간도 부족했지만, ISTQB의 선넘는 응시 가격탓에.. 한번만에 합격하자고 다짐했었다. 응시 난이도는 전공자도 살짝 어려울 정도라고 했기에 한번 할때 제대로 하자는 마음으로 CSTS 교재도 샀지만 시간이 부족해 풀지는 못했다 ㅎ</p>
<p>'개발자도 알아야할 소프트웨어 테스팅 실무'(개알)를 <strong>3주</strong>에 걸쳐 학습하고, '문제로 배우는 소프트웨어 테스팅2'(문배)를 <strong>1주</strong> 동안 나눠 풀어 개알에서 학습한 개념을 점검하였다.</p>
<p>개알이나 문배의 ISTQB 모의고사를 보면, 키워드 문제도 꽤 있었지만 응용 문제가 발목을 많이 잡았었다. 예를 들어, <strong>특정 상황을 주고 여기에 적용 가능한 테스트 기법, 대처법을 골라야하는 문제</strong> 등이 상당히 힘들었다.
따라서 각 기법에 대하여 애매하게 외우기 보다는 <strong>어떤 상황에서 어떤 목적으로 쓰이는지 해당 기법의 상위 개념은 무엇인지 등 확실하게 외우기 위해 노력</strong>했다.</p>
<p>개알의 내용을 확실하게 암기하였는지 확인하기 위해 한 단원을 끝낼 때마다 <strong>빈 A4용지에 책을 보지 않고 학습한 단원의 키워드를 쭈욱 써내려갔다.</strong>
중요 키워드를 작성한 다음에는 키워드에 대한 <strong>세부 내용과 특징들을 최대한 기억나는대로 적어 개념을 구체화시켰다.</strong> 이때 기억 못한부분은 <span style="color:blue;">다른 색 볼펜(ex, 파란색)</span>을 이용해 작성하는데,
나중에 <strong>파란색 글씨 위주로 복습</strong>하면 시간도 절약하고 부족한 부분도 점검할 수 있어 효율적으로 학습할 수 있었다.</p>

## 시험 후기
대체 서울은 왜그렇게 복잡합니까?!!!<br>

시험 장소인 STA 교육센터가 골목 안쪽에 있어서 찾아가기가 너무 힘들었다.. 대구 토박이인 나에게 서울은 너무 힘든 곳😭<br>

여러모로 힘들었던 날이라 큰 기대는 안하고 있었는데 다행히 하늘께서 도와주셨느지 34/40의 점수로 합격할 수 있었다.🥺 규정상 문제에 대해 말할 순 없지만, 간단히 팁을 주자면 다음과 같다.<br>

<ol style="font-weight:bold;">
  <li>개념을 외울때 예시와 함께 외울 것(ISTQB의 문제는 대부분 응용 문제이다)</li>
  <li>모든 수행 절차를 각 스텝에서 수행하는 내용과 함께 모두 빠짐없이 외울 것</li>
  <li>여러가지 모델이 나오는 경우, 차이점 위주로 외울 것</li>
  <li>테스트 또는 리뷰에서 각 파트 담당자의 역할 위주로 외울 것</li>
  <li>테스트 설계 기법은 많은 문제를 직접 풀어볼 것</li>
  <li>비슷해 보이는 용어가 많이 나오는데, 각기 다른 용어이므로 실수하지 않게끔 구별해서 잘 외울 것(공부하다보면 애매하게 겹치는 개념들이 있다보니 각 개념에 대한 확실한 정의를 외우는게 아니라,
  대충 비슷한 개념을 하나의 카테고리로 잡고 외우는 경우가 있는데, 이걸 출제자가 노린건지 차이점을 구별할 줄 알아야 풀 수 있는 문제도 더러 나온다)</li>
  <li>한국어 시험은 번역 퀄이 별로 좋지 못하다고 한다. 영어 시험은 한국어 시험보다 시간도 더 많이 주기에 영어 시험을 선택했었는데, 공부할 때 각 개념에 대한 영어 표현법도 같이 공부해주는 것이 좋다.
  안그러면 시험장에서 당황할 수 있다.</li>
</ol>
