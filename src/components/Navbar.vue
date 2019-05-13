<template>
  <b-navbar toggleable="md" type="dark" variant="dark" class="py-3">
    <div class="container-fluid main">
      <a class="navbar-brand" href="#">
        <img src="../assets/images/logo.png" alt="Fujifilm" class="img-fluid" width="40" height="40">
      </a>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" class="flex-column" is-nav>
        <b-navbar-nav class="ml-auto navbar-nav-sm navbar-nav-dark ml-auto">
          <b-nav-item-dropdown right>
            <template slot="button-content">
              News & Events <i class="fa fa-chevron-down fa-fw caret-sm text-danger"></i>
            </template>
            <b-dropdown-item href="#">Dropdown 1</b-dropdown-item>
            <b-dropdown-item href="#">Dropdown 2</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item href="#">Comunity</b-nav-item>
          <b-nav-form>
            <div class="input-group input-group-sm input-group-icon input-group-dark mr-3">
              <input type="text" class="form-control rounded-pill" placeholder="Search" aria-label="Search">
              <div class="input-group-append">
                <span class="input-group-text text-light rounded-pill" id="basic-addon1"><i class="fa fa-search fa-fw"></i></span>
              </div>
            </div>
            <b-dropdown variant="outline-light rounded-pill px-3 text-white" size="sm">
              <template slot="button-content">
                En | <i class="fa fa-chevron-down fa-fw caret-sm text-white"></i>
              </template>
              <b-dropdown-item>English</b-dropdown-item>
              <b-dropdown-item>Indonesian</b-dropdown-item>
            </b-dropdown>
          </b-nav-form>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto mt-2">
          <b-nav-item-dropdown right>
            <template slot="button-content">
              Cameras <i class="fa fa-chevron-down fa-fw caret-sm text-danger"></i>
            </template>
            <b-dropdown-item href="#">Dropdown 1</b-dropdown-item>
            <b-dropdown-item href="#">Dropdown 2</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown right>
            <template slot="button-content">
              Lenses <i class="fa fa-chevron-down fa-fw caret-sm text-danger"></i>
            </template>
            <b-dropdown-item href="#">Dropdown 1</b-dropdown-item>
            <b-dropdown-item href="#">Dropdown 2</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown right>
            <template slot="button-content">
              Accessories <i class="fa fa-chevron-down fa-fw caret-sm text-danger"></i>
            </template>
            <b-dropdown-item href="#">Dropdown 1</b-dropdown-item>
            <b-dropdown-item href="#">Dropdown 2</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown right>
            <template slot="button-content">
              Inspirations <i class="fa fa-chevron-down fa-fw caret-sm text-danger"></i>
            </template>
            <b-dropdown-item href="#">Dropdown 1</b-dropdown-item>
            <b-dropdown-item href="#">Dropdown 2</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-nav-item-dropdown right>
            <template slot="button-content">
              Service & Support <i class="fa fa-chevron-down fa-fw caret-sm text-danger"></i>
            </template>
            <b-dropdown-item href="#">Dropdown 1</b-dropdown-item>
            <b-dropdown-item href="#">Dropdown 2</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</template>

<script>
import { BNavbar, BCollapse, BDropdown, BNavbarToggle, BNavForm, BNavbarNav, BNavItem, BNavItemDropdown, BDropdownItem } from 'bootstrap-vue/es/components'

export default {
  components: {
    BNavbar,
    BCollapse,
    BDropdown,
    BNavbarToggle,
    BNavForm,
    BNavbarNav,
    BNavItem,
    BNavItemDropdown,
    BDropdownItem
  }
}
</script>
