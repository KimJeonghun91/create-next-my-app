# Create Next App 커스텀

```tsx
const baseNextVersion = '14.1.2';
const nextRepository = 'https://github.com/KimJeonghun91/next-my-core';
```

### 개발

```bash
# 빌드
npm run build:pkg

# 테스트
npm run test:pkg

```

### 사용법

- npx <GitHub 사용자명>/<저장소명>

- yarn install
    
    몇몇 next 패키지가 npm 으로 설치되지 않기 때문에 yarn install이 필요.
    

### TODO

- [ ]  아키텍쳐 도입
    - FSD
        - https://emewjin.github.io/feature-sliced-design/?utm_source=substack&utm_medium=email
        - https://github.com/noveogroup-amorgunov/nukeapp
    - Atomic

- [ ]  디자인 시스템 및 디자인 패키지
    - [ ]  style/theme

- [ ]  npm install 404 에러