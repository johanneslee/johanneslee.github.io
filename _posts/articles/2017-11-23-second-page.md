---
layout: post
title: Five Tips for Using Trello for Scrum
excerpt: "Scrum 을 위해 Trello 를 사용하기 위한 다섯 가지 팁"
modified: 2017-11-23T01:43:25-04:00
categories: articles
comments: true
share: true
---

CivicActions 는 설립된 이래로 가상조직이었고, 최근 몇 년간 모든 프로젝트에 Scrum 이라는 Agile method 을 채택했습니다. 그리고, 2012년 3월부터 Virtual, Scrum 프로젝트를 관리하기 위한 go-to 솔루션으로서 Trello 를 채택했습니다.

Trello 의 장점은 우리에게 프로젝트의 큰 그림을 보게 해준다는 것입니다. 이 개념은 Scrum 의 핵심이기도 합니다. 팀 구성원이 Sprint 나 release 의 큰 그림을 이해하지 못하면 팀 구성원은 이와 같은 방식으로 각자의 업무를 다룰 수 없습니다. 다른 팀 구성원이 수행하는 작업과 관련하여 자신의 업무를 이해하지 못하면 Collaborate 도 안 되고 Cross-skill 도 안 되고 팀이 나아지질 않습니다.

Trello 의 또다른 장점은 다른 많은 프로젝트 관리 도구처럼 속이 거북하거나, 관료주의를 느끼는 불편없이 풍부한 기능을 제공한다고 생각합니다. 대부분의 프로젝트에서 우리는 거의 모든 Trello 의 기능을 사용합니다. 우리는 다른 툴을 사용하면서 종종 감추어져 있거나, 관련 없는 기능들로 인한 혼란을 무시하기 위해 눈을 가늘게 뜨고 보았을 것입니다.

virtual Scrum 팀과 함께 수십 개의 프로젝트를 위해 Trello 를 6개월 간 사용하고, 우리는 몇 가지를 배웠습니다. 다음은 Trello 를 시작하거나 Scrum 프로젝트를 위해 Trello 사용을 향상시키는 데 도움이되는 몇 가지 Tip 입니다.

### Tip 1: 프로젝트 당 둘 이상의 보드를 사용하십시오

Trello 는 모든 것이 같은 페이지에 있기 때문에 프로젝트의 큰 그림을 보기 좋습니다. 그러나 프로젝트에 단 하나의 보드 (하나의 큰 그림) 만 사용하면 잠재적인 단점이 있습니다.

* 팀 구성원이 작업에 집중하려고 할 때, 가끔 디테일한 부분(the tree for the forest)을 놓칠 수 있습니다.
* 중요한 사안이 너무 쉽게 변경 될 수 있습니다. ("누가 Product Backlog 에 있던 Card 를 Sprint 한 가운데의 Sprint Backlog 로 끌어오래?")
* 보드가 너무 넓어지면서 가로 스크롤이 너무 넓어집니다.
* Product Owner 에게 Sprint Candidate list 에 포함시키고 싶은 것이 너무 많습니다. 그 중 일부는 Active Sprint 를 방해합니다.

Scrum 에는 Mode-Active 개발(Sprint)과 Reviewing/Planning, 두 가지 모드가 있으므로, Product Backlog 및 Sprint Planning 에 하나의 보드를 사용하고 Sprint 마다 다른 보드를 사용하는 것이 좋습니다. Product Owner 가 카드를 승인하면 Product Backlog 보드에서 별도의 Sprint 보드에 있는 Sprint Backlog 로 옮깁니다.

__*Product Backlog 보드*__

Product Backlog 보드를 다음과 같은 Card 들의 목록으로 구성하는 것이 좋습니다.

* 아이디어 - 세부 사항이 없으며 제품 소유자가 아이디어를 개발하기 위한 stub 일뿐입니다.
* 수집된 요구사항 - 사용자 스토리 및 원하는 기능을 표시하는 목록입니다.
* 추정 준비과정.
* Sprint Candidates - 추정된 티켓의 경우에 한해서 입니다.

이 보드에서 Product Owner 는 각 목록에 있는 Card 의 우선 순위를 결정하며, 우선 순위가 가장 높은 Card 가 항상 위에 표시됩니다.

팀은 Sprint Planning 회의 중 Card 를 추정이 준비된 것들을 Sprint Candidates 로 이동시킵니다. 만약 User story 가 완성되지 않으면 Card 를 Requirement Gathering 으로 되돌립니다. 여기 [템플릿](https://trello.com/b/eTl6hudO/template-product-backlog)이 있습니다.

__*스프린트 보드*__

Card 는 Product Owner 가 특정 Sprint 에 대한 승인을 받은 경우에만 이 보드에 표시해야 합니다.

* Sprint Backlog. 이것은 제품 소유자가 결정한 우선 순위에 따라 정렬됩니다.
* In Progress.
* QA bug reports. 이렇게하면 QA 테스터가 카드를 제품 백 로그로 이동하거나 "진행 중"으로 바로 이동할 수 없습니다.
* Ready for QA release. 선택 사항으로 엔지니어가 작업을 완료했지만 코드가 QA 환경에 배포되지 않은 카드의 경우이 목록을 사용합니다.
* Ready for QA.
* Ready for Release.
* Done.

다음은 [Sprint 보드 템플릿](https://trello.com/b/fQYAslyL/template-sprint-board)입니다.

### Tip 2 : 추정치와 비교하여 시간을 추적하십시오

Trello에는 아직 예상 시간 기능이나 시간 추적 기능이 내장되어 있지 않지만, Trello Scrum 확장 기능은 Google 크롬 사용자에게 이 기능을 제공합니다.

확장 기능은 Card 에 예상치를 추가하는 일련의 피보나치 순서 버튼을 제공 한 다음 각 목록에 모든 카드를 추가하고 전체 보드에 대한 총 예상치 뿐만 아니라 목록 당 예상치를 표시합니다.

각 보드에 Sprint 가 있는 경우 Sprint Planning 미팅에서 Sprint 에 추가한 시간 또는 User point 를 쉽게 추적할 수 있습니다.

Sprint 가 시작된 후에는 Card 제목의 대괄호 안에 숫자를 추가하여 Card 당 시간을 추적할 수 있습니다. 이 숫자는 각 목록 상단에 밝은 파란색으로 표시되는 집계에 추가되고 오른쪽 상단에는 Current Sprint Burndown 의 즉각적인 의미를 제공하는 집계에 추가됩니다.

CivicActions 에서 우리는 대부분 시간 추정을 사용합니다. Trello method 가 User point 에서 어떻게 작동하는지는 분명하지 않습니다. Trello 를 통해 사용자 지점과 추적 시간에 대한 경험이 있다면 의견을 보내주십시오!

### Tip 3 : 가능한 한 자주 업무를 위한 체크리스트를 작성하십시오

작업에 참여하는 팀원으로서 카드 설명이나 의견의 산문을 통해 읽는 것보다 다음에 수행할 사항에 대한 체크리스트를 분석하는 것이 훨씬 쉽습니다. QA 테스터와 마찬가지로, 개별 체크리스트 항목으로 설명된 경우 Acceptance Criteria 를 읽고 테스트하는 것이 훨씬 쉽습니다.

승인 기준, 구현 (개발자를위한 작업 분류), 테스트 (자동화 또는 단원 테스트의 경우), 배포 작업 등 각 Card 에 대한 체크리스트가 있는 것이 좋습니다. 개별 체크리스트 항목이 너무 커지면 Card 의 경우, "Card 로 변환"기능을 사용하여 자체적으로 분리 할 수 ​​있습니다.

구성원이 두 명 이상인 Card 의 경우 각 체크리스트 항목 담당자의 이름을 지정하는 것이 좋습니다.

견적을하기 위해 체크리스트에 각 작업의 예상치를 포함시킨 후 카드 제목의 총 견적까지 추가하는 것이 유용하다는 사실을 발견했습니다.

### Tip 4 : 신중하게 Card 를 할당하십시오

팀 구성원을 Card 나 Card 뒷면에 끌어 Card 에 할당 할 수 있습니다. Card 당 한 명 이상의 회원을 추가하지는 마십시오. 이것은 실제로 책임자를 혼란스럽게합니다. 팀의 다른 구성원이 계속 참여하거나 정보를 얻고자 한다면 Card 에 등록 할 수 있습니다. 진행 과정을 따르기를 원하는 Product Owner 는 모든 Card 또는 보드 전체를 한꺼번에 구독하고 싶을 수 있습니다. 이것은 투머치인포(TMI)입니다! "알아야 할 것을 아는 것"이 생산성의 열쇠입니다.

엔지니어가 되어 Card 로 작업을 마친 후 QA 준비 상태로 이동하는 경우 직접 제거하십시오. 누가 QA 할 것인지 이미 알고 있다면 카드를 그들에게 할당하십시오.

QA 테스터 인 경우 QA 를 마친 후에 제품을 제거하십시오. 그것을 작업한 엔지니어 또는 버그 수정을 담당하는 담당자에게 할당하십시오.

Trello 는 [모든 사용자의 Card 를 모든 게시판에 표시하는 페이지](https://trello.com/my/cards)를 제공합니다. 한 번에 두 개 이상의 프로젝트를 작업하는 경우 매우 유용합니다!

### Tip 5 : Sprint Retrospective 를 위해 Trello Board 를 사용하십시오

Trello 보드는 훌륭한 Sprint Retrospective 도구가 될 수 있습니다. [Sprint Retrospective Template](https://trello.com/b/YEXXigXH/template-sprint-retrospective-basic) 을 게시했습니다. 언제든지 복사하십시오!

우리는 Scrum을 위해 Trello를 사용하는 다른 사람들의 이야기를 듣고 싶어합니다. 우리의 프로세스는 여전히 진화하고 있으며, 최선의 사용 방법을 계속해서 배우고 있으므로 아래에 의견을 게시 할 것입니다.
