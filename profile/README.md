# Furry_Friend

# 💡 주제
- **애완동물 관련 물품을 거래하는 중고 거래 플랫폼**

# ✍🏻 요약

[애완동물들과 더불어 살아가기]

 최근 MZ 세대에 들어서면서 점점 애완동물들을 키우는 사람들이 많아지고 있습니다. 그래서 애완동물과 더불어 살아가기 위해 필요한 물품들을 거래하는 사이트를 만들어 사용하지 않는 애완 용품들을 거래할 수 있는 플랫폼을 개발하려고 합니다.

# ⭐ 주요 기능
- **인증/인가**
    - Spring Cloud Gateway를 통해 라우팅 및 토큰 검증.
    - Oauth2와 JWT를 이용한 인증/인가.
- **상품 서비스**
    - 판매 상품을 사용자가 조회, 등록, 수정 삭제할 수 있음.
    - 상품에 대한 댓글을 작성하고 삭제가 가능.
    - 중고 거래 물품을 찜해둘 수 있음.
    - 상품 검색 및 카테고리 선택.
- **채팅 서비스**(개발 중)
    - WebSocket과 Stomp(pub/sub)를 사용해 채팅 기능 구현.
    - 조회 성능 향상을 위한 CQRS 도입 중.(진행 중)

# 🛠️  기술 스택
- Back End: Java 11, Spring Boot 2, Spring Security, Sprint Cloud Gateway, MySQL
- FrontEnd: TypeScript, Next.js, Tailwindcss

# ⚱️ 아키텍처
`MicroService Architecture`
![image](https://github.com/youngsoosoo/Furry_Friend_v3/assets/87405853/a6f8814c-a782-4d4c-8353-0116e8cefe6a)

# 🔜 방향성
- 채팅 서비스 도입(미개발)
  - Kafka를 통해 채팅 서비스를 개발해 나갈 예정
  - 데이터 처리할 때 CQRS 패턴을 도입할 예정

# 👨🏻‍💻 팀
<table>
  <tbody>
    <tr>
      <tr>
        <td align="center">FE</td>
        <td align="center">Ops/BE</td>
      </tr>
      <tr>
      <td align="center"><a href="https://github.com/kkukileon"><img src="https://avatars.githubusercontent.com/u/102274941?v=4" width="100px;" alt=""/></td>
      <td align="center"><a href="https://github.com/youngsoosoo"><img src="https://avatars.githubusercontent.com/u/87405853?v=4" width="100px;" alt=""/></td>
      </tr>
      <tr>
      <td align="center"><a href="https://github.com/kkukileon">다익</td>
      <td align="center"><a href="https://github.com/youngsoosoo">용수</td>
      </tr>
    </tr>
  </tbody>
</table>
