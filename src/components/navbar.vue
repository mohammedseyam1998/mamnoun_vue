<template>
    <div>
          <!--Header start-->
    <header>
        <div class="container">
            <div class="main-logo">
                <img class="lazyload"  src="../assets/mainlogo.png" alt="">
            </div>
            <div class="search-section">
                <input type="text" class="search-bar" name="search-bar" placeholder="ابحث هنا ...">
                <button class="btn search-icon">
                    <i class="fas fa-search"></i>
                </button>

            </div>
            <div class="social-media">
                <a href="#">
                    <button class="btn account-btn btn-link">
                        <i class="far fa-user"></i>
                        حسابي
                    </button>
                </a>
                <a href="#">
                    <button class="btn btn-link">
                        <i class="fab fa-instagram"></i>
                    </button>
                </a>
                <a href="#">
                    <button class="btn btn-link">
                        <i class="fab fa-snapchat-ghost"></i>
                    </button>
                </a>
                <a href="#">
                    <button class="btn btn-link">
                        <i class="fab fa-twitter"></i>
                    </button>
                </a>
                <a href="#">
                    <button class="btn btn-link">
                        <i class="fab fa-facebook-f"></i>
                    </button>
                </a>
            </div>
        </div>
    </header>
    <!--Header end-->

    <!--Nav section start-->
    <nav class="navbar navbar-expand-lg">
        <div class="container">
            <button class="btn navbar-toggler" type="button" data-toggle="collapse" data-target="#main_nav">
                <span class="navbar-toggler-icon">
                    <i class="fas fa-bars"></i>
                </span>
            </button>
            <div class="collapse navbar-collapse" id="main_nav">
                <ul class="navbar-nav">
                    <li class="nav-item active"> <a class="nav-link" href="#">الرئيسية</a> </li>
                    <li class="nav-item"> <a class="nav-link" href="#">بناتي</a></li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown"> ولادي </a>
                        <ul class="dropdown-menu">
                            <li><a class="dropdown-item" href="#"> طقم </a></li>
                            <li><a class="dropdown-item" href="#" > فستان </a>
                                <ul class="submenu dropdown-menu">
                                    <li><a class="dropdown-item" href=""> فستان ربيعي</a></li>
                                    <li><a class="dropdown-item" href="">فستان صيفي</a></li>
                                    <li><a class="dropdown-item" href=""> فستان أعياد </a></li>

                                </ul>
                            </li>
                            <li><a class="dropdown-item" href="#">طقم</a></li>
                            <li><a class="dropdown-item" href="#"> فستان</a></li>
                        </ul>
                    </li>
                    <li class="nav-item"> <a class="nav-link" href="#"> تشكيلة جديدة</a> </li>
                    <li class="nav-item"> <a class="nav-link" href="#">شتوي </a></li>
                    <li class="nav-item"> <a class="nav-link" href="#">معارض ممنون </a></li>
                </ul>
                <div class="purcahse-cart my-2 my-lg-0">
                    <div class="favourite">
                        <button class="btn"><i class="far fa-heart"></i></button>
                    </div>
                    <a class="cart-button">
                        سلة المشتريات
                        <span class="notification">8</span>
                    </a>

                </div>
            </div>
        </div>
    </nav>
    <!--Nav section end-->
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
header {
  height: 92px;
  display: flex;
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    .main-logo {
      width: 140px;
      height: 55px;
      display: flex;
      justify-content: center;
      align-items: center;
      img {
        max-width: 100%;
        object-fit: cover;
      }
    }
    .search-section {
      position: relative;
      .search-bar {
        width: 574px;
        height: 35px;
        border: solid 1px #000000;
        padding: 0 11px;
        position: relative;
        &::placeholder {
          font-size: 10px;
          color: #3b2d49;
        }
      }
      .search-icon {
        position: absolute;
        top: 0;
        left: 0;
        svg {
          font-size: 13px;
        }
      }
    }
    .social-media {
      display: flex;
      justify-content: flex-end;
      a {
        .btn-link {
          height: 35px;
          width: 25px;
          border: solid 1px #000000;
          display: flex;
          justify-content: center;
          align-items: center;
          color: #000000;
          margin-right: 5px;
          border-radius: 0;
          text-decoration: none;
          &:hover {
            background-color: #ed0c6e;
            color: white;
          }
        }
        .account-btn {
          width: 81px;
          margin-left: 5px;
          svg {
            margin-left: 7px;
          }
          &:hover {
            background-color: #ed0c6e;
            color: white;
          }
        }
        &:hover {
          text-decoration: none;
        }
      }
    }
  }
}
/************ Navbar start *************/
.navbar {
  border-bottom: 2px solid #000000;
  padding: 0;
  #main_nav {
    display: flex;
    justify-content: space-between !important;
    align-items: center !important;
    .navbar-nav {
      .nav-item {
        height: 43px;
        text-align: center;
        border: solid 1px transparent;
        .nav-link {
          color: #000000;
          font-size: 14px;
        }

        &:hover {
          border: solid 1px #000000;
          background-color: #000000;
          a {
            color: #ffffff;
          }
        }
        .dropdown-menu {
          text-align: right;
          right: 0;
          left: auto;
          .dropdown-item {
            color: #000000;
            &:hover {
              background-color: #fafafa;
              color: #ed0c6e;
            }
          }
          > li {
            &:hover {
              > .submenu {
                transform: translateX(-158px);
              }
            }
          }
        }

        &.active {
          border: solid 1px #000000;
          background-color: #000000;
          a {
            color: #ffffff;
          }
        }
      }
      .purcahse-cart {
        display: flex;
        justify-content: center;
        align-items: center;
        margin-right: auto;
        .favourite {
          width: 44px;
          height: 44px;
          border: solid 1px #000000;
          display: flex;
          justify-content: center;
          align-items: center;
          button {
            justify-content: center;
            padding: 0;
            display: flex;
            align-items: center;
            svg {
              font-size: 15px;
            }
          }
        }
      }
    }
    .purcahse-cart {
      display: flex;
      justify-content: center;
      align-items: center;
      .favourite {
        width: 44px;
        height: 44px;
        border: solid 1px #000000;
        display: flex;
        justify-content: center;
        align-items: center;
        border-bottom: none;
        button {
          justify-content: center;
          padding: 0;
          display: flex;
          align-items: center;
          svg {
            font-size: 15px;
          }
          &:focus {
            box-shadow: none;
          }
        }
      }
      .cart-button {
        position: relative;
        display: flex;
        width: 112px;
        height: 44px;
        border: solid 1px #000000;
        background-color: #000000;
        justify-content: center;
        align-items: center;
        margin-right: 5px;
        font-size: 14px;
        color: #fff;
        border-radius: 0;
        &:hover {
          cursor: pointer;
          text-decoration: none;
          background-color: #ed0c6e;
          color: white;
        }
        .notification {
          position: absolute;
          left: 3px;
          top: -13px;
          width: 20px;
          height: 20px;
          border-radius: 50%;
          background-color: #ed1c24;
          color: white;
          display: flex;
          justify-content: center;
          align-items: center;
          border: solid 2px #ffffff;
        }
      }
    }
  }
}
.dropdown-menu .dropdown-toggle:after {
    border-top: 0.3em solid transparent;
    border-right: 0;
    border-bottom: 0.3em solid transparent;
    border-left: 0.3em solid;
  }
  .dropdown-menu .dropdown-menu {
    margin-left: 0;
    margin-right: 0;
  }
  .dropdown-menu li {
    position: relative;
  }
  .nav-item .submenu {
    display: none;
    position: absolute;
    left: 100%;
    top: -7px;
  }
  .nav-item .submenu-left {
    right: 100%;
    left: auto;
  }
  .dropdown-menu > li:hover {
    background-color: #f1f1f1;
  }
  .dropdown-menu > li:hover > .submenu {
    display: block;
  }
/************ Navbar end *************/
</style>