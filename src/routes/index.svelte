<style>
  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    justify-content: center;
    margin: 2em 0;
    min-height: 400px;
  }

  .home-copy {
    flex: 1;
  }

  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  p {
    font-size: 1.4em;
    line-height: 2;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }

  figcaption {
    font-size: .8em;
    font-style: italic;
  }
  .actions li {
  display: inline;
  list-style-type: none;
  padding-right: 5px;
  font-size: 1.2em;
}

  img {
    width: 100%;
    max-width: 400px;
  }

  @media (max-width: 1020px) {
    p {
      font-size: 1.2em;
    }

    img {
      max-width: 300px;
    }
  }

  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
    }

    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;
    }
  }
  
</style>

<svelte:head>
  <title>Himanshu Singh</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
    <h1>Hi there, </h1>
    <p>I am <a href="https://twitter.com/hi_man_shoe" target="_blank">Himanshu Singh</a>. An Engineer with passion into Mobile Engineering. I am a <a href="https://developers.google.com/community/experts/directory/profile/profile-himanshu_singh" target="_blank">Google Developer Expert for Android</a>.</p>
<span class="actions">
 
</span>  </div>

  <figure>
    <img alt='Person typing on laptop' src='undraw-illustration.svg'>
    <figcaption>Illustration thanks to <a href="https://undraw.co" target="_blank">Undraw</a></figcaption>
  </figure>
</div>
