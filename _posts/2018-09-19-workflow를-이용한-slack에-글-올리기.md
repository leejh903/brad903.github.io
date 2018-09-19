---
layout: post
title: workflow를 이용한 Slack에 글 올리기
tags: [코드스쿼드, 출입문, slack]
---

안녕하세요, Brad입니다. 저의 블로그의 첫 글을 공부 내용이 아닌 것으로 시작하게 되었네요. 하하.. 평소 코드스쿼드에서 출입문을 여는 방식에 대하여 큰 불편함을 느끼진 않았지만 뭔가 좀 더 편하게 열 수 있는 방법은 없을까 생각하곤 하였습니다.

그러다가 문득 자기 전 아이폰의 [Workflow](https://itunes.apple.com/us/app/shortcuts/id915249334?mt=8)(iOS 버전 12이상 Shortcuts) 앱이 떠올랐는데요. slack 같이 많은 사람들이 사용하는 어플이라면 당연히 채널에 글을 올리는 기능이 있지 않을까 하는 생각이 들었습니다. 역시나 찾아보니 있더라구요! 그래서 정말 간단하게 3분 안에 아이폰  workflow앱을 통해 버튼 하나로 코드스쿼드 출입문을 열 수 있는 방법을 같이 공유하고자 합니다 :)

간단하게 진행할 순서를 아래와 같습니다.

1. [Workflow](https://itunes.apple.com/us/app/shortcuts/id915249334?mt=8) 어플을 다운 받는다(무료)
2. Workflow 어플 안에서 Slack을 연동한다
3. Workflow 만든다

<video class='featured wide' controls poster='/assets/img/posts/2018-09-19-video-thumbnail.png' width='1080px' height='608px' preload='auto'>
  <source src='{{ site.baseurl }}/assets/video/ScreenRecording_Workflow.MOV' type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'>
</video>

어플 다운로드 후 Workflow 안에서 Slack 연동을 해야합니다. 그 방법에 관해선 [Slack 홈페이지](http://workflow.is/slack)를 참고하시면 될 것 같습니다.

마지막으로 Slack 연동까지 끝냈다면 "열어"라는 텍스트를 Slack 채널로 전달해야 하는데요. 이는 Actions 탭에서 text를 검색으로 찾은 후 Workflow로 끌어와 추가하면 됩니다.  
혹시 위 내용이 이해가 안된다면 동영상을 참고해주세요!

저 같은 경우 아이폰 Widget에서 통하거나 애플워치의 Workflow 앱을 통해 이 Workflow를 이용하려고 합니다.