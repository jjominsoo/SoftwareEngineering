# Community
유저들이 실제로 여러가지 기능들을 이용할 수 있는 커뮤니티를 구현하는 모듈이다.

# Function
### Personal Information Function ( 개인정보 기능 )
* 개인정보와 관련된 내용을 다룬다

  1. 회원가입/정보수정/회원탈퇴 
  >커뮤니티 서비스 이용을 위한 계정에 관련된 기능들이다
  2. 로그인/로그아웃
  >로그인/로그아웃 기능을 제공한다
  3. 아이디/비밀번호찾기
  >아이디/비밀번호 찾는 기능을 제공한다
  4. 등록 게시물 수정/확인/삭제
  >자신이 등록한 음원에 대한 기능들을 제공한다
<hr/>

### Community Configuration Function ( 커뮤니티 구성 기능 )
* 커뮤니티 서비스에 대한 내용을 다룬다

  1. 공지사항 게시판
  > 운영자들이 중요사항을 공지하는데 사용하는 게시판이다.
  2. 문의 게시판
  > 유저들과 운영진이 소통할 수 있는 게시판이다.
  3. 자유 게시판
  > 유저들과 유저들이 소통할 수 있는 게시판이다.
  4. 장르별 게시판
  > 장르별로 유저들과 유저들이 소통할 수 있는 게시판이다.
<hr/>

### Main Function ( 주요기능 )
* NFT를 활용한 음원등록에 관한 내용이다. [(NFT)](https://github.com/JaeHwanWO/SoftwareEngineering/tree/ntf_generator)

  1. 음원등록
  >핵심 기능으로, Simularity Analysis를 통과한 음원을 블록체인 노드에 패킷포장하여 업로드한다. 
  이 후 과반수의 블록체인노드들(음원등록자들)이 패킷에 대한 무결성 검사를 실시한다.
  이 두 과정들을 통과하면 블록체인노드에 추가된다.
  [Simularity Analysis](https://github.com/JaeHwanWO/SoftwareEngineering/blob/simularity_analysis/README.md)
  ( or 음원을 등록하는 기능이다. )
<hr/>

### Secondary Function ( 부차적기능 )
* 음악에 대한 다른 기능들을 다룬다.

  1. 음악검색
  > 등록된 음원을 조건부로 검색하는 기능을 제공한다. ( 가수별 검색, 나라별 검색, 장르별 검색 ... )
  2. 음악평가
  > 등록된 음원을 평가하고, 피드백을 제공하는 기능이다. ( 추천, 댓글 )
<hr/>

### List Function ( 리스트 기능 )
* 다양한 리스트에 대한 내용을 다룬다

  1. 관심음악
  > 음악평가에서 추천을 누른 아티스트의 음악들을 표시한다.
  2. 관련음악 리스트
  > 유저의 음악과 유사도가 높은 음악을 표시하는 리스트이다.
  3. 탑 리스트
  > 조회수가 많은 순서대로 나열해준다.
  4. 레코드 리스트
  > 특정 기록을 달성한 음악을 표시하는 리스트이다 ( 조회수 1등을 장기간 유지한 기록, 플레이시간이 제일 긴 기록 )
  5. 추천 리스트
  > 특정 기준에 따라 음악들을 추천해주는 리스트이다 ( 추천수가 많은 아티스트의 최신음악, 조회수가 급격히 올라가는 음악 )
  ( 알고리즘을 통한 유저들 맞춤 리스트를 제공한다 )
    
