<template>
  <body>
    <div class="main-container">
      <!-- HEADER -->
      <header class="block">
        <ul class="header-menu horizontal-list">
          <li>
            <a class="header-menu-tab" href="#3"
              ><span class="icon fontawesome-edit scnd-font-color"></span
              >Planner</a
            >
          </li>
          <li>
            <a class="header-menu-tab" href="#2"
              ><span class="icon fontawesome-calendar scnd-font-color"></span
              >Events</a
            >
          </li>
          <li>
            <a class="header-menu-tab" href="#1"
              ><span class="icon fontawesome-user scnd-font-color"></span
              >Guest</a
            >
          </li>
          <li>
            <a class="header-menu-tab" href="#5"
              ><span class="icon fontawesome-file-alt scnd-font-color"></span
              >Viewer</a
            >
          </li>
        </ul>
        <div class="profile-menu">
          <p>
            Me
            <a href="#26"
              ><span class="entypo-down-open scnd-font-color"></span
            ></a>
          </p>
          <div class="profile-picture small-profile-picture">
            <img
              width="40px"
              alt="Mark Zuck Pic"
              src="https://yourwikis.com/wp-content/uploads/2020/01/mark-zuck-img.jpg"
            />
          </div>
        </div>
      </header>

      <div class="account block">
        <h2 class="titular">Guest Management</h2>
        <div>
          <div class="input-container">
            <input type="text" placeholder="First" class="text text-input" />
            <div class="input" />
          </div>
          <div class="input-container">
            <input type="text" placeholder="Last" class="text text-input" />
            <div class="input" />
          </div>
          <a class="sign-in button" href="#22">Create Guest</a>
        </div>
      </div>
    </div>
  </body>
</template>
