Project Title: Purchases Tracker App

Project Description: Purchases Tracker is a simple application, it allows users to record, manage, and monitor their personal purchases. Users can create an account, log in, and keep track of their orders including the item name, price, date, and delivery status. 
The app includes the following features:
• User registration and login
• Add, edit, and delete purchase entries
• Mark orders as To Receive or Arrived
• Live search bar to filter purchases by item name
• Filter tabs: All, To Receive, Arrived
• Dashboard showing Total Spent, Orders count, and Arrived count
• Form validation — empty fields and negative prices are not allowed

Detailed System Flow
1. App Launch
The app starts on the device. It checks local storage for an existing login session. If a session is found, the
user goes directly to the Dashboard. If not, the Login screen is shown.
2. Register
A new user fills in their Full Name, Username, and Password. The app validates all fields and checks that
the username is not already taken. On success, the account is saved locally and the user is redirected to
Log In.
3. Log In
The user enters their username and password. The app checks the credentials against the saved accounts.
If correct, the session is saved and the user's purchase data is loaded. The Dashboard is then displayed.
4. Dashboard
The Dashboard shows a stats header with Total Amount Spent, total Orders, and Arrived count. Below it
is a search bar, filter tabs, and the list of all purchases sorted by date. All stats update automatically when
data changes.
5. Add Purchase
The user taps "+ Add Purchase". A form appears with fields for Item Name, Price, Date, and Delivery
Status. All fields are validated before saving. On success, the purchase is added and the totals update right
away.
6. Edit Purchase
The user taps "Edit" on any purchase card. The form opens with the existing data pre-filled. After making
changes and saving, the Dashboard updates instantly.
7. Delete Purchase
The user taps "Delete" on a purchase card. A confirmation prompt appears. On confirm, the item is
removed and the Total Amount Spent recalculates automatically.
8. Toggle Delivery Status The user taps the status badge on any card to switch between "To Receive" and
"Arrived" without opening the edit form. The stats header updates instantly.
9. Search and Filter
The user types in the search bar to filter purchases by item name in real time. The filter tabs (All, To
Receive, Arrived) can be combined with the search to narrow down results further. 
10. Logout
The user taps the logout button. After a confirmation, the session is cleared, the app resets, and the Login
screen is shown again. 
