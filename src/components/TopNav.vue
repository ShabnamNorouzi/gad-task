<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <a class="navbar-brand" href="#">
            <img style="width: 3rem" alt="Plexer"
                src="https://is1-ssl.mzstatic.com/image/thumb/Purple125/v4/54/25/45/542545ce-9a01-35c1-68fd-de106e9baaa0/source/512x512bb.jpg" /> Plexer
        </a>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#" data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#" data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show">Contact</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#" data-bs-toggle="collapse" data-bs-target=".navbar-collapse.show">
                        <i class="bi bi-person"></i> User
                    </a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
  name: 'TopNav',
}
</script>