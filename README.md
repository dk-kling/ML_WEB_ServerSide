<h1 align="center">
  <strong>React - Django</strong>
</h1>

<h3 align="center">
    <strong>ML-WEB</strong><br>
</h3>
<h3 align="center">
  Django와 React 연동 <br>
<h3>

<h2>
  <br><br>
  구성
</h2>

<br>
  <h3> 📋 개요 </h3>
<br>
<p>
  Django는 API를 Frontend로 데이터 전달<br>
  React는 전달받은 데이터로 Frontend 구성
  <br><br>
</p>

<br>
  <h3> 📋 django-rest-framework (DRF) API </h3>
<br>
<p>
  데이터를 다루는 별도의 API 서버 생성<br>
  Serializer는 말 그대로 직렬화하는 클래스로서 사용자의 DB안에 사용자 프로필 사진, 이메일, 이름, 성별이 있다고 가정하면, 사용자 모델 인스턴스를 JSON형태 혹은 Dictionary형태로 직렬화 가능 <br>
  -> Naver Clova Face Recognition API의 자료 형태와 호환이 좋을 것으로 예상
  <br><br>
</p>

<br>
  <h3> 📋 CORS (Cross-Origin Resource Sharing) </h3>
<br>
<p>
  분리된 django 서버와 react 서버의 Cross-Domain Issue 해결
  <br><br>
</p>

<br>
  <h3> 📋 Start </h3>
<br>

  ```
  git clone "this repository"
  cd react_frontend
  git submodule init
  git submodule update
  npm install
  cd ..
  pip install -r requirements.txt
  python manage.py runserver react
  ```

<br>
<br>
<h4 align="center">
  💻 Projected by 💻 <br>
</h4>
<h5 align="center">
  <a href="https://github.com/dk-kling">
    dk_kling <br>
  </a>

  <a href="https://github.com/jae-yong-2">
    jae-yong-2 <br>
  </a>

</h5>
