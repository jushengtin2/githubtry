<template>
  
    <div class="gray_area">
        <p>首頁</p>
        <svg id="search" xmlns="http://www.w3.org/2000/svg" width="2em" height="2em" viewBox="0 0 1024 1024">
        <path fill="currentColor" d="M1014.64 969.04L703.71 656.207c57.952-69.408 92.88-158.704 92.88-256.208c0-220.912-179.088-400-400-400s-400 179.088-400 400s179.088 400 400 400c100.368 0 192.048-37.056 262.288-98.144l310.496 312.448c12.496 12.497 32.769 12.497 45.265 0c12.48-12.496 12.48-32.752 0-45.263zM396.59 736.527c-185.856 0-336.528-150.672-336.528-336.528S210.734 63.471 396.59 63.471c185.856 0 336.528 150.672 336.528 336.528S582.446 736.527 396.59 736.527z"></path>
        </svg>
    </div>

</template>


<style>
.gray_area {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  text-align: center;
  width: 100vw; /* Full viewport width */
  background-color: lightgray;
}

html,
body {
  height: 100%;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
}

body {
  margin: 0;
}
#search {
  margin-right: 2rem;
}

.gray_area p {
  flex: 1; /* Takes up available space */
  text-align: center;
  font-size: 2rem;
  margin: 0; /* Reset any default margin */
}

#dark_background {
  background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url("https://loremflickr.com/320/240");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>

<script>
export default {
  layout: "default",
  methods: {},
};
</script>