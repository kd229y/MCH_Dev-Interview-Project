<template>
  <div class="introduction">
    <header class="intro-header">
      <h2>自我介紹</h2>
      <p>
        Hi，我是楊豈東，目前就讀交大資工系大一， 去年參加過梅竹黑客松
        ，覺得辦得很好，今年想來開發部學習，希望能遇到志同道合的朋友，在軟體開發的路上一起學習。
        
        
        <img src="/images/self.jpg"alt="self Image"class="self-image">

      </p>
      
    </header>
    <section class="about-section">
      <h3>個人資訊補充</h3>
      <ul>
        <li>我很菜</li>
        <li>喜歡打桌球</li>
        <li>喜歡看動漫</li>
      </ul>
      
    </section>
  </div>
</template>


<style scoped>
.introduction {
  padding: 40px 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.intro-header {
  background-color: #f5f5f5;
  padding: 40px;
  border-radius: 10px;
}

.self-image {
  width: 300px; /* 設定寬度 */
  height: auto; /* 讓高度自適應 */
  display: block;
  margin: 0 auto; /* 讓圖片水平置中 */
  
}


.intro-text h2 {
  font-size: 2rem;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

.contact-button {
  padding: 10px 20px;
  background-color: #656d73;
  border: none;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
}

.contact-button:hover {
  background-color: #36383a;
}

.about-section {
  margin-top: 40px;
  padding: 0 40px;
}

.about-section h3 {
  font-size: 1.6rem;
  margin-top: 20px;
  margin-bottom: 10px;
}

.about-section p {
  font-size: 1rem;
  line-height: 1.6;
}
</style>
