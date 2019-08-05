# 변경 제안 및 리포지토리에서 공동 작업

GitHub를 사용하면 당신이 관심 있는 과정에서 다른 Microsoft Learning 사용자와 손쉽게 공동 작업을 할 수 있습니다. 

본인의 랩 자료 사본을 수정한 후 변경 내용을 Microsoft Learning에 제출하여 업데이트를 통합할 수 있습니다. 다음 경우에 랩 자료를 수정할 수 있습니다.

- 랩에서 오류가 발견된 경우. 

- 랩이 생성된 후 UI가 변경된 경우. 

- 랩에 개선이나 수정이 필요하다고 생각되는 경우.

랩 자료를 수정하려면 리포지토리를 분기하고, 분기에서 업데이트한 후 끌어오기 요청을 주(마스터) 분기로 제출해야 합니다. 이렇게 하면 Microsoft Learning 직원, 그리고 다른 MCT 및 GitHub 사용자가 변경 내용을 리뷰하고 댓글을 달 수 있습니다. 

다른 사용자의 변경 내용을 리뷰하고 댓글을 달 수 있으며, 이후 Microsoft Learning 직원이 이러한 변경 내용을 승인하고 마스터 분기에 통합합니다. 이 작업은 변경이 발생한 리포지토리를 감시하는 모든 사용자에게 알려줍니다.

## 리포지토리 분기 만들기

1.	Internet Explorer에서 GitHub의 리포지토리로 이동합니다.

1.	**Branch : branchname** 을 클릭한 후 **Branches** 목록에서 복사할 분기를 선택합니다.

    > **참고**:	하나의 분기만 있는 경우 **Branch** 드롭다운 목록에 **Branch: master** 가 표시되고, 선택할 수 있는 유일한 분기는 **master** 가 됩니다. 

3.	빈 텍스트 상자에 생성할 분기 이름을 입력합니다.

4.	**Create branch: new branch name** 이 표시되면 클릭합니다.

분기를 만든 후 파일을 로컬 리포지토리에 복제하고, 컴퓨터에서 업데이트한 후 GitHub Desktop에서 변경 내용을 확인합니다. Markdown 또는 다른 텍스트 파일로 작업 중이라면 GitHub에서 편집한 후 온라인으로 변경 내용을 확인할 수 있습니다.

## 리포지토리 분기 삭제

1.	Internet Explorer에서 GitHub의 리포지토리로 이동합니다.

2.	***n* branches** 를 클릭합니다. 여기서 ***n***은 기존 분기의 개수입니다.

3.	**Branches** 페이지의 삭제할 분기 행에서 **Delete this branch** 아이콘을 클릭합니다.

## GitHub Desktop을 사용하여 변경 내용을 커밋합니다.

1.	**GitHub Desktop** 을 엽니다.

2.	변경 내용이 포함된 리포지토리를 선택한 후 **Changes** 을 클릭합니다.

3.	커밋할 변경 내용을 선택한 후 **Summary** 텍스트 상자에 좀 더 자세하게 변경 내용을 입력합니다.

4.	필요한 경우, **Description** 텍스트 상자에 좀 더 자세하게 변경 내용을 입력합니다.

5.	**Commit to master** 을 클릭한 후 **Sync** 를 클릭하여  로컬 변경 내용을 온라인 리포지토리에 밀어 넣습니다.

## 파일 편집 및 온라인 리포지토리에서 변경 내용 커밋:

1.	브라우저에서 **GitHub** 의 해당 리포지토리로 이동한 후 편집할 파일을 선택합니다.

2.	**Edit this file** 아이콘을 클릭합니다.

3.	웹 페이지의 **Edit file** 탭에서 변경한 후 **Preview changes** 를 클릭하여 변경 내용을 커밋하지 않고 제안한 변경 내용을 봅니다.

4.	**Commit changes** 의 **Update *filename*** 텍스트 상자에서 간단한 변경 설명을 입력합니다.

5.	필요한 경우, **Add an optional extended description...** 텍스트 상자에서 좀 더 자세한 변경 설명을 입력한 후 **Commit changes** 을 클릭합니다.

## 끌어오기 요청 만들기:

1.	브라우저에서 **GitHub** 의 해당 리포지토리로 이동합니다.

2.	**Branch:branchname** 을 클릭한 후 **Branches** 목록에서 끌어오기 요청을 만들 분기를 선택합니다.

3.	필요한 경우, **New pull request** 을 클릭한 후, **Open a pull request** 페이지의 **Title** 텍스트 상자에 끌어오기 요청의 이름을 업데이트합니다.

4.	**Write** 탭의 **Leave a comment** 텍스트 상자에 제안한 변경의 설명을 입력한 후 **Create pull request** 를 클릭합니다.
