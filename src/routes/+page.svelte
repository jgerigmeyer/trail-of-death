<script lang="ts">
  import { base } from '$app/paths';

  let start = 2023;
  let year = new Date().getFullYear();
</script>

<div data-layout="app">
  <main data-layout="main">
    <h1>Potawatomi Trail of Death Association</h1>
    <img src="{base}/logo.gif" alt="silhouette of three people and a bird" />
    <h2>Under Construction</h2>
    <p>
      While we build our new site, a lot of information about the Potawatomi Trail of Death can be
      found at <a href="http://potawatomi-tda.org">potawatomi-tda.org</a>.
    </p>
    <p>
      Contact us at
      <a href="mailto:PotawatomiTrail1838@gmail.com">PotawatomiTrail1838@gmail.com</a>.
    </p>
  </main>

  <footer data-layout="footer">
    &copy; {start}{year > start ? `–${year}` : ''} Potawatomi Trail of Death Association.
  </footer>
</div>
