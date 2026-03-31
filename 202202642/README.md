#202202642 
1. feature 브랜치는 어디서 분기해야할까? → develop                            
    - feature는 항상 develop에서 분기하고, 완료 후 다시 develop으로 merge       
  2. 작업을 완료 했다. PR을 어디로 Merge 요청 해야할까? → develop               
    - feature -> develop으로 PR                                               
  3. Master로 Merge가 된 작업에 대해 수정사항이 발생했다. 이때 사용해야하는     
  브랜치는? → hotfix
    - production(master)의 긴급 수정은 master에서 hotfix 브랜치를 분기하여 처리
