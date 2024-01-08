<script>
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
    DarkMode,
  } from "flowbite-svelte";
</script>

<Navbar>
  <NavBrand href="/">
    <!--<img src="/images/flowbite-svelte-icon-logo.svg" class="me-3 h-6 sm:h-9" alt="Flowbite Logo" />-->
    <span
      class="self-center whitespace-nowrap text-xl font-semibold text-dark dark:text-white"
      >BlazePunch</span
    >
  </NavBrand>
  <NavHamburger />
  <NavUl>
    <NavLi href="/">Home</NavLi>
    <NavLi href="/about">games</NavLi>
    <NavLi href="/about">privacy policy</NavLi>
    <DarkMode>Dark</DarkMode>
  </NavUl>
</Navbar>
