# <span style="color: #3DA5F5;">내일의 집 UI 개발 (클론 코딩) </span>
* [사이트 링크 (미완성 작업중)]()
<br>
<hr>
# 프로젝트 정보
#####회사에 재직 중이었던 때, 웹 표준과 웹 접근성 그리고 HTML 마크업이 아닌 javascript에 대한 사용 빈도가 높았기에 취약하다고 생각한 부분을 채우기 위해 공부하는 프로젝트입니다.




<br>
# 참고 사항
#### 1. GNB
<br>
##### 로그인을 하지 않았을 경우 HTML

```html
<div class="button-group">
    <button class="gnb-icon-button is-search lg-hidden" type="button" aria-lable="검색창 열기 버튼">
        <i class="ic-search"></i>
    </button>
    <a href="/" class="gnb-icon-button" aria-lable="장바구니 페이지로 이동">
        <i class="ic-cart"></i>
    </a>
    <div class="gnb-auth sm-hidden">
        <a href="/">로그인</a>
        <a href="/">회원가입</a>
    </div>
</div>
```
<br>
##### 로그인 했을 경우 HTML

```html
<div class="button-group">
        <button class="gnb-icon-button is-search lg-hidden" type="button" aria-lable="검색창 열기 버튼">
            <i class="ic-search"></i>
        </button>
        <a href="/" class="gnb-icon-button sm-hidden" aria-lable="스크랩북 페이지로 이동">
            <i class="ic-bookmark"></i>
        </a>
        <a href="/" class="gnb-icon-button sm-hidden" aria-lable="나의 알림 페이지로 이동">
            <i class="ic-bell"></i>
        </a>
        <a href="/" class="gnb-icon-button" aria-lable="장바구니 페이지로 이동">
            <i class="ic-cart"></i>
            <strong class="badge">3</strong>
        </a>
        <button class="gnb-avatar-button sm-hidden" type="button" aria-label="내 정보 버튼">
            <div class="avatar-32">
                <img src="./assets/images/img-user-02.jpg" alt="프로필 사진">
            </div>
        </button>
</div>
```