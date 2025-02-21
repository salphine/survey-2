<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SALPHINE CHEMOS APPS</title>
    <!-- material cdn -->
    <link
      rel="stylesheet"
      href="https://fonts.googleapis.com/css2?family=Material+Symbols+Sharp:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200"
    />
    <!-- stylesheet -->
    <link rel="stylesheet" href="./styles.css" />
  </head>
  <body>
    <div class="container">
      <aside>
        <div class="top">
          <div class="logo">
            <img
              src="./images/logo/logo_lifework-enterprise_150px-by-150px_transparent.png"
            />
            <h2>SALPHINE<span class="danger">APPS</span></h2>
            <div class="close" id="close-btn">
              <span class="material-symbols-sharp"> close </span>
            </div>
          </div>
        </div>
        <div class="sidebar">
          <a href="#">
            <span class="material-symbols-sharp"> grid_view </span>
            <h3>DASHBOARD</h3>
          </a>
          <a href="#" class="active">
            <span class="material-symbols-sharp"> person_outline </span>
            <h3>CUSTOMERS</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> receipt_long </span>
            <h3>ORDER</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> insights </span>
            <h3>MARKETING</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> mail_outline </span>
            <h3>MESSAGES/h3>
            <span class="message-count">26</span>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> inventory </span>
            <h3>PRODUCTS</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> report_gmailerrorred </span>
            <h3>Reports</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> settings </span>
            <h3>Settings</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> add </span>
            <h3>Add Product</h3>
          </a>
          <a href="#">
            <span class="material-symbols-sharp"> logout </span>
            <h3>Logout</h3>
          </a>
        </div>
      </aside>
      <!-- end of aside -->
      <main>
        <h1>Dashboard</h1>
        <div class="date">
          <input type="date" />
        </div>
        <div class="insights">
          <div class="sales">
            <span class="material-symbols-sharp"> analytics </span>
            <div class="middle">
              <div class="left">
                <h3>Total Sales</h3>
                <h1>$25,024</h1>
              </div>
              <div class="progress">
                <svg>
                  <circle cx="38" cy="38" r="36"></circle>
                </svg>
                <div class="number">
                  <p>81%</p>
                </div>
              </div>
            </div>
            <small class="text-muted">Last 24 Hours</small>
          </div>
          <!-- end of sales -->
          <div class="expenses">
            <span class="material-symbols-sharp"> bar_chart </span>
            <div class="middle">
              <div class="left">
                <h3>Total Expenses</h3>
                <h1>$14,160</h1>
              </div>
              <div class="progress">
                <svg>
                  <circle cx="38" cy="38" r="36"></circle>
                </svg>
                <div class="number">
                  <p>62%</p>
                </div>
              </div>
            </div>
            <small class="text-muted">Last 24 Hours</small>
          </div>
          <!-- end of expenses -->
          <div class="income">
            <span class="material-symbols-sharp"> stacked_line_chart </span>
            <div class="middle">
              <div class="left">
                <h3>Total Income</h3>
                <h1>$10,864</h1>
              </div>
              <div class="progress">
                <svg>
                  <circle cx="38" cy="38" r="36"></circle>
                </svg>
                <div class="number">
                  <p>44%</p>
                </div>
              </div>
            </div>
            <small class="text-muted">Last 24 Hours</small>
          </div>
          <!-- end of income -->
        </div>
        <!-- end of insights -->

        <div class="recent-orders">
          <h2>Recent Orders</h2>
          <table>
            <thead>
              <tr>
                <th>Product Name</th>
                <th>Product Number</th>
                <th>Payment</th>
                <th>Status</th>
                <th></th>
              </tr>
            </thead>
            <tbody>
              <!-- <tr>
                <td>Foldable Mini Drone</td>
                <td>85631</td>
                <td>Due</td>
                <td class="warning">Pending</td>
                <td class="primary">Details</td>
              </tr> -->
            </tbody>
          </table>
          <a href="#">Show All</a>
        </div>
      </main>
      <!-- end of main -->

      <div class="right">
        <div class="top">
          <button id="menu-btn">
            <span class="material-symbols-sharp">menu</span>
          </button>
          <div class="theme-toggler">
            <span class="material-symbols-sharp active"> light_mode </span>
            <span class="material-symbols-sharp"> dark_mode </span>
          </div>
          <div class="profile">
            <div class="info">
              <p>Hey, <b>SALPHINE</b></p>
              <small class="text-muted">Admin</small>
            </div>
            <div class="profile-photo">
              <img src="" alt="" />
            </div>
          </div>
        </div>
        <!-- end of top -->
        <div class="recent-updates">
          <h2>Recent updates</h2>
          <div class="updates">
            <div class="update">
              <div class="profile-photo">
                <img src="" />
              </div>
              <div class="message">
                <p>
                  <b>JOE</b> ELECTRONIC KATTLE
                </p>
                <small class="text-muted">2 Minutes Ago</small>
              </div>
            </div>
            <div class="update">
              <div class="profile-photo">
                <img src="" />
              </div>
              <div class="message">
                <p>
                  <b>ANTONY</b> received his order of tv screen 32inches
                </p>
                <small class="text-muted">4 Minutes Ago</small>
              </div>
            </div>
            <div class="update">
              <div class="profile-photo">
                <img src="" />
              </div>
              <div class="message">
                <p>
                  <b>jeff</b> received his order of smart watch
                </p>
                <small class="text-muted">6 Minutes Ago</small>
              </div>
            </div>
          </div>
        </div>
        <!-- end of recent updates -->

        <div class="sales-analytics">
          <h2>Sales marketing</h2>
          <div class="item online">
            <div class="icon">
              <span class="material-symbols-sharp"> shopping_cart </span>
            </div>
            <div class="right">
              <div class="info">
                <h3>ONLINE ORDERS</h3>
                <small class="text-muted">Last 24 Hours</small>
              </div>
              <h5 class="success">+39%</h5>
              <h3>3849</h3>
            </div>
          </div>
          <div class="item offline">
            <div class="icon">
              <span class="material-symbols-sharp"> local_mall </span>
            </div>
            <div class="right">
              <div class="info">
                <h3>OFFLINE ORDERS</h3>
                <small class="text-muted">Last 24 Hours</small>
              </div>
              <h5 class="danger">-17%</h5>
              <h3>1100</h3>
            </div>
          </div>
          <div class="item customers">
            <div class="icon">
              <span class="material-symbols-sharp"> person </span>
            </div>
            <div class="right">
              <div class="info">
                <h3>NEW CUSTOMERS</h3>
                <small class="text-muted">Last 24 Hours</small>
              </div>
              <h5 class="success">+25%</h5>
              <h3>849</h3>
            </div>
          </div>
          <div class="item add-product">
            <div>
              <span class="material-symbols-sharp"> add </span>
              <h3>add the product</h3>
            </div>
          </div>
        </div>
      </div>
    </div>

    <script src="./orders.js"></script>
    <script src="./index.js"></script>
  </body>
</html>

