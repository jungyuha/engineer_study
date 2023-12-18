# Ad-hoc

**기록 ✍️**

**author : jung yuha**

**first registered : 2023-09-12 Tue**

**last modified : 2023-09-12 Tue**

## 구조

1. **Ad-hoc Network의 개요**
   * 가. Ad-hoc 네트워크의 정의
2. **Ad-Hoc Network의 활용 환경 및 요소기술**
   * 가. Ad-hoc Network의 활용 환경
   * 나. Ad-hoc Network의 요소 기술
   * 다. Ad-hoc 네트워크의 특징
   * 라. Ad-hoc Network 라우팅 프로토콜
3. **Ad-hoc 네트워크의 구조 및 Infrastructure 네트워크와의 기술 비교**
   * 가. Ad-hoc 네트워크의 구조
   * 나. Ad-hoc 네트워크와 유무선 네트워크 비교
4. **Ad-hoc Network Routing 기법간 비교**
5. **Ad-hoc Network의 기술 동향**
   * 가. Ad-hoc Network를 위한 무선 응용 기술
   * 나. 기존 네트워크 기술과의 연동을 통한 활용 방안

## 키워드

1. **Ad-hoc Network의 개요**
   *   가. Ad-hoc 네트워크의 정의

       <table data-view="cards"><thead><tr><th></th></tr></thead><tbody><tr><td><p><mark style="background-color:blue;"><strong>＃</strong></mark>통신인프라X</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>구축곤란상황</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>이동Node들</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>자율적 <mark style="background-color:blue;"><strong>＃</strong></mark>경로 <mark style="background-color:blue;"><strong>＃</strong></mark>의사소통</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>네트워크토폴로지<mark style="background-color:blue;"><strong>＃</strong></mark>동적 <mark style="background-color:blue;"><strong>＃</strong></mark>기반구조X 네트워크</p></td></tr></tbody></table>
2. **Ad-Hoc Network의 활용 환경 및 요소기술**
   * 가. Ad-hoc Network의 활용 환경
     *

         | 활용 환경                                                                                                                                                                                                                                                                                                   | 활용 사례                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
         | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
         | <p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>통신인프라X</strong></p><p><mark style="background-color:blue;"><strong>＃</strong></mark>구축곤란 <mark style="background-color:blue;"><strong>＃</strong></mark>상황 <mark style="background-color:blue;"><strong>＃</strong></mark>조건</p> | <p> <mark style="background-color:blue;"><strong>＃</strong></mark>전쟁 <mark style="background-color:blue;"><strong>＃</strong></mark>재난 <mark style="background-color:blue;"><strong>＃</strong></mark>구조 <mark style="background-color:blue;"><strong>＃</strong></mark>화재 <mark style="background-color:blue;"><strong>＃</strong></mark>태풍</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>광범위범위 <mark style="background-color:blue;"><strong>＃</strong></mark>센싱 <mark style="background-color:blue;"><strong>＃</strong></mark>환경오염 <mark style="background-color:blue;"><strong>＃</strong></mark>산불감시</p>                                                                                                                                                                                                                                                                             |
         | <mark style="background-color:blue;">**＃**</mark>기존기간망 <mark style="background-color:blue;">**＃**</mark>**한계보완**                                                                                                                                                                                        | <p><mark style="background-color:blue;"><strong>＃</strong></mark>특정조건하 <mark style="background-color:blue;"><strong>＃</strong></mark>이동Node <mark style="background-color:blue;"><strong>＃</strong></mark>컨퍼런스 <mark style="background-color:blue;"><strong>＃</strong></mark>공항</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>홈네트워크 <mark style="background-color:blue;"><strong>＃</strong></mark><strong>이기종Node간</strong> <mark style="background-color:blue;"><strong>＃</strong></mark>통신지원</p><p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>멀티캐스팅</strong>(<mark style="background-color:blue;"><strong>＃</strong></mark>한번의송신 ,<mark style="background-color:blue;"><strong>＃</strong></mark>여러동시전송)</p><p><mark style="background-color:blue;"><strong>＃</strong></mark>화상 회의 <mark style="background-color:blue;"><strong>＃</strong></mark>미팅</p> |
   * 나. Ad-hoc Network의 요소 기술
     *

         | 활용환경                                                       | 설명                                                                                                                                                                                                                                                                                                                                                                                                                                      | 필요기술                                                                                                                                                                                          |
         | ---------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
         | <mark style="background-color:blue;">**＃**</mark>**라우팅**   | <p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>잦다 </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>참여 </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>탈퇴</strong></p><p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>자율성 </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>보장</strong></p> | <p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>브로드캐스트라우팅</strong></p><p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>멀티캐스트라우팅</strong></p> |
         | <mark style="background-color:blue;">**＃**</mark>**저전력**   | <p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>이동성 </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>전력공급</strong></p><p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>제한성 </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>지원</strong></p>                                                                                | <mark style="background-color:blue;">**＃**</mark>**차세대배터리**                                                                                                                                   |
         | <mark style="background-color:blue;">**＃**</mark>**멀티링크**  | <p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>한Node </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>동시</strong></p><p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>여러Node</strong></p>                                                                                                                                                               | <mark style="background-color:blue;">**＃**</mark>**멀티링크**                                                                                                                                     |
         | <mark style="background-color:blue;">**＃**</mark>**기기소형화** | <p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>센서 </strong><mark style="background-color:blue;"><strong>＃</strong></mark><strong>휴대단말기</strong></p><p><mark style="background-color:blue;"><strong>＃</strong></mark><strong>소형화</strong></p>                                                                                                                                                                  | <mark style="background-color:blue;">**＃**</mark>**ASIC반도체**                                                                                                                                  |
   * 다. Ad-hoc 네트워크의 특징
   * 라. Ad-hoc Network 라우팅 프로토콜
3. **Ad-hoc 네트워크의 구조 및 Infrastructure 네트워크와의 기술 비교**
   * 가. Ad-hoc 네트워크의 구조
   * 나. Ad-hoc 네트워크와 유무선 네트워크 비교
4. **Ad-hoc Network Routing 기법간 비교**
5. **Ad-hoc Network의 기술 동향**
   * 가. Ad-hoc Network를 위한 무선 응용 기술
   * 나. 기존 네트워크 기술과의 연동을 통한 활용 방안

|   |   |   |
| - | - | - |
|   |   |   |
|   |   |   |
|   |   |   |

## 상세
