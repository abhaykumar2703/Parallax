<!DOCTYPE html>

<style>
    * {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#Wrapper {
  height: 100vh;
  overflow-x: hidden;
  overflow-y: auto;
  perspective: 10px;
}

.container {
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  transform-style: preserve-3d;
  z-index: -1;
}

.background {
  transform: translateZ(-40px) scale(5);
}

.foreground {
  transform: translateZ(-20px) scale(3);
}

.background,
.foreground {
  position: absolute;
  height: 100%;
  width: 100%;
  z-index: -1;
  object-fit: cover;
}

h1 {
  position: absolute;
  top: 20rem;
  left: 50%;
  transform: translateX(-50%);
  font-size: 7rem;
  letter-spacing: 2.5px;
  background: -webkit-linear-gradient(#eee, #333);
  text-shadow: 0, 0, 10px rgba(0, 0, 0, 0.3);
}

section {
  background-color: rgb(45, 45, 45);
  color: yellow;
  padding: 5rem 0;
}

.bg1 {
  background-image: url('https://images2.giant-bicycles.com/b_white,c_pad,h_1000,q_80,w_1920/ewoxzxceozrsnnqoskha/Banner_101Skills.jpg') ;
}

.bg2 {
  background-image: url('https://assets.website-files.com/615092d0991b1c05d15b1a0d/630e001e1a3da4335930fc50_is-hang-gliding-illegal%253F.jpeg');
}

.bg3 {
  background-image: url('https://res.cloudinary.com/manawa/image/upload/f_auto,c_limit,w_3840,q_auto/articles/3104/surfing-wipeout');
}

.secheading {
  font-size: 5rem;
  padding: 0 10rem;
}

.text {
  font-size: 1.5rem;
  padding: 0 10rem;
  margin: 5rem 0;
}

.bg {
  position: relative;
  width: 100%;
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 500px;
}

.desc {
  position: absolute;
  padding: 0.5rem 1.5rem;
  top: 50%;
  left: 50%;
  transform: translateX(-50%) translateX(-50%);
  color: black;
  background-image: linear-gradient(yellow,red);
  font-size: 3.5rem;
  font-weight: 600;
}
.owner{
    background-image: linear-gradient(white,red);
    text-align: right;
    color: blue;
    font-size: 2rem;

}

</style>

<html>

  <head>

    <title>Parallax</title>
      <link rel="stylesheet" href="styles.css">

  </head>

  <body>

    <div id="Wrapper">
      <div class="container">
        <img src="https://img.redbull.com/images/c_limit,w_1500,h_1000,f_auto,q_auto/redbullcom/2018/04/18/3defc76b-795c-4cfa-a005-c2fabd43f6fb/adventure-travel-cliff" class="foreground" />
        <h1>ADVENTURE</h1>
      </div>
      <section>
        <h2 class="secheading">
          Adventure Time
        </h2>
        <p class="text">
          jhiuhnvj rhehceyur347t3 tc8y8n3ybj hjithjj Wix.com Ltd. is an Israeli software company, publicly listed in the US, that provides cloud-based web development services. It allows users to create HTML5 websites and mobile sites through the use of online drag and drop tools. Wikipedia
          <br>
          <br>
          Founders: Avishai Abrahami, Nadav Abrahami, Giora Kaplan
          President: Nir Zohar
          Stock price: WIX (NASDAQ) $91.35 +2.60 (+2.93%)
          13 Apr, 4:00 pm GMT-4 - Disclaimer
          CEO: Avishai Abrahami (Sept 2010–)
          Founded: 5 October 2006, Tel Aviv-Yafo, Israel
          Headquarters: Tel Aviv-Yafo, Israel
          Number of employees: 5,929 (December 2021)
          Owners: Baillie Gifford (14.2%); Starboard Value (9%); BlackRock (4.7%); Principal Global (4.3%); Jackson Square Partners (4.3%)
        </p>
        <div class="bg bg1">
          <h2 class="desc">
            Biking
          </h2>
        </div>
        <p class="text">
          jhiuhnvj rhehceyur347t3 tc8y8n3ybj hjithjj Wix.com Ltd. is an Israeli software company, publicly listed in the US, that provides cloud-based web development services. It allows users to create HTML5 websites and mobile sites through the use of online drag and drop tools. Wikipedia
          <br>
          <br>
          Founders: Avishai Abrahami, Nadav Abrahami, Giora Kaplan
          President: Nir Zohar
          Stock price: WIX (NASDAQ) $91.35 +2.60 (+2.93%)
          13 Apr, 4:00pm GMT-4 - Disclaimer
          CEO: Avishai Abrahami (Sept 2010–)
          Founded: 5 October 2006, Tel Aviv-Yafo, Israel
          Headquarters: Tel Aviv-Yafo, Israel
          Number of employees: 5,929 (December 2021)
          Owners: Baillie Gifford (14.2%); Starboard Value (9%); BlackRock (4.7%); Principal Global (4.3%); Jackson Square Partners (4.3%)
        </p>
        <div class="bg bg2">
          <h2 class="desc">
            Gliding
          </h2>
        </div>
        <p class="text">
          jhiuhnvj rhehceyur347t3 tc8y8n3ybj hjithjj Wix.com Ltd. is an Israeli software company, publicly listed in the US, that provides cloud-based web development services. It allows users to create HTML5 websites and mobile sites through the use of online drag and drop tools. Wikipedia
          <br>
          <br>
          Founders: Avishai Abrahami, Nadav Abrahami, Giora Kaplan
          President: Nir Zohar
          Stock price: WIX (NASDAQ) $91.35 +2.60 (+2.93%)
          13 Apr, 4:00pm GMT-4 - Disclaimer
          CEO: Avishai Abrahami (Sept 2010–)
          Founded: 5 October 2006, Tel Aviv-Yafo, Israel
          Headquarters: Tel Aviv-Yafo, Israel
          Number of employees: 5,929 (December 2021)
          Owners: Baillie Gifford (14.2%); Starboard Value (9%); BlackRock (4.7%); Principal Global (4.3%); Jackson Square Partners (4.3%)
        </p>
        <div class="bg bg3">
          <h2 class="desc">
            Surfing
          </h2>
        </div>
        <p class="text">
          jhiuhnvj rhehceyur347t3 tc8y8n3ybj hjithjj Wix.com Ltd. is an Israeli software company, publicly listed in the US, that provides cloud-based web development services. It allows users to create HTML5 websites and mobile sites through the use of online drag and drop tools. Wikipedia
          <br>
          <br>
          Founders: Avishai Abrahami, Nadav Abrahami, Giora Kaplan
          President: Nir Zohar
          Stock price: WIX (NASDAQ) $91.35 +2.60 (+2.93%)
          13 Apr, 4:00pm GMT-4 - Disclaimer
          CEO: Avishai Abrahami (Sept 2010–)
          Founded: 5 October 2006, Tel Aviv-Yafo, Israel
          Headquarters: Tel Aviv-Yafo, Israel
          Number of employees: 5,929 (December 2021)
          Owners: Baillie Gifford (14.2%); Starboard Value (9%); BlackRock (4.7%); Principal Global (4.3%); Jackson Square Partners (4.3%)
        </p>
        <div>
            <h2 class="owner">
                - ABHAY   KUMAR
            </h2>
        </div>
      </section>

    </div>

  </body>

</html>

