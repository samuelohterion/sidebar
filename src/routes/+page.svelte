<script>
    import Header from "../lib/Header.svelte";
    import Sidebar from "../lib/Sidebar.svelte";
</script>

<Header title="Hallo Kopf" />
<Sidebar />
<div class="content">
  <h2>Responsive Sidebar Example</h2>
  <p>This example use media queries to transform the sidebar to a top navigation bar when the screen size is 700px or less.</p>
  <p>We have also added a media query for screens that are 400px or less, which will vertically stack and center the navigation links.</p>
  <h3>Resize the browser window to see the effect.</h3>
</div>

<style>
    body {
      margin: 0;
      font-family: "Lato", sans-serif;
    }

    div.content {
      margin-left: 100px;
      padding: 1px 16px;
      height: 1000px;
    }
</style>