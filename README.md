# baecomm 프론트엔드 개발자 사전과제

### 1. 사용언어 및 패키지
React와 Typescript를 사용하여 개발
styling을 위해 styled-component를 사용
routing을 위해 react-router를 사용
상태 관리를 위해 redux를 사용
그 외 외부 패키지, 라이브러리 사용 안함

### 2. 그 외...
1) https://dummyjson.com/docs/products API를 이용하여 상품 데이터 검색, 상세 조회 가능
2) 상품 목록 페이지
- 검색어를 입력하고 검색을 누르거나 enter key를 입력하면 검색 결과 반영
- 검색 결과 상품 목록이 한 행에 2개씩 출력되며 한번에 10개의 상품 출력(검색 이전에는 all product를 보여줌)
- 각 상품 목록은 썸네일, 브랜드, 상품명, 가격을 보여주며 브랜드와 상품명은 한줄로 보여줌
- 품 목록에 마우스를 올리면 브랜드와 상품명의 글씨 색상이 변함
- 하단에 더보기 버튼이 존재하며 클릭 시 10개의 상품을 추가로 보여줌
- 더 보여줄 상품이 없으면 버튼은 표시안됨
3) 상품 상세 페이지
- 페이지 상단에 '목록으로 돌아가기'버튼이 있으며 클릭 시 상품 목록 페이지로 이동
- 상품 목록 페이지로 이동하면 검색어, 검색 결과, 스크롤 위치가 유지
- '목록으로 돌아가기' 버튼 아래에는 상품의 썸네일, 브랜드, 상품명, 가격, 상세설명, 기타 이미지가 표시
