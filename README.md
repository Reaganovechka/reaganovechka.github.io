<style>
  .about-container {
    display: flex;
    align-items: center;   /* vertically center image + text */
    gap: 20px;             /* space between image and text */
  }

  .about-container img {
    width: 200px;          /* size of image */
    border-radius: 8px;    /* rounded corners */
    flex-shrink: 0;        /* keeps image from squishing */
  }

  /* Mobile screens: stack image above text */
  @media (max-width: 768px) {
    .about-container {
      flex-direction: column;  /* stack vertically */
      text-align: center;      /* center text under image */
    }

    .about-container img {
      margin-bottom: 15px;     /* space between image and text */
    }
  }
</style>

<div class="about-container">
  <img src="https://github.com/Reaganovechka/reaganovechka.github.io/blob/main/Photo%20at%20Capitol.JPEG?raw=true" alt="About me photo">
  <div>
    <h1> About me </h1>
      <p> She/Her </p>
    
  <h2> Education </h2>
    <p>Persuing BS in Computer Science with Machine Learning Emphasis at Boise State University <br/>
    Expected graduation in May 2028</p>

  <h2> Involvement </h2>
    <ul> 
      <li> Member of the BSU Blue Thunder Marching Band </li>
      <li> Officer for Phi Sigma Rho (Sorority for women in STEM) </li>
      <li> Member of BSU club softball </li>
    </ul>
  <h2> Other Interests </h2>
    <ul>
      <li> Plant Enthusiast 🪴 </li>
      <li> Music lover </li>
      <li> Tea enjoyer </li>
    </ul>
  </div>
</div>




