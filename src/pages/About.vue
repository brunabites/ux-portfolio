<template>
  <Layout>
    <div class="container">
      <div class="about-header">
        <h1 class="about-title">About me!</h1>
        <div class="tophead">
          <img src="@/assets/bruna-bites.jpg" class="avatar" />
          <div>
            <h3 class="about-desc">
              I’m a product designer living in Brasília, the capital of Brazil,
              working at iFood - the leading food delivery app in Latin America,
              helping to improve Financial services for restaurants and
              groceries stores.
            </h3>
            <p>
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="https://www.linkedin.com/in/brunabites/"
                >LinkedIn</a
              >
              <span class="light-spacer">—</span>
              <a
                rel="noopener noreferrer"
                href="https://dribbble.com/brunabites"
                >Dribbble</a
              >
              <span class="light-spacer">—</span>
              <a
                target="_blank"
                rel="noopener noreferrer"
                href="http://github.com/brunabites/"
                >Github</a
              >
            </p>
          </div>
        </div>
      </div>

      <div class="about-me">
        <p>
          My name is Bruna and since 2004 I've been working either as art
          director or designer in different places. Ad agencies, big companies
          like Newell Brands and Banco do Brasil, startups or even my own
          studio.
        </p>

        <p>
          In my past life, I've worked with graphic design, but at some point I
          got into the Digital Industry, where I've been for the past 12 years.
        </p>

        <p>
          Right now I'm a Sr Product Designer at iFood, Latin America's largest
          food delivery app, building better financial services for restaurants
          and groceries stores.
        </p>

        <p>
          A phrase that defines me is "Ask Bruna. She knows it". Yeap, I'm
          curious and I keep learning things so I can share with others. A
          colleague once described me as "a live rss feed".
        </p>

        <p>
          Aggregator, Connected, Detail-oriented, Insightful, Self taught,
          Creative, Leader. Those are just a few terms that begin to describe me
          as a professional (and human being).
        </p>

        <p>
        As a Product Designer, I hope to help a design-driven company or a novice startup creating impressive digital services and products with a strategic approach. Contact me if you want to know more about my skills or visit my <a href="https://www.linkedin.com/in/brunabites/" target="_blank">LinkedIn profile</a>. My expertise covers Design (UI / UX / Visual) and Digital Art Direction. I can create some stuff using Html, CSS, Javascript, and Github (like this portfolio).
        </p>

        <blockquote>
          I do believe that design make things and people better. And that makes
          me want to help makers and companies to build and design solutions
          based on people.
        </blockquote>

        <p>
          👩‍💻 I'm not avaiable for projects right now.
        </p>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {};
</script>

<style scoped>
.about-header {
  padding: 2rem 0 2rem 0;
}
.about-title {
  font-size: 3rem;
  margin: 0 0 4rem 0;
  padding: 0;
}
.tophead {
  display: flex;
}
.about-desc {
  font-size: 1.6rem;
  line-height: 2.5rem;
}

img.avatar {
  width: 220px;
  height: 220px;
  border-radius: 100%;
  margin: 0 2rem 0 0;
}
.about-me {
  color: var(--color-contrast);
  font-size: 1.2rem;
  line-height: 2rem;
}

blockquote {
  border-left: 5px solid var(--color-accent);
  font-size: 1.66667rem;
  line-height: 1.3;
  margin: 2.5rem 0;
  padding-left: 30px;
  position: relative;
}

@media only screen and (min-device-width: 295px) and (max-device-width: 812px) {
  .tophead {
    text-align: center;
    display: inline-block;
  }
}
</style>
