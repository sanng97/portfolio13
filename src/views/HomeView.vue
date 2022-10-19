<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="moon.jpg" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="blue--text text--darken-4 top">
            안녕하세요! 저의 포트폴리오에 오신걸 환영합니다!
          </h5>
          <h1 class="black--text">명지전문대학 정보통신공학과 박상언</h1>
          <p class="grey--text">
            안녕하세요! 저는 명지전문대학 정보통신공학과 4학년 전공심화중에 있는
            박상언 입니다. 1학년부터 3학년 까지는 '서일대학교'에서
            정보통신공학과를 마친 후 전공심화를 하기위해 '명지전문대'로
            전공심화를 하러 공부하러 왔습니다. <br />
            "우리가 출발한 곳은 선택할 수 없지만 그곳에서 어디를 향해 갈지는
            선택할 수 있다." 제가 선택한 길을 걸어와서 지금의 제가 있다고
            생각합니다.
            <br />
            앞으로도 선택의 길을 걷기위해 저는 한걸음 씩 나아갈 것 입니다!
            <br />
          </p>
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-controller</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Game</h3>
                  <p class="black--text ml-3 mt-6">
                    저는 게임을 자주하는 편입니다 ! <br />그 중에서도
                    '오버워치'를 매우 즐겨하는데요!
                    <br />
                    이 게임에 대해 궁금하시면 더보기를 클릭하여 눌러주세요 !
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                    <v-btn
                      :href="`https://overwatch.blizzard.com/ko-kr/`"
                      target="_blank"
                    >
                      <span>click</span>
                      <v-icon>mdi-alpha- go -circle</v-icon>
                    </v-btn>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="" x-large class="ml-3" dark
                    >mdi-music-note-eighth</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Music recommendation</h3>
                  <p class="black--text ml-2 mt-3">
                    <br />'Jason Derulo - Take You Dancing' <br />
                    제가 제일 좋아하는 팝송 중 하나 입니다! <br />
                    하루에 한번은 꼭 듣는 팝송인데요. 이 노래를 들으면 하루를
                    <br />
                    즐겁게 시작할 수 있어서 듣습니다! 한번 들어보세요 !
                  </p>
                  <v-btn color="" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                    <v-btn
                      :href="`https://www.youtube.com/watch?v=vC8qJfVYxZY`"
                      target="_blank"
                    >
                      <span>click</span>
                      <v-icon>mdi-alpha- go -circle</v-icon>
                    </v-btn>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-book-open-page-variant</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Reading</h3>
                  <p class="black--text ml-3 mt-6">
                    최근에는 책을 읽기 시작했는데요!<br />
                    하나씩 읽어보면서 추천하고 싶은 책이 생겼습니다!
                    <br />
                    제 기준 베스트셀러니까 한번 읽어주세요 !
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                    <v-btn
                      :href="`https://search.shopping.naver.com/book/catalog/34106011618?query=20%EB%8C%80%20%EC%B1%85%20%EC%B6%94%EC%B2%9C&NaPm=ct%3Dl9bd1h94%7Cci%3Df400afae31831674ee86f51f75abaec470319d08%7Ctr%3Dboksl%7Csn%3D95694%7Chk%3D87079f8a13037e411d5ffbb56ce19040c70cce80`"
                      target="_blank"
                    >
                      <span>click</span>
                      <v-icon>mdi-alpha- go -circle</v-icon>
                    </v-btn>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="10" class="mt-4">
                <div class="child1">
                  <h1 class="black--text text--darken-5 mt-5 number"></h1>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="black--text text--darken-4">Birthday</h1>
                        <p class="white--text">1997.04.30</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="black--text text--darken-4">blood groups</h1>
                        <p class="white--text">O형</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="black--text text--darken-4">MBTI</h1>
                        <p class="white--text">ISFP</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="black--text text--darken-4">gender</h1>
                        <p class="white--text">Women</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about">
         <v-col cols="12" sm="12">
       
        <div class="d-flex justify-center mb-6"></div>
      </v-col>
        <div class="pre">
            <v-row>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="ubi.jpg" height="200px" cover> </v-img>
                <v-card-title>  ꕤ 'ubi' ꕤ  </v-card-title>
                <v-card-subtitle class="text-yellow"
                  >By 2018 ubi | 04 03 best</v-card-subtitle
                >
               
                <v-card-text>
                  중소기업으로 외부실습을 나갈 때 배우고 <br/>사용했던 프로그램 입니다.
          <br />
          이 프로그램으로 입력값을 넣고 <br/>데이터베이스를 사용하여 제가 직접 디자인
          샘플을 받고 디자인 해서 더욱 의미가 있었습니다.
          <br />
                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="650" height="">
                <v-img src="use.jpg" height="200px" cover> </v-img>
                <v-card-title>  ꕤ '회로이론' ꕤ  </v-card-title>
                <v-card-subtitle class="text-yellow"
                  >By 2018 회로이론 | 08 09 best</v-card-subtitle
                >
                
                <v-card-text>
  3학년때 1년동안 회로수업을 받으면서 회로도를 보며 제가 직접 전선을 꼽는 재미가 <br/>있었고 비록 처음에는 헤매고 부족했지만 
 <br/>수업을 열심히 들어서 적극적으로 참여하여 많이 배워서 재미를 붙일 수 있었으며<br/> 회로수업이 매력적으로 다가왔습니다!

                </v-card-text>
              </v-card>
            </v-col>
            <v-col cols="12" sm="4">
              <v-card class="mw-auto" max-width="3000" height="">
                <v-img src="adi.jpg" height="200px" cover> </v-img>
                <v-card-title>  ꕤ '아두이노' ꕤ  </v-card-title>
                <v-card-subtitle class="text-yellow"
                  >By 2018 아두이노 | 07 10 best</v-card-subtitle
                >
               
                <v-card-text>
       외부 침입을 감지하여 스마트폰과 연동하여 이에 대응하는 시스템인 침입
          감지 <br/>시스템을 완성해 보았습니다.
          <br />
          모션 센서를 이용해 움직임을 감지하여 <br/>음성 녹음 모듈을 통해
          
          침입 경고 메시지를 전달하고 Red LED를 점멸하여 침입을 경고함
          <br />

                </v-card-text>
              </v-card>
            </v-col>   
          </v-row>
          </div> 
        </v-col>
        
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="10">
                  <h1 class="black--text">
                    💛 저의 sns를 소개합니다 ! <br />
                    💛 Let me introduce my SNS
                  </h1>
                  <p class="grey--text">
                    마지막으로 저의 sns를 소개합니다 ! 포트폴리오를 봐주셔서
                    감사합니다 ! <br /><br />
                  </p>
                </v-col>
                <v-col cols="2">
                  <v-btn
                    :href="'https://blog.naver.com/rty6258'"
                    target="_blank"
                    color="#FF1976"
                  >
                    <span>Blog</span>
                    <v-icon>mdi-alpha- go -circle</v-icon>
                  </v-btn>
                  <br />
                  <br />
                  <v-btn
                    :href="'https://www.facebook.com/profile.php?id=100007944960313'"
                    target="_blank"
                    color="#FF1976"
                  >
                    <span>facebook</span>
                    <v-icon>mdi-alpha- go -circle</v-icon>
                  </v-btn>
                </v-col>
              </v-row>
            </div>
          </div>
        </v-col>
        <br />
        <br />
      </v-row>
      <br />
    </v-container>
    <br />
    <Footer />
    <br />
  </v-app>
</template>
   

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";
export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
};
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -50px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #fea4be,
    #181818 50%,
    #111111 50%,
    #fbb8ef 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: hsl(0, 0%, 100%);
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #ffffff;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 230px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #f677a2;
}
.bgColor2 {
  background-color: #d36767;
}
.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
.pre {
  width: 200%;
  height: 550px;
  text-align: center;
  padding: 0 200px;
  background-color: #f5f5f5;
}
</style>