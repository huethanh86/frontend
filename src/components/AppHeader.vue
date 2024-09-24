<template>
    <nav class="navbar navbar-expand navbar-dark bg-dark">
        <a href="/" class="navbar-brand">ỨNG DỤNG QUẢN LÝ DANH BẠ</a>
        <dic class="mr-auto navbar-nav">
            <li class="nav-item">
                <router-link :to="{ name: 'contactbook' }" class="nav-link">
                    DANH BẠ
                <i class="fas fa-address-book"></i>
                </router-link>
            </li>
        </dic>
    </nav>
</template>