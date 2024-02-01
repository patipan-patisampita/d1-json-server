<script scoped>
import { RouterLink } from 'vue-router';
</script>

<template>
    <nav class="navbar navbar-expand-lg nabar-dark shadow stickey-top" style="background: #7A0FB6;">
        <div class="container">
            <router-link :to="{ name: 'home' }" class="navbar-brand text-white">สาขาไอที</router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link :to="{ name: 'home' }" class="nav-link active text-white" aria-current="page"
                            href="#">หน้าแรก</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{ name: 'about' }" class="nav-link text-white" href="#">เกี่ยวกับเรา</router-link>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle text-white" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            เว็บที่เกี่ยวข้อง
                        </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="https://www.trattc.ac.th" target="_blank">วท.ตราด</a></li>
                            <li><a class="dropdown-item" href="https://www.vec.go.th" target="_blank">อาชีวศึกษา</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="https://www.moe.go.th" target="_blank">กระทรวงศึกษาธิการ</a>
                            </li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <router-link to="" class="nav-link text-white" aria-disabled="true" href="#">แผนที่</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Sarabun&display=swap');

.navbar {
    font-family: 'Sarabun', sans-serif;
}
</style>
