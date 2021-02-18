# Learning Svelte

## 00. Summary

[Svelte Homepage](https://svelte.dev/)

- Svelte의 특징

  - Write less code

    - 높은 가독성 유지, 개발 시간 단축
    - 쉬운 리팩토링, 쉬운 디버깅
    - 더 작은 번들(SPA 최적화), 낮은 러닝 커브

  - No virtual DOM

    - No Diffing, No Overhead

      - *Diffing: 가상DOM끼리 비교해서 갱신해줄 데이터를 찾음

      - *Overhead: 어떤 처리를 위해 들어가는 간접적인 시간이나 메모리 등

    - 빠른 성능(퍼포먼스)

  - Truly reactive

    - Framework-less Vanilla JS
    - Only use  'devDependencies'
    - 명시적 설계(창의적 작업)

- 단점
  - 낮은 숙성도(작은 생태계)
  - CDN 미제공
  - IE 지원X