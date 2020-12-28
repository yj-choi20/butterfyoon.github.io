---
title : "Color Space"
category : jekyll update
date: 2020-12-17
___


conda를 깔았는데, mac의 terminal에서 conda 실행 시, "zsh conda command not found" 발생
경로 설정이 잘못된 것으로 경로 수정으로 해결

여러번 깔았다 지웠다 난리를 폈는데도 해결이 안되서 찾아보니 새로운 맥북의 경로 문제인듯!

[해결법]
1. %export PATH="/opt/anaconda3/bin:$PATH"
2. terminal 종료
3. % export PATH="/opt/anaconda3/bin:$PATH"
   % conda
   
끗!
