# ImageChatBubbleApp

- RoundedCornerShape 가 적용된 카카오톡 묶음 이미지 말풍선 compose ui 구현
- Development of Kakao Talk Bundle Image with Compose ui RoundedCorner Shape

## Overview

- 묶음 이미지 전송시 말풍선 ui 구현
- 묶음 이미지에 대하여 모서리에 위치하는 이미지에 대해서만 BIG_RADIUS 적용 그 외의 이미지에 대해서는 SMALL_RADIUS 적용 

- 1장 일 경우 -> wrapContent && maxWidth = 250.dp
- 2장, 4장 묶음 일 경우 -> height = 124.dp, width = 250.dp  
- 3장, 5~N장 묶음 일 경우 -> height = 80.dp, width = 250.dp 


https://user-images.githubusercontent.com/59822833/163770894-5700fa74-4d01-4cf4-a0a5-d6800e387d9b.mp4


## Description

- UI
  - [Compose](https://developer.android.com/jetpack/compose) declarative UI framework
  - [Material design](https://material.io/design)
- Tech/Tools
  - [Kotlin](https://kotlinlang.org/) 100% coverage
  - Jetpack
    - [Compose](https://developer.android.com/jetpack/compose)
    - [Coil](https://coil-kt.github.io/coil/compose/) image loader
