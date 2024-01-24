<template>
    <div id="header">
        <b-container>
            <div class="d-flex align-items-center justify-content-center">
                <img src="../assets/image/bg-header.jpg" alt="" class="w-100 rounded">
            </div>
            <div class="deskripsi">
                <div class="pp">
                    <img src="../assets/image/pp.jpg" alt="" class="rounded circle" width="250px">
                </div>
                <div>
                    <div class="mt-4 d-flex align-items-center">
                        <h3 class="name">Eko Sutriono</h3>
                        <img src="../assets/icon/verify.png" alt="" width="30px" height="30px" class="ms-2">
                    </div>
                    <div>
                        <span>Frontend Developer | Creative & UI/UX Designer | Digital Marketer</span>
                    </div>
                    <div class="mt-1 d-flex align-items-center">
                        <img src="../assets/icon/pin.png" alt="" width="20px" height="20px">
                        <span class="text-secondary ms-2">Purbalingga, Central Java, Indonesia</span>
                    </div>
                </div>
                <div class="mt-4 gap-3 d-flex">
                    <a href="https://instagram.com/ekosoetriono_" target="_blank">
                        <i class="fi fi-brands-instagram"></i>
                    </a>
                    <a href="https://www.behance.net/ekosutriono99" target="_blank">
                        <i class="fi fi-brands-behance"></i>
                    </a>
                    <a href="https://www.linkedin.com/in/eko-sutriono" target="_blank">
                        <i class="fi fi-brands-linkedin"></i>
                    </a>
                    <a href="mailto:ekosutriono321@gmail.com" target="_blank">
                        <i class="fi fi-rr-envelope-open"></i>
                    </a>
                </div>
            </div>
        </b-container>
    </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
a {
    text-decoration: none;
    color: black;
}
.fi {
    font-size: 30px;
}
.fi-brands-linkedin {
    font-size: 33px;
}
.deskripsi {
    margin-left: 50px;
}
.pp {
    margin-top: -130px;
}
.circle {
    border-radius: 200px !important;
    border: 7px solid white !important;
}
.name {
    font-weight: 700;
}
</style>