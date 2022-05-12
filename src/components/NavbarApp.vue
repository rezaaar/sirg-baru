<template>
    <nav class="navbar fixed-top navbar-expand-sm navbar-light bg-light">
        <a class="navbar-brand" href="#">
            <img src="@/assets/logo-sirg.png" width="30" height="30" class="d-inline-block align-top">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#toggleMobileMenu" aria-controls="toggleMobileMenu" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="toggleMobileMenu">
            <ul class="navbar-nav ms-auto text-center">
                <li>
                    <router-link class="nav-link" to="/">Home</router-link>
                </li>
                 <li>
                    <router-link class="nav-link" to="/karya">Karya</router-link>
                </li>
                <li>
                    <router-link class="nav-link" to="/judulpa">Judul PA</router-link>
                </li>
                 <li>
                    <router-link class="nav-link" to="/daftardosen">Daftar Dosen</router-link>
                </li>
                <li>
                    <router-link class="nav-link" to="/about">About</router-link>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
    name : 'NavbarApp'
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
}

nav {
  padding: 50px;
}

.nav-link {
  font-family: 'Roboto', sans-serif;
  font-weight: bold;
}
</style>