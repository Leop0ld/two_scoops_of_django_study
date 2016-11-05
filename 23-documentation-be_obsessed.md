23장. 문서화에 집착하자
=====

# Index
- [파이썬 문서에 rst 이용하기](#파이썬-문서에-rst-이용하기)
- [rst로부터 스핑크스를 이용하여 문서 생성하기](#rst로부터-스핑크스를-이용하여-문서-생성하기)
- [어떤 문서들을 작성해야 하는가](#어떤-문서들을-작성해야-하는가)
- [문서화에 대한 자료](#문서화에-대한-자료)
- [Markdown](#Markdown)
- [위키와 다른 문서화 방법들](#위키와-다른-문서화-방법들)

## 파이썬 문서에 rst 이용하기

최근 경향을 보면 reStructuredText를 이용해서 문서 작성을 많이 하는 것 같다라고 말하고 있다(~~나는 이 글을 작성할 때 Markdown을 사용했...~~)
핵심 명령을 간추려보겠다.

```rst
각 섹션의 헤더
============

**강조(Bold)**

*이탤릭(italic)*

기본 링크: https://djangoproject.com
구문에 링크 달기: 'Django DOCUMENTATION'_

.. _Django DOCUMENTATION: https://djangoproject.com

서브 섹션의 헤더
-------------

#) 번호를 가진 리스트 아이템

#) 두 번째 아이템

* 첫 번째 목록 기호

* 두 번째 목록 기호

  * 들여 쓴 목록 기호

  * 들여 쓴 상태에서 줄 바꾸기


코드 블록::
    def like():
        print('I like it!')

    def i in range(10):
        like()

파이썬 코드 블록(highlighting을 위해서는 pygments가 필요):

code-block:: python
    # pip install pygments

    for i in range(10):
        print(i)

자바스크립트 코드 블록(highlighting):

code-block:: javascript
    console.log("Don't use alert().");
```

## rst로부터 스핑크스를 이용하여 문서 생성하기

## 어떤 문서들을 작성해야 하는가

## 문서화에 대한 자료

## Markdown

## 위키와 다른 문서화 방법들
