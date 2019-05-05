# 함수형 프로그래밍과 Javascript ES6+ 응용편

## 강의 목록

1. 이터러블 프로그래밍 혹은 리스트 프로세싱 (Lisp)
    1. 들어가며
    2. 홀수 n개 더하기
    3. if를 filter로
    4. 값 변화 후 변수 할당을 map으로
    5. break를 take로
    6. 축약 및 합산을 reduce로
    7. while을 range로
    8. 효과를 each로 구분
    9. 추억의 별 그리기
    10. 추억의 구구단
2. 명령형 습관 지우기 - 만능 reduce? No!
    1. reduce + 복잡한 함수 + acc 보다 map + 간단한 함수 + reduce
    2. reduce 하나 보다 map + filter + reduce
    3. query, queryToObject
3. 안전한 합성에 대해
    1. map으로 합성하기
    2. find 대신 L.filter 써보기
4. 객체를 이터러블 프로그래밍으로 다루기
    1. values
    2. entries
    3. keys
    4. 어떠한 값이든 이터러블 프로그래밍으로 다루기
    5. object
    6. mapObject
    7. pick
    8. indexBy
    9. indexBy 된 값을 filter 하기
5. 객체지향과 함께 사용하기 - 사용자 정의 객체를 이터러블 프로그래밍으로
    1. Map, Set, NodeList
    2. Model, Collection 클래스 만들어서 이터러블 프로토콜 지원하기
    3. Product, Products - 메서드를 함수형으로 구현하기
6. 이터러블 프로그래밍 함수 계층
    1. reduce 계열 함수 - groupBy, indexBy, countBy, partition
    1. map 계열 함수 - pluck, prices, ages, mapEntries, map+pick
    2. filter 계열 함수 - reject, compact
    4. take 계열 함수 - find, every, some, none
7. 시간을 이터러블로 다루기
    1. range와 take의 재해석
    2. take, takeWhile, takeUntil
    3. 일어나야할 일을 이터러블(리스트)로 바라보기
    4. 아임포트 결제 누락 스케쥴러 만들기
8. 커머스 서비스 데이터를 이터러블 프로그래밍으로 다루기
    1.
    2.
9. SNS 서비스 데이터를 이터러블 프로그래밍으로 다루기
    1.
    2.
10. 프론트엔드에서 함수형/이터러블/동시성 프로그래밍
    1. ES6 템플릿 리터럴 활용
    2. 이미지 목록 그리기
    3. 경고창 만들기 confirm, alert
    4. 경고창에서 Promise 활용
    5. 이미지 동시성 다루기
    6. 페이지 띄우기
11. SQL을 함수형/이터러블 프로그래밍으로 다루기
    1. 함수형 사고
    2. QUERY
    3. INSERT
    4. UPDATE
    5. IN, EQ
    6. partition 활용, 그리고 뒤로 미루기
12. map, filter, reduce, take 다시보기
    1. 위키피디아 페이지의 단어 새기
    2. 결국은 map, filter, reduce, take의 반복