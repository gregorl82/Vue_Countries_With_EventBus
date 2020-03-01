<h1>Vue Multicomponent Countries Application</h1>
<h2>Objectives</h2>
<ul>
<li>Be able to create a Vue app with multiple components and templates</li>
</ul>
<h2>Brief</h2>
<p>The task is to create an app that shows info for all the countries using multiple components. Use the <a href="https://restcountries.eu/rest/v2/all">Countries API</a> to make a request to get the data.</p>
<h2>MVP</h2>
<ul>
<li>Display a list of country names.</li>
<li>Add a click event to the list item which should then render more detail about that country (name, capital, population).</li>
<li>Use reusable components.</li>
</ul>
<h2>Extensions</h2>
<ul>
<li>Instead of rendering a list, populate a dropdown with all of the countries names.</li>
<li>Add a change event to the select that renders information about the selected country.</li>
</ul>
<h2>Advanced Extensions</h2>
<ul>
<li>Add the countries flag and languages spoken in the country to the country detail component.</li>
<li>Add a search bar to the page so that when a user enters the countries name the country detail component renders. Try to achieve this without the user having to enter the whole name.</li>
</ul>

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
