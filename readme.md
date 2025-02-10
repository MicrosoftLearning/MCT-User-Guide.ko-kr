#README

We've turned off the ability to report issues directly on this repo and do not monitor PRs.

Provide feedback here: https://aka.ms/provide-feedback

Or, if you are a trainer with a microsoft.com email address, please create a ticket in AzDO.

# MCT용 GitHub 사용자 가이드

Microsoft Azure와 같은 클라우드 서비스는 자주 업데이트되므로 교육 과정 및 랩 단계가 더 이상 클라우드 서비스와 일치하지 않을 때 MCT(Microsoft Certified Trainers)에 문제가 발생합니다. . 변경 빈도와 변경이 발생할 때 알림이 없다는 사실 때문에 과정 개발 팀이 랩 변경 내용을 신속하게 파악하고 조정하기가 어려울 수 있습니다.

Microsoft는 이러한 문제를 해결하기 위해 GitHub를 사용하여 Azure와 같은 클라우드 서비스가 포함된 과정의 랩 단계와 랩 스크립트를 게시합니다. 과정 작성자와 MCT는 GitHub를 사용하여 랩 콘텐츠에 클라우드 서비스 변경 사항을 최신으로 유지할 수 있습니다. MCT는 GitHub를 사용하여 랩 변경에 대한 피드백과 제안을 제공할 수 있으며, 과정 작성자는 랩 단계와 스크립트를 즉시 업데이트할 수 있습니다.

이러한 과정을 가르칠 준비를 할 때는 GitHub에서 적절한 파일을 다운로드하여 최신 랩 단계 및 스크립트를 사용하고 있는지 확인해야 합니다.

이 사용자 가이드는 GitHub를 처음으로 사용하는 MCT를 위한 것입니다. GitHub에 연결하고, 과정 자료를 다운로드 및 인쇄하고, 수강생이 랩에서 사용하는 스크립트를 업데이트하고, 과정의 컨텐츠를 최신으로 유지하는 방법을 설명합니다.

> **참고**: GitHub 파일 액세스와 GitHub 사이트 탐색에 대한 Microsoft Learning 지원은 이 과정을 가르치는 MCT에게만 제공됩니다.

과정의 기술적 내용이나 과정 또는 랩의 준비 방법을 논의하는 데 GitHub를 사용해서는 안 됩니다. GitHub는 특히 랩의 변경 내용을 다루기 위한 것입니다.

 
> **참고**: 과정 및 데모에 관한 일반적인 의견 제안이나 과정 준비 방법에 관한 설명은 기존 MCT 포럼을 사용하세요.

## 섹션

- [GitHub 용어](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [업데이트 알림 수신 및 프로젝트 공동 작업](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- 랩 지침에 대한 변경 제안 또는 문제 제출

## GitHub 용어

GitHub에 새로운 용어가 도입되었습니다. 다음 목록에는 이 문서 전체에서 사용되는 용어와 개념이 나와 있습니다. 하지만 GitHub 용어의 전체 목록은 [GitHub 용어집](https://docs.github.com/en/get-started/quickstart/github-glossary)을 참조하세요.

| 용어| 설명 |
| - | - |
| Git 및 GitHub| Git은 오픈 소스 변경 추적 프로그램이고 GitHub는 Git을 기반으로 빌드된 사이트/솔루션입니다. Git을 백 엔드로 사용하는 다른 웹 사이트와 솔루션이 있습니다. GitHub는 주로 오픈 소스(공용) 개발 프로젝트에 사용되며 해당 프로젝트에는 무료입니다. 그러나 오픈 소스가 아닌 프라이빗 프로젝트에 GitHub를 사용하려면 유료 버전에 등록해야 합니다. |
| 리포지토리| GitHub의 각 프로젝트는 리포지토리에 있습니다. 리포지토리에는 설명서를 포함한 모든 프로젝트 파일이 포함되며 수정 버전 기록을 지원합니다. 리포지토리는 공용 또는 프라이빗일 수 있습니다. 컴퓨터 하드 드라이브에 리포지토리의 로컬 복사본을 보유하거나 GitHub 내에서 리포지토리를 사용할 수 있습니다. |
| Markdown| 이는 설명서를 만드는 데 사용할 수 있는 텍스트 파일 형식입니다. 텍스트 기반이며 업데이트가 매우 간단하여 협업 중에 쉽게 사용할 수 있습니다. 그런 다음 GitHub는 이를 HTML로 렌더링합니다. |
| GFM(GitHub Flavored Markdown)| Markdown 파일 형식에는 다양한 변형 또는 특징이 있습니다. 일반적으로 GFM이라고 하는 GitHub 버전은 Markdown의 가장 일반적인 변형 중 하나입니다. GFM에 대한 자세한 내용과 GFM 문서에 태그 서식을 사용하는 방법은 https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/의 "GitHub에서 쓰기 및 서식 지정 시작"을 참조하세요. |
| 포크| 원래 리포지토리에 있는 분기와 비교하여 GitHub 계정에 있는 다른 리포지토리의 복사본입니다. 바로 아래의 "분기"를 참조하세요. |
| 지점| 원본과 동일한 리포지토리에 있는 리포지토리의 복사본입니다. 분기를 원본과 병합할 수 있습니다. |
| Fetch| 온라인 리포지토리에서 최신 변경 내용의 복사본을 검색하는 프로세스입니다. 그러나 페치는 변경 내용을 병합하지 않습니다. |
| 끌어오기| 온라인 리포지토리에서 최신 변경 내용을 가져와서 로컬 변경 내용과 병합하는 프로세스입니다. |
| 병합| 한 분기에서 변경 내용을 가져와서 다른 분기에 적용하는 프로세스입니다. 여기에는 온라인 리포지토리에서 변경 내용을 검색한 다음 해당 리포지토리의 로컬 버전에 적용하는 작업이 포함됩니다. |
| 끌어오기 요청| 사용자가 제출한 리포지토리에 대해 제안된 변경 내용 집합이며, 리포지토리의 소유자 또는 협력자는 끌어오기 요청을 수락하거나 거부할 수 있습니다. |
| Push| 로컬 변경 내용을 온라인 리포지토리로 보내거나 제출하는 프로세스입니다. |
| 협력자| 리포지토리의 콘텐츠를 추가, 삭제 또는 변경할 수 있는 권한이 있는 GitHub 사용자입니다. |

## 업데이트 알림 수신, 변경 제안, 프로젝트 협업

GitHub 리포지토리에 업데이트가 발생할 때 알림을 받도록 GitHub 환경을 구성할 수 있습니다. 알림에 등록할 수 있는 방법은 여러 가지가 있으며 그중 대부분은 프로젝트에서 협업할 수 있는 다양한 방법과 관련이 있습니다. 알림을 받으려면 다음 작업을 수행하면 됩니다.

| 작업| 설명 |
| - | - |
| [리포지토리 감시](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| 리포지토리를 감시할 때 GitHub는 해당 특정 리포지토리에 대해 만들어진 새로운 끌어오기 요청이나 문제에 대한 알림을 자동으로 구독합니다. 사용자가 만들었거나 협업자로 참여한 리포지토리를 자동으로 감시합니다. |
| [끌어오기 요청](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| 끌어오기 요청을 만들고 리포지토리 소유자에게 변경 내용을 수락하도록 제안하면 끌어오기 요청 관련 토론에 대한 알림을 수신하도록 자동으로 구독하게 됩니다. Pull 요청을 만들려면 먼저 분기를 만들어야 합니다. |
| [설명](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| 다른 사람의 끌어오기 요청에 대해 의견을 달면 GitHub는 해당 의견과 관련된 포럼을 자동으로 구독하거나 포럼을 수동으로 구독할 수 있습니다. |
| [문제](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| 문제는 리포지토리와 관련된 제안, 질문 또는 요청입니다. 각 문제에는 자체 토론이 있으며 문제를 구독할 수 있습니다. 또는 GitHub가 사용자가 만든 문제를 자동으로 구독합니다. |
| [멘션](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| 다른 사용자가 GitHub 사용자 이름([@username](https://github.com/username))을 사용하여 대화에서 사용자를 멘션하면 GitHub가 자동으로 토론을 구독합니다. |

> **참고**: 알림을 받는 방법과 시기를 수정할 수 있으며 일부 또는 모든 토론의 구독을 취소할 수도 있습니다.

## 랩 지침에 대한 문제 제출 또는 변경 제안

제안 사항이 있거나 랩에서 오류가 발생하는 경우 끌어오기 요청을 제출하고 문제를 로그할 수 있습니다. 오류에 대한 수정 사항을 이미 알고 있는 경우 끌어오기 요청을 제출하는 것이 좋습니다. 그렇지 않으면 문제를 제출합니다.

| 작업| 설명 |
| - | - |
| [끌어오기 요청](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| 끌어오기 요청을 만들고 리포지토리 소유자에게 변경 내용을 수락하도록 제안하면 끌어오기 요청 관련 토론에 대한 알림을 수신하도록 자동으로 구독하게 됩니다. Pull 요청을 만들려면 먼저 분기를 만들어야 합니다. |
| [설명](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| 다른 사람의 끌어오기 요청에 대해 의견을 달면 GitHub가 해당 의견과 관련된 포럼을 자동으로 구독하거나, 사용자가 포럼을 수동으로 구독할 수 있습니다. |
| [문제](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| 문제는 리포지토리와 관련된 제안, 질문 또는 요청입니다. 각 문제에는 자체 토론이 있습니다. 사용자가 문제를 구독하거나, GitHub가 사용자가 만든 문제를 자동으로 구독할 수 있습니다. |
