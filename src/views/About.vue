<template>
  <div class="about">
    <h1>Front-end developer assignment</h1>
    <p>
      Your mission, should you choose to accept it, is to create a one-page
      application with a list of people and the details about their related home
      planet. The list of people and the information related to a planet can be
      accessed using the swapi api: SWAPI api details: https://swapi.dev/
      Wireframe description:
    </p>
    The candidate should implement a table that contains a list of users with
    the following columns:
    <li>Name</li>
    <li>Height</li>
    <li>Mass</li>
    <li>Created</li>
    <li>Edited</li>
    <li>Planet Name</li>

    When the user clicks on the planet name link a popup is displayed showing
    the following information regarding the planet:
    <li>Name</li>
    <li>Diameter</li>
    <li>Climate</li>
    <li>Population</li>

    The user should be able to sort the table by each column. The user should
    also be able to filter by searching the person’s name.

    <li>Stack</li>
    <li>ES6</li>
    <li>Webpack</li>
    <li>
      VueJs and vue router are a plus but not necessary, use the JS framework
      you like, eg React, Angular, Vue etc
    </li>

    <p>
      The candidate has 5 days to complete this assignment. The completed
      assignment should be sent to your recruiter. This can either be a public
      git repository that we can access or a zipped attachment or a link to a
      zipped file of the completed assessment.
    </p>
    <p>Code: <a href="https://github.com/theWhiteFox/List-the-SWAPI-Characters">theWhiteFox List the SWAPI Characters</a></p>
  </div>
</template>

<style scoped>
.about {
  max-width: 860px;
  margin: 0 auto;
  text-align: left;
}
</style>
