---
layout: post
title: 데이터 타입의 종류
subtitle: Variety of data type
description: >
  코어자바스크립트를 참조하여 작성한 글입니다.
sitemap: false
hide_last_modified: false
categories:
  - Dev
  - JavaScript
---

# 데이터 타입의 종류

자바스크립트의 데이터 타입에는 크게 **기본형(Primitive Type)**과 **참조형(Reference Type)** 두가지가 있습니다. 기본형은 할당이나 연산시에 복제되고 참조형은 참조된다고 알려져 있지만 둘 모두 복제를 합니다.
그럼 어떻게 기본형과 참조형으로 나누게 되는지 질문이 생깁니다. 여기서 기본형은 값이 담긴 주솟값을 바로 복제하고, 참조형은 값이 담긴 주솟값들로 이루어진 묶음을 가리키는 주솟값을 복제한다는 점이 다르기 때문에 구분하게 됩니다.

## 1. 기본형

> 종류로는 숫자(number), 문자열(string), 불리언(boolean), null, undefined 등이 있으며 ES6에서 심볼(symbol)이 추가되었습니다.

## 2. 참조형

> 종류로는 객체(object)가 있고, 배열(Array), 함수(Function), 날짜(Date), 정규표현식(RegExp) 등과 ES6에서 추가된 Map, WeakMap, Set, WeakSet 등이 객체의 하위 분류에 속합니다.

<br><br>
![data type](/assets/drawio/dataType.png)
<br><br><br><br>
기본형은 불변셩(immutability)을 띕니다. 그렇다면 우리가 숫자 7을 담은 변수 a에 다른 숫자 10을 담으면 a의 값은 10으로 변하게 되는데 어떤 의미에서 불변성을 띈다고 하는거지? 라는 의문이 듭니다.
이 불변성을 잘 이해하기 위해선 대략적으로 메모리와 데이터에 대한 지식과 '식별자'와 '변수'의 개념을 구분할 수 있어야 하기에 다음 글에서 더 깊이 다뤄보도록 하겠습니다.
