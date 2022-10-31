<script>
  import svelteLogo from './assets/svelte.svg'
  import Counter from './lib/Counter.svelte'
</script>
  <main>
<div class="wrapper">
<h1>Sabrina Abrodi</h1>
<p>New portfolio coming soon!</p></div>
<div class="socials">
  <a href="https://www.linkedin.com/in/sabrina-abrodi-a52ab0239/"><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path fill="currentColor" fill-rule="evenodd" d="M1 2.838A1.838 1.838 0 0 1 2.838 1H21.16A1.837 1.837 0 0 1 23 2.838V21.16A1.838 1.838 0 0 1 21.161 23H2.838A1.838 1.838 0 0 1 1 21.161V2.838Zm8.708 6.55h2.979v1.496c.43-.86 1.53-1.634 3.183-1.634c3.169 0 3.92 1.713 3.92 4.856v5.822h-3.207v-5.106c0-1.79-.43-2.8-1.522-2.8c-1.515 0-2.145 1.089-2.145 2.8v5.106H9.708V9.388Zm-5.5 10.403h3.208V9.25H4.208v10.54ZM7.875 5.812a2.063 2.063 0 1 1-4.125 0a2.063 2.063 0 0 1 4.125 0Z" clip-rule="evenodd"/></svg></a>
  <a href="https://github.com/Sabrinascrib"><svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 2048 2048"><path fill="currentColor" d="M1024 25q141 0 272 36t244 104t207 160t161 207t103 245t37 272q0 165-50 318t-143 281t-221 224t-286 149q-3 1-9 1t-9 1q-24 0-38-14t-14-37v-140q0-69 1-141q0-51-15-103t-54-87q116-13 203-47t146-96t88-150t30-212q0-78-26-147t-79-128q11-28 16-58t5-60q0-39-8-77t-23-76q-5-2-11-2t-11 0q-32 0-67 10t-69 26t-67 35t-57 36q-125-35-256-35t-256 35q-25-17-57-36t-66-34t-70-26t-67-11h-11q-6 0-11 2q-14 37-22 75t-9 78q0 30 5 60t16 58q-53 58-79 127t-26 148q0 122 29 211t88 150t146 97t203 48q-29 26-44 62t-21 75q-27 13-57 20t-60 7q-64 0-106-30t-75-82q-12-19-29-38t-37-34t-43-24t-48-10h-12q-8 0-15 3t-14 6t-6 10q0 12 14 23t23 18l3 2q22 17 38 32t30 33t23 38t23 47q34 78 95 113t147 36q26 0 52-3t52-9v174q0 24-14 38t-39 14h-8q-5 0-9-2q-157-51-286-147t-221-225t-142-282t-51-318q0-141 36-272t104-244t160-207t207-161T752 62t272-37z"/></svg></a>
</div>


</main>

<style>
.wrapper {
  display: flex;
  align-self: center;
  background-color: #100d2f;
  height: 100vh;
  width: 100vw;
  flex-direction: column;
align-items: center;
justify-content: center;
font-family: 'Poppins', sans-serif;
color: aqua;
position: relative;
  }

  h1 {
  font-family: "Bebas Neue", cursive;
  color: #dfddf6;
  }

  p {
      color: #514d79;
      font-style: italic;
  }
  .socials {
    display: flex;
    flex-direction: column;
    bottom: 40px;
    right: 40px;
    position: absolute;
  }

  .socials svg {
    color: #dfddf6;
    font-size: 20px;
    margin-top: 20px;
  }

  .socials svg:hover {
color: #514d79;
transition-duration: 0.3s;
  }
</style>
