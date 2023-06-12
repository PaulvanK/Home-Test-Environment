<template>
  <div
    data="vue"
    class="
      sidenav
      navbar navbar-vertical
      fixed-left
      navbar-expand-xs navbar-light
      bg-white
    "
  >
    <div class="scrollbar-inner ps ps--active-y">
      <div class="sidenav-header d-flex align-items-center">
        <a href="/" class="navbar-brand"
          ><img
            src="../images/Jongstra mooi transparent.jpeg"
            alt="Sidebar logo"
            class="navbar-brand-img"
        /></a>
      </div>
      <div class="navbar-inner">
        <ul class="navbar-nav" style="padding-bottom: 80px">
          <li class="nav-item nuxt-link-active">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/" class="nav-link nuxt-link-active"
              ><i class="fa fa-home"></i>
              <span class="nav-link-text">Dashboard</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/products" class="nav-link"
              ><i class="fa fa-chair"></i>
              <span class="nav-link-text">Producten</span></a
            >
          </li>
          <h6 class="navbar-heading text-muted pb-0">Inkoop</h6>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/suppliers" class="nav-link"
              ><i class="fa fa-users"></i>
              <span class="nav-link-text">Leveranciers</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/purchases" class="nav-link"
              ><i class="fa fa-box"></i>
              <span class="nav-link-text">Inkooporders</span></a
            >
          </li>
          <h6 class="navbar-heading text-muted pb-0">Verkoop</h6>
          <li class="nav-item nuxt-link-active">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/retailers" class="nav-link nuxt-link-active"
              ><i class="fa fa-store"></i>
              <span class="nav-link-text">Bedrijven</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/orders" class="nav-link"
              ><i class="fa fa-money-bill-wave"></i>
              <span class="nav-link-text">Verkooporders</span></a
            >
          </li>
          <h6 class="navbar-heading text-muted pb-0">Leveren</h6>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/deliveries" class="nav-link"
              ><i class="fa fa-truck"></i>
              <span class="nav-link-text">Leveringen</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/take-away" class="nav-link"
              ><i class="fa fa-warehouse"></i>
              <span class="nav-link-text">Afhalen</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/maps" class="nav-link"
              ><i class="fa fa-map"></i>
              <span class="nav-link-text">Maps</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/delivery-slip" class="nav-link"
              ><i class="fa fa-truck"></i>
              <span class="nav-link-text">Digitale Leverbon</span></a
            >
          </li>
          <h6 class="navbar-heading text-muted pb-0">Overige</h6>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/service" class="nav-link"
              ><i class="fa fa-heart-broken"></i>
              <span class="nav-link-text">Servicemeldingen</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/alerts" class="nav-link"
              ><i class="fa fa-bell"></i>
              <span class="nav-link-text">Actiecentrum</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/cars" class="nav-link"
              ><i class="fa fa-car"></i>
              <span class="nav-link-text">Wagenpark</span></a
            >
          </li>
          <li class="nav-item">
            <!---->
            <div class="collapse show" style="display: none">
              <ul class="nav nav-sm flex-column"></ul>
            </div>
            <a href="/users" class="nav-link"
              ><i class="fa fa-users"></i>
              <span class="nav-link-text">Gebruikers</span></a
            >
          </li>
          <!---->
        </ul>
      </div>
      <div class="ps__rail-x" style="left: 0px; bottom: 0px">
        <div
          class="ps__thumb-x"
          tabindex="0"
          style="left: 0px; width: 0px"
        ></div>
      </div>
      <div class="ps__rail-y" style="top: 0px; height: 666px; right: 0px">
        <div
          class="ps__thumb-y"
          tabindex="0"
          style="top: 0px; height: 469px"
        ></div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style>
.sidenav-header {
  height: 78px;
}

.navbar-brand {
  display: block;
}
</style>
