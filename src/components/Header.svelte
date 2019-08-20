<script>
  import { Link } from "svero";
</script>

<style>
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.5em 3em;
    background-color: #313131;
  }

  nav ul {
    display: flex;
    list-style-type: none;
    margin: 0;
  }

  :global(.logo) {
    color: white !important;
    font-weight: bold;
  }

  :global(nav a) {
    padding: 1em;
    display: block;
    color: white !important;
  }
</style>

<header>
  <Link href="/home" className="logo">My Svelte App</Link>

  <nav>
    <ul>
      <li>
        <Link href="/home" className="link">Home</Link>
      </li>
      <li>
        <Link href="/about" className="link">About</Link>
      </li>
    </ul>
  </nav>
</header>
