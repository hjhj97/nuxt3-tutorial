# Nuxt3 Tutorial

## Routing

## Components

## Layouts

## Assets

#### `assets/` Directory

- `vite`, `webpack` 같은 번들러를 통해서 processing 과정을 거친다.
- processing 과정을 통해서 성능 최적화를 할 수 있다.
- processing 과정을 통해 파일이름이 변경된다.(직접 접근 방지)
- `~/assets/` 경로를 통해서 접근할 수 있다.

#### `public/` Directory

- processing 을 거치지 않기 때문에 원본 파일 그대로 유지된다.
- 정적 파일로 서빙된다. (직접 접근 가능)
- `/` 경로를 통해서 접근할 수 있다.

## Plugins

`NuxtApp` 인스턴스에 함수를 추가할 수 있음

## Middleware

- `defineNuxtRouteMiddleware((to,from)=>{})` 함수를 통해 미들웨어(라우트가드)를 설정할 수 있다.
- 미들웨어의 파일이름 suffix에 `global`을 붙이면 모든 페이지에서 작동하게끔 할 수 있다. (ex.`auth.global.ts`)

## State Management

- 전역상태를 관리하는 방법으로는 `useState()`를 사용하거나 `pinia` 라이브러리를 사용할 수 있다.
- 간단한 상태관리로는 `useState()`를, 복잡한 상태에서는 `pinia`를 사용한다.

## Reference

https://www.youtube.com/watch?v=ww94Jvi8JJo&t=1210s
