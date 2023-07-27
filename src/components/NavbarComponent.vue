<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid class="nav" >
      <template #logo>
        <Navbar>
          <h1><b>SneakersHead.</b></h1>
        </Navbar>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>Beranda</NavbarLink>
          <NavbarLink>Tentang</NavbarLink>
          <NavbarLink>Galeri</NavbarLink>
          <NavbarLink>Kontak</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>

