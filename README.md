# 커머스 과제

## 주요 기능

### 1. 상품 검색 기능
- **기능 요약**: 사용자가 입력한 키워드로 상품 목록을 검색.
- **요구 사항**:
  - 상품명, 카테고리, 가격대별 검색 필터 제공.
  - 검색 결과는 페이징 처리.
  - 정렬 옵션(가격순, 인기순 등) 제공.

### 2. 장바구니 기능
- **기능 요약**: 사용자가 선택한 상품을 장바구니에 추가, 수정, 삭제.
- **요구 사항**:
  - 장바구니에 상품 추가 시 수량 및 옵션 지정 가능.
  - 상품 수량 변경 및 삭제 가능.
  - 장바구니 상태는 사용자별로 관리.

### 3. 로그인/로그아웃에 따른 장바구니 접근 허가
- **기능 요약**: 로그인 상태에서만 장바구니에 접근 가능.
- **요구 사항**:
  - 비로그인 시 장바구니 접근 시도 시 로그인 화면으로 리다이렉트.
  - 세션 또는 토큰 기반 인증 시스템 활용.

### 4. 회원 기능
- **회원 관리**:
  - 회원가입, 로그인, 로그아웃.
- **상품 관리** (관리자용):
  - 상품 등록, 수정, 삭제.
